---
title: Research
nav:
  order: 1
  tooltip: Our research projects
---

# Research

{% include section.html %}

## Research Themes

{% capture text %}

Individuals with neurological disorders often exhibit abnormal gait and poor balance due to factors such as muscle weakness, spasticity, deformities, or self-developed compensatory movements. Detecting and correcting these compensations in real time is critical to improving clinical outcomes, promoting natural gait, reducing overuse injuries, pain, and fall risk. Our group works on designing smart wearable devices equipped with customized, real-time on-device machine learning to detect compensatory movements and provide real-time cueing or stimuli, enabling human-in-the-loop interaction to support continuous adaptation and improvement. 

{% endcapture %}

{%
  include feature.html
  image="images/research1.jpg"
  link=""
  title="Smart Wearable Electronics"
  flip=true
  style="bare"
  text=text
%}


{% capture text %}

Remote patient monitoring offers clinicians the full picture of their patients in the community. Consumer-grade wearables (e.g., Fitbit, Apple Watch) offer great potential for remote health monitoring by capturing multi-modal data like heart rate, activity, and sleep. Our group models longitudinal wearable data to develop novel digital biomarkers and predictive AI, aiming to support clinical decision-making as well as engaging patients by providing them feedback, ultimately enhancing community-based remote health monitoring.

{% endcapture %}

{%
  include feature.html
  image="images/research2.jpg"
  link=""
  title="Novel Wearable-derived Biomarkers and Predictive AI"
  flip=true
  style="bare"
  text=text
%}


{% capture text %}

Uncertainty in wearable data has been a critical challenge in developing reliable AI for wearables. This uncertainty often undermines the robustness and generalizability of AI models due to individual variability, missing data, and limited ground truth in real-world use. Our group aims to tackle these challenges by developing and applying different learning strategies to enhance the AI training process and improve performance when AI is being deployed.

{% endcapture %}

{%
  include feature.html
  image="images/research3.jpg"
  link=""
  title="Learning Strategies to Build Robust AI using Health Sensor Data"
  flip=true
  style="bare"
  text=text
%}