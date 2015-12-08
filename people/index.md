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
     document.getElementById("rsch_div").style.boxShadow="0px 0px 0px 1px black";
     document.getElementById("ml_div").style.boxShadow="0px 1px 0px 1px black";
   }
   else if(flag==2)
   {
     document.getElementById("research_div").style.display="none";
     document.getElementById("faculty_and_professor").style.display="inline";
     document.getElementById("research_group_link").style.color='black';
     document.getElementById("faculty_and_professor_link").style.color='blue';
     document.getElementById("rsch_div").style.boxShadow="0px 1px 0px 1px black";
     document.getElementById("ml_div").style.boxShadow="0px 0px 0px 1px black";
   }
 }
</script>
<body onload="pageSet()">
<div id="rsch_div" style="float:left;width:50%;cursor:pointer;box-shadow:0px 0px 0px 1px black;">
  <a href="#research-groups" id="research_group_link" name="ResearchGroup" onclick="hideDiv(1)"> Research Group</a>
</div>

<div id="ml-div" style="float:right;width:50%;cursor:pointer;box-shadow:0px 1px 0px 1px black;" onclick="hideDiv(2)">
  <a href="#machine-learning-faculty-india" id="faculty_and_professor_link" > Faculty And Professors</a>
</div>
<!--
<table>
    <tr>
        <td id="research_group_td" width="50%" align="center"><a href="#research-groups" id="research_group_link" name="ResearchGroup" onclick="hideDiv(1)"> Research Group</a></td>
        <td id="faculty_and_professors_td" width="50%" align="center"><a href="#machine-learning-faculty-india" id="faculty_and_professor_link" onclick="hideDiv(2)"> Faculty And Professors</a></td>
    </tr>
</table>
-->
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
