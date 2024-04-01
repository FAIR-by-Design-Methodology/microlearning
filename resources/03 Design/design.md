---
title: "Stage 3 - Design"
author: "Skills4EOSC T2.3"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
hide:
    - toc
    - navigation
---

# Stage 3 - Design

!!! quote ""

    Design is intelligence made visible - *Alina Wheeler​*

## Time to brainstorm

<div class="card w-100 mb-3">
  <div class="row no-gutters">
    <div class="col-md-4" style="width: 18rem;">
      <img class="card-img" src="../../attachments/brain-3829057_640.jpg" alt="Developing concept map"/>
      <p class="card-text"><small class="text-muted">
                Image by <a href="https://pixabay.com/users/geralt-9301/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=3829057">Gerd Altmann</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=3829057">Pixabay</a> </small>
                </p>
    </div>
    <div class="col-md-8" style="width: 36rem;">
      <div class="card-body">
        <h2 class="card-title">Concept map</h2>
        <p class="card-text">Build a concept map of your learning materials aligning with the MVS profiles.</p>
        <p class="card-text">The aligned MVS profile can help you cristalize the learning objectives using MVS taxonomy.</p>
        <p class="card-text">Each MVS profile defines a list of technical and soft skills required for the profile. Think on how to incorporate both aspects in your learning materials.</p>
      </div>
    </div>
  </div>
</div>

​
## Structure is everything

<div class="grid cards" markdown>

- <i class="fa fa-cogs" aria-hidden="true"></i> Create an intuitive logical organisation of all learning materials. 
- <i class="fa fa-cubes" aria-hidden="true"></i> The goal is for other people to easily reuse a single item (plan, activity, unit, assessment, ...).
- <i class="fa fa-sitemap" aria-hidden="true"></i> Use a hierarchical structure to combine learning units into larger compositions.

</div>

## Diagrams Example

``` mermaid
graph LR
root: Root
root.shape: package

res: resources
root.shape: package

rm: README
rm.shape: page

l: LICENSE
l.shape: page

c: CITATION.cff
c.shape: page

misc: (opt) Miscellaneous files
misc.shape: document

a: attachments
a.shape: package

f: Feedback
f.shape: package

s1: (opt) 01 Section Name
s1.shape: package

s: syllabus
s: page

fg: facilitator guide
fg.shape: page

mf: media files
mf: document

fqf: feedback questions
fdf.shape: page

m1: (opt) 01 Module Name
m1.shape: package

l1: 01 Learning Unit Name
l1.shape: package

lx: ...
lx.shape: package

lN: N Learning Unit Name
lN.shape: package

act: Activities
act.shape: package

ass: Assessment
ass.shape: package

att: attachments
att.shape: package

amf: media files
amf.shape: document

lc: Learning Content Description
lc.shape: page

sd: Slide Deck
sd.shape: page

lup: Learning Unit Plan
lup.shape: page

act1: 01 activity details
act1.shape: page

actx: ... activity details
actx.shape: page

actK: K activity details
actK.shape: page

assq: Assessment questions
assq.shape: page

asss: (opt) Assessment strategy
asss.shape: page

root -- res
root -- rm
root -- l
root -- c
root -- misc

res -- a
res -- f
res -- s1
res --s 
res -- fg

a -- mf

f -- fqf

s1 -- m1

m1 -- l1
m1 -- lx
m1 -- lN

l1 -- act
l1 -- ass
l1 -- att
l1 -- lc
l1 -- sd
l1 -- lup

act -- act1
act -- actx
act -- actK

ass -- assq
ass -- asss

att -- amf


  A[Start] --> B{Error?};
  B[example <a href='https://google.com'>link</a>] -->|Yes| C[Hmm...];
  C[<a href='https://google.com'>just a link</a>] --> D[Debug];
  D --> B;
  B ---->|<a href='https://google.com'>No</a>| E[Yay!];
```



## Develop
Hunter

## Facilitation Guide

## Feedback Form
​

​
Don't worry, we got you covered with templates​

<a href="https://fair-by-design-methodology.github.io/FAIR-by-Design_ToT/latest/Stage%203%20%E2%80%93%20Design/04-Conceptualisation/04-Conceptualisation/" class="btn btn-dark text-white btn-lg btn-block">Start an in-depth training on the Design stage....</a>
<a href="https://fair-by-design-methodology.github.io/FAIR-by-Design_Book/4%20-%20FAIR-by-design%20learning%20materials%20creation/4.1%20-%20Workflow%20stages%20description/413-design/" class="btn btn-dark text-white btn-lg btn-block">FAIR-by-Design Methodology: Design stage....</a>