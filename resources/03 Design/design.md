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
            <a href="https://fair-by-design-methodology.github.io/MVS/latest/MVS%20Profiles/Civil%20Servant/civil_servant/" class="btn btn-primary stretched-link">Go to MVS profiles catalogue</a>
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

!!! example "How to organise the files"

    The diagram shows how to organise all files. Click on the links to discover and use pre-prepared templates.

``` mermaid
graph LR
  r[root] --> res;
  r --> rm[<a href='https://www.makeareadme.com/'>README</a>];
  r --> l[<a href='https://creativecommons.org/licenses/by/4.0/legalcode.txt'>LICENSE</a>];
  r --> c[<a href='https://citation-file-format.github.io/'>CITATION.cff</a>];
  r --> misc[opt miscellaneous files];

  res[resources] --> att[attachments];
  att --> mf[multimedia files];
  res --> f[Feedback];
  f --> fq[<a href='https://github.com/FAIR-by-Design-Methodology/templates/blob/main/resources/Feedback/training_feedback_template.md'>survey</a>];
  res --> s1[opt 01 Section Name];
  res --> s[<a href='https://github.com/FAIR-by-Design-Methodology/templates/blob/main/resources/syllabus.md'>Syllabus</a>];
  res --> fg[<a href='https://github.com/FAIR-by-Design-Methodology/templates/blob/main/resources/template_facilitator_guide.md'>Facilitator Guide</a>];

  s1 --> m1[opt 01 Module Name];
  m1 --> lu1[01 Learning Unit Name];
  m1 --> lux[...];
  m1 --> luN[N Learning Unit Name];

  lu1 --> act[Activities];
  lu1 --> ass[Assessment];
  lu1 --> at[attachments];
  at --> mff[multimedia files];
  lu1 --> lc[Learning Content];
  lu1 --> sd[Slide Deck];
  lu1 --> lp[Learning Unit Plan];

  act --> a1[01 activity desc];
  act --> ax[...];
  act --> aK[K activity desc];

  ass --> qb[questions];
  ass --> st[opt strategy];

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