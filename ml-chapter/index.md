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
  var n = current_url.indexOf("gurgaon");
  if(n!=-1)
  {
      document.getElementById("tab2").checked = true;
      hideDiv(2);
  }
  
  else if(current_url.match("mumbai$"))
  {
      document.getElementById("tab3").checked = true;
      hideDiv(3);  
  }
  else if(current_url.match("mumbai/$")||current_url.match("mumbai$")||current_url.match("bangalore$"))
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
     document.getElementById("mumbai_div").style.display="none";
     window.location.hash = "bangalore";
   }
   else if(flag==2)
   {
      
     document.getElementById("bangalore_div").style.display="none";
     document.getElementById("gurgaon_div").style.display="inline";
     document.getElementById("mumbai_div").style.display="none";
     window.location.hash = "gurgaon";
   }
   else if(flag==3)
   {
      
     document.getElementById("bangalore_div").style.display="none";
     document.getElementById("gurgaon_div").style.display="none";
     document.getElementById("mumbai_div").style.display="inline";
     window.location.hash = "mumbai";
   }
 }
</script>

# Want to organize a meetup in your city? 
<p><b> <a href="/ml-chapter/ML-India_Get Started Kit.zip">Download</a> our 'Get Started Kit'! </b></p>

<body onload="pageSet()">
  <input id="tab1" type="radio" name="tabs" onclick="hideDiv(1)">
  <label for="tab1" >Bangalore</label>
   <input id="tab2" type="radio" name="tabs" onclick="hideDiv(2)">
  <label for="tab2" >Gurgaon</label>
  <input id="tab3" type="radio" name="tabs" onclick="hideDiv(3)">
  <label for="tab3" >Mumbai</label>

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
      <br>
      <li style="margin-left:15px;">28th January, 2017. Discussion on applications of some simple ML algos and data forecasting strategies to trading solution.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-eighth-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">18th February, 2017. Discussion on Entity search systems and improving search query responses.
      
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-bangalore-chapter-ninth-meetup/" target="blank">here</a>.
      </li>
      <br>
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
<li style="margin-left:15px;">27th November, 2016. Discussion on the learnings and doubts from Week 1 of CS231, a computer vision and deep learning course offered by Stanford.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-fifth-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">18th December, 2016. Discussion on the learnings and doubts from Week 2 of CS231, a computer vision and deep learning course offered by Stanford.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-sixth-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">15th January, 2017. Discussion on vectorization of textual data and its’ applications in classification problems.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-seventh-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">5th February, 2017. Discussion on applications of some simple ML algos and data forecasting strategies to trading solutions.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-gurgaon-chapter-eighth-meetup/" target="blank">here</a>.
      </li>
      <br>
      
</ol>     
<hr>

</div>
<div id="mumbai_div">
<ol>
     <li style="margin-left:15px;">4th February, 2017. Introduction to ML and discussion of the paper: A Machine Learning Approach to Twitter User Classification by Pennacchiotti et al.<a href="http://www.aaai.org/ocs/index.php/ICWSM/ICWSM11/paper/view/2886/3262" target="blank">[link]</a>
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-mumbai-chapter-first-meetup/" target="blank">here</a>.
      </li>
      <br>
      <li style="margin-left:15px;">4th March, 2017. Introduction to Natural Language Processing.
      <br>
      Read a blog entry related to it <a href="http://ml-india.org/ml-india-mumbai-chapter-second-meetup/" target="blank">here</a>.
      </li>
  
</ol>
<hr>
</div>
{% include _subscribe.html %}

</body>
