---
layout: post
title: "Quick data mining on proceedings of a conference"
description: ""
category: tips
tags: [data mining]

---
{% include JB/setup %}

A quick snippet that I jot down during WWW'13. Within the conference proceedings directory, I am basically iterating over pdf files, converting into text, and extracting the references. This simple script works for most of the papers.

	$ for f in `ls p*.pdf`; do
		fn=`echo $f | sed 's/\.pdf//'`;
		echo $fn;
		pdftotext -raw $f;
		awk '{if(a){if(match($0,"APPENDIX")){a="";} else if(match($0,/^\[[0-9]+\]/)){if(ref!=""){print ref;} ref=$0;}else{ref=(ref " " $0);}} if(match(toupper($0),/\.? *REFERENCES/) && RSTART<10 && length($0)==RSTART+RLENGTH-1){a=1;}} END{print ref;}' ${fn}.txt > ${fn}.refs;
	done

