---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can find my complete list of publications on [PubMed](https://pubmed.ncbi.nlm.nih.gov/?term=bourdenx+mathieu&sort=date). Below, I selected several projects and associated publications. 

Tau and Proteostasis
===
My recent work as post-doctoral fellow in the laboratory of **Prof. Ana Maria Cuervo** focuses on chaperone-mediated autophagy (CMA) in the context of aging and tauopathies. 

* Bourdenx et al. *Cell.* **2021** [Chaperone-mediated autophagy prevents collapse of the neuronal metastable proteome](https://doi.org/10.1016/j.cell.2021.03.048). 

Here, we first described the consequences of **CMA failure** to neuronal proteostasis. Then, we characterized the dysfunction of CMA in a model of tau pathology and correlated it with observation made in data from Alzheimer's disease patients. We demonstrated that **CMA is not only inhibited in disease but also contributes to disease progression** by aggravating key aspect of the pathology. Last, we showed, using a first-in-class small molecule, that **targeting CMA could be of interest in tauopathies**. This publication is also described in a shorter version [here](https://doi.org/10.1080/15548627.2021.1935007).

* Caballero", Bourdenx" et al. *Nature Communications*. **2021** [Acetylated tau inhibits chaperone-mediated autophagy and promotes tau pathology propagation in mice](https://doi.org/10.1038/s41467-021-22501-9). 
	
In this publication, we focused on the consequences of tau's acetylation to its degradation. Interestingly, we observed that acetylated tau is not only a poor CMA substrate but it also blocks CMA, therefore preventing other substrates from being timely degraded. In absence of degradation through CMA, tau is re-routed to other pathways including endosomal-microautophagy, that could contribute to its extracellular release. In fact, experimental **blockage of CMA enhances cell-to-cell propagation of pathogenic tau**. 

Related to this topic, here is a review of the literature on [selective autophagy and neurodegenerative diseases](https://doi.org/10.1016/s1474-4422(18)30238-2). 

Molecular signatures of pathogenic proteins
===

In this project, we got interested in the different types of alpha-synuclein assemblies. A good amount of the current literature uses smaller, soluble, species of alpha-synuclein as a control for the injection of large, insoluble, aggregates of alpha-synuclein. In this study, we aimed to establish such model in non-human primates as the similarity of their dopaminergic neurons with human neurons is a strong advantage for preclinical research. However, we were surprised by the fact that, contrary a large literature in rodents, non-human primates were as sensitive to soluble alpha-synuclein as to insoluble alpha-synuclein. Indeed, both species triggered the same level of neurodegeneration in monkeys (but not in mice). This observation suggests that **primates are uniquely sensitive to alpha-synuclein toxicity**.

In order to understand the pathogenic mechanisms engaged by both species of alpha-synuclein, we used an agnostic and holistic approach. We analyzed a large number of known contributors to alpha-synuclein toxicity and dopaminergic cell death: autophagy dysfunction, protein aggregation, neurotransmitter imbalance, gliosis, etc. Facing such a large amount of data, we relied on the unique power of machine-learning to identify patterns within complex sets of data. With [Dr. Aurelien Nioche](https://aureliennioche.github.io/), we designed an *ad hoc* **wrapper feature selection method**. To do so, we trained a simple neural network, the perceptron, to predict the level of degeneration using values from the different contributors to degeneration that we investigated. That approach allowed us to understand that each alpha-synuclein specie was associated with a unique set of predictors, therefore implying distinct pathogenic mechanisms. Overall, this study contributed to demonstrate the true **multifactorial nature of parkinsonian degeneration**. 

* Bourdenx et al. *Science Advances*. **2020**. 
[Identification of distinct pathological signatures induced by patient-derived α-synuclein structures in nonhuman primates](https://doi.org/10.1126/sciadv.aaz9165)


Lysosomal welfare
===
During my graduate work working with Dr. Benjamin Dehay, I got interested in the welfare of the cell's degradative organelle: the **lysosome**. This organelle is acidic in nature and that low pH is essential to its proper functionning. Benjamin Dehay, together with other scientists in different diseases, notably contributed to show that lysosomal pH is altered in the context of mutations associated with familial forms of Parkinson's disease ([paper](https://doi.org/10.1073/pnas.1112368109)). Here, we developed a nanoparticle-based approach to rescue lysosomal pH. Interestingly, we observed that restoring the normal acidic pH of lysosomes in various pathological contexts was sufficient to release the upstream accumulation of undegraded materials. 

* Bourdenx et al. *Autophagy*. **2016**. [ Nanoparticles restore lysosomal acidification defects: Implications for Parkinson and other lysosomal-related diseases](https://doi.org/10.1080/15548627.2015.1136769)

<!--
To automatically build the publication list
{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}-->
