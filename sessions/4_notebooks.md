---
layout: page
title: "Hands-on session 4: Making computational notebooks accessible"
permalink: /notebooks/
---

This session focusses on accessibility of computational notebooks. Computational notebooks are essential in computational biology. They are used to interact and present data. In this session, we focus on Jupyter Notebooks, as they are one of the most widely used type of notebooks, but these principles extend to other types of notebooks as well. As with other documents, notebooks should also be Perceivable, Operable, Understandable, and Robust.

## Notebooks used in this session
This session uses the following notebooks: 
1. Notebook with guidelines [Google Colab](https://colab.research.google.com/drive/1n-kETLh2XHIgsxCG4tu2gdxVEjO7rjOy) and [download](../assets/notebooks/1-notebook-overview.ipynb)
2. Exercise on squidpy tutorial [Google Colab](https://colab.research.google.com/drive/1v9XcolBFJk_qiC32d9UALIkpV9vCr6e4) and [download](../assets/notebooks/2-squidpy-slideseqv2.ipynb)


## Current state of accessibility in notebooks
[Potluri et al., 2023](https://arxiv.org/pdf/2308.03241), assessed 100000 notebooks for accessibility, of which 92050 Python notebooks. We highlight a few findings:
- They found that 42.95% of notebooks have at least 1 programmatic figure, of which 99.81% do not have alt text. Of the 609 images with alt text, only 1 is generated with code, while the rest are added with markdown. Most of these alt texts are not useful (e.g., "image", "colab", "png"). So, most figures are not accessible through text.
- They found that 34.1% of notebooks had at least one table, so a vast majority of the notebooks do not display their data in a tabular way. Only 4.53% of notebooks had a table close to a figure, suggesting accompanying data with a figure. The average table has 15 rows and 140 columns, or 2100 cells.
- They found that 28.90% notebooks had a `<h1>` element in their first cell.


## How to make your notebooks accessible
Here, we focus on three themes to make your notebook more accessible: 
- Navigability (landmarks, notebook size, links). This ensures a notebook is perceivable and operable. Someone needs to be able to navigate the notebook, e.g. by using proper headings.
- Data interpretability (figures, tables). This ensures a notebook is perceivable and understandble. By providing the data in manageable and annotated tables and providing alternative texts for figures, someone can explore the data patterns even without seeing these.
- Exporting (format, theme). Our main focus is on navigability and data interpretability, but we will also highlight how exporting a notebook can have a big impact on its accessibility.


## Checklist
As part of this tutorial, we provide the following checklist. This checklist does not guarentee full accessibility, but rather is meant to give a quick hands-on method to directly improve the accessibility of your notebooks.

1. Single `<h1>` element at the top of the notebook
2. First cell explains the background of the notebook
3. Rest of the notebook is structures with `<h2>` - `<h6>` elements
4. Markdown and code comments explain the notebook
5. Expected errors are marked
6. Links have a descriptive name
7. Table of the data is included
8. Tables have a caption
9. Tables have limited number of rows and columns
10. Static images have alt text
11. Dynamic images have alt text where possible
12. Notebook is not too long
13. An HTML version of the notebook is available if possible


## References
- [Project Notebooks For All](https://iota-school.github.io/notebooks-for-all/)
- [Tutorial Accessible Pandas DataFrames](https://tonyfast.github.io/tonyfast/xxiii/2023-01-02-accessible-dataframes-basic-indexes.html)
- [Repository Jupyter Accessibility](https://github.com/jupyter/accessibility/)
- [Repository MatplotAlt](https://github.com/make4all/matplotalt) and [documentation](https://matplotalt.readthedocs.io/en/latest/)
- [Paper of survey of notebook accessibility - Potluri et al., 2023](https://arxiv.org/pdf/2308.03241)
- [Slides of notebook best practises - Isabela Presedo-Floyd, 2023](https://docs.google.com/presentation/d/1LBcEOGhZfLXCaGAWUaGl4c6O5AXBBXzfoA9dV0W-5Pc/)
- [Tutorial for making Computational Notebooks accessible](https://create.uw.edu/a11y-in-action/accessible-courses/making-computational-notebooks-accessible/)
