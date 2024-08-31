---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
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


<style>
.abstract{text-align:justify; }
.button{ text-align:justify; }
</style>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}




<ol>

<div id="1">
<li> <b>impactR4PHU R Package</b>, <em>Global Public Health Unit - Impact Initiatives</em>, 2024 [<a href="https://github.com/impact-initiatives/impactR4PHU">link</a>]
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






<!-- 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->