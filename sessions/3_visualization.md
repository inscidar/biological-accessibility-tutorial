---
layout: page
title: "Hands-on session 3: Designing accessible biomedical data visualization"
permalink: /visualization/
---

## Overview

* You will learn accessibility guidelines for biological visualizations.
* These guidelines are based on Chartability ([Elavsky et al.](https://www.frank.computer/chartability/)).
* (Activity) You will evaluate two biological data visualizations using the guidelines.

## [Chartability](https://chartability.fizz.studio/)	
* A set of heuristics for ensuring the accessibility of data visualizations and interfaces
* Helpful for both accessibility experts and novices
* We mainly use “critical” heuristics

## “Critical” Checklist
* Low contrast
* Small text size
* No explanation for purpose or for how to read
* No title, summary, or caption
* Data density is inappropriate

## Color
* Must have a contrast ratio of at least 4.5:1 ([Contrast Checker](https://webaim.org/resources/contrastchecker/))
* Use colorblindness-friendly palette (e.g., [okabe-ito](https://thenode.biologists.com/data-visualization-with-flying-colors/research/))
* Human cannot easily differentiate more than 10 colors
    * If necessary, group and filter categories
* Avoid using colors only
    * Different shapes of mark
    * Bar charts with different textures

## Textual Descriptions
* Title, summary, or caption
* Axis labels
* Legend labels

## “Critical” Checklist for Interactive Charts
* Interaction modality only has one input type
* No interaction cues or instructions
* No data table or spreadsheet
* Navigation and interaction is tedious

## Activity (15 mins)
Evaluate the accessibility of two biological visualizations using Google Form ([Link](https://forms.gle/iRDDFXqMLqUrTZrv8)).

* [Spitzer et al. (Nature Genetics 2025)](https://www.nature.com/articles/s41588-025-02168-4)
![A boxplot with dots overlaid, showing the proportion on the y-axis and cell types on the x-axis, with two colors used, labeld "T1 (primary)" and "T2 (recurrence)."](../assets/imgs/a11y-vis-activity-1.jpg)

* [Corces et al. (Nature Genetics 2020)](https://www.nature.com/articles/s41588-020-00721-x)
![A chromosome 3 overview, multiple bar tracks, gene annotations, and circular line connections are shown.](../assets/imgs/a11y-vis-activity-2.jpg)

## Choosing Chart Types
There are many different chart types that you can choose (e.g., 66 chart types in [datavizcatalogue](https://datavizcatalogue.com).

![Chart types are listed in grid, each represented with an icon in a circle.](../assets/imgs/chart-types.png)

## We Love Circos, But Is It Most Effective?
![A screenshot of a new article including three Circos plots, which shows line connections between different regions of human or other species' chromosomes.](../assets/imgs/circos.jpg)

## Circular vs. Linear Layouts
This examples shows a limitation of circular layouts when perceiving the difference of bars that are positioned in distant.

![A circular visualization showing bars where two bars that are distant are highlighted in red for comparison.](../assets/imgs/circular-layout.jpg)

![A linear visualization showing the same data in the circular visualization, where two bars that are distant are highlighted in red for comparison.](../assets/imgs/linear-layout.jpg)

## Sequence Logos

![A sequence logos plot showing four letters stacked on top of each other along a x-axis.](../assets/imgs/sequence-logos.jpg)

The use of inaccessible colors and distorting the height of letters in Sequence Logos is not accessible and effective visual encoding for human perception.

## Alternative Sequence Logos
* Maguire et al. 2014
![An alternative sequence logos showing bars instead of letters.](../assets/imgs/alt-sequence-logos-1.jpg)

* Marek et al. 2014
![An alternative sequence logos showing lines that correspond to individual sequences, instead of using letters.](../assets/imgs/alt-sequence-logos-2.jpg)

## Visualization Guidelines
* VisGuides ([visguides.org](https://visguides.org)) is a resource and an open community for visualization guidelines.

![A screenshot of VisGuides showing list of topic categories on the left, such as Visual Design and Theory, and a community panel on the right, showing questions and discussions that VisGuides users posted.](../assets/imgs/visguides.jpg)
