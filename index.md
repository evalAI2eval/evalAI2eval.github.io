

# Model Evaluation and Explanation


In this course, we will aim to answer one key question, through a multidisciplinary
examination: 

```{admonition}
:class: hint 
What does it mean to say:
> an AI can do that
```

We will answer this question by first looking at how to **measure** what an AI can do
and then by looking at how to **explain** what an AI does. 

We will begin with a review of model evaluation for simpler ML models, emphasizing the more 
abstract goals that underlie the standard evaluation procedures. Then we will use these underlying
goals to build an understanding of the tools available for evaluating more complex systems. 
Then we will study various AI benchmarks to see what specific AI abilities we can make rigorous 
claims about. In this section, we will also compare how these rigorous claims get translated into 
nonscientific literature. 
In the second part of the course, we will study model explanation techniques, again starting 
with simple models where we can build good intuition and then working up to what we can do 
for  deep neural networks with millions-hundreds of billions of parameters. 

Complete this [form to request a permission number](https://forms.gle/FranBuJd1mfpZSR38)



## Course structure

**Spring 2025: TTh 5:00-6:15pm**

There will be 1-3 papers or freely available textbook chapters to read most weeks. 
Most class sessions will be focused on a discussion of the paper(s) assigned for that 
class session.  

While we study up-to-date papers of benchmarks and new model evaluation techniques, 
students will prepare short, lightening-talk style presentations of papers. For these class
sesssions, several students each student will read and present different papers and 
we will discuss them as a group.   

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

Remember, this is a 4 credit cass with only 3 contact hours per week. This means that you should be spending a minimum of 9 hours per week on things for the course outide of class time, but most weeks probably closer to 12. When project milestones are due, expecations for community contribution will be a bit lower, and between milestones especially when I am giving feedback, you'll have more community contributions expected.

### community contribution evaluation

Community Contributions will be based on

- preparing for class, every time, so whatever different days I request thigns, there will be different ways this looks. I will ask for different evidence on different days and basically record 1 thing per day for you. (completion- based on check)
- glossary and shared notes contributions (completion-number)
- contribution to shared infrastructure (completion -number and scope)
- lightning talk presentations (quality/binary)
- contributions to class discussion & prismia responses (completion -number and quality)

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
Do not use this to try to start the project early
```
:::::

The project will be completed by meeting several milestones, these milestones are not likely to change and changes will be announced with a lot of warning
```{list-table}
* - project milestone
  - due date
  - submission
* - evaluate ideas based on interest from a group-created list of ideas
  - 2025-02-13 
  - course discussion
* - draft proposal an AI benchmark component
  - 2025-02-20 
  - tba
* - peer review of proposals
  - 2025-03-06 
  - form will be provided
* - consolidation into teams[^teams]
  - 2025-03-06 
  - in class
* - implement at least one benchmark task
  - 2025-03-27 
  - benchmark repo + presentation
* - apply explanation techniques to better understand *why* it performs as it does
  - 2025-04-15 
  - in class demo/discussion
* - draft paper for peer review 
  - 2025-04-24 
  - benchmark repo or overleaf, team preference, **[registration](https://docs.google.com/forms/d/16NN941Oydub9h00fSeVsXGJs4NVIeM0buHx6w546vTE/edit) of the location required**
* - extend the benchmark with a task that gives different performance [^performancevary] 
  - 2025-04-29 
  - benchmark repo
* - in class presentation
  - 2025-04-29
  - presentation and draft paper, location tba
* - complete a final conference-paper style report 
  - 2025-05-06  
  - final paper for grading
* - *optional* register abstract for [neurips](https://neurips.cc/Conferences/2025/CallForDatasetsBenchmarks)
  - May 15 
  - abstract and all authors registered in openreview
* - *optional* submit paper for neurips
  - May 15 
  - paper with all required sections to openreview
* - *optional* submit supplemental materials for neurips
  - May 22
  - paper with all required sections to openreview
```

[^teams]: depending on enrollment and similarity of proposal topics benchmarks
 may be completed in teams or indvidually but the proposal stage and peer review will 
 be individual assignments. Teams will be expected to have more tasks in their benchmarks
 than individuals. 

[^llmcredits]:Students motivated to extend their benchmark and complete a broader evaluation 
in order to submit their project to, eg the NeurIPS Datasets & Benchmarks track 
may be provided credits to evaluate commercial LLMs may be available, but non-free
evaluation will not be required to complete the project. 

[^performancevary]: if the LLM scores well on the first task, add one where it does not score well; if it scores poorly on the first add one that it can do well

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

- we will use prismia chat to share materials. Join link on brightspace
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
* - 2025-01-23
  - intro
  - none 
* - 2025-01-28
  - classic evaluation  in predictive systems
  - prep work (see prismia)
* - 2025-01-30
  - novel evaluation in predictive systems + syllabus discussion
  - contribute informal evaluations
* - 2025-02-04
  - basics of evaluation in generative systems + reading research discussion
  - discuss/comment on informal eval + contribute benchmark ideas +copilot arena informal audit 
* - 2025-02-06
  - what is a benchmark? + synthesizing research discussion
  - possible benchmarks to present for approval
* - 2025-02-11
  - benchmark spotlights  
  - spotlight presentations (all students 5 min presentation)
* - 2025-02-13
  - benchmark common structures
  - decide benchmark proposal topic (rough) 
* - 2025-02-18
  - benchmark spotlights II (possible swap to following week)
  -  
* - 2025-02-20
  - benchmark spotlights III (possible swap to following week)
  - full benchmark propsal  
* - 2025-02-25
  - evaluating evaluation I (possible swap to previous week)
  -  
* - 2025-02-27
  - evaluating evaluation II (possible swap to previous week)
  -  
* - 2025-03-04
  - peer review (Sarah out)
  - proposal revisions
* - 2025-03-06
  - team formation (Sarah out)
  - full reads of proposals
* - 2025-03-11
  - spring break
  -  none
* - 2025-03-13
  - spring break
  -  none
* - 2025-03-18
  - canceled
  -  
* - 2025-03-20
  - explanation concepts
  -  
* - 2025-03-25
  - TCAV
  - 
* - 2025-03-27
  - benchmark demos
  - presentations
* - 2025-04-01
  - evaluating explanations
  - 
* - 2025-04-03
  - explanation techniques
  - paper location registered 
* - 2025-04-08
  - communicating and contextualizing performance
  -  
* - 2025-04-10
  - explanation techniques
  -  
* - 2025-04-15
  - making a plan based on explanation results
  - explanation results spotlights
* - 2025-04-17
  - communicating explanations
  - revision plan
* - 2025-04-22
  - communicating limitations
  - paper draft for reading
* - 2025-04-24
  - (possibly presentations)
  - paper draft for reading
* - 2025-04-29
  - final presentations
  - 2nd task, slides
```