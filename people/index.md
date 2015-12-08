---
layout: page
title: 
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Indian faculty and research groups in machine learning and data science"
---
  <head>
    <style>
      .nav {
	padding-left: 0;
	margin-bottom: 0;
	list-style: none
}

.nav>li {
	position: relative;
	display: block
}

.nav>li>a {
	position: relative;
	display: block;
	padding: 10px 15px
}

.nav>li>a:focus, .nav>li>a:hover {
	text-decoration: none;
	background-color: #eee
}

.nav>li.disabled>a {
	color: #777
}

.nav>li.disabled>a:focus, .nav>li.disabled>a:hover {
	color: #777;
	text-decoration: none;
	cursor: not-allowed;
	background-color: transparent
}

.nav .open>a, .nav .open>a:focus, .nav .open>a:hover {
	background-color: #eee;
	border-color: #337ab7
}

.nav .nav-divider {
	height: 1px;
	margin: 9px 0;
	overflow: hidden;
	background-color: #e5e5e5
}

.nav>li>a>img {
	max-width: none
}
.nav-tabs {
	border-bottom: 1px solid #ddd
}

.nav-tabs>li {
	float: left;
	margin-bottom: -1px
}

.nav-tabs>li>a {
	margin-right: 2px;
	line-height: 1.42857143;
	border: 1px solid transparent;
	border-radius: 4px 4px 0 0
}

.nav-tabs>li>a:hover {
	border-color: #eee #eee #ddd
}

.nav-tabs>li.active>a, .nav-tabs>li.active>a:focus, .nav-tabs>li.active>a:hover
	{
	color: #555;
	cursor: default;
	background-color: #fff;
	border: 1px solid #ddd;
	border-bottom-color: transparent
}

.nav-tabs.nav-justified {
	width: 100%;
	border-bottom: 0
}

.nav-tabs.nav-justified>li {
	float: none
}

.nav-tabs.nav-justified>li>a {
	margin-bottom: 5px;
	text-align: center
}

.nav-tabs.nav-justified>.dropdown .dropdown-menu {
	top: auto;
	left: auto
}
    </style>
  </head>
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
