---
layout: post
title: "ML-India interview series - Prof. Mausam, Associate Professor, Indian Institute of Technology-Delhi (IIT-D)"
excerpt: "Prof. Mausam is an associate professor at the Dept. of Computer Science in IIT-Delhi and an affiliate faculty
at the University of Washington. He got his undergraduate degree from IIT-Delhi in
Computer Science in 2001 and completed his PhD. work titled Stochastic Planning with Concurrent, Durative Actions from the University of Washington in 2007. 
"
tags: [india, machine learning, data science, interview, mausam, IIT-D, indian institute of technology delhi]
comments: true

tags_relevant: [interview]
---

<img src="http://homes.cs.washington.edu/~mausam/mausam-head.jpg" align='left' style="margin-right:4px;width:30%">
[Prof. Mausam](http://homes.cs.washington.edu/~mausam/){:target="_blank"} is an associate professor at the Dept. of Computer Science in IIT-Delhi and an affiliate faculty
at the University of Washington. He got his undergraduate degree from IIT-Delhi in
Computer Science in 2001 and completed his PhD. work titled Stochastic Planning with Concurrent, Durative Actions from the University of Washington in 2007. 

Mausam's work focuses on large-scale information extraction and text summarization, AI & ML applications to crowdsourcing and education, automated planning under uncertainty, machine learning, and probabilistic reasoning. 

<br><br>
Mausam on ..

 - <a href="#research_areas">His research areas.</a>
 - <a href="#research_crowdsourcing">Research in Crowdsourcing</a>
 - <a href="#research_information_extraction">Research in Information Extraction</a>
 - <a href="#research_education">Research in Education</a>
 - <a href="#about_research_ML_India">About the research in ML in India</a>


**ML-India:**
What is your undergraduate background and what initiated you in the field of
ML? 


**Mausam:** I did my undergraduate studies in Computer Science from IIT-Delhi but we did not have any ML teacher at the time. I had a course on AI but I had not taken it. During the first
quarter of my graduate studies I took my course on AI, but I didn't know what to expect from it. As part of our coursework, teams had to create bots which would compete with each other in the game of Chess. Our bot faced a Chinese team in the finals and we won! The Chinese team later found out that their code had a small bug and asked for a rematch. We had a rematch and we won again! In hindsight, one thing that really hooked me onto AI was that I found its balance between theory and practice really engaging. 

During my undergraduate studies in IIT-D, I noticed that our department had a really strong research agenda in theoretical computer science and though I enjoyed it thoroughly, I was not quite satisfied pursuing core theoretical research. On the other hand, systems and networks research had many visible applications in everyday life, but I wasn’t sure about that as my research area either. I guess I had sort of an open mind when it came to choosing a specialization and pleasantly found out that AI and ML attracted me the most. My advice to students is the same - keep an open mind and explore as many concepts as possible during your undergrad. It would help make an informed choice in grad school.


**ML-India:**
You did your PhD during 2001-2007, which was the golden era for all sorts of ML/AI technologies. So, was that also a compelling reason to get into ML or was your motivation totally disconnected from the whole pursuit?


**Mausam:** I was not that affected by the other developments at the time, as, for me, my research areas were solely a function of what I wished to pursue further. I chose ML/AI because I thought that I would be happy doing work in this area. But, I can see that “what’s hot” can be a reason for a choosing a specific research area for many people. I personally believe that because PhD is a long hiatus, one should always choose a topic, which they are highly passionate about. 

In fact, I zeroed in on my research topic early in 2002, and all the hype around ML started around 2005. When I was introduced to AI, it was sort of like its pre-golden era. Self-driving cars hadn't crossed the Mojave desert, Watson hadn’t won jeopardy against humans, deep learning hadn't revolutionized machine learning. During that time, AI was not even that hot a topic, but my advisor was a core AI guy. And from his and my vantage point, ML is basically a part of AI. 

I would say that I was kinda lucky that suddenly ML/AI became huge and a lot of researchers and companies got interested in it. My personal belief is that we should work in the field that we are good at and enjoy doing. Every field has some top people who are making significant advances in the area. We should just try to excel in our chosen field and aim to become one of those top people.


<a name="research_areas"></a>


**ML-India:**
Can you talk a little about the research problems that you are working on?

<a name="research_crowdsourcing"></a>


**Mausam:** I like to work on real life problems and try to model them within an AI framework. For example, I am currently working on crowdsourcing, which has almost been like a parallel revolution. It is the modern version of outsourcing, except that you are not outsourcing your work to one company or a set of known people, instead, your tasks are divided into sub-tasks and are completed by people who are totally unknown to you. Once you put up a task, people from all over the world will pick it up, be it in India, Philippines or the United States. So the labor market is sort
of becoming global through crowdsourcing. 

ML comes into this picture because a crowdsourcing platform requires a lot of optimization to be successful. We must optimize its efficiency -- the tasks must be done in optimum time and cost, and even though there are a lot of quality differences within the crowd, we must ensure that the final answers are of high quality. This requires us to track the quality profiles of each individual worker automatically. We are also developing recommendation engines to find the best tasks for each worker, thereby making the system even more efficient.


This research problem is interdisciplinary and combines core ideas from different subfields of artificial intelligence, such as decision-theoretic analysis, model-based planning and execution, machine learning and constraint optimization to solve the multitudes of technical problems that arise in this space. For example, we use machine learning to continually refine models of worker performance and task difficulty. Using these models and decision-theoretic optimization we aim to choose between alternative workflows, optimize parameters for a workflow and dynamically control and alter them. Our preliminary experiences suggest that these optimized workflows are 
very economical and yield a higher quality output than manually controlled workflows.


<a name="research_information_extraction"></a>

Another area of research I am involved with is information extraction (IE), where the machine reads natural language text and extracts the information expressed in it. There can be many downstream applications for this such as in question answering, automated summarization of news and even in automated essay assessments. We use a combination of ML and linguistics to do IE at large scales. 

Our model, Open IE, overcomes the well-known knowledge-acquisition bottleneck by automatically extracting not just the arguments but also the relation between them from large text corpora in a domain-independent manner. I am currently working on improving the quality of Open IE extractors by pushing their precision and recall. We are currently extending it to process noun phrases and numeric extractions better. A recent paper on this work [Numerical Relation Extraction with Minimal Supervision.](http://homes.cs.washington.edu/~mausam/papers/aaai16a.pdf){:target="_blank"} Our
most recent Open IE extractor is publically [available](https://github.com/knowitall/openie){:target="_blank"} on GitHub. 

<a href="#">[Top]</a>


ML-India: That’s really cool. I think it connects with some of the work which Partha is working on. [We’d recently interviewed him](http://ml-india.org/ml-india-interview-partha-pratim-talukdar/){:target="_blank"}.

Mausam: Yes, we are motivated by similar dreams of making machines read large texts and gather valuable world knowledge. 

<a name="research_education"></a>


Recently, I have also begun working in the field of education. The idea is to understand each student in a fine grained fashion because as the education industry is evolving, you see more and more of e-platforms and online courses like Khan Academy, Coursera etc. gaining prominence and students spending a lot of time there. As students interact with these platforms a lot of valuable data gets generated, which can allow us a peek into their learning habits, knowledge holes, and commitment levels. In a classroom, one teacher deals with 50 students and finds it really hard to keep track of what is going on with each student. If the system can enable this for us, it can be huge for countries like India where the quality of education is not consistent, especially in tier 2 and 3 cities. Digital platforms could also suggest the most optimum study plan personalized to each individual student. This topic is sort of an early exploration for me, and I have to see where I can take it to.



**ML-India:**
This is very interesting. We were talking to Dr. Richard Baraniuk who is working in the same domain. They have built a system of their own where they are trying to figure out student engagement and hidden concepts inside a set of questions which can help in making the content generation and maintenance an easier task.


**Mausam:** There are a lot of people who are working in this domain. Many people have found that student engagement is a fairly hard problem. They have experienced that students do come for one or two lectures but dropout in between. It's really hard to keep them engaged. 


**ML-India:** Which are the research groups in India interested in these problems?


**Mausam:** In crowdsourcing, [Dr.Y.Narhari](http://lcm.csa.iisc.ernet.in/hari/){:target="_blank"} is working on it from game theory standpoint. I am not aware of any
other group. In information extraction, [Dr. Sunita](https://www.cse.iitb.ac.in/~sunita/){:target="_blank"}, [Dr. Ganesh](https://www.cse.iitb.ac.in/~ganesh/){:target="_blank"} and [Dr. Soumen](https://www.cse.iitb.ac.in/~soumen/){:target="_blank"} are also trying to work on similar questions. But their work is more from the databases angle where they are trying to learn information from tables and web. They have done some work in text as well, infact we have a paper coming up in AAAI this year where I have collaborated with Dr. Sunita and Dr. Ganesh. As I mentioned before, Dr. Partha is also working in this area.


<a name="about_research_ML_India"></a>

**ML-India:**
Given you have the advantage of seeing research in both IIT-D and UWash, what
are your thoughts on the ecosystem here?


**Mausam:** I often think about this and I've realized that IIT-D is a very nice system by
and large. There is a lot of freedom given to the faculty members here. One advantage in
IITs is that significant funding is being provided by the government, whereas in the US each faculty member has to work hard to fund their projects. The advisor’s salary and the students’ salaries have to be taken out from the funding. This hassle sometimes dries out some research agendas, which are not of current commercial interest. This model is also helpful since the researchers are forced to be always on the top of their game. On the other hand, the Indian system helps us pursue our research agendas without worrying about funding. Additionally, it is really great that many students are paid by corporates like Microsoft, Google, TCS, IBM etc. through fellowships. 


People often lament about the quality of graduate students in India. But, I have always maintained that the best of students won't stay here if the best of faculty is not available here. We can’t put the cart before the horse. A lot of good work can happen in an area if there is a critical mass of serious researchers in that field. We have started such an attempt at IIT-D, where we established the data analytics and intelligence research group [DAIR]((http://www.cse.iitd.ac.in/dair){:target="_blank"}. It comprises four faculty members having complementary skill sets who are going after various technically challenging problems. 

One strength of University of Washington was continual exposure -- 
there used to be a lot of talks, about 3-4 interesting research talks in a week. A lot
of knowledge is exchanged during these talks and you get to know about different
 research projects from all across the globe, and that makes it easier for you to retain the ideas useful for your own research. This aspect lags in the Indian system. We are doing our bit by inviting people to our weekly [DAIR seminar series](http://www.cse.iitd.ac.in/dair/index.php/events){:target="_blank"} and also inviting people from outside IIT-D to attend them.


There is also some bureaucracy one has to wade through to get things done here. The situation is improving, but things are not as hassle free as in the systems outside. 

I am told that there used to be a time about 20 years ago when in the whole department one person used to get funded for attending a conference in the whole year. Thankfully, things have improved drastically. One thing where the institution can help us further is by making travel to high-quality international conferences completely hassle free, since such travel is not a luxury but a necessity. Attending conferences gets you to be up to date with the things going on in the world. My advisor once sent me to a conference just to understand what the hot topics were
in our field of research in spite of us not having submitted any paper to that conference. I hope that someday I can have the same luxury for my early career PhD students here.

<a href="#">[Top]</a>



**ML-India:** Any specific activities in ML in India that has caught your attention?


**Mausam:** Yes. Xerox research recently held a winter school in machine learning and I was there to give a talk. It was a very well organized school; the best of the researchers were there and I was so impressed that it made me want to enroll in it as a student! Similar schools
in machine learning keep on happening. Last year TCS had also organized one called TCS-Tactics. NMI had organized one which was about [reinforcement learning and optimization algorithms](http://math.iisc.ernet.in/~nmi/MLDM.php){:target="_blank"}. 

A recent initiative which I am quite happy about involves opening of advanced graduate
level courses to students from across universities. [Prof. M. Balakrishnan](http://www.cse.iitd.ernet.in/~mbala/){:target="_blank"}
is working on a system where PhD students from other IITs could enroll in our graduate courses and attend them online. The larger idea is for universities not be limited by the faculty they
have in advanced topics. 

The government of India is also taking up some exciting work in ML and Data Analytics. I was involved in a project where we had to evaluate the next generation infrastructure for the income tax department. I was quite amazed at the depth of their vision and passion to build a huge-scale integrated knowledge repository with advanced risk assessment capabilities. Multiple such efforts are taking place.


**ML-India:**
Are you optimistic about the quality of the students here?


**Mausam:** I think that the quality of students keeps on getting better; students now are much better than what they were 10 years ago. I am lucky to have excellent students who are publishing at the best of conferences. But we are nowhere near the best PhD students that I've seen in UWash. The undergrads here could do great work comparable to best places in US, but I don't
think that system is ready to attract them to continue their graduate-level work here.
It takes time; I’m optimistic of getting there.

**ML-India:** It was great chatting with you, Mausam.Thank you for your time and words. All the very best to you from ML-India!


