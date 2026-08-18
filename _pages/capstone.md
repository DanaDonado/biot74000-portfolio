---
permalink: /capstone/
title: "Capstone Connection"
author_profile: true
---

<!--
  ============================================================================
  SECTION 4: CAPSTONE CONNECTION  (20 points)  |  Suggested length: 200–300 words
  ============================================================================
  A concise, professional summary of how you applied bioinformatics to your
  capstone project. This draws from your Assignment 2 work — it is a
  professional-context summary, NOT a repeat of the assignment.

  INCLUDE:
    - A 2–4 sentence description of your capstone project (assume a general
      audience who is not in your program)
    - The bioinformatics tool, dataset, or method you applied in Assignment 2,
      and why it was relevant
    - What you found or produced, described in plain language
    - 1–2 sentences on how this bioinformatics component strengthened your capstone
    - (Optional) embedded images or output figures — see the guide for how to
      add an image

  HOW TO EDIT:
    - Replace the placeholder text below with your own.
    - Delete these grey instruction notes before you submit.
  ============================================================================
-->

## My Capstone Project

My capstone project investigates whether nisin and rosmarinic acid can reduce the growth of _Listeria monocytogenes_, a food-borne pathogen that can be difficult to control in food environments. We are testing different concentrations of these two antimicrobials to understand how effectively they inhibit bacterial growth and whether together they could be useful as potential approaches for controlling _L. monocytogenes_. This work is important because finding effective ways to control this pathogen can contribute to safer food production.

## The Bioinformatics Component

For my individual bioinformatics component, I used R and RStudio to analyze the growth-curve data collected from my capstone experiments. The dataset was collected using an Agilent BioTek Synergy H1 microplate reader and contained 49 time points over 24 hours, with measurements for the different treatments and their corresponding blank controls. I used R to select the untreated control, four nisin concentrations, and their blank controls, perform blank correction, calculate the mean OD600 values, and generate growth curves. R was a good choice because it allowed me to process the large dataset systematically and create a reproducible analysis rather than manually working through the measurements.

The analysis showed a concentration-dependent effect of nisin on _Listeria monocytogenes_ growth. The highest concentration tested, 0.060 mM nisin, showed the greatest inhibition and maintained the lowest optical density throughout the 24-hour period. The untreated control showed the most growth, reaching approximately OD600 = 2.0, while the lower nisin concentrations delayed growth but did not suppress it to the same extent.

## Why It Strengthened My Capstone

Using R strengthened my capstone by turning a large set of raw experimental measurements into a clear visual comparison of how the different nisin concentrations affected bacterial growth. It also gave me a reproducible way to process and interpret the data, making it easier to connect our laboratory results back to the biological question.

<!--
  OPTIONAL — to embed an image or figure you produced:
  1. Upload the image file to the images/ folder in your repository.
  2. Add a line like this where you want it to appear (remove the leading
     grey-comment marks):

     ![Growth of Listeria monocytogenes treated with varying concentrations of nisin](/biot74000-portfolio/images/Growth%20of%20Listeria%20monocytogenes%20Treated%20with%20Varying%20Concentrations%20of%20Nisin.png)

  Make sure the path matches your repository name.
-->
