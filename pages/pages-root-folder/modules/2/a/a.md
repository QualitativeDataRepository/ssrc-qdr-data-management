---
title: "Principles of Documenting Data"
layout: page-fullwidth
breadcrumb: true
header: false
hidefooter: false
module: "2a"
lesson: "Module 2, Lesson 1"
categories: [module2,modulecontent,hasexercises]
permalink: "/modules/2/a/"
next: "/modules/2/b/"
previous: false
description: "What should you document about your data and when should you do so?"
learningobjectives:
-   What “data documentation” is and what good documentation includes
-   At what point in your research you should document your data
-   What different types (or “levels”) of documentation exist  
initialquestions:
-   Why is it important to document your data?
-   What are the most important components of data to document?
-   Are there “right” and “wrong” ways to document data?
---
{% include _learningobjectivesandquestions.html %}


## Documentation Overview

At the core of good data management is documentation. Documentation
introduces, provides a detailed description of, and contextualizes your
data. It serves as a bridge to the fundamentals of your data.

Documentation can be written at many “levels” and comes in many forms
(as described below). Together, all of the documentation associated with
a research project should answer a series of important questions
(although any particular piece of documentation may only answer a subset
of those questions). Your documentation should describe your data’s key
attributes, what you did, *and why* you made the choices you made.

-   What was / is the context of data collection (empirical, theoretical or normative)?
-   How did you generate / collect the data?
-   What do the data comprise?
-   How are the data formatted, structured, and organized?
-   How did you transform or manipulate the data (e.g., modify format)?
-   How did you validate / assure the quality of the data?
-   What ethical or legal limits (e.g., confidentiality, copyright) are there on access to / use / re-use of the data?
-   (Perhaps) How did you analyze the data?

Clear, thorough documentation is helpful to you (and the “future you”), to other members of your research team (if you have research assistants or are otherwise working collaboratively), and to scholars who may re-use your data later in time. Good documentation helps you and others to remember (or come to understand) details about your data and its provenance, to assess the quality and evidentiary value of the data, and to avoid misinterpreting or incorrectly using the data. If you share some or all of your data (as discussed in the next module), good documentation improves the processing and archiving of your data, and facilitates the creation of good metadata and an accurate catalog record for a published data collection.

The specific types of documentation that might best introduce, describe, and contextualize data differ from research project to research project. Below we offer some examples of types of data documentation that you might produce as you carry out a research project: 

-   Questionnaires used for surveys or semi-structured interviews
-   Guidance materials used for team-based fieldwork
-   Instructions for focus group facilitation
-   Consent forms and information sheets
-   Approved IRB application
-   Permissions or licenses from copyright holders
-   Description of methods used to analyze the data
-   Description of fieldwork and project context
-   Description of how derived materials (individual files or variables) were created
-   Coding schemas

## When to Document Data

Documentation plays an important role throughout the lifecycle of your research project. You engage in different types of documentation tasks at each stage of the research lifecycle.

-   *When you are beginning to plan your research* think of the different types of documentation you will need and create templates for each type. For instance:
    -   Generate a template for your archive log.
    -   Create a template for “informal metadata” from interactive data collection.
    -   Create a field observations template (see the next lesson for more on this type of template).

-   You create the bulk of documentation *as you are collecting / generating data*; use the templates you created to:
    -   Create documentation relating to individual files.
    -   Create documentation relating to variables.

-   *As you analyze your data and write* you finalize your documentation. For example:
    -   Pull together and organize existing documentation.
    -   Finalize project-level documentation.

In particular when you are deep in the trenches generating data, you may feel that working on documentation is not the best use of your time. To the contrary, while you’re collecting / generating data is the *best* moment to document them. Systematically capturing all relevant information about your data as you gather / create them -- i.e., when that information is most available to you -- will allow you and others to make the best use of your data.

## Levels of Documentation

It is helpful to think of documentation by the unit of data it documents. Some information refers to the whole project. Other information refers to an individual file. Sometimes information refers to an individual variable, although this is far more common in quantitative work. No matter at what level you are documenting data, documentation files should be clearly labeled using a consistent labeling schema.

### Project Level Documentation 

Project level documentation describes the general parameters of your project. This type of documentation typically begins with a high level overview of your project and its focus. Thereafter, you describe the “what,” “who,” “when,” and “how” of data collection / generation. 

-   Describe the *what* of your data
    -   What types of data are you collecting?
    -   What is their content?
-   Document anyone *who* contributed to a project -- research assistants, translators, transcribers, interviewers, coders, etc. -- and what role they played.
-   Document *when* any important project-related events occur.
-   Describe *how* you / your team collected / generated the data, detailing important methodological choices, for example:
    -   How did you pick interview respondents?
    -   How did you recruit focus group participants?
    -   How did you pick research sites?
    -   How did you select archival documents?
    -   Why did you do what you did?
    -   If you deviated from your original data collection plans, in what ways and why?

As you generate data you should keep informal but complete and accurate
lists to document these activities. Spreadsheets are a great way to keep
track of, for example, which websites you consult, whom you interview,
or what documents you review. Later, you can formalize these lists into
clear documentation.

### File Level Documentation

File-level documentation reflects the contents of an individual data file. Often, you keep track of this information in the header of a file/document. Alternatively, you can record information using the file “properties”, which makes descriptions of a file and its content visible to your computer’s operating system. You can construct templates for either type of documentation, and different types of data files, before you start your research so the information is structured similarly across different files of the same type.

Software tools can help you create file-level metadata. You may already use a reference manager like [Zotero](https://zotero.org), [Mendeley](https://mendeley.com), or [Endnote](https://endnote.com) to keep file-level metadata for your documents. These tools are most often used for academic work (e.g,. scholarly articles), but you can also use them to store newspaper articles, archival documents, or even interview transcripts plus descriptive information for each document such as date collected, location collected, people involved, main topics, etc.

There are other tools that can help you to keep track of documents. For example, the [Tropy software](http://tropy.org) was developed by historians to facilitate keeping track of and organizing large numbers of pictures taken in archives.

### Variable Level Documentation

If you conduct mixed-methods research, you may measure or construct individual variables. Quantitative variables should be documented in a codebook that lists details such as (for a survey) the exact question asked, the scale used, and any additional coding (such as non-response, not asked, etc.).

Ideally, you will also integrate this information directly into your data using your statistical software. You can do so with the label commands [in Stata](https://stats.idre.ucla.edu/stata/modules/labeling-data/) or the `VALUE LABEL/VARIABLE LABEL` commands [in SPSS](https://www.spss-tutorials.com/spss-set-variable-labels-with-syntax/). In R, you can assign value labels by [assigning labels](https://www.statmethods.net/input/valuelabels.html) to levels of factors; there is no standard support for variable labels in R, but several packages provide support; we recommend using the [haven](https://cran.r-project.org/web/packages/haven/index.html) package, specifically the `haven:labelled()` function. See for example [this excellent codebook](https://doi.org/10.7910/DVN/WPVSMH/SPP6PL) by Boas, Hidalgo, and Melo.

{% include _exercise.html exerciseid="8" %}
