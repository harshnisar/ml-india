---
layout: page
title: People
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Indian faculty and research groups in machine learning and data science"
---

{% include _toc.html %}

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
  
  <script>
 function hideDiv(flag)
 {
   if(flag==1)
   {
     alert();
     document.getElementById("research_div").style.display="inline";
     document.getElementById("faculty_and_professor").style.display="none";
   }
   else if(flag==2)
   {
     document.getElementById("research_div").style.display="none";
     document.getElementById("faculty_and_professor").style.display="inline";
   }
 }
</script>
<ul class="nav nav-tabs">
  <li><a href="#" class="active" id="research_group_link" onclick="hideDiv(1)"> Research Group</a></li>
  <li><a href="#" id="faculty_and_professor_link" onclick="hideDiv(2)"> Faculty And Professors</a></li>
</ul>

<div id="faculty_and_professor">


<p><b>Faculty And Professors Div</b></p>
</div>

<div id="research_div">

<p><b>Research Group Div</b></p>
</div>


{% include _subscribe.html %}
