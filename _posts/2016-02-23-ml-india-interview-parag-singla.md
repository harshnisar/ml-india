---
layout: post
title: "ML-India interview series - Prof. Parag Singla, Assistant Professor, Indian Institute of Technology-Delhi (IIT-D)"
excerpt: "We interviewed today Prof. Parag Singla. He is an assistant professor in the Dept. of Computer Science in IIT-Delhi. He did his undergraduate studies from IIT-Bombay in Computer Science and completed his PhD. in Markov Logic: Theory, Algorithms and Applications from the University of Washington. Parag has been working in the field of AI and ML. "
tags: [india, machine learning, data science, interview, parag singla, IIT-D]
comments: true
---

<img src="http://www.cse.iitd.ac.in/~parags/images/parag-bw.jpg" align='left' style="margin-right:4px;width:30%">

[Prof. Parag](http://www.cse.iitd.ac.in/~parags/){:target="_blank"} is an assistant professor in the Dept. of Computer Science in IIT-Delhi. He did his undergraduate studies from IIT-Bombay in Computer Science and completed his PhD. in Markov Logic: Theory, Algorithms and Applications from the University of Washington. Parag has been working in the field of AI and ML. 

<br>

Parag’s work focuses on Statistical Relational Learning (SRL), Machine Learning and Lifted Inference. Parag talks in detail on ..

- <a href="#parag_research_areas">His research areas.</a>
- <a href="#parag_on_lifted_inference_learning">Lifted Inference Learning</a>
- <a href="#parag_future_research_directions">His future research directions.</a>
- <a href="#parag_views_on_ML_space">His views on ML-space in India.</a>
- <a href="#parag_some_quick_changes_ML_space">Some quick changes which can benefit ML research in colleges.</a>

**ML-India**: To begin with, congratulations to your group for having three publications at NIPS this year! We want to start off by understanding what motivated you to get into this field?

**Parag**: Thanks! Well, I graduated from IIT-B, 2002 batch. During my undergrad, mainly two areas fascinated me - one was theoretical computer science and the other was databases and information retrieval. I had undergone a course on databases and had liked it very much. I was working on a project which included keyword like querying on relational databases and at that time, it was a big thing. It was interesting to see how one could do unstructured queries on structured databases and it was a fun project to work on. I always wanted to pursue higher studies and was quite clear that I wanted to pursue research. Hence during placements, I sat for only one company. At that time, we didn't have as much resources as are available presently on internet on different researches going on in different part of the world but I was happy that I gained admission into U-wash, Seattle and U. Maryland. Students nowadays have access to a lot of information about the grad schools’ background; they can seek guidance from their seniors. I was happy to know that there was freedom to switch research areas in U-Wash. I took a course by[Oren Etzioni](http://homes.cs.washington.edu/~etzioni/){:target="_blank"} which I really liked and which eventually hooked me to machine learning. I also talked to[Pedro Domingos](http://homes.cs.washington.edu/~pedrod/){:target="_blank"}, my advisor-to-be and started doing an independent research project with him. I had my doubts on machine learning and its relevance; theoretical computer science was still on my mind. So I took one summer off where I worked with someone in theory to be sure that applied machine learning is the area I wanted to work on.

<a name="parag_research_areas"></a>

**ML-India**: Great! So MDPs (Markov decision process) is something you have worked on and continue to pursue even today?

**Parag**: My work was mainly on[Markov logic](https://en.wikipedia.org/wiki/Markov_logic_network){:target="_blank"}; there is a slight difference between Markov logic and MDPs. Markov logic exploits Markov properties but is quite different, in a sense that MDP is more about planning - where you plan and decide the action that should be taken by an agent against an objective. My research is mainly about statistical relational AI. If you look at the history of AI, researchers started off with the idea that they could build logical systems and emulate human intelligence. One approach was to create a system that can represent knowledge in a compact manner. For example, Man is mortal, Anil is a man and therefore, Anil is mortal. To represent knowledge as a logical formula was popular in the beginning. Then came Bayesian networks which have made statistical models very popular. But these models have their pros and cons - logical representation is compact and powerful but doesn't have any notion of uncertainty while we have probabilistic graphical models that capture the uncertainty beautifully but are not compact. I started working on creating a combination of these two. Markov logic is one such model and it was proposed way back by one of my colleagues. I pursued my PhD work on this and I continue to work on it but have also moved on to other areas.

**ML-India**: So do you imply that with Markov logic, we not only have an angle of uncertainty but also rules are being generated statistically?

**Parag**: It is a good inference, though my work was not around rule generation. In logic theory, you can learn the rules automatically but in my case, the rules were probabilistically defined. My work was to efficiently interpret the rules and assign weightage for these rules. If all weights are infinite, it reduces to first order logic. These weights will combine conflicting pieces of knowledge and take care of the exceptions. For example, there is one rare case where cancer happens because of a certain symptom. In a probabilistic model, you can give it a weightage and capture the uncertainty of its occurrence.

<a href="#">[Top]</a>

**ML-India**: Is there any application where you have applied this work and demonstrated its superiority?

**Parag**: People have used it in a number of applications ranging from information retrieval to language processing. I have used it in a problem of entity resolution. The problem is to get the underlying entity over a bunch of records. For example, each citation represents some underlying paper, but different papers cite the same paper differently. So, given different representations of the same entity, how can you resolve it as one entity? A similar problem is faced by governments when they have information about the same person in different forms and from different sources. In such situations, the challenge is how to merge different information to represent a single entity.

**ML-India**: So is this all over supervised data?

**Parag**: Yes, all of this was over a labelled data set.

**ML-India**: In terms of standard machine learning techniques, which is the technique that comes closest to it?
  
**Parag**: The closest that it translates is to a graphical model which is a Markov network. So the logical formulae can be composed into a Markov network, where the formulae can sort of work like features of your network. In Markov networks, we have interconnections with nodes and we do have formulas to represent the relationships. Let's say Bob smokes and Bob and Anna are friends. So, there is a likelihood that Anna also smokes. So it comes close to a graphical model i.e. a Markov network.

<a name="parag_on_lifted_inference_learning"></a>

**ML-India**: Are there any other areas that you are currently focusing on?

**Parag**: This was my PhD work that I finished in March, 2009. After that I did a Post Doc from 2010 to late 2011 in UT Austin, with[Raymond J. Mooney](https://www.cs.utexas.edu/~mooney/){:target="_blank"}. The problem we worked on then was  on applying Markov logic to derive a higher level plan of a person. Let's say if a person goes out to the market and buys flour and is then heating up the oven, then can one figure out that he is planning to bake a cake. Here you have to look at contrasting information, which you have to consider and assume certain things while defining the rules. The other work was around constraint satisfaction.

I came back in 2011 to join as a faculty at IIT-Delhi. In the last 4 years, the core of my research has moved on., I still work in the same framework but we have started to work on[lifted inference learning](http://jmlr.org/proceedings/papers/v33/sarkhel14.pdf){:target="_blank"},[ on which I also worked during my PhD](http://jmlr.org/proceedings/papers/v33/sarkhel14.pdf){:target="_blank"}. What happens in these models is that because we have such a powerful language, we create huge networks. Assume we have a simple rule that if x smokes and x and y are friends, y also smokes. But let's say we have 1000 people, now I have 1000x1000 pairs of friends, which makes it a million connected nodes. Instead of simply about learning weights, it is about both performing inference as well learning of weights efficiently.. In our work on this, we realized that there is another algorithm that can perform better in such scenarios. In[lifted belief propagation](http://www.aaai.org/Papers/AAAI/2008/AAAI08-173.pdf){:target="_blank"}, we use the property of graphical models and make use of the fact that they are symmetrical in nature. So we can use the same probability weightage for all people in the example data-set I discussed earlier. This helps in finding small clusters and guarantees that you get identifiable results had you run it on the entire ground network. This whole area is called lifted inference. Our NIPS paper was in this space which explains how you exploit the fact that everyone has the same probability in the system.

**ML-India**: It’s counter intuitive in the sense that I would think that distance between the two entities would matter.

**Parag**: Here the premise is that how x and y are symmetrically connected to some other entity; we will combine people only based on the same kind of information. This is a very simplistic example but generally you have a lot of information for each entity. Then you can have certain assumptions and bounds to cluster the entities.

<a href="#">[Top]</a>

<a name="parag_future_research_directions"></a>

**ML-India**: Any thoughts on the direction of research you would like to pursue in the next few years?

**Parag**: My main focus is still on the problems that we are working on and it's going nice. I do want to explore the problem of satisfiability. There is another problem of Automorphism in graphs which is more of a theoretical problem. I am also actively collaborating with a researcher from IIIT-D in the field of computer vision. I am collaborating with[Dr. Amitabha Bagchi](http://www.cse.iitd.ernet.in/~bagchi/){:target="_blank"}, a faculty in IIT-D, on social network analysis where we are trying to identify the tweets that are going to go viral etc., which was more about machine learning and feature engineering. We also had a project on opinion mining with DRDO which was more of an applied research project. There the problem was to predict whether their stakeholders would have a negative or positive opinion on any new changes or modifications made to a project they launch. For this project, we had hosted an interesting competition in IIT-D for labelling the data so that the data can be used for supervised learning. I am also working with[Mausam](http://homes.cs.washington.edu/~mausam/){:target="_blank"}, faculty at IIT-D, in the NLP space. Down the line, I wish to work on applications which are directly relevant to the society using ML, on a day to day basis. Presently, I haven't given much thought to it but I wish to work on these areas.

<a href="#">[Top]</a>

<a name="parag_views_on_ML_space"></a>

**ML-India**: What is your take on the general AI/ML space in India?

**Parag**: I am optimistic about the developments which are going on in India around ML. I can talk more about academia and I was browsing through ML-India and I agree that the number of publications from India are very low. But, looking at the papers in the past years it is definite that the publication numbers are going up. Some people have done very good research and are moving back to India and things are warming up. If we keep the bar high and not celebrate mediocrity, it will definitely push the students to move forward.

<a href="#">[Top]</a>

<a name="parag_some_quick_changes_ML_space"></a>

**ML-India**: Do you think  there are any low-hanging fruits that can be utilized to bring quick change?

**Parag**: I can answer from my perspective, the things that worked for me.

1. Keep the collaborations with the West intact. Many good conferences happen in the West and many discussions do happen over these conferences and talks. Right after returning, I felt that I was out of touch with the research happening there. A good deal of learning happens over face to face discussions in such conferences. I am now consciously keeping internal collaborations intact so that I don’t lose touch. I would recommend the same to other junior faculty members as well.

2. The quality of the graduate students is going up. I've had grad students who are competing with   most confident undergraduates. One thing that has worked for me is to have a really smart undergrad, who will leave in a year, work with another smart and motivated grad student, who in turn will be working on the project for a reasonably longer period of time. They tend to build on each other's skills which is a good thing for a project.  I try to handpick students who are really motivated towards higher studies because the research also incentivizes them to work harder for their profile.

<a href="#">[Top]</a>

**ML-India**: Given your schedule, what is the time split between working on a research problem, coursework and conference visits?

**Parag**: The conference travelling time is not very significant. I try to go to one conference every year and it’s usually a week's time. The coursework takes about 25-30% of time and that is required. I have been getting good feedback with regards to my coursework. 10% of the time is taken up by the administrative duties and the rest of the time is taken up in research. If it’s a totally new coursework, it takes a little more time but otherwise it’s near to 25-30% only.

**ML-India**: Thank you for your time and words, Parag. All the very best to you from ML-India!
