

# Model Evaluation and Explanation


In this course, we will aim to answer one key question, through a multidisciplinary
examination: 

```{admonition}
:class: hint 
What does it mean to say:
> an AI can do that
```

We will begin with a review of model evaluation for simpler ML models, emphasizing the more 
abstract goals that underlie the standard evaluation procedures.  
Next, we will consider how far away the claims of abilities of AI from marketing materials are
from what these metrics can show us study various AI benchmarks to see what we can make 
rigorous claims about. 
In the second part of the course, we will study model explanation techniques, again starting 
with simple models where we can build good intuition and then working up to what we can do 
for  deep neural networks with millions-hundreds of billions of parameters. 

<!-- Complete this [form to request a permission number]() -->



## Course structure

**Spring 2025: TTh 5:00-6:15pm**

There will be 1-3 papers or freely available textbook chapters to read most weeks. 
Most class sessions will be focused on a discussion of the paper(s) assigned for that 
class session.  

While we study up-to-date papers of benchmarks and new model evaluation techniques, 
students will prepare short, lightening-talk style presentations of papers. For these class
sesssions each student will read and present a different paper and then we will discuss them
as a group.   

## Evaluation

Students will have to: 
- present lightning-talk (5min) style presentations of papers
- engage in course discussions
- complete reading reflections/article critques
- meet project milestones
- complete a project developing a (part of) an AI benchmark



## Project

:::::{warning}
This is a first draft and will be refined before students should start working on it

```{important}
Do not use this to try to start the project early
```
:::::

The project will be completed by meeting several milestones:
- evaluate ideas based on interest from a group-created list of ideas
- propose an AI benchmark component
- peer review of proposals
- consolidation into teams[^teams]
- implement at least one benchmark task
- evaluate an open source LLM [^llmcredits]
- apply explanation techniques to better understand *why* it performs as it does
- extend the benchmark with a task that gives different performance [^performancevary] 
- complete a final conference-paper style report 

[^teams]: depending on enrollment and similarity of proposal topics benchmarks
 may be completed in teams or indvidually but the proposal stage and peer review will 
 be individual assignments. Teams will be expected to have more tasks in their benchmarks
 than individuals. 

[^llmcredits]:Students motivated to extend their benchmark and complete a broader evaluation 
in order to submit their project to, eg the NeurIPS Datasets & Benchmarks track 
may be provided credits to evaluate commercial LLMs may be available, but non-free
evaluation will not be required to complete the project. 

[^performancevary]: if the LLM scores well on the first task, add one where it does not score well; if it scores poorly on the first add one that it can do well

<!-- ## LLM use 

All work must reflect the students understanding. LLM assistants may be used to 
improve writing quality for assignments where writing quality will be assessed. 
However, when quality will be assessed, concision and proper style will also be
required. Any submitted writing that contains classic "bot" phrasing or that is
overly verbose and off topic will not be assessed and earn zero credit. 

At the instructor's discretion, any submitted work may be re-assessed by oral 
exam to ensure that the student actually understands.  -->

## Tools

This class meets in person, synchronously. 

Most course work will be done in GitHub repos, you may choose to work in Github.com, a codespace, or locally for text work. 

A reading list will also be shared via [zotero](https://www.zotero.org/groups/5719529/evalexplainai)

## Annotated Bibliography

::::{warning}
This is a tentative list of papers and references for the course. It will contain sources relevant to the course, but not all will be assigned as readings.
::::

### Intro and Philosophical

@agre2014toward

### Benchmarks

- 