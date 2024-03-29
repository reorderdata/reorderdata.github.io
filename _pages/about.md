---
layout: about
title: About
permalink: /
subtitle: A Dataset for Matrix Reordering

# profile:
#   align: right
#   image: prof_pic.jpg
#   image_circular: false # crops the image to make it circular
#   more_info: >
 
# news: false # includes a list of news items
# selected_papers: false # includes a list of papers marked as "selected={true}"
# social: false # includes social icons at the bottom of the page
---
<br />

<h3><span class="font-weight-bold">What is Reorder Data?</span></h3>

ReorderData is a large-scale dataset built for matrix reordering. ReorderData has the following features:

- [x] Matrix reordering
- [x] Visual pattern recognition
- [x] 544,500 binary matrices and 1,089,000 continuous matrices
- [x] Four visual patterns: block, off-diagonal block, star, and band
- [x] Scores to measure visual patterns

Each matrix is of size 200x200 and symmetric.

<br />
TODO: A video introduction of the dataset.
<br />

<h3><span class="font-weight-bold">Dataset & Codes</span></h3>

We provide the matrix dataset ReorderData as well as the unified scoring model and the reordering models introduced in Sections 6.2 and 6.3. 
- [Dataset](https://drive.google.com/drive/u/1/folders/1QAEHPqj7Tog1gpj10dfqKBwSQffRHsIX) (TODO: upload training data)
- [Code for data generation pipeline]() (TODO: upload code)
- [Unified scoring model]() (TODO: upload code and model)
- [Reordering models]() (TODO: upload code and model)

<br />

<h3><span class="font-weight-bold">Dataset Generation Pipeline</span></h3>
<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/system_pipeline.png" class="img-fluid rounded z-depth-1" zoomable=true %}
</div>
To increase the dataset's representativeness, the number and size of visual patterns in the matrix templates are aligned with real-world matrices. Diversity is achieved through a large number of matrix variations with diverse degrees of degeneration. We propose the convolution- and entropy-based scoring method to directly measure the quality of visual patterns.

<br />

<div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/examples.png" class="img-fluid rounded z-depth-1" zoomable=false %}
</div>


