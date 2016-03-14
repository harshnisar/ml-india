<style>
      
*, *:before, *:after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
ml-chapter/
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
    


<body>
  <input id="tab1" type="radio" name="tabs">
  <label for="tab1" >Banglore</label>

<div id="banglore_div">
<hr>
<h2>List of meetups: </h2>
<ol>
      <li>27th February, 2016. Discussion of the paper: A Machine Learning Approach to Twitter User Classification by Pennacchiotti et al.<a href="http://www.aaai.org/ocs/index.php/ICWSM/ICWSM11/paper/view/2886/3262" target="blank">[link]</a>
      <br>
      Read a blog entry related to it <a href="http://suyash1003.github.io/ml-india/ml-india-bangalore-chapter/">here</a>.
      </li>
<ol>

</div>



{% include _subscribe.html %}
</body>
