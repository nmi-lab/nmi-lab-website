---
title: Deep Continuous Local Learning
summary: Learning in Spiking Neural Networks with the Tools of Deep Learning
tags:
- Spiking Neural Networks
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Neftci et al. 2016
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

A growing body of work underlines striking similarities between biological neural networks and recurrent, binary neural networks. A relatively smaller body of work, however, addresses the similarities between learning dynamics employed in deep artificial neural networks and synaptic plasticity in spiking neural networks. The challenge preventing this is largely caused by the discrepancy between the dynamical properties of synaptic plasticity and the requirements for gradient backpropagation. Learning algorithms that approximate gradient backpropagation using local error functions can overcome this challenge. Here, we introduce Deep Continuous Local Learning (DECOLLE), a spiking neural network equipped with local error functions for online learning with no memory overhead for computing gradients. DECOLLE is capable of learning deep spatio-temporal representations from spikes relying solely on local information, making it compatible with neurobiology and neuromorphic hardware. Synaptic plasticity rules are derived systematically from user-defined cost functions and neural dynamics by leveraging existing autodifferentiation methods of machine learning frameworks. We benchmark our approach on the event-based neuromorphic dataset N-MNIST and DvsGesture, on which DECOLLE performs comparably to the state-of-the-art. DECOLLE networks provide continuously learning machines that are relevant to biology and supportive of event-based, low-power computer vision architectures matching the accuracies of conventional computers on tasks where temporal precision and speed are essential.



