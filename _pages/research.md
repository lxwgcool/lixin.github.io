---
layout: archive
permalink: /research/
author_profile: true
title: "Research"
---


Detecting genomic deletions from NGS data with unsupervised learning
------
Developed a new method called EigenDel. EigenDel first uses discordant & clipped reads to get initial
deletion candidates, and then it clusters similar candidates by using PCA and hierarchical clustering.
Finally, EigenDel uses a carefully designed approach for calling true deletions from each cluster


Detecting circular RNA from high-throughput sequence data with de Bruijn graph
------
Presented a new method named CircDBG, which creates a de Bruijn graph based on k-mers from the
boundary parts of exons in annotated genome. Then, we take advantage of this graph to find the
relationship between k-mer of reads and the potential donor/acceptor exon by tracking the path in the
graph for circRNA detection. Reported a special case of circRNA: chimeric circRNA.


CircMarker: a fast and accurate algorithm for circular RNA detection
------
Presented a new computational approach, named CircMarker, based on k-mers rather than reads mapping. CircMarker takes advantage of annotation files to create the k-mer table for circRNA detection.
