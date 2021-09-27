---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank  # See https://wowchemy.com/docs/page-builder/
headless: true  # This file represents a page section.
weight: 15  # Order that this section will appear.
title: "Our Work"
subtitle: ""
hero_media: 
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
advanced:
  css_style:
  css_class:
---
We are the Intelligent Health Monitoring and Predictive Maintenance Project from the Mechatronics Research Laboratory at MIT. This webpage serves as an access point where you can find out information about our synthesizer apparatus: A General-Purpose Anomalous Scenario Synthesizer (GPASS), and the synthetic dataset:  A Synthetic Time-Series General-Purpose Anomaly Dataset in Physical Domain (GPAD).

Dear colleagues, you all know that anomalous event datasets are difficult to acquire, and even more challenging to label, no matter they are in the physical or virtual domain, or whether these events are natural or synthetic. To deal with this problem, we designed and developed a multi-modal anomalous event synthesizer for rotary machines. We call it the GPASS apparatus. It introduces an extensive range of anomalous modes, including time-invariant (TI) ones, such as defective mechanical components and imbalanced inertia. A unique feature of the GPASS setup is it actively controls the health condition of the plant in a time-varying (TV) fashion. During a normal runtime, introduce three types of TV operational conditions to the plant, including TV rotational damping behavior (e.g., in an injection molding machine), TV large shear load (e.g., on vehicle drivetrains), and TV vibratory excitation (e.g., on almost every physical machine). The health condition are actively controlled to be normal or anomalous. Additionally, all health conditions, TI and TV ones, are LABELED synchronously with the plant’s operation! For detailed technical consideration, refer to [1] and <A HREF="synthesizer">Synthesizer </A> section.

Its product is the time-series general-purpose anomalous event dataset! In the <A HREF="data">Dataset </A> section on top, you gain access to all the synthetic operation condition data sequences under various health modes. What’s more exciting is that even more data sequence are coming as we scale up the data archive! We hope to cover an operation condition as extensive as possible, so that you can transfer more easily the GPAD-trained model onto the setup that you want to monitor. Additionally, you can also access our dataset generation pipeline by submitting an API packet in the <A HREF="test">API </A> section up above. We will conduct the anomalous event synthesis at the earliest. For more detail about the dataset, refer to [2].

Refer to individual sections on the top of this webpage for more detail.

[1] Y-F. Yeung, A. Alshehri, L. Wampler, M. Furokawa, H. Takayuki, K. Youcef-Toumi, "A General-Purpose Anomalous Scenario Synthesizer for Rotary Equipment", in the IEEE International Conference on Robotics and Automation (ICRA), Automation Award Finalist, 2021. 

[2] [Under Review] Y-F. Yeung, A. Paul-Ajuwape, F. Tahiry, M. Furokawa, H. Takayuki, K. Youcef-Toumi, " GPAD: A Synthetic Time-Series General-Purpose Anomaly Dataset in Physical Domain", in the IEEE International Conference on Robotics and Automation (ICRA), 2022.
