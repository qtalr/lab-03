# Lab 03: Trace the datascape

## Preparation

- Read/ annotate: [Recipe \#3](https://qtalr.github.io/qtalrkit/articles/recipe-3.html). You can refer back to this document to help you at any point during this lab activity.

## Objectives

- Review using Markdown syntax for formatting, including tables, numbering sections, and citations and references
- Review reading, inspecting, and writing data using R functions and Quarto code blocks
- Learn to describe data using prose and code in a Quarto document
- Practice interpreting datasets through statistical, tabular, and visual summaries.

## Instructions

### Getting started

1. Create a Quarto document using the RStudio toolbar
  - Provide the title: "Lab 03: Trace the datascape"
  - Provide the author: \<Your Name\>
2. Render the Quarto document (without changes)
  - Click the 'Render' button on the RStudio toolbar
  - Save the Quarto file with the name `lab-03.qmd`.

### Trace the datascape

In the repository for this lab, you will find three data files corresponding to the data origin, data dictionary, and the data itself.

  - `data_origin.csv`
  - `data_dictionary.csv`
  - `data.csv`

These are the same files you used in Lab 02 which correspond to a transformed version of the [Manually-Annotated Subcorpus (MASC)](https://anc.org/data/masc/about/). I suggest you review the data dictionary and data origin files and/ or your work from Lab 02 to help refesh your memory about the data.

1. Create the following sections and subsections in your `.qmd` document:

  - Overview
    - About the data
    - Assessment aims
  - Setup
    - Load packages
    - Read data
    - Inspect data
  - Assessment
    - Statistical overview
    - Tabular summaries
    - Visual summaries

2. In the section "Overview", summarize the data and describe the aims of your assessment. Include the following information:

  - What is the name of the data source?
  - Where did it come from?
  - What is the sampling frame?
  - What are you trying to learn about the data?

3. In the section "Setup", use strategies from Recipes 2 and 3 to load the necessary packages to read and inspect rectangular data. You may choose to subset your data to include only the variables and/ or observations you need for your assessment. Then, write a paragraph describing the data. Include the following information:

  - How many variables are included?
  - What are the variable types?
  - How many observations are included?

4. In the section "Assessment", use strategies from Recipe 3 to assess the data. You may choose to include a statistical overview, tabular summaries, and/ or visual summaries as part of your assessment. Include at least one table and one figure in your assessment. These should be cross-referenced in your prose description of the dataset assessment.

5. Render the `.qmd` as a PDF or a Word document

6. (optional) Explore adding the following table and plot enhancements to your Quarto document:

  - `kableExtra` package
    - `kable_styling()`: `font_size`, `striped_rows`, `full_width`, *etc*.
  - `ggplot2` package
    - `theme_*()`: `theme_bw()`, `theme_classic()`, `theme_minimal()`, *etc.*
    - `labs()`: `labs(title = "Title", subtitle = "Subtitle", x = "X-axis", y = "Y-axis")`

## Assessing your progress

1. Add a section which describes your learning in this lab.

Some questions to consider:

  - What did you learn?
  - What did you find most/ least challenging?
  - What resources did you consult?
    - Instructor? R or Quarto documentation, Websites (provide links)?
  - What more would you like to know about Trace the datascape in R and/ or Quarto?
    - Find potential resources you might consult to continue your learning. Provide links and a brief description of the resource.

## Submission for feedback

1. To prepare your lab report for submission you will need to render your Quarto document to PDF or Word.
2. Download this file to your local computer.
3. Submit your report as described by your instructor.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
