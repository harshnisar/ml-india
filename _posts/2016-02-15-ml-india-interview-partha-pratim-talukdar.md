---
layout: post
title: "ML-India interview series - Prof. Partha Pratim Talukdar, Assistant Professor, Indian Institute of Science (IISc)"
excerpt: "We interviewed today Prof. Partha Pratim Talukdar. He is an assistant professor, Dept. of Computational and Data Sciences and Dept. of Computer Science and Automation in IISc. He did his undergraduate from BITS-Pilani in Computer Science and completed his PhD. in Graph-based Weakly-Supervised Methods for Information Extraction & Integration from UPenn. Partha has been working in the field of ML, NLP and Big Data."
tags: [india, machine learning, data science, interview, partha pratim talukdar]
comments: true
---

<img src="http://talukdar.net/IMG_3074.jpg" align='left' style="margin-right:4px;width:30%">
We interviewed today [Prof. Partha Pratim Talukdar](http://www.talukdar.net/){:target="_blank"}. He is an assistant professor, [Dept. of Computational and Data Sciences](http://www.cds.iisc.in/){:target="_blank"} and [Dept. of Computer Science and Automation](http://www.csa.iisc.ernet.in/){:target="_blank"} in IISc. He did his undergraduate from BITS-Pilani in Computer Science and completed his PhD. in Graph-based Weakly-Supervised Methods for Information Extraction & Integration from UPenn. Partha has been working in the field of ML, NLP and Big Data.

Partha’s current work focuses on creating knowledge graph from unstructured data available on the internet. Partha talks in detail on ..

 - <a href="#partha_research_areas">His research areas.</a>
 - <a href="#partha_on_knowledge_graphs">Knowledge graphs from unstructured data. </a>
 - <a href="#partha_on_crowdsourcing">Crowdsourcing</a>
 - <a href="#partha_group_furture_research_directions">His group’s future research directions</a>
 - <a href="#partha_views_initiatives">His views and initiatives for ML in India.</a>

**ML-India**: What is your undergraduate background and what initiated you in the field of ML?

**Partha**: I did my undergrad in BITS Pilani and at that time I was into networking. During my third year, I was offered [summer fellowship in IISc](http://www.successcds.net/Scholarships/IISc-YOUNG-ENGINEERING%20-FELLOWSHIP.php){:target="_blank"}. During my fellowship, I started working on natural language processing under the guidance of [Dr. N. Balakrishnan](http://www.serc.iisc.ernet.in/~balki/){:target="_blank"} and [Dr. K.R.Ramakrishnan](http://www.ee.iisc.ernet.in/faculty/krr/index.php){:target="_blank"}. The fellowship introduced me to a whole new world there has been no looking back since then. I got really fascinated by the problem and the potential this area has. I also worked in HP labs for a year right after undergrad where too I worked on text and machine learning. After that I went to grad school. In essence,  it was summer the fellowship that hinged me to machine learning.

**ML-India**: From which department of IISc did you do your fellowship?

**Partha**: It was [Supercomputer Education & Research Center (SERC)](http://www.serc.iisc.in/facilities/){:target="_blank"}; in a way I am completing the loop as presently I am teaching in the same department.

<a name="partha_research_areas"></a>

**ML-India**: What was your focus of research in your graduate studies? Do you continue to work on the same topics now?

**Partha**: My focus of research was the same as what I am pursuing today in the field of machine learning. Recently, in a bout of reminiscence, I was going through read my SOP and was quite pleased to learn that I am still working on the same problems that I said I wanted to work on in grad school. I worked in the broad area of unstructured text management. Increasingly, we are getting dependent on machines for decision making which humans used to do, but they don't have the background knowledge that we have. This is in a way unfair to them as we are expecting them to decide in the same way as we do but without giving them the background knowledge. Our lab is trying to make the required world knowledge available to machines with enough granularity.

**ML-India**: Am I correct in assuming that this work spans both, systems and theory?

**Partha**: Yes, imagine a bot which has to make real-time decisions and where it needs to query a about the world around it and expects results in a fraction of a second. This is what we’re building; we are building a search engine like Google but for machines. We see the entire web as one proxy where most of the knowledge is present but in an unstructured format. Our goal is to take that information and extract  knowledge out of it so that it's really easy for machines to interpret. There are different entities on the web and they may or may not be related to each other. In a way it is a multi-relational graph where nodes are the entities of interest and edges are relationships between entities. We want to move from [unstructured data to a structured graph](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.228.9777&rep=rep1&type=pdf#page=612){:target="_blank"}. Moreover, new data keeps on appearing on the web, so the next problem is to keep such a knowledge updated and fresh. The construction of the knowledge is not the end goal; we want to use it for different applications which may require different “kinds of knowledge” from the same data. It can also happen that the application pushes new knowledge into the graph. In some sense, it is using machine learning to extract a knowledge graph but also to use this knowledge graph to improve different machine learning algorithms. One can see this as a positive feedback loop.

<a href="#">[Top]</a>

<a name="partha_on_knowledge_graphs"></a>

**ML-India**: I am assuming that there are a lot of players in this space who are working on generating Knowledge graphs and curating them so that they can be consumed in different applications. Is your work domain specific to some extent or is it domain agnostic?

**Partha**: Before coming here I was a part of [CMU's NELL(Never-Ending Language Learning)](http://rtw.ml.cmu.edu/rtw/){:target="_blank"}, where the idea was to push a parallel theme of advancing this paradigm of using machine learning learn  in a knowledge-rich environment. Traditionally, we have a dataset where we train a single approx. function, finalize the best performing function and then use the trained function on new data. This is not how humans learn though. We learn multiple tasks over the same time and use older task learnings to learn new tasks. The training time is not fixed and is spread over the life span. The goal there was to use this paradigm and then apply this to the knowledge extraction project where there is constant updation of data. It was sort of a dual project.

The effort was unique, which motivated me to extend that work over here in our lab. Coming back to your question, there are multiple school of thoughts in this space, one of them being the idea of a semantic web The goal of creating a knowledge graph is a shared objective but the knowledge that you are extracting from the data varies between applications. Researchers usually start from structured or semi-structured data where the knowledge is semi-organized to create a unified graph. There are many commendable efforts such as [Yago](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/){:target="_blank"} and [Freebase](https://www.freebase.com/){:target="_blank"}, where Yago is making a unified semantic web from semi-structured data and freebase is a human-centric solution to the same. In this spectrum, NELL is unique as they use totally unstructured text. There is also a Google project named as [Knowledge Vault](https://www.cs.ubc.ca/~murphyk/Papers/kv-kdd14.pdf){:target="_blank"}, where they too are working on unstructured data. In my opinion, it is one of the hardest problem out there. About your question, NELL was domain agnostic and we were trying to convert the unstructured data to structured knowledge graphs. But we increasingly felt that if we wanted to use this knowledge graph in a specific application, it ought to be more granular and domain specific. At my lab, we are working on how can we make such a knowledge graph if fed specific domain data, say just cancer research papers. However, in doing so, we have to be careful to not do away with a general purpose graph since it has its own benefits of learning general concepts. For instance, in cancer research, I need to know specific proteins which are creating a gene, but the idea of a protein creating a gene  might have been discovered in a general purpose knowledge graph. So we have are looking at how we can start from a general purpose background knowledge graph and then develop a specific domain graph over it.

<a href="#">[Top]</a>

<a name="partha_on_crowdsourcing"></a>

**ML-India**: A related question, how does one understand how well a knowledge graph one has built? What are the metrics that are used to understand its “richness”?

**Partha**: Evaluation of a knowledge graph is a very critical and important aspect while developing them. There are two ways of evaluating a knowledge graph, 1. Intrinsic evaluation measure: Once the knowledge graph has been prepared by the algorithm, one can go to each of the K fragments of the knowledge graph and evaluate whether what it has learned is correct or wrong, aggregate all of the statistics and then get a graph level accuracy. 2. Extrinsic evaluation measure: See how well knowledge graph performs on a specific application. We can plug a particular version of the knowledge graph to the application and observe how it improves the performance of the system. In a way, it's an indirect feedback. For intrinsic evaluation, there are a lot of interesting challenges. Let's say my knowledge graph has 10 million edges and I use humans or crowdsourcing, where I have to pay the evaluator something for each evaluation, but I have a limited budget. This raises another interesting question of how can I utilize my constrained resources to the best evaluate my knowledge graph. This is a parallel paradigm of crowdsourcing which interestingly has not been explored earlier. We are working on this problem of getting the best out of a constrained budget in crowdsourcing.

**ML-India**: Is [Prof. Narahari](http://lcm.csa.iisc.ernet.in/hari/){:target="_blank"} also working on the same problem but from a game theory standpoint?

**Partha**: Yes, their lab also works on problems in crowdsourcing and mechanism design in general. But they do not currently focus on problems related to knowledge graphs.

<a href="#">[Top]</a>

**ML-India**: So, You are running a truly interdisciplinary lab, what are the different areas that are worked on in your lab on an everyday basis?

**Partha**: This is one of the thing that I like about working in this area that it touches upon various aspects of different disciplines. In Computer Science, this research touches on many different areas of machine learning, natural language processing and big data analysis. Since, we want to do things at scale, we don't have the luxury to work on supervised learning and we need to learn using weakly or semi-supervised methods. While you work on large data, all the system related problems become true. Systems are really important while implementing these projects. Graphs, particularly multi-relational graphs, are an important data structure for us and thus concepts of graph theory also comes into play. It's not surprising because knowledge is universal and the technique to build knowledge, and make them useful, touches many different area of computer science. This is more on the side of techniques but regarding to applications, once you have built this, how will you use them in different applications. In the past I have explored its use in neuroscience and can typically be used in an area where there is a kind of non-trivial decision making going on. We are trying to collaborate with a team which works in the field of neuroscience. There are material scientists who are interested in using materials’ knowledge to do better material discovery. This project is highly interdisciplinary not just from a techniques standpoint but also from the applications it serves. This is really important for us as it provides an opportunity to allow people having diverse interests contribute to it.

<a name="partha_group_furture_research_directions"></a>

**ML-India**: What are your research goals in the immediate future? Any specific problem which you are keen on chasing but haven't yet tackled?

**Partha**: There is so much to do and only so many hours in a day. I'm hoping that somebody reading this gets excited and decides to contribute in these areas. Representational learning is one area which is important and is a common theme. We plan to make more advances in this area. . I see one spectrum in the field of knowledge learning, where at one end we have this highly effective representation that learns i.e deep learning but they are usually non interpretable which makes its' reasoning difficult because we don't know what we are dealing with. On the other hand there are these highly interpretable knowledge graphs on which it is really easy to do some reasoning but which has limitations on what can be learnt. There are a lot of opportunities to explore in between where the hybrid of symbolic and continuous representational learning can be explored. We can use their representations to do inferences. We have done some work on this but we want to make them more advance. We would also like to have some demonstrative use cases and applications where we could prove the use of our knowledge graph.

<a href="#">[Top]</a>

**ML-India**: Is there any poster boy application that your group is really proud of?

**Partha**: [My group](http://talukdar.net/mall-lab){:target="_blank"} is very new and it’s been only a year. We are trying to put things together but there are some user generated content analysis. We recently worked on on predicting which of the questions get answered online and which don't. We are trying to extract the factors which contribute to this. We are exploring many potential applications.

**ML-India**: Having had the perspective of how things happen outside, what would be your current take on the research ecosystem in India? Are there any new initiatives which are being taken or is there need of a larger systematic change?

**Partha**: I haven't been here for too long. But from what I have seen in IISc and other research labs, I am optimistic and there is a positive gradient and things are moving in the right direction. Also, because of the development of industries in these areas there is a strong interest to develop and use these techniques. It is an exciting time to be in this area in India. People are working on really interesting problems and we are in a good position to do some contribution.

**ML-India**: How do you find the general quality of graduate students that you have worked with?

**Partha**: I am quite satisfied and happy with the quality of the students that I have worked with, but we need more of that. There is much larger demand than the supply. We need more outreach programs to expose undergraduates for research oriented internships similar to the one I had during my undergrad. As compared to the west, I don't think there is much of a difference in the quality of students or research work. It is more advantageous in a way that we don't have to thrive for funding as in the west and can focus more on research.

**ML-India**: How do you split your time between teaching and research? Do you find it challenging?

**Partha**: Here at IISc, which is primarily a graduate school, we have two courses maximum per year. Also, if you co-teach the load comes down even more. Over the time, I have realized that the teaching is the best way of improving your knowledge. I have thought about different topics from different angles while teaching which I hadn't thought of earlier. The enthusiasm of the students to work with me gives me an extra boost, students are giving up better options to work with me. The enthusiasm of the students as well as such interesting research challenges gives you an extra energy.

<a name="partha_views_initiatives"></a>

**ML-India**: Do you think there are any low-hanging fruits that can be utilized to bring quick changes in the system?

**Partha**: We need to increase the number of good quality students in this field. We need to motivate good students to pursue research in Indian institutions. I have seen things on both sides and I think we can offer some good value in terms of training students. I see a lot of undergrads applying abroad, I would like to see them apply to IISc and other Indian institutions. I don't think training available here, for graduates, is any way less than what’s offered outside. So, I try to focus on these outreach events and inform undergraduates about the possibilities over here. I try to go to undergraduate colleges for talks and seminars. Also, there should be more research internships and participation in conferences. Summer/winter schools in ML and other topics are definitely important and should be repeated more often because the amount of training that is available in different universities may not be uniform. We should also try to invite international speakers, who are pioneers in their fields, for seminars and talks. Students these days are putting an effort to learn from online courses but they need to take the more important next step and take up some projects where they can apply the learned knowledge. So its equally important to have more internships in the field.

<a href="#">[Top]</a>

**ML-India**: Are there any other research groups that are working on similar problems?

**Partha**: There are multiple research groups interested on different aspects of this spectrum. There are also some researchers in IIT-D, IIT-B, NELL at CMU etc. who are working in these fields. We also have industrial partnership with Google, Accenture, Bosch-India and NVIDIA. We are also interested in doing some collaborative projects. In my own career, I have benefitted largely from industry collaborations and most of the time they do have a lot of interesting datasets.

**ML-India**: Thank you for your time, Partha. All the very best to you from ML-India!
