---
layout: post
title: "ML-India interview series - Dr. Niraj Kumar, Senior Machine Learning Scientist at Phenom People, India"
excerpt: "Dr. Niraj Kumar is a senior machine learning scientist at Phenom People, India. He completed his Ph.D. in computer science from the IIIT Hyderabad, and did his MCA in computer science from IGNOU, Delhi. 
"
tags: [india, machine learning, data science, interview, niraj kumar, IIIT-Hyderabad, International Institute of Information Technology Hyderabad]
comments: true

tags_relevant: [interview]
---

<br>
<img src="http://i66.tinypic.com/16lir5y.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">
[Dr. Niraj Kumar](https://sites.google.com/site/nirajatweb/){:target="_blank"} is a senior machine learning scientist at Phenom People, India. He completed his Ph.D. in computer science from IIIT Hyderabad, and did his MCA in computer science from [IGNOU](http://www.ignou.ac.in/){:target="_blank"}, Delhi. He completed his post doc from University of California, Davis. His research interests are NLP, IR&IE, Data Mining, Machine Learning and Deep Learning. 

<br><br><br><br><br><br>Niraj on ..

 - <a href="#work_exp">His problem statements during PhD</a>
 - <a href="#tcs">His work at TCS Innovation Labs</a>
 - <a href="#personal">Personal research interests</a>
 
 
<br><br>

**ML- India:** We'd like to start off by understanding how you got initiated into the machine learning space?

  

**Niraj:** Since I had a strong interest in computer science, I decided to pursue BCA and MCA from [IGNOU](http://www.ignou.ac.in/){:target="_blank"} university through correspondence from 1999 to 2004. During the same period, I was working as a private tutor (for computer science courses taught in IGNOU and other college/universities). I also worked as a Computer Science teacher at DAV school, at the early stage of my study. Such involvements in computer science courses strengthened my interest in computer science and I wanted to study further and pursue research in this area. With this aim in mind, I appeared for GATE examination and [IIIT-H](https://www.iiit.ac.in/){:target="_blank"} PG-entrance examination for MS by research program at IIIT-H in 2006. During my MS, I was exposed to concepts like data mining, machine learning, and unsupervised learning, etc., and I found them really exciting.<img src="http://i68.tinypic.com/2vtquzn.jpg" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> The interest in these topics led me to convert my MS program to a Ph.D. and I explored these ideas in greater detail. I got some machine learning experience in the industry while working as a researcher in [TCS innovation lab](https://www.tcs.com/research-innovation){:target="_blank"} for two years. During this period, I started strengthening my grasp on deep learning. Even to make these things freely available to needful students/professionals, I started a YouTube Channel: “Be Expert in Minutes”. I further explored my knowledge of machine learning and deep learning during my PostDoc at [UC Davis](https://www.ucdavis.edu/){:target="_blank"} (2015-2016) and in now using it in the current company. 

  
  
  <a name="work_exp"></a>

**ML- India:** Could you elaborate more about your PhD work at IIIT-H ? And also the work that you did at UC Davis?

  
  

**Niraj:** During my PhD at IIIT-H, I majorly worked on social graph-based unsupervised techniques for intelligent text mining. The first of many projects that I worked on was focused on ‘meaningful phrase identification’. It was based on the premise that the performance of several text mining tasks depends upon the quality of the identified phrases. We introduced the centrality measures based technique for phrase identification having accuracy more than 90%. We effectively applied this technique to key-phrase extraction. I also worked on differentiating role and sense of words, preferring to do it via a single measure. Several times words having same sense may have different roles in document(s). Neglecting such information may misguide us, especially when we compare two different texts having matching words, like: summarization evaluation, and evaluation of descriptive answers and essays, etc. We introduced the use of graph based mapping of co-occurring words and closeness centrality score to identify the role and sense of words in text.

Another project that I worked on dealt with handling information gap at the phrase level by using unsupervised scheme. We introduced the Wikipedia anchor text community detection based scheme, to reduce the information gap between N-grams that are conceptually-related, despite not having a match owing to differences in writing scheme or strategies. For example, identifying differently expressed phrases, which carry the same meaning in texts like: [1] AK47 and [2] Kalashnikov rifle.

  

Integrating the importance of words as a core feature was another aspect of my work during my PhD. As every word/phrase in the document may have different levels of importance, therefore, ignoring this fact entails to working with less information about the text. By following this trend, we integrated the weighted importance of terms with social graph based techniques for improvements in the quality of information extraction. My work on identifying group semantics and/or logically related features for the sequence of terms focused on searching terms which are semantically/logically related to a given set of terms. Even, if, each term in a group may have different semantics. Eg. If we have a sequence: "cause of Swine flu" the logically related terms will be: H1N1 # 0.734, H3N2v # 0.671, virus # 0.760, influenza # 0.478, contacts # 0.332 and so on. Here weights are included with extracted terms. 

  

I also worked on sentence abstraction. This included logically connecting the useful information spread in multiple sentences. For instance, if we have three sentences like: "Prime-minister ABC visited USA. The visit was very useful. Prime-minister signed defense-deal with president XYZ." Our sentence abstraction technique will combine the useful information like: "Prime-minister ABC visited USA, signed defense-deal with president XYZ". We used vertex constrained shortest path based technique, with Wikipedia based semantics and other statistical techniques to achieve such type of abstractions.

  

We used these techniques in the development of multiple text mining applications, which performed better than the state-of-the-arts at that time. The text mining applications are: (a) Single and Multi-Document summarization, (b) Automatic Summarization Evaluation, (c) [Document Clustering](https://en.wikipedia.org/wiki/Document_clustering){:target="_blank"}, (d) Key phrase Extraction and (e) Automatic Question Answering.

  
  

During my PhD, My system was in Top system for "Automatic Summarization Evaluation Task" at Text Analysis Conference in 2011 as well as in 2010 (TAC 2011, TAC 2010), organized by National Institute of Standards and Technology (NIST), Gaithersburg, Maryland. Our unsupervised phrase identification technique for keyphrase extraction has been appreciated by the survey paper published in COLING-2010, Titled: "Conundrums in Unsupervised Keyphrase Extraction: Making Sense of the State-of-the-Art"

  

During my postdoc at UC Davis, I worked on taxonomy classification: We considered <img src="http://i65.tinypic.com/2hi5ypz.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> it as a multi-class classification problem. To identify features related to the different knowledge classes in the given document, we used the NLP based techniques (especially to identify the linguistic dependencies between terms) and deep learning (to identify the logical connectivities between terms, as an improvement). Finally, based on the extracted features, we classified the text into the corresponding categories. 

  
  
<a name="tcs"></a>
**ML- India:** Could you tell us about some of your work at TCS Innovation lab and your internship at IBM ?

  

**Niraj:** At TCS Innovation Lab, I worked on two major projects. First was focused on devising automatic quality assessment strategies to identify the quality of documents and the second on paraphrasing techniques. Actually, paraphrases are sentences or phrases that convey the same meaning using different wording. The presence of the high volume of paraphrased text is a major challenge in almost all areas of text mining, as it badly affects the performance of the system. I developed a semantically reach graph-based technique to handle the paraphrasing in the field of Plagiarism detection. The system finally uses multi-class classification strategy to classify the plagiarised text into four different categories. I received the ‘Best Paper Award’ at [CICLing](http://www.cicling.org/){:target="_blank"} 2014, for my work on the paper: "A Graph Based Automatic Plagiarism Detection Technique to Handle the Artificial Word Reordering and Paraphrasing". 

  

During my two and half months at IBM research internship, I developed a new system to answer “Why based questions” (eg., Why Sky is Blue ?) with the help of Wikipedia dump. The system uses [LUCENE](https://lucene.apache.org/){:target="_blank"} to identify the candidate Wikipedia documents, which may contain the answer to the given question. Next, It converts the candidate documents into word graph of text (similar, as applied in TEXTRANK). Next, It uses the pagerank with prior to rank all the words in the candidate documents by using non-stopwords of the given question as seed words (or prior). Finally, with the help of high ranked words (obtained by using pagerank with prior), the system identify the Wikipedia passage, which may contain the answer. I got the best summer intern research and presentation award, 3rd place.

  
  
  
  

**ML- India:** How is data science and machine learning involved in your work at Phenom People?

**Niraj:** At Phenom people, we make use of data science to provide highly effective and personalized B-2-B job search and other related services. Recently we develop a novel weighted knowledge graph for Smart B-2-B hiring (filed patent). The system has been successfully tested in healthcare and information technology domain. This graph captures a broad range of job-requirements and features (applicable for skilled workers), like required skills, job titles, job area, required education, soft-skills, and so on. What is really valuable in this graph is that it can automatically<img src="http://i67.tinypic.com/qyhmdd.png" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> learn weighted relations and hence recommend stuff/ mine patterns and perform a lot of querying to gain insights. The key data science technologies used in this weighted knowledge graph are NLP, statistical techniques, and deep learning. We started using this weighted knowledge graph as a key ingredient in new job-search features like contextual search (with dynamically extracted personalized context) and personalized search, etc. We are also using this weighted knowledge graph and some new data science stuff (NLP, deep learning, and machine learning) to effectively rank the candidates for the given job profile, recommend the quality jobs to candidates and so on.

  
  
  <a name="personal"></a>

**ML- India:** What are your personal research interests? Any problems that you have in mind that you'd like to solve using ML research?

  

**Niraj:** My current research areas are: (1) Exploring and enhancing the construction of domain-specific weighted knowledge graphs and dynamic ontologies, (2) Automatic taxonomy categorization, (3) Handling issues related to paraphrasing and (4) Meaningful fusion of information spread in heterogeneous sources. I am using NLP, statistical techniques, machine learning, and deep learning to solve these problems.

  

My personal research agenda is somewhere where I have not worked a lot yet. I’m very curious to understand the human brain. I want to understand and develop algorithms which can help us understand and model human brain. Recently there was a buzz in the community that deep learning models the way human brain works but they are yet far from explaining many activities which our brains performs in a flash which any deep learning algorithm struggles to achieve with even acceptable accuracy. There is another line of thought which says that brain can be better explained through quantum computing. Since I deeply believe in the fact that most of the research we do is already available in nature, understanding the way brain (and some other such naturally smarter systems) functions will help us in introducing/improving a lot of algorithms and applications in ML and AI. I want to work on these lines somewhere in future.

  
  

**ML- India:** What is your take on the current ML research atmosphere in India? Do you think there are any low hanging initiatives that could be exploited to propel the current state or any steps that you think can be taken to achieve the same?

  

**Niraj:** The education in India definitely needs improvement and especially in ML domain. The world is going through an ML/ AI revolution through and I believe India has the potential to tap from this revolution. In the near future, all government and economic policies would be determined by data science, doctors would write prescriptions based on insights extracted from clinical data. We might see new types of fusion and intelligent interfaces, like chatbots, which would have the ability to process audio/ text/ visual data and provide services. We have adequate talent in terms of good and interested students to work in these areas but we fall flat when we compare the education level and facilities in western universities. One quick improvement that can be made is to increase in funding. For example, there should be enough funding for students to attend conferences. Only through these conferences can students get to know about the latest research. This is one area which is kind of a low hanging fruit. Other may be research focused teaching. The government should take some impactful steps to make research outcomes mandatory (I mean quality research, which is absent these days) in all academic institutions.


**ML- India:** Thanks a lot for your time, Niraj. We wish you all the best for your future work.
