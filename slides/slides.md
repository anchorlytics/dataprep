<!-- .slide: <%= bg("unsplash-TStNU7H4UEE-hand_sunset.jpg") %> -->
# Reproducible Data Preparation
[Montreal, CA. Marc-Olivier Jodoin](https://unsplash.com/photos/TStNU7H4UEE "caption")

>>>
+ Seems like **unattainable** goal, but
+ **direction** we want to head in

---
“**Reproducibility** refers to the ability of a researcher 
to duplicate the **results** of a prior study using the 
same **materials** as were used by the original investigator. 

That is, a second researcher might use the same raw **data**
to build the same analysis **files** and implement the same 
statistical **analysis** in an attempt to yield the same results. 

Reproducibility is a **minimum** necessary condition 
for a finding to be **believable** and **informative**.”

[Report of the Subcommittee on Replicability in Science Advisory Committee, U.S. National Science Foundation, 2015](https://www.nsf.gov/sbe/AC_Materials/SBE_Robust_and_Reliable_Research_Report.pdf "caption")

>>>
+ Different **person**
+ Same **data**, same **analysis**

---
## Reproducibility <br> Crisis in Research
![Failed to reproduce](/img/failed_to_repr.png)

+ Psychology: [Open Science Collaboration, *Science* (2015)](http://dx.doi.org/10.1126/science.aac4716)
+ Cancer biology: [Begley, C. G. and Ellis, L. M., *Nature* 483, 531–533 (2012)](https://www.nature.com/articles/483531a)

[Baker, M., *Nature* 533, 452–454 (2016)](https://www.nature.com/articles/533452a "caption")

>>>
+ Meta-analyses of reproducibility in **psych**: 40%
  + in **cancer biology**: 10%!

---
## Technology Life Cycle
[Technology life cycle](/img/Technology_Life_Cycle.png)
[CC-BY-SA 3.0](https://en.wikipedia.org/wiki/Technology_life_cycle "caption")

>>>
+ although not **business**, but still
  + **expend** budget and goodwill and would like to
  + **deliver** actionable insight 
  + reflecting **patient** experiences and
  + equipping **stakeholders**
+ Initial **investment** in R+D, incl **repr**
+ Reproducibility **accelerates** adoption, trust, agility in response to changing needs

---
## Research Cycle
![Research cycle](/img/research-cycle.jpg)

[The Turing Way](https://the-turing-way.netlify.app/)
[Scriberia for Turing Way, CC-BY 4.0](https://zenodo.org/record/4906004 "caption")

>>>
+ Data **processing** in the pipeine
  + Streamlining / productizing this **enables** research to iterate more quickly
+ Also **after** analysis + report publication:
  + **Data** publishing, archiving, and reuse

---
## Beyond Reproducibility

![Reproducibility Grid](/img/reproducible-definition-grid.jpg)

>>>
+ in our **context**:
+ **data**: subseq surveys, diff sectors
+ **analyses**: kinds of reporting, charting

---
## Software Engineering Principles 
### for research data analysis

+ **Reproducibility**: automation, syntax
+ **Transparency**: docs, test cases, version control
+ **Modularity**: packages and functions
+ **Generalisability**: compartmentalisation of dataset-specific quirks
  + *multiple-select* questions
  + non-standard user-defined *missing*
  + erroneous *coding* of responses
  + *reordering* and reverse coding of response levels

>>>
+ **Reproducibility**: No manual editing of data, all transformations are done
  in syntax / code / macros that can be re-run and validated
  + Don't **fear** coding: natural evolution of reproducible menu-driven operations
  + **Textual** syntax for analysis enables:
+ **Transparency**: Documentation and unit tests using simulated data
  explicate intent and assumptions. Revision control provides an immutable
  record of code evolution.
+ **Modularity**: Complex, multi-stage pipelines with multiple datasets are
  decomposed into packages and functions, each with a single, clearly-defined
  purpose
+ **Generalisability**: Bespoke processes for each dataset's unique quirks 
  are compartmentalised into functions, in a modular infrastructure supporting
  a general process that can be applied to other PCM surveys

