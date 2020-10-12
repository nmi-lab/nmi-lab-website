---
title: "Memory-Efficient Synaptic Connectivity for Spike-Timing- Dependent Plasticity"
date: 2019-01-01
publishDate: 2020-04-29T17:50:07.288960Z
authors: ["Bruno U. Pedroni", "Siddharth Joshi", "Stephen R. Deiss", "Sadique Sheik", "Georgios Detorakis", "Somnath Paul", "Charles Augustine", "Emre O. Neftci", "Gert Cauwenberghs"]
publication_types: ["2"]
abstract: "Spike-Timing-Dependent Plasticity (STDP) is a bio-inspired local incremental weight update rule commonly used for online learning in spike-based neuromorphic systems. In STDP, the intensity of long-term potentiation and depression in synaptic efficacy (weight) between neurons is expressed as a function of the relative timing between pre- and post-synaptic action potentials (spikes), while the polarity of change is dependent on the order (causality) of the spikes. Online STDP weight updates for causal and acausal relative spike times are activated at the onset of post- and pre-synaptic spike events, respectively, implying access to synaptic connectivity both in forward (pre-to-post) and reverse (post-to-pre) directions. Here we study the impact of different arrangements of synaptic connectivity tables on weight storage and STDP updates for large-scale neuromorphic systems. We analyze the memory efficiency for varying degrees of density in synaptic connectivity, ranging from crossbar arrays for full connectivity to pointer-based lookup for sparse connectivity. The study includes comparison of storage and access costs and efficiencies for each memory arrangement, along with a trade-off analysis of the benefits of each data structure depending on application requirements and budget. Finally, we present an alternative formulation of STDP via a delayed causal update mechanism that permits efficient weight access, requiring no more than forward connectivity lookup. We show functional equivalence of the delayed causal updates to the original STDP formulation, with substantial savings in storage and access costs and efficiencies for networks with sparse synaptic connectivity as typically encountered in large-scale models in computational neuroscience."
featured: false
publication: "*Frontiers in Neuroscience*"
url_pdf: "https://www.frontiersin.org/article/10.3389/fnins.2019.00357"
doi: "10.3389/fnins.2019.00357"
---

