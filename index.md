

# Evaluating AI and AI Evaluations


In this course, we will aim to answer one key question, through a multidisciplinary
examination: 

```{admonition}
:class: hint 
What does it mean to say:
> an AI can do that
```

We will answer this question by examining  how to **measure** what an AI can do robustly and reliably. 
We will study both evaluations of AI and evaluations of AI evaluations and along the way, you will build a benchmark. 

We will begin with a review of model evaluation for simpler ML models, emphasizing the more 
abstract goals that underlie the standard evaluation procedures. Then we will use these underlying
goals to build an understanding of the tools available for evaluating more complex systems. 
Then we will study various AI benchmarks to see what specific AI abilities we can make rigorous 
claims about. We will also compare how these rigorous claims get translated into 
nonscientific literature. 


Complete this [form to request a permission number](https://forms.gle/FranBuJd1mfpZSR38)



## Course structure

**Spring 2026: TTh 3:30-4:45 in Tyler 106pm**


There will be 1-3 papers or freely available textbook chapters to read most weeks. 
Most class sessions will be focused on a discussion of the paper(s) assigned for that 
class session.  

While we study up-to-date papers of benchmarks and new model evaluation techniques, 
students will prepare short, lightning-talk style presentations of papers. For these class
sesssions, several students each student will read and present different papers and 
we will discuss them as a group.  


:::::{warning}
The following is from Spring 2025 and is subject to minor changes for spring 2026
:::::
## Evaluation

Students will have to: 
- present lightning-talk (5min) style presentations of papers
- engage in course discussions
- complete reading reflections/article critques
- meet project milestones
- complete a project developing a (part of) an AI benchmark


The grade will be based on two components: 
- 40% course community contributions
- 60% benchmarking project 

within each of these categories some things will be graded on completion only (full points for doing it in good faith & on time) and some will be graded on quality (a more traditional score will be provided).  For quality items a rubric will be provided 1 week or more in advance. 

Remember, this is a 4 credit class with only 3 contact hours per week. This means that you should be spending a minimum of 9 hours per week on things for the course outide of class time, but most weeks probably closer to 12. When project milestones are due, expecations for community contribution will be a bit lower, and between milestones especially when I am giving feedback, you'll have more community contributions expected.

### community contribution evaluation

Community Contributions will be based on

- preparing for class, every time, so whatever different days I request thigns, there will be different ways this looks. I will ask for different evidence on different days and basically record 1 thing per day for you. (completion- based on check)
- glossary and shared notes contributions (completion-number)
- contribution to shared infrastructure (completion -number and scope)
- lightning talk presentations (quality/binary)
- contributions to class discussion (completion -number and quality)

<!--  & prismia responses -->

All of these are grouped together becasue for each of you your contributions will look different, because we are all contributing to the community, each specific contribution will be different. 

For final grading, you will receive one of: 
- meet/exceeds expecation (full credit); 
- insconsistent/slighlty below (half credit);
- far below expecation (no credit).

There will be a chance to contest your standing here at the end of the semester if you do not reach meet/exceeds expecatations and want something between

I will let you know at least every 2 weeks if I think your contributions are below, meeting, or exceeding expectations. You can cancel out a below expectation with an exceeding expectation in order to get your average up to on track. You cannot have more than 2 below expecations in a row and still get meet/exceeds in your final grade (so you cannot just exceed at the beginning and then quit)



### project evaluation 


This will be evaluated by, percentatges are of the project grade not of the final course grade
- overall  repo (quality 30%)
- your specific contributions to your project based on evidence and team mate review (quality; 20%)
- project milestones (completion 20%) 
-  report (quality 20%) 
-  presentation (quality 10%)


## Project

:::::{warning}
This is a first draft and will be refined before students should start working on it

```{important}
Dates are not yet updated for sp26, but do not use this to try to start early, formats may change
```
:::::

The project will be completed by meeting several milestones, these milestones are not likely to change and changes will be announced with a lot of warning
```{list-table}
* - project milestone
  - due date
  - submission
* - evaluate ideas based on interest from a group-created list of ideas
  - 2026-02-12 
  - course discussion
* - draft proposal an AI benchmark component
  - 2026-02-19 
  - tba
* - peer review of proposals
  - 2026-03-05 
  - form will be provided
* - consolidation into teams[^teams]
  - 2026-03-05 
  - in class
* - implement at least one benchmark task
  - 2026-03-26 
  - benchmark repo + presentation
* - benchmark map
  - 2026-04-02
  - plain text or table that indicates your plan of how many tasks
* - apply an explanation technique to better understand *why* at least one model performs as it does on your benchmark
  - 2026-04-16
  - in class demo/discussion
* - better bench self assessment for peer review 
  - 2026-04-23
  - [checklist template](https://betterbench.stanford.edu/checklist.html) in repo or paper overleaf (use google doc and convert to md for repo)
* - draft paper[^paperreqs] for peer review [^peerrev] 
  - 2026-04-23 
  - benchmark repo or overleaf, team preference, **[registration]() of the location required**
* - extend the benchmark with a task that gives different performance [^performancevary] 
  - 2026-04-23,28 
  - benchmark repo
* - in class presentation
  - 2026-04-23,28
  - presentation[^presentation] and draft paper[^draft], 
* - complete a final conference-paper[^paperreqs] style report 
  - 2026-05-06 [^approx] 
  - final paper for grading and [short reflection]() **form will be active after may 1**
* - *optional* register abstract for [neurips](https://neurips.cc/Conferences/2025/CallForDatasetsBenchmarks)
  - 2026-05-11 [^approx]
  - abstract and all authors registered in openreview
* - *optional* submit paper for neurips
  - 2026-05-15[^approx]
  - paper with all required sections to openreview, inluding [checklist](https://neurips.cc/public/guides/PaperChecklist)
* - *optional* submit supplemental materials for neurips
  - 2026-05-22[^approx]
  - paper with all required sections to openreview
```


[^approx]: final dates to be announced, these are based on last year
<!-- https://docs.google.com/forms/d/e/1FAIpQLSe85EU-DvevdyyZNRhfG5ZSe7MwAXe8psFD-eJGxD1iYRT5hA/viewform?usp=header) 
https://docs.google.com/forms/d/e/1FAIpQLSfgKq0w26jaxBKsuEsKSkXyAnmB8C0BlblsTAYyhL9qj7NlxA/viewform?usp=header-->

[^teams]: depending on enrollment and similarity of proposal topics benchmarks
 may be completed in teams or indvidually but the proposal stage and peer review will 
 be individual assignments. Teams will be expected to have more tasks in their benchmarks
 than individuals. 

[^llmcredits]:Students motivated to extend their benchmark and complete a broader evaluation 
in order to submit their project to, eg the NeurIPS Datasets & Benchmarks track 
may be provided credits to evaluate commercial LLMs may be available, but non-free
evaluation will not be required to complete the project. 

[^performancevary]: if the LLM scores well on the first task, add one where it does not score well; if it scores poorly on the first add one that it can do well

[^draft]: Your draft should be a complete paper, but may have only partial results 

[^presentation]: Your presentation should be 15 minutes, strictly enforced, so that there is time for questions

[^peerrev]: there is a [short form](https://docs.google.com/forms/d/e/1FAIpQLSdAPkOT8xL473iwW8B4rPqcnFJNyJ5xtHG9yaTVvtLYG70juA/viewform?usp=header) to complete for each benchmark, you should take notes enough to complete the forms after class, once per presenatation

[^paperreqs]: the paper should be in the style (tone and content level) of a CS conference. It should be 6-10 pages in the neurips format( [latex from neurips](https://media.neurips.cc/Conferences/NeurIPS2025/Styles.zip) or `arxiv_nips` myst template), including figures, but unlimited additional pages for references. 

## LLM use 

All work must reflect the students understanding. LLM assistants may be used to 
improve writing quality for assignments where writing quality will be assessed. 
However, when quality will be assessed, concision and proper style will also be
required. Any submitted writing that contains classic "bot" phrasing or that is
overly verbose and off topic will not be assessed and earn zero credit. 

At the instructor's discretion, any submitted work may be re-assessed by oral 
exam to ensure that the student actually understands. 

## Tools

This class meets in person, synchronously. 

<!-- - we will use prismia chat to share materials. Join link on brightspace -->
- Most course work will be done in GitHub repos, you may choose to work in Github.com, a codespace, or locally for most work. Join link for github is on Brightspace. 
- A reading list will developed collaboratively via [zotero](https://www.zotero.org/groups/5719529/evalexplainai)
- paper writing will be on [overleaf](https://www.overleaf.com/) via github, Sarah will create overleaf projects as needed so they get paid features via URI
- this site and other public materials from benchmarks will use [myst markdown](https://mystmd.org/) 

## Overall Schedule

:::{warning}
the way class time is used is subject to change, but the project milestone deadlines are unlikely to move
:::

```{list-table}

* - date
  - topic
  - due
* - 2026-01-22
  - intro & why it's hard
  - none 
* - 2026-01-27
  - novel evaluation in predictive systems + syllabus discussion + reading research discussion
  - [prep work](#readinformal) 
* - 2026-01-29
  - informal audits
  - [informal audits, etc](#copilot)
* - 2026-02-03
  - basics of evaluation in generative systems + what is a benchmark
  - [better bench, prepare to present](#betterbench) 
* - 2026-02-05
  -  synthesizing research discussion
  - TBA
* - 2026-02-10
  - benchmark spotlights  
  - spotlight presentations (all students 5 min presentation)
* - 2026-02-12
  - benchmark common structures
  - decide benchmark proposal topic (rough) 
* - 2026-02-17
  - benchmark spotlights II (possible swap to following week)
  -  
* - 2026-02-19
  - benchmark spotlights III (possible swap to following week)
  - full benchmark propsal  
* - 2026-02-25
  - evaluating evaluation I (possible swap to previous week)
  -  
* - 2026-02-27
  - evaluating evaluation II (possible swap to previous week)
  -  
* - 2026-03-03
  - peer review 
  - proposal revisions
* - 2026-03-05
  - team formation 
  - full reads of proposals
* - 2026-03-10
  -  tba
  -  none
* - 2026-03-12
  -  tba
  -  none
* - 2026-03-17
  - spring break
  -  
* - 2026-03-19
  - spring break
  -  
* - 2026-03-24
  - benchmark demos
  - presentations
* - 2026-03-26
  - benchmark demos
  - presentations
* - 2026-04-01
  - tba
  - 
* - 2026-04-03
  - communicating and contextualizing performance
  - paper location registered 
* - 2026-04-08
  - tba
  - paper spotlights
* - 2026-04-10
  - tba
  -  spotlights
* - 2026-04-15
  - communicating benchmark results
  - none
* - 2026-04-17
  - making a plan based on preliminary
  - progress spotlights - one per team
* - 2026-04-22
  - communicating limitations
  - paper draft for reading
* - 2026-04-24
  - final presentations
  - presentations
* - 2026-04-29
  - final presentations
  - presentations
```


## Prepare for class

:::{attention}
These are organized by due date, some dates have multiple steps. 
::::

(readinformal)=
### Tuesday Jan 27

- how to read a paper: [CS specific](https://dl.acm.org/doi/10.1145/1273445.1273458) & [more general](https://www.science.org/content/article/how-seriously-read-scientific-paper) *this might be familiar, but review it for tips to be sure*
- post one or more [informal audit  articles](#informalaudits)
- contribute [benchmark ideas](#benchmark-ideas)
- read section 6 of [towards falsifiable reserch in interpretableml](https://ml-retrospectives.github.io/neurips2020/camera_ready/4.pdf) and skim the whole paper


(copilot)=
### Thursday Jan 29
- conduct an informal audit of coding copilots with [copilot arena](https://marketplace.visualstudio.com/items?itemName=copilot-arena.copilot-arena) - you can do it more privately using a codespace or try it locally, but submit to [discussion repo](https://github.com/evalexplainAI/discussion-sp25/tree/main/copilot-arena)
- comment on at least two others' informal audit posts
- be prepared to discuss patterns in informal audits

(betterbench)=
### Tues Feb 3
- read and comment on at least 2 peers copilot arena audits
- read the [neurips datasets and benchmarks cfp](https://neurips.cc/Conferences/2024/CallForDatasetsBenchmarks) *remember the ideal is that your course project is submittable to this venue*
- read about [betterbench](https://openreview.net/forum?id=hcOq2buakM#discussion): read the full paper, but also skim the peer review (both at that link) and the [public project page](https://betterbench.stanford.edu/)
- bring 2-3 options for benchmark papers you want to present the following week, should be from neurips datasets & benchmarks track, but others may be approved. You'll get approval for one during class time. You'll need to read the abstract and skim the paper to figure out if it's good and you may need to skim more than 2-3 to find a few good options. Final list/format of what to record will be provided by Tuesday.

NeurIPS datasets and benchmarks: 
- [2025](https://neurips.cc/virtual/2024/events/datasets-benchmarks-2025)
- [2024](https://neurips.cc/virtual/2024/events/datasets-benchmarks-2024)
- [2023](https://neurips.cc/virtual/2023/events/datasets-benchmarks-2023)
- [2022](https://neurips.cc/virtual/2022/events/datasets-benchmarks-2022)
- [2021](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021) *proceedings only*


## Community Contributions 

(informalaudits)=
### Informal Evaluations

Lots of popular media (i.e. not sholarly literature) is informal audits of AI.  We want to build up our skill in *formal* evaluation, but *informal* auditing can give ideas and serve as a good discussion.  

When you post an article, use the template below for the body and make the title the article title. 

Post to the [informal audits category](https://github.com/orgs/evalAI2eval/discussions/categories/informal-audits)

````{code-block}
<a one sentence summary>

I think this is interesting because < a short phrase or a few sentences>

[read the article](url/to/article)

## Strengths

- a few
- bullets
- on what is good

## Weaknesses

- a few
- bullets
- on what could be better
````

(benchmarkideas)=
### Benchmark ideas

Post to the [benchmark ideas category](https://github.com/orgs/evalAI2eval/discussions/categories/benchmark-ideas)

No specific format, but try to include enough detail that a classmate can understand your goal/idea. No need for it to be complete by any standard. 
You can post multiple, you will be able to choose freely later. 
