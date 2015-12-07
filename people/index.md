---
layout: page
title: People
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Indian faculty and research groups in machine learning and data science"
---
  <script>
  $(document).ready(function(){
    $("#research_div").show();
    $("#faculty_and_professor").hide();
    $("#research_group_td").css('backgroundColor', '#FF9966');
    $("#faculty_and_professors_td").css('backgroundColor', '#FFFFFF');
  });
 function hideDiv(flag)
 {
   if(flag==1)
   {
     document.getElementById("research_div").style.display="inline";
     document.getElementById("faculty_and_professor").style.display="none";
     document.getElementById("research_group_td").style.backgroundColor = "#FF9966";
     document.getElementById("faculty_and_professors_td").style.backgroundColor = "#FFFFFF";
   }
   else if(flag==2)
   {
     document.getElementById("research_div").style.display="none";
     document.getElementById("faculty_and_professor").style.display="inline";
     document.getElementById("research_group_td").style.backgroundColor = "#FFFFFF"
     document.getElementById("faculty_and_professors_td").style.backgroundColor = "#FF9966";
   }
 }
</script>
<table>
    <tr>
        <td id="research_group_td" align="center"><a href="#research-groups" id="research_group_link" name="ResearchGroup" onclick="hideDiv(1)"> Research Group</a></td>
        <td id="faculty_and_professors_td" align="center"><a href="#machine-learning-faculty-india" id="faculty_and_professor_link" onclick="hideDiv(2)"> Faculty And Professors</a></td>
    </tr>
</table>
<h1>Indian research groups in the field of machine learning and data science</h1>
<div id="research_div">
<h2>Introduction</h2>

<p>There is no consolidated resource for Data and Machine Learning which is centered around the Indian ecosystem. In our aim of fostering the Indian ML eco-system we've curated a few reserouces which are India centric.</p>

<h3>Are you a research group working in ML/Data/Analytics?</h3>

<p>Write to <a href='/contact'>us</a>, or edit _includes/_research-groups.html in our GH repo and send a pull request!</p>
<hr>
<h2>Machine Learning Research Groups in India</h2>

<p>A list of research groups in India which are working in machine learning and data science.</p>

{% include _research-groups.html %}
<hr>
<hr>
</div>

<div id="faculty_and_professor">
<h3>Are you professor/faculty in ML/Data/Analytics?</h3>

<p>If your name is not mentioned or link to your website is missing, please write to <a href='/contact'>us</a>, or edit _includes/_research-groups.html in our GH repo and send a pull request!</p>
<hr>
<h2>Machine Learning professors in India</h2>

{% include _ml-faculty.html %}
<hr>
<hr>
</div>


{% include _subscribe.html %}

