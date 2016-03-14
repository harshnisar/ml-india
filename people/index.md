---
layout: page-table
title: 
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Indian faculty and research groups in machine learning and data science"
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
     window.location.href = "http://ml-india.org/people/#research-groups";
   }
   else if(flag==2)
   {
      
     document.getElementById("research_div").style.display="none";
     document.getElementById("faculty_and_professor").style.display="inline";
     window.location.href = "http://ml-india.org/people/#machine-learning-faculty-india";
   }
 }
</script>

<body onload="pageSet()">

  <input id="tab1" type="radio" name="tabs" onclick="hideDiv(1)">
  <label for="tab1" >Research Group</label>
    
  <input id="tab2" type="radio" name="tabs" onclick="hideDiv(2)">
  <label for="tab2">Faculty And Professors</label> 

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
