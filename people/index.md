---
layout: page
title: People
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Indian faculty and research groups in machine learning and data science"
---

{% include _toc.html %}

  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
  <script type="text/javascript">
  <script>
  
$(document).ready(function(){
        $("#research_div").show();
        $("#faculty_and_professor").hide();
  
    $("#faculty_and_professor_link").click(function(){
        $("#research_div").hide();
        $("#faculty_and_professor").show();
    });
    
    $("#research_group_link").click(function(){
        $("#research_div").show();
        $("#faculty_and_professor").hide();
        
    });
 });
</script>
<ul class="nav nav-tabs">
  <li><a href="#" class="active" id="research_group_link"> Research Group</a></li>
  <li><a href="#" id="faculty_and_professor_link"> Faculty And Professors</a></li>
</ul>

<div id="research_div">

<h2>Introduction</h2>


<p>There is no consolidated resource for Data and Machine Learning which is centered around the Indian ecosystem. In our aim of fostering the Indian ML eco-system we've curated a few reserouces which are India centric.</p>

<h3> Are you a research group working in ML/Data/Analytics?<h3>

<p>Write to <a href='/contact'>us</a>, or edit <i>includes<i>research-groups.html in our GH repo and send a pull request!</p>


<h2> Machine Learning Research Groups in India </h2>

A list of research groups in India which are working in machine learning and data science.


{% include _research-groups.html %}

</div>

<div id="faculty_and_professor">

<h3> Are you professor/faculty in ML/Data/Analytics? <h3>

<p>If your name is not mentioned or link to your website is missing, please write to </p><a href='/contact'>us</a><p>, or edit <i>includes/<i>research-groups.html in our GH repo and send a pull request!</p>


<h2> Machine Learning professors in India


{% include _ml-faculty.html %}


</div>
---



{% include _subscribe.html %}