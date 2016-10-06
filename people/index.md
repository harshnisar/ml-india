---
layout: page-table
title: 
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Indian faculty, research groups and professionals in machine learning and data science"
---
<style>
      
*, *:before, *:after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

input {
  display: none;
}

label {
  display: inline-block;
  margin: 0 0 -1px;
  padding: 15px 25px;
  font-weight: 600;
  text-align: center;
  color: #555;
  border: 1px solid transparent;
}

label:before {
  font-family: fontawesome;
  font-weight: normal;
  margin-right: 10px;
}


label:hover {
  color: #888;
  cursor: pointer;
}

input:checked + label {
  color: #555;
  border: 1px solid #ddd;
  border-top: 2px solid orange;
  border-bottom: 1px solid #fff;
}
    </style>
    
  <script>
 function pageSet()
 {
  var current_url=document.URL;
  var n = current_url.indexOf("machine-learning-faculty-india");
  if(n!=-1)
  {
      document.getElementById("tab2").checked = true;
      hideDiv(2);
  }
  else if(current_url.match("people/$")||current_url.match("people$")||current_url.match("machine-learning-professionals-india$"))
  {
      document.getElementById("tab3").checked = true;
      hideDiv(3);  
  }
  else if(current_url.match("people/$")||current_url.match("people$")||current_url.match("research-groups$"))
  {
      document.getElementById("tab1").checked = true;
      hideDiv(1);  
  }
 }
 function hideDiv(flag)
 {
   if(flag==1)
   {
     document.getElementById("research_div").style.display="inline";
     document.getElementById("faculty_and_professor").style.display="none";
     document.getElementById("professionals_div").style.display="none";
     window.location.href = "http://nishankvboy.github.io/ml-india/people/#research-groups";
   }
   else if(flag==2)
   {
      
     document.getElementById("research_div").style.display="none";
     document.getElementById("faculty_and_professor").style.display="inline";
     document.getElementById("professionals_div").style.display="none";
     window.location.href = "http://nishankvboy.github.io/ml-india/people/#machine-learning-faculty-india";
   }
   else if(flag==3)
   {
      
     document.getElementById("research_div").style.display="none";
     document.getElementById("faculty_and_professor").style.display="none";
     document.getElementById("professionals_div").style.display="inline";
     window.location.href = "http://nishankvboy.github.io/ml-india/people/#machine-learning-professionals-india";
   }
 }
</script>

<body onload="pageSet()">

  <input id="tab3" type="radio" name="tabs" onclick="hideDiv(3)">
  <label for="tab3" >Professionals</label>
    
  <input id="tab2" type="radio" name="tabs" onclick="hideDiv(2)">
  <label for="tab2">Faculty And Professors</label> 
  
  <input id="tab1" type="radio" name="tabs" onclick="hideDiv(1)">
  <label for="tab1" >Research Groups</label>

<div id="professionals_div">
<hr>
<h2>Machine Learning Professionals in India</h2>

{% include _ml-professionals.html %}
<hr>
<hr>
</div>


<div id="research_div">
<hr>
<h2>Machine Learning Research Groups in India</h2>

{% include _research-groups.html %}
<hr>
<hr>
</div>

<div id="faculty_and_professor">
<hr>
<h2>Machine Learning Faculty/Professors in India</h2>

{% include _ml-faculty.html %}
<hr>
<hr>
</div>


{% include _subscribe.html %}
</body>
