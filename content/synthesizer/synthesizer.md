---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank  # See https://wowchemy.com/docs/page-builder/
headless: true  # This file represents a page section.
weight: 10  # Order that this section will appear.
title: "About the Testbed"
subtitle: ""
hero_media: 
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
advanced:
  css_style:
  css_class:
---
There is still more to come in the future! Feel free to contact us to develop a new anomalous mode together. The status of the GPASS is publicly available via sensor and video online <a href="https://thingspeak.com/channels/1289599"> here</a>.

Our conference proceeding "A General-Purpose Anomalous Scenario Synthesizer for Rotary Equipment" entered the Automation Award Finalist in ICRA 2021!!

The GPASS software and hardware apparatus are detailed in [1]. Currently, we support three health mode controls, including rotational damping (D-mode), large stationary shear load (N-mode), and vibratory shear load (V-mode). These conditions can be commanded either healthy or anomalous, with a specific anomalous attribute. The attributes are:

D-mode: Discrete damping motor resistance from 1 to 15Ω, with 15Ω as a healthy operating condition.

N-mode: Continuous shear load from 0-15N, with 0N as a healthy operating condition.

V-mode: Discrete vibratory excitation from 0-25Hz, with 0Ω as a healthy operating condition.

In [2], we talked about how to generate Markov-Chain based packets to generate automated health mode trajectory. You can participate in the GPAD archive augmentation process by submitting your own packet! As an instructional sample, the following packet:
