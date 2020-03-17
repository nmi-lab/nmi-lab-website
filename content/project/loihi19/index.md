---
title: Loihi Embedded Plasticity Dynamics for Deep Continuous Local Learning
summary: Learning on the Intel Loihi Neuromorphic Research Chip
tags:
- Spiking Neural Networks
- Learning
- Synaptic Plasticity
date: "2016-02-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Intel Loihi and DAVIS 240 Silicon Retina
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
Recent breakthroughs in deep neural networks and deep reinforcement learning in a wide variety of cognitively relevant tasks prompts the question whether the ingredients of their success are compatible with neurobiology and neuromorphic hardware. Recent work in three-factor synaptic plasticity rules suggests that synaptic plasticity dynamics are compatible with gradient-based learning, provided that credit can be assigned to hidden neurons. Our preliminary work shows that local errors computed from layer-wise loss functions can approximate credit in deep layers and enable spiking neurons to learn complex tasks, outperforming existing spike-based BPTT methods in learning speed and accuracy, while relying on spatial complexity linear in the number of neurons. The resulting learning rule is local and largely compatible with the Loihi architecture. Our team will showcase variations of this strategy  in the Intel Loihi hardware and demonstrate them on suitable computer vision and reinforcement learning benchmarks using the Dynamic Vision Sensor.


