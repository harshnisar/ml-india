---
layout: post
title: "ML-India interview series - Dr. Mausam, Associate Professor, Indian Insititute of Technology-Delhi (IIT-D)"
excerpt: "Prof. Mausam is an associate professor the Dept. of Computer Science in IIT-Delhi and an affiliate faculty
at the University of Washington. He did his undergraduate from IIT-Delhi in
Computer Science and completed his PhD. in Stochastic Planning with Concurrent,
Durative Actions from the University of Washington. 
"
tags: [india, machine learning, data science, interview, mausam, IIT-D, indian institute of technology delhi]
comments: true
---

<img src="http://homes.cs.washington.edu/~mausam/mausam-head.jpg" align='left' style="margin-right:4px;">
Prof. Mausam is an associate professor the Dept. of Computer Science in IIT-Delhi and an affiliate faculty
at the University of Washington. He did his undergraduate from IIT-Delhi in
Computer Science and completed his PhD. in Stochastic Planning with Concurrent,
Durative Actions from the University of Washington. 

Mausam on ..
 - <a href="#research_areas">His research areas.</a>
 - <a href="#research_crowdsourcing">Research in Crowdsourcing</a>
 - <a href="#research_information_retrieval">Research in Information retrieval</a>
 - <a href="#research_education">Research in Education</a>
 - <a href="#about_research_ML_India">About the research in ML in India</a>


**ML-India:**
What is your undergraduate background and what initiated you in the field of
ML? 


**Mausam:** I did my undergraduate
studies in Computer Science from IIT-Delhi but I was not fascinated by ML at
that time. I had a course on AI but I had not taken it. During the first
quarter of my graduate studies I took a course on AI, but I didn't know what to
expect from it. As part of our coursework, teams had to create bots which would
compete with each other. Our bot faced a Chinese team in the finals and we won!
The Chinese team later found out that their code had a small bug and asked for
a rematch. We had a rematch and we won again! In hindsight, one thing that really
hooked me onto ML was its’ balance between theory and practice. The course was
also really interesting. During my undergraduate in IIT-D, I noticed that our
department had a really research agenda in theoretical computer science and
though I enjoyed it thoroughly, I was not quite satisfied pursuing research in
it. Likewise, systems and networks research also really fascinated me as it was
very principled and had visible applications in everyday life. I hence had
quite an open mind when it came to choosing a specialization and pleasantly
found out that ML was what impressed me the most. My advice to students is the
same - keep an open mind and explore as many concepts as possible during your
undergrad. It would help make an informed choice in grad school.


**ML-India:**
You did your PhD during 2001-2007, which was the golden era for all sorts of
ML/AI technologies. So, was that also a compelling reason to get into ML or was
your motivation totally disconnected from the whole pursuit?


**Mausam:** In my personal life, I
was not affected by it as for me my research areas have been a function of what
I wish to pursue further, but I can see that it can be affect the research area
of many people. PhD is a long hiatus and one should always choose a topic in
which he/she is largely interested in. I had started doing my PhD from Jan,
2002 and all the hype around it has started to begun in 2005. I had chosen ML
as my research area only because I thought that I would be happy doing work in
this area. When I was introduced to AI, during 2002, it was sort of pre-golden
era for AI. Self-driving car hadn't happened, deep learning hadn't happened.
During that time, AI was not even a hot topic but my advisor was a core AI guy
and he told me to work in the field of AI and ML is basically a part of AI. I
would say that I was lucky that suddenly it became huge and a lot of companies
and people have started working around it. I personally feel that one should
work in the field that you are good at and enjoy doing it. Every field requires
some top people, so just try to excel in the particular field that you are
interested in.


<a name="research_areas"></a>


**ML-India:**
Can you talk a little about the research problems that you are working on?

<a name="research_crowdsourcing"></a>


**Mausam:** As I have mentioned
earlier, I like to work on real life problems and try to model them in the AI
framework. For example, I am currently working on crowdsourcing which is almost
like a parallel revolution that has happened. It is modern kind of outsourcing,
just that you are not outsourcing your work to one company or a set of known people.
Your tasks are divided into sub-tasks and are completed by people who are
totally unknown to you. Once you put up a task people from all over the world
will pick it up, be it India, Philippines or China. So the labor market is sort
of becoming a global phenomena. ML can come into the picture as there is a lot
of optimization which is required in crowdsourcing. The whole system needs a
lot of optimization in terms of the efficiency. The tasks which are to be done
in optimum time and though there are a lot of differences amongst the crowd,
how can we ensure that the answers are of the same good quality and can be
achieved with low cost. There are tasks where you need to track the workers as
well and what tasks have they picked up so that they are recommended with such
tasks to make the whole system more efficient.


This research problem is interdisciplinary and
combines core ideas from different subfields of artificial intelligence, such
as decision-theoretic analysis, model-based planning and execution, machine
learning and constraint optimization to solve the multitude of sub-problems
that arise in the design. We want to use machine learning to continually refine
models of worker performance and task difficulty. Using these models and
decision-theoretic optimization we aim to help choose between alternative
workflows, optimize parameters for a workflow and dynamically control and alter
them. Our preliminary experience suggests that these optimized workflows are
more economical and yield higher quality output.


<a name="research_information_retrieval"></a>

The other area is information extraction, where
the system should read the text and try to extract the meaning of the sentence.
There can be many applications where you want to understand the meaning of
sentences such as in automated summarization of news and automated essay
assessments. We use ML and linguistic knowledge to do this. We hope to overcome the state of the art research in
knowledge-acquisition by automatically extracting information from
natural language text in a domain-independent manner. We work on improving the
quality of Open IE extractors by pushing their precision and recall. Our
most recent Open IE extractor is publically [available](https://github.com/knowitall/openie) on GitHub. We are currently extending it to process noun phrases
and numeric extractions better. A recent paper on this work [Numerical Relation
Extraction with Minimal Supervision.](http://homes.cs.washington.edu/~mausam/papers/aaai16a.pdf)

<a href="#">[Top]</a>


ML-India: That’s really cool. I think it connects with some
of the work which Partha is working on. [We’d recently
interviewed him](file:///D:/ML%20-%20India/transcripts/ml-india.org/ml-india-interview-partha-pratim-talukdar/).

Mausam: Yes, we have collaborated on some of
this work. 

<a name="research_education"></a>


Recently, I have begun working in the field of
education. The idea is to understand each student in a fine grained fashion
because as the education industry is evolving, you see more and more of
e-platforms and online courses like Khan Academy, Coursera etc. gaining
prominence and students spending a lot of time on. Students can be understood
in a more fine grained fashion because the students interact a lot on these
platforms. In a classroom, one teacher deals with 50 students and is really
hard to keep track of what is going on with each student. If the system can
enable this for us, it can be huge for places like India where the quality of
education is not very good. Digital platforms like these can help us keep track
of each student and her progress and can suggest the most optimum study plan.
This topic is sort of an early exploration for us and we have to see where we
can take it to.


**ML-India:**
This is very interesting. We were talking to Dr. Richard Baraniuk who is
working in the same domain. They have built a system of their own where they
are trying to figure out student engagement and hidden concepts inside a set of
questions which can help in making the content generation and maintenance an
easier task.


**Mausam:** Sure, there are a lot
of people who are working in this domain. Many people have started working on
it and have found that student engagement is a fairly hard problem. They have
experienced that students do come for one or two lectures but dropout in
between. It's really hard to keep them engaged. 


**ML-India:** Which
are the research groups in India interested in these problems?


**Mausam:** In crowdsourcing, Dr.
Y.Narhari is working on it from game theory standpoint. I am not aware of any
other group. In information retrieval, Dr. Sunita, Dr. Ganesh and Dr. Soumen
LINKS are also trying to figure out similar questions. But their work is more from
the databases angle where they are trying to learn information from tables and
web. They have done some work in text as well, infact we have a paper coming up
in AAAI this year where we have collaborated with Dr. Sunita. As I mentioned
before, Dr. Partha is also working in this area.


<a name="about_research_ML_India"></a>

**ML-India:**
Given you have the advantage of seeing research in both IIT-D and UWash, what
are your thoughts on the ecosystem here?


**Mausam: **I
often think about this and I've realized that IIT-D is a very nice system by
and large. There is lot of freedom given to the advisor here. One advantage in
IITs is that the funding is being provided by the government whereas in the US
each faculty member has to work for funding their projects. The advisor’s
salary and the students’ salaries have to be taken out from the funding. This
hassle sometimes dries out some research agendas which are not of any
commercial interest. This is also helpful in a way that the researchers are
always on the top of their game. The Indian system helps us pursue such
research agendas with their means of funding. Additionally, it is really great
that many students are paid by the institute and other corporates like
Microsoft, Google, TCS, IBM etc. through fellowships. 


I have always maintained that the best of
students won't stay here if the best of faculty is not available here. There
are a lot of things that keep happening in an area if there is a critical mass
of good people that are interested in the idea. We have started such an attempt
in IIT-D, where we established the data analytics and research group (DAIR). It
is advised by four faculty members having complementary skill sets and are
going after some really rich and hard problems. One good thing in Seattle was
there used to be a lot of talks, about 3-4 interesting talks in a week. A lot
of knowledge is exchanged during the talks and you get to know about different
interesting work going on and you can grab on to some knowledge which seems
interesting enough. This aspect lags in the Indian system. We are doing our bit
by inviting people for seminars and also ensuring people from outside IIT-D get
to attend them.


There is also a fair amount of bureaucracy one
has to wade through to get things done here. The situation is improving, but
things are not as hassle free as in the systems outside. There used to be a
time when in the whole department one person used to be funded for attending a
conference. Thankfully, things have improved substantially. One thing where the
institution can help is by making travel to international conferences
completely hassle free, since such travel is not a luxury but is a necessity. Attending
conferences gets you to be up to date with the goings on in the world. My
advisor once sent me to a conference just to understand what the hot topics were
in our field of research in spite of us not having submitted any paper in that
conference.

<a href="#">[Top]</a>


**ML-India:** Any
specific activities in ML in India that has caught your attention?


**Mausam:** Yes. Xerox research
recently held a winter school in machine learning and I was there for a talk. It
was a very well organized school; the best of the researchers were there and I
was so impressed that it made me want to enroll in it as a student! Similar schools
in machine learning keep on happening. Last year TCS had also organized one called TCS-Tactics. [NMI had organized one which was
around reinforcement learning and optimization algorithms](http://math.iisc.ernet.in/~nmi/MLDM.php). A recent
initiative which I am quite happy about involves opening of advanced graduate
level courses to students from across universities. [Prof. M. Balakrishnan](http://www.cse.iitd.ernet.in/~mbala/) [LINK}
started a course where students from other IITs could enroll and attend it
online. The larger idea is for universities not be limited by the faculty they
have in core, advanced topics. The government of India is also taking up some
interesting work in ML. I was involved in a project where we had to evaluate
the next generation infrastructure for the income tax department. Multiple such
efforts are taking place.


**ML-India:**
Are you optimistic about the quality of the students here?


**Mausam:** I think that the quality
of students keeps on getting better; students now are better than what they
were 10 years ago. I have some students who are really good in terms of the
work they are doing; they are publishing their work in the best conferences.
But we are nowhere near the best PhD students that I've seen in UWash. The
undergrads here are doing very good work which is comparable to US, but I don't
think that system is there yet to attract them to continue graduate-level work.
It takes time; I’m optimistic of getting there.

**ML-India: **It was great chatting with you, Mausam.Thank you for your time and words. All the very
best to you from ML-India!
