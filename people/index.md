---
layout: page
title: 
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Indian faculty and research groups in machine learning and data science"
---
  <script>
 function pageSet()
 {
  var current_url=document.URL;
  var n = current_url.indexOf("machine-learning-faculty-india");
  if(n!=-1)
  {
      hideDiv(2);
  }
  else
  {
    hideDiv(1);
  }
 }
 function hideDiv(flag)
 {
   if(flag==1)
   {
     document.getElementById("research_div").style.display="inline";
     document.getElementById("faculty_and_professor").style.display="none";
     document.getElementById("research_group_link").style.color='blue';
     document.getElementById("faculty_and_professor_link").style.color='black';
   }
   else if(flag==2)
   {
     document.getElementById("research_div").style.display="none";
     document.getElementById("faculty_and_professor").style.display="inline";
     document.getElementById("research_group_link").style.color='black';
     document.getElementById("faculty_and_professor_link").style.color='blue';
   }
 }
</script>
<body onload="pageSet()">
<ul class="nav nav-tabs">
  <li><a href="#research-groups" id="research_group_link" onclick="hideDiv(1)"> Research Group</a></li>
  <li><a href="#machine-learning-faculty-india" id="faculty_and_professor_link" onclick="hideDiv(2)" > Faculty And Professors</a></li>
</ul>

<div id="research_div">
<hr>
<h2>Machine Learning Research Groups in India</h2>

<p>A list of research groups in India which are working in machine learning and data science.</p>

{% include _research-groups.html %}
<hr>
<hr>
</div>

<div id="faculty_and_professor">
<hr>
<h2>Machine Learning professors in India</h2>

{% include _ml-faculty.html %}
<hr>
<hr>
</div>


{% include _subscribe.html %}
</body>
