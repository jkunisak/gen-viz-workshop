---
title: Authors
feature_text: ""
feature_image: "assets/genvis-dna-bg_optimized_v1a.png"
excerpt: ""
layout: "home"
---

***

### Obi L. Griffith
<nav class="nav  nav--social">
{% for link in site.contact_obi %}
    {% assign id = link[0] | downcase %}
    {% capture refer %}{{link[1]}}{% endcapture %}
<a class="link" target="_blank" href="{{refer}}" title="{{link[0]}}">{% include icon.html id=id %}</a>
{% endfor %}
</nav>
{% include figure.html image="/assets/obig2.jpg" position="right" %}
Dr. Obi Griffith is Assistant Professor of Medicine and Assistant Director at the McDonnell Genome Institute. Dr. Griffith's research is focused on the development of personalized medicine strategies for cancer using genomic technologies with a particular focus on gene regulatory changes associated with breast cancer. He develops and uses bioinformatics and statistical methods for the analysis of high throughput sequence data and identification of biomarkers for diagnostic, prognostic and drug response prediction. Dr. Griffith has developed and instructs a workshop on RNA sequence analysis for Cold Spring Harbor Laboratories and is a regular instructor for the Canadian Bioinformatics Workshops series. Before coming to Washington University, Dr. Griffith completed bioinformatics post-doctoral fellowships at Lawrence Berkeley National Laboratory in Berkeley, California and at the BC Cancer Agency Genome Sciences Centre in Vancouver, British Columbia. He received his Ph.D. (Medical Genetics, 2008) from the University of British Columbia and B.S. (Biochemistry and Biology with Honors, 2002) from the University of Winnipeg.

***

### Malachi Griffith
<nav class="nav  nav--social">
{% for link in site.contact_malachi %}
    {% assign id = link[0] | downcase %}
    {% capture refer %}{{link[1]}}{% endcapture %}
<a class="link" target="_blank" href="{{refer}}" title="{{link[0]}}">{% include icon.html id=id %}</a>
{% endfor %}
</nav>
{% include figure.html image="/assets/MG14.jpg" position="right" %}
Dr. Malachi Griffith is an Assistant Director of the McDonnell Genome Institute and an Assistant Professor in the Department of Medicine. Dr. Griffith's research is focused on the development of genomics, bioinformatics and statistical methods as they apply to the study of cancer biology and medicine. A particular focus of his work is in the translation of genomics data from whole genome, exome and transcriptome sequencing into clinically actionable observations and personalized cancer therapies.
 Dr. Griffith is a regular instructor for the Canadian Bioinformatics Workshops series and Cold Spring Harbor Laboratories. Dr. Griffith is currently supported by an NIH R00 pathway to independence grant. Before coming to Washington University Dr. Griffith was a bioinformatics post-doctoral fellow at the BC Cancer Agency Genome Sciences center in Vancouver, British Columbia. He received his Ph.D. (Medical Genetics, 2009) from the University of British Columbia and B.S. (Biochemistry and Biology with Honors, 2002) from the University of Winnipeg.

***

### Zachary L. Skidmore
<nav class="nav  nav--social">
{% for link in site.contact_zach %}
    {% assign id = link[0] | downcase %}
    {% capture refer %}{{link[1]}}{% endcapture %}
<a class="link" target="_blank" href="{{refer}}" title="{{link[0]}}">{% include icon.html id=id %}</a>
{% endfor %}
</nav>
{% include figure.html image="/assets/ZacharySkidmore.png" position="right" %}
I am a staff scientist at the McDonell Genome Institute at Washington University in Saint Louis. My undergraduate work was completed at the Ohio State University where I obtained a B.Sc. in biology. Graduate work was performed at the University of Illinois where I obtained a M.eng in bioinformatcs. My research focus is in the realm of cancer biology where I use and develop tools and techniques to aid in the analysis and interpretation of cancer sequencing data. I have worked on several large sequencing projects across many cancer types and have expertise in a variety of languages (perl, R, bash, python, typescript, angular2). I am the creator and maintainer of the bioconductor package GenVisR, a graphics program designed to help visualize cohort level genomic data.
