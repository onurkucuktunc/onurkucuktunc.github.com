---
layout: page
title: "Biclustering"
description: "We address this problem of evaluating the strengths and weaknesses of existing biclustering methods for <strong>gene expression data</strong> that were recently published or have not been extensively studied."
group: projects-phd

---
{% include JB/setup %}

<div class="row">
<div class="span8">

<h1>A Comparative Analysis of Biclustering Algorithms for Gene Expression Data</h1>
<p><i class="icon-user"></i> Kemal Eren, Mehmet Deveci, Onur Kucuktunc, Umit V. Catalyurek</p>
<p><strong><em>Abstract - </em></strong>
The need to analyze high-dimension biological data is driving the
development of new data mining methods. Biclustering algorithms have
been successfully applied to gene expression data to discover local
patterns, in which a subset of genes exhibit similar expression
levels over a subset of conditions. However, it is not clear which
algorithms are best suited for this task. Many algorithms
have been published in the past decade, most of which have been compared
only to a small number of algorithms.
Surveys and comparisons exist in the literature, but because
of the large number and variety of biclustering algorithms, they are
quickly outdated.<br /><br />

In this paper we partially address this problem of evaluating the
strengths and weaknesses of existing biclustering methods. We used
the BiBench package to compare twelve algorithms, many of which were
recently published or have not been extensively studied. The
algorithms were tested on a suite of synthetic datasets to measure
their performance on data with varying conditions, such as different
bicluster models, varying noise, varying numbers of biclusters, and
overlapping biclusters. The algorithms were also tested on eight
large gene expression datasets obtained from the Gene Expression
Omnibus (GEO). Gene Ontology enrichment analysis was performed on
the resulting biclusters, and the best enrichment terms are reported.
Our analyses show that the biclustering method and its parameters should 
be selected based on the desired model, whether that model allows 
overlapping biclusters, and its robustness to noise.
In addition, we observe that the biclustering algorithms capable of 
finding more than one model are more successful at capturing biologically 
relevant clusters. 
</p>
<p><i class="icon-info-sign"></i> <a href="http://dx.doi.org/10.1093/bib/bbs032">10.1093/bib/bbs032</a><br />
<i class="icon-file"></i> <a href="http://bib.oxfordjournals.org/cgi/reprint/bbs032?ijkey=ozbpqPzX2OlKHXB&keytype=ref">PDF</a><br />
<i class="icon-tags"></i> biclustering, microarray, gene expression, clustering
</p>
<div class="well">K. Eren, M. Deveci, Onur Kucuktunc, U.V. Catalyurek, <strong>A Comparative Analysis of Biclustering Algorithms for Gene Expression Data</strong>, (accepted to) <em>Briefings in Bioinformatics</em>, 2012.</div>

</div>
<div class="span4">
<h3>Supplementary Material</h3>
</div>
</div>