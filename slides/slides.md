<!-- .slide: <%= bg("unsplash-Jztmx9yqjBw-stars.jpg") %> id="title" -->
# Reproducible Data Preparation

---
+ Data processing: Applying **software engineering** principles 
  to research data analysis

---
+ **Reproducibility**
+ **Transparency**
+ **Modularity**
+ **Generalisability**

>>>
+ **Reproducibility**: No manual editing of data, all transformations are done
  in syntax / code / macros that can be re-run and validated
+ **Transparency**: Documentation and unit tests using simulated data
  explicate intent and assumptions. Revision control provides an immutable
  record of code evolution.
+ **Modularity**: Complex, multi-stage pipelines with multiple datasets are
  decomposed into packages and functions, each with a single, clearly-defined
  purpose
+ **Generalisability**: Bespoke processes for each dataset's unique quirks 
  are compartmentalised into functions, in a modular infrastructure supporting
  a general process that can be applied to other PCM surveys

