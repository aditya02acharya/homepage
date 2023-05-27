---
title: Touchscreen Typing As Optimal Supervisory Control
summary: This project presents a computational model to improve touchscreen keyboard usability and design intelligent text entry solutions. We explore the interaction between hand-eye coordination and its effect on typing. 
tags:
date:

# Optional external URL for project (replaces project detail page).
external_link: "https://userinterfaces.aalto.fi/touchscreen-typing/"

image:
  caption:
  focal_point: Smart

links:
url_code: "https://github.com/aditya02acharya/TypingAgent"
url_pdf: "https://userinterfaces.aalto.fi/touchscreen-typing/resources/touchscreen_typing_as_optimal_adaptation.pdf"
url_slides: ""
url_video: "media/typist.mp4"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

**MOTIVATION**

Improve our understanding of how people adapt multitasking behavior.

**WHY SHOULD I CARE?**

Typing on touchscreen is hard, because both finger movements and proofreading of possible errors need vision. Yet, humans are able to divide attention efficiently. Our computational model discovers ways to efficiently move eyes and fingers while typing, and as a result is able to simulate human-like typing. The model can be used to improve touchscreen keyboard usability and design intelligent text entry solutions.


**ABSTRACT**

Traditionally, touchscreen typing has been studied in terms of motor performance. However, recent research has exposed a decisive role of visual attention being shared between the keyboard and the text area. Strategies for this are known to adapt to the task, design, and user. In this paper, we propose a unifying account of touchscreen typing, regarding it as optimal supervisory control. Under this theory, rules for controlling visuo-motor resources are learned via exploration in pursuit of maximal typing performance. The paper outlines the control problem and explains how visual and motor limitations affect it. We then present a model, implemented via reinforcement learning, that simulates co-ordination of eye and finger movements. Comparison with human data affirms that the model creates realistic finger- and eye-movement patterns and shows human-like adaptation. We demonstrate the model's utility for interface development in evaluating touchscreen keyboard designs.
