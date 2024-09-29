---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
  $(document).ready(function () {
    $(".abstract").hide();
    $(".button").on("click", function () {
        $(this).next(".abstract").slideToggle(400);
    });
});
</script>

<script src="/assets/scripts/copyCode.js"></script>

<style>
.abstract{text-align:justify; }
.button{ text-align:justify; }
</style>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
## R Packages

<ol>

<div id="1">
<li> <b>impactR4PHU Package</b>, <em>Global Public Health Unit - Impact Initiatives</em>, 2024 [<a href="https://github.com/impact-initiatives/impactR4PHU">link</a>]
  <br>Public Health Technical Support: Saeed Rahman, Olivia Falkowitz, Noortje Gerritsma, Martin Njoroge, Michele Citton. Other Support: Yann Say-Liang-Fat
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
impactR4PHU is designed for creating quality check reports, cleaning, analysing and outputing results of core outcome indicators of Public Health Unit. This package will target mainly Food Security and Livelihoods, WASH, Nutrition and Health Sectors.
<p style="margin-top: -0.1%;">
The Data Quality and Plausibility Report serves as a crucial tool for assessing the reliability and accuracy of the data collection of all related public health indicators across different assessments. This comprehensive analysis is designed to identify and address potential issues within the data, ensuring that field teams are being informed on potential issues detected in the data collection.
</p>
<p style="margin-top: -2.5%;">
The Data Cleaning Template serves as a crucial tool for assessing the data collection of all related public health indicators indicators across different assessments. This comprehensive tool is designed to identify and address potential issues within the data, ensuring that field teams are being followed up on potential issues detected in the data collection.
</p>
<p style="margin-top: -2.5%;">
The Descriptive Analysis is an analytical platform that presents a multitude of quantitative data tables. It encompasses a wide range of public health indicators collected through the assessment process, empowering users to examine and interpret complex datasets effectively. This tool is structured to support understanding the distribution of your data and support you writing your factsheets/outputs/reports, and create other visualizations.
</p>
</div></li></div>

<div id="2">
<li> <b>utilityR Package</b>, <em>Ukraine Mission - Impact Initiatives</em>, 2024 [<a href="https://github.com/REACH-WoU/utilityR">link</a>]
  <br>A collaborative work with: Nestor Cheryba, and Bohdan Marynenko
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
The package is devoted to a number of functions used within the standard Reach Ukraine cleaning processes.
<p style="margin-top: -0.1%;">
 The package is composed of a number of function 'families' each dealing with a specific aspect of the data manipulation. Please read vignettes and individual function documentation to discover more about each of the families in greater detail. you can browse the vignettes of this package by calling vignette(package='utilityR'). 
</p>
<p style="margin-top: -2.5%;">
The text below presents a comprehensive overview of the cleaning process and how each of the functions are used within their respective frameworks. The text below follows the structure of the cleaning template presented in the markdown templates of this package.
</p>
<p style="margin-top: -2.5%">
This set of functions and scripts is a legacy of Reach Syria team. It was later transfered to Reach Regional team in Ukraine/Poland/Moldova. Reach Ukraine team has built a package around those functions by testing, optimizing and improving the legacy scripts and running the presented script on multiple research cycles. If you find any bugs or have any suggestions, please text the package maintainers.
</p>
</div></li></div>

<div id="3">
<li> <b>cleaning_template Package</b>, <em>Ukraine Mission - Impact Initiatives</em>, 2024 [<a href="https://github.com/REACH-WoU/cleaning_template">link</a>]
  <br>A collaborative work with: Nestor Cheryba, and Bohdan Marynenko
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
This document is based on the standard cleaning procedure of the utilityR package. Please check the documentation of the package for more details
<p style="margin-top: -0.1%;">
This set of functions and scripts is a legacy of Reach Syria team. It was later transfered to Reach Regional team in Ukraine/Poland/Moldova. Reach Ukraine team has built a package around those functions by testing, optimizing and improving the legacy scripts and running the presented script on multiple research cycles. If you find any bugs or have any suggestions, please text the package maintainers.
</p>
</div></li></div>

</ol>


## Guidelines

<ol>
<div id="4">
<li> <b>Rcookbook</b>, <em>Impact Initiatives</em>, 2023 [<a href="https://github.com/impact-initiatives/rcookbook">link</a>]
  <br>A collective work of the R Squad.
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
This book aims to be a small collection of codes used across different mission. It contains examples of different problems you can face and offers guidance to solve them. The codes are not exhaustive but just examples.
</div></li></div>

<div id="2">
<li> <b>KoboToolbox XML</b>, <em>Impact Initiatives</em>, 2023 [<a href="https://github.com/REACH-WoU/kobo_guidelines">link</a>]
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
This guideline aims to provide the Do's and Dont's of coding XML forms for KoboToolBox or ODK.
</div></li></div>
</ol>

## Dashboards & Data Visualizations

<ol>
<div id="4">
<li> <b>Ukraine Population Distribution Dashboard</b>, <em>Ukraine Mission: Impact Initiatives</em>, 2023 [<a href="https://abrahamazar.shinyapps.io/UKR_population_distribution_dashboard">link</a>]
  <br>Merged and Adapted from the work of Md. Mehedi. 
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
<p style="margin-top: -0.1%;">
 This app has been created to smoothen the host community sampling process all over Ukraine. WolrdPop population data has been used to identify the populated area over Ukraine. Note that WorldPop used remote sensing techniques to find the population distribution. Hence the population figure and their distribution may not be error-free. The detailed methodology they have followed can be found.
</p>
<p style="margin-top: -2.5%;">
The project was developed for Ukraine, divided into hexagons covering an area of one square kilometer for the whole country. Then the non-livable areas were classified by using OSM data, based on the location of governmental buildings, airports, schools, colleges, waterbodies, forests, and other relevant geospatial information. After that, for each hexagon, were calculated the coverage of non-livable areas in percentage and the number of population, by using the raster dataset of population published by WorldPop (2020). Hexagons where the number of population was less than 50, or where the coverage of non-livable area was greater than or equal to 90% added to the number of population between 50 and 100 were disregarded. The detailed R script is available on request.
</p>
</div></li></div>

<div id="2">
<li> <b>Analysis App</b>, <em>Impact Initiatives</em>, 2023 [<a href="https://impact-initiatives.shinyapps.io/tabularAPP/">link</a>]
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
This analysis tool will provide various tools and functionalities to analyse and interpret data across your different assessment and tools. It was built in a way to provide a user-friendly interface and a range of tools tailored to specific IMPACT needs.
<p style="margin-top: -0.1%;">
Credits: 
The variance tool was built by Nestor Cheryba. For any information or question, please contact nestor.cheryba@reach-initiative.org
</p>
</div></li></div>
</ol>

## Publications

<ol>
<div id="4">
<li> <b>Data Imputation using ISMI Data</b>, <em>Ukraine Mission: Impact Initiatives</em>, 2023 
  <br>Merged and Adapted from the work of Md. Mehedi. 
<!-- <div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
ADD DESCRIPTION HERE
</div></li></div> -->

<div id="2">
<li> <b>Remote Mortality Studies in DRC</b>, <em>Impact Initiatives</em>, 2024
 <!-- [<a href="https://github.com/REACH-WoU/kobo_guidelines">link</a>] -->
  <br>Collaborative work: Saeed Rahman, Joeri Smits, Christina Kay
<div class='button' data-content="toggle-text"><a href="#8">abstract</a></div>
<div class='abstract'>
To be pubished soon
</div></li></div>
</ol>





<!-- 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->