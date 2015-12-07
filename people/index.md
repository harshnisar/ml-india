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
<style>
.nav { padding-left: 0; margin-bottom: 0; list-style: none } .nav&gt;li { position: relative; display: block } .nav&gt;li&gt;a { position: relative; display: block; padding: 10px 15px } .nav&gt;li&gt;a:focus, .nav&gt;li&gt;a:hover { text-decoration: none; background-color: #eee } .nav&gt;li.disabled&gt;a { color: #777 } .nav&gt;li.disabled&gt;a:focus, .nav&gt;li.disabled&gt;a:hover { color: #777; text-decoration: none; cursor: not-allowed; background-color: transparent } .nav .open&gt;a, .nav .open&gt;a:focus, .nav .open&gt;a:hover { background-color: #eee; border-color: #337ab7 } .nav .nav-divider { height: 1px; margin: 9px 0; overflow: hidden; background-color: #e5e5e5 } .nav&gt;li&gt;a&gt;img { max-width: none } .nav-tabs { border-bottom: 1px solid #ddd } .nav-tabs&gt;li { float: left; margin-bottom: -1px } .nav-tabs&gt;li&gt;a { margin-right: 2px; line-height: 1.42857143; border: 1px solid transparent; border-radius: 4px 4px 0 0 } .nav-tabs&gt;li&gt;a:hover { border-color: #eee #eee #ddd } .nav-tabs&gt;li.active&gt;a, .nav-tabs&gt;li.active&gt;a:focus, .nav-tabs&gt;li.active&gt;a:hover { color: #555; cursor: default; background-color: #fff; border: 1px solid #ddd; border-bottom-color: transparent } .nav-tabs.nav-justified { width: 100%; border-bottom: 0 } .nav-tabs.nav-justified&gt;li { float: none } .nav-tabs.nav-justified&gt;li&gt;a { margin-bottom: 5px; text-align: center } .nav-tabs.nav-justified&gt;.dropdown .dropdown-menu { top: auto; left: auto }

</style>
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
