---
permalink: /
title: "Home"
layout: splash
header:
  image: /assets/images/boston3.jpeg
# feature_row2:
#   - image_path: /assets/images/headshot.jpeg
#     alt: "placeholder image 2"
#     title: "Stephen Kissler"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
gallery:
  - image_path: /assets/images/covid_projections.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - image_path: /assets/images/abx_ma.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - image_path: /assets/images/viral_trajectory.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"
  - image_path: /assets/images/life_expectancy.jpg
    alt: "placeholder image 4"
    title: "Image 4 title caption"
  - image_path: /assets/images/unvax_viral_kinetics.jpg
    alt: "placeholder image 5"
    title: "Image 4 title caption"
  - image_path: /assets/images/NYC_prev.jpg
    alt: "placeholder image 6"
    title: "Image 4 title caption"
news: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
---

<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
</style>

<!-- Try putting in images using the gallery option: https://mmistakes.github.io/minimal-mistakes/post%20formats/post-gallery/ -->

<div class="row">
  <div class="column">
    <!-- {% include feature_row id="feature_row2" type="left" %} -->
    <br>
    <br>
    <img src="/assets/images/headshot.jpeg" alt="Stephen Kissler" width=150px style="float: left; padding: 0px 10px 10px 0px"> 
    <h1> Stephen Kissler </h1>
    <font size=2>
    Postdoctoral Fellow<br>
    Harvard T.H. Chan School of Public Health<br>
    Grad Lab, Dept. of Immunology and Infectious Diseases<br> <br>

    CV | Google Scholar | Twitter | GitHub <br>
    skissler@hsph.harvard.edu
    </font>
  </div>
  <div class="column">
    {% include gallery %}
<!--     <img src="/assets/images/covid_projections.jpg" alt="Stephen Kissler" width=200px style="float: right; padding: 0px 10px 10px 0px"> 
    <img src="/assets/images/abx_ma.jpg" alt="Stephen Kissler" width=200px style="float: right; padding: 0px 10px 10px 0px"> 
    <img src="/assets/images/viral_trajectory.jpg" alt="Stephen Kissler" width=200px style="float: right; padding: 0px 10px 10px 0px"> <br clear=right>
    <img src="/assets/images/life_expectancy.jpg" alt="Stephen Kissler" width=200px style="float: right; padding: 0px 10px 10px 0px"> 
    <img src="/assets/images/unvax_viral_kinetics.jpg" alt="Stephen Kissler" width=200px style="float: right; padding: 0px 10px 10px 0px"> 
    <img src="/assets/images/NYC_prev.jpg" alt="Stephen Kissler" width=200px style="float: right; padding: 0px 10px 10px 0px">  -->
  </div>
</div>

{% include feature_row id="news" type="left" %}


<!-- <h2> News </h2>

- __9-11 Aug 2022:__ I'll be at the Contagion on Complex Social Systems (CCSS) workshop at the University of Colorado Boulder -->

