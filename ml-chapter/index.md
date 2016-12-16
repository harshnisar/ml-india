---
layout: page-table
title: 
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "ML Chapter"
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
      if(current_url.match("ml-chapter/$")||current_url.match("ml-chapter$")||current_url.match("bangalore$"))
      {
            document.getElementById("tab1").checked = true;
            hideDiv(1);
      }
 }
 function hideDiv(flag)
 {
      if(flag==1)
      {
            document.getElementById("bangalore_div").style.display="inline";
            document.getElementById("gurgaon_div").style.display="none";
            window.location.hash = "bangalore";
      }
      if(flag==2)
      {
            document.getElementById("bangalore_div").style.display="none";
            document.getElementById("gurgaon_div").style.display="inline";
            window.location.hash = "gurgaon";
      }
 }
</script>

# Want to organize a meetup in your city? 
** [Download](/ml-chapter/ml meetup guide.pdf) our step-by-step guide!**

<body onload="pageSet()">
  <input id="tab1" type="radio" name="tabs" onclick="hideDiv(1)">
  <label for="tab1" >Bangalore</label>
   <input id="tab2" type="radio" name="tabs" onclick="hideDiv(2)">
  <label for="tab2" >Gurgaon</label>
<hr>
<h2>List of meetups: </h2>
<div id="bangalore_div">
<ol >
     <li style="margin-left:15px;">27th February, 2016. Discussion of the paper: A Machine Learning Approach to Twitter User Classification by Pennacchiotti et al.<a href="http://www.aaai.org/ocs/index.php/ICWSM/ICWSM11/paper/view/2886/3262" target="blank">[link]</a>
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">2nd April, 2016. Discussion of Borde and Kwik algorithms, and Kaggle problems.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-second-meetup/" target="blank">here</a>.
      </li>
      <br>
       <li style="margin-left:15px;">30th April, 2016. Discussion on the significance of the role of a data scientist and as well as a workshop on Neural Networks.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-third-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">28th May, 2016. Discussion on the basics of Deep Learning and Neural Networks.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-fourth-meetup/" target="blank">here</a>.
      </li>
      <br>
       <li style="margin-left:15px;">28th August, 2016. Discussion on NLP evolution and various word representations.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-fifth-meetup/" target="blank">here</a>.
      </li>
       <br>
       <li style="margin-left:15px;">8th October, 2016. Discussion on Skymind, and Deeplearning4j and why they exist.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-sixth-meetup/" target="blank">here</a>.
      </li>
       <br>
       <li style="margin-left:15px;">22nd October, 2016. Discussion on mapping a person’s skills to the right job.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-seventh-meetup/" target="blank">here</a>.
      </li>
      
</ol>
<hr>
</div>
<div id="gurgaon_div">
<ol >
     <li style="margin-left:15px;">14th May, 2016. Introduction to machine learning pipeline and its fundamentals. A hands-on session on data interpretation and analysis followed by simple model building using Linear-Regression.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-first-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">25th June, 2016. Discussion on proactive search and digital assistants.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-second-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">21st August, 2016. Discussion on face and finger recognition, image processing, and making the learners understand how to break down the problem and then approach it.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-third-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">13th November, 2016. Discussion on kaggle Titanic dataset, and on basic implementation and workflow to build predictive models.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-fourth-meetup/" target="blank">here</a>.
      </li>
      <br>
</ol>     
<hr>

</div>
{% include _subscribe.html %}

</body>
