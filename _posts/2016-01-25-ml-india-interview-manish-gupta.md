---
layout: post
title: "ML-India interview series - Dr. Manish Gupta, VP, Xerox Research Center India"
excerpt: "We interviewed today ​Dr. Manish Gupta. He is Vice President at Xerox Corporation and Director of Xerox Research Centre in India. Previously, Manish has served as Managing Director, Technology Division at Goldman Sachs India, and has held various leadership positions with IBM, including that of Director, IBM Research - India. Manish holds a Ph.D. in Computer Science from the University of Illinois at Urbana Champaign and is a distinguished IIT-Delhi alumnus.
"
tags: [india, machine learning, data science, interview, manish gupta]
comments: true
---

As part of the new year's initiatives on ML India, we promised you that we will be talking to leading researchers and academics in the field of machine learning to understand their work better. We start off this series by putting out the first interview we had! We have a couple of more very interesting interviews of academics from IIT-Delhi, IISc, IIT Kharagpur and more. Stay tuned!

<img src="http://www.xrci.xerox.com/sites/default/files/Manish_1.jpg" align='left' style="margin:2px;">
We interviewed today ​Dr. Manish Gupta. He is Vice President at Xerox Corporation and Director of Xerox Research Centre in India. Previously, Manish has served as Managing Director, Technology Division at Goldman Sachs India, and has held various leadership positions with IBM, including that of Director, IBM Research - India. Manish holds a Ph.D. in Computer Science from the University of Illinois at Urbana Champaign and is a distinguished IIT-Delhi alumnus.

Manish talks about four areas which Xerox is innovating in - Education, Healthcare, Transportation and the services vertical. He describes how challenges in each of these domains can be posed as hard computer science and specifically, machine learning problems in areas as diverse as vision, NLP and speech. He talks of how his group is pushing the boundaries by having their own modifications to deep neural networks.

Manish on:

 - <a href="#problem_tackled_at_XRCI">The flavor of problems being tackled at XRCI</a>
 - <a href="#healthcare_innovation_XRCI">Innovation in active healthcare</a>
 - <a href="#education_chat_bots_XRCI">Education and smart chat bots</a>
 - <a href="#startups_India">Startups space in India</a>
 - <a href="#outreach_program_XRCI">Outreach programs by XRCI</a>

**ML-India:** Hi Manish.
Thanks a lot for agreeing to talk to us on such a short notice. We understand
you must be having a busy schedule.

**Manish:** Oh, no worries. In
fact, Xerox is organizing a winter school for machine learning and today was
its first day. I may have to head back to it in sometime. Hope that’s fine.

**ML-India:** That’s great to
hear. We’ll be keen to know more about it and will chat about it in a while. Sure,
we’ll keep a tab on the time. We wanted to start off with understanding what
problems are of interest to Xerox research.

<a name="problem_tackled_at_XRCI"></a>

**Manish:** Sure. Today, a
vast section of our population is underserved in the most fundamental services like
health care, transportation and education. 
There is a room for improvement in the general area of personalization. A
case in point is education. We are beginning to see a shift from traditional
human intensive education systems to massive online courses where lectures
given by eminent professors are utilized at a massive scale. The aspect of
personalization is however still missing there. There’re no systems currently
which learn what content suits you best, what style and pace of lecture
delivery helps you learn best etc. There has to be a two way interaction
between the users and providers of technology driven services. The unique needs
and preferences of the end users need to be an inherent part of the technology.
This is the key focus area of Xerox Research Centre India.

Xerox Research
is fairly new – we set up shop in 2010 in India. We have a strong focus on
targeting the top tier conferences to showcase the quality of our work; some of
our recent work includes a paper at [ACM multimedia](https://en.wikipedia.org/wiki/ACM_Multimedia){:target="_blank"}, the top
conference for video (multimedia) where we addressed the problem of
automatically creating table of content for online lecture videos. We had two
papers in [Intelligent User Interface (IUI)](http://iui.acm.org/2016/){:target="_blank"},
one of the best conferences for showcasing working in human computer
interfaces; and a couple in [ICASSP](https://en.wikipedia.org/wiki/International_Conference_on_Acoustics,_Speech,_and_Signal_Processing){:target="_blank"} or [Interspeech](http://www.isca-speech.org/iscaweb/index.php/conferences){:target="_blank"},
the best conferences for [speech
processing related work](https://www.icsi.berkeley.edu/icsi/gazette/2012/09/speech){:target="_blank"}, where we published our work done in
education-related products. 

So to
specifically list out XRCI’s key areas of focus, they’d be -

 - Health care
 - Transportation 
 - Technologies for education
 - Services across different
industry verticals. Example of this is customer care contact centre.

I could probably
talk about each of them in some detail, which will help give your readers a
good grasp of the kind of specific problems we’re pursuing.

**ML-India:** Sounds good!

<a name="healthcare_innovation_XRCI"></a>

**Manish:** I’ll start with
healthcare.We are targeting two
goals there. First, personalization and second, making it proactive. Today’s
health care system is very reactive in nature. A multitier system exists today where
the ICU is the most expensive tier. The aim of our healthcare systems should be
to minimize the escalations into the ICU. There is a lot of activity these days
in healthcare analytics but we all have a long way to go. Technologies which
predict complications in ICUs, some of which even Xerox has built, do not work
very well because they are still based on a bunch of clinical rules formulated
by doctors. These are good preliminary interventions to have, but these systems
are wrought with false alarms. There is a need to apply modern techniques of
machine learning and data science to improve the accuracy of these systems. 

In this regard,
one of the areas we’ve worked on is in predicting which patients get admitted
to ICUs. The state of the art method of predicting this is based on a scoring
system called [Modified
Early Warning Scores (MEWS)](https://en.wikipedia.org/wiki/Early_warning_score){:target="_blank"}, which is based on the measurement of
temperature, blood pressure, heart beat and many such body vitals. The alert
generated by these methods are generally ignored by doctors and nurses given
the high false alarm rates the present systems have. Our team has worked on one
specific [complication
called the acute hypertension episode](https://en.wikipedia.org/wiki/Complications_of_hypertension){:target="_blank"}. Our recent results show we’ve
managed to do better than the best known results by a significant margin. Encouraged
by these results, our business groups have given us the challenge that of
having 99% specificity so that there are at least 3-4 true positives for every
false positive reported by the system. We’re pleased to say that we’re taking
this challenge head on and pushing the state of the art.

Another area
we’re tackling is in breast cancer screening. We are trying to resurrect an old
idea which the health community gave up on sometimes ago. Today, breast cancers
are screened for using mammography, which involves pumping X-rays into the
body. It’s a very painful procedure and additionally, it’s not effective at all
in younger woman. The medical community has known for a while that one can
detect a tumour using thermal cameras. When a malignant tumour grows fast, a distinct
thermal signature around that tumour can be captured through a thermal camera.
In the early 80s, there were too many false positives in analysing these
images. By applying modern machine learning and image processing techniques, we
have been able to dramatically decrease the false positives for this detection.
We are also working with a cancer hospital in Bangalore to collect more data
and run our algorithms for a larger datasets and a larger class of cancer
detection problems. This work has been submitted to a top-tier peer reviewed
conference.

**ML-India:** That’s great to
hear.

<a name="education_chat_bots_XRCI"></a>

**Manish:** In the education space, we have built just the product to provide
what I spoke of in the introduction. It’s called [TutorSpace](http://www.xrci.xerox.com/tutorSpace-at-scale-personalized-learning){:target="_blank"}
which is a comprehensive suite for a learner to learn rich and relevant content
from the web. It automatically stitches the most relevant content for you by
skimming through scores of lecture videos on the internet and also summarizes
the key concept and the equations/content that’s delivered. 

Customer care is
the third area where we are doing a lot of work on automation. This is the first
year where our group has two papers accepted at [AAAI](http://www.aaai.org/home.html){:target="_blank"}, one of which is our work in customer
care. We have a product in place currently where virtual agents, as against humans,
try to automatically answer customer queries. These agents could be designed to
answer queries over web chats or over phone calls. We started with the easier
problem of designing agents for web chats. Our team at XRCI has built a watchdog
which constantly monitors the interaction between the customers and these
virtual agents and identifies when a human representative ought to intervene
and take over the process. Such a system could also be applied to how one might
automatically analyze everyday web chats. In essence, what we have demonstrated
is that it is now possible to analyse these chats in real time, unlike the
current mechanism in which a post-hoc analysis of such logs take place. With
the successful demonstration over web chats, we are now moving towards replicating
similar systems for voice chats. Our speech research group at XRCI is coming up
with its own enhancements of how deep learning is applied to speech, surpassing
[Andrew Ng’s recently published
results](http://arxiv.org/pdf/1412.5567.pdf){:target="_blank"}. We will be submitting our work to some of the best conferences
in speech research, where we shall get a chance to compare our work with the state
of the art.

In
transportation, the focus is more on algorithms and optimization. We work on
solving integer linear programming problems, coming up with greedy algorithms to
get close to optimal solutions. All this is done in the backdrop of scheduling
and routing problems.

**ML India:** That’s great. So from what we’ve heard, is
it the business team pushing XRCI with challenging problems? How does it start?

**Manish:** It’s a
combination. We try to have a balanced portfolio. Roughly one third of our work
is exploratory in nature. For that one third unit you are not driven by a
business unit telling you what to do. That is more bottom up where our
researchers identify a relevant problem. They don’t need a close business case
but they at least need a hypothesis. Our work on education and breast cancer
screening are examples of exploratory research. In both these cases, we are
working with startups to commercialize our technology. The problem of
predicting complications in ICUs was given to us by a business group. Half of the
two third work being informed by our business groups is relatively short term
and other half is relatively medium term.

**ML India:** You mention working with lots of startups. What
is your take on startups innovating in the machine learning space?

<a name="startups_India"></a>

**Manish:** In our case
specifically, we try to connect with those startups which do not have much
depth in machine learning. They bring to the table agility, market access and products.
We combine it with our research depth to bring something unique and technically
sound into the market.

Having said
that, I think there’s a very positive vibe in the startup community regarding
machine learning. I think today’s entrepreneur realizes machine learning helps
in giving an edge and making services more competitive. I would say lot of the
current capability of many of these startups are still not great, but I am very
optimistic that it will get there. I would really think of your company as
again a shining example of guys who have been actually publishing papers at KDD
and the likes. In due course of time I would imagine that others would follow
suit.

**ML India:** What steps are Xerox taking? I see machine learning
school being one such initiative. Is there any other initiative that you are
trying to push forward so that you engage with the community at large?

<a name="outreach_program_XRCI"></a>

**Manish:** We are
organizing a [winter school
in machine learning](http://xrci.xerox.com/xerox-research-innovation-challenge){:target="_blank"} where we have ten teams spending a fully paid
two week internship at XRCI, where they will be working on problem of
complication prediction in ICUs. We also give out [faculty research grants](http://www.xrci.xerox.com/collaborative-programs){:target="_blank"}
which is a global process. Our lab is championing 5 faculty research grants of
which at least three are in machine learning. We are funding [Indrajeet Dhillon at UT Austin](https://www.cs.utexas.edu/~inderjit/){:target="_blank"},
[Jennifer at
MIT](http://www.xrcc.external.xerox.com/people/profiles/jennifer-belelie){:target="_blank"} and [Chiranjib
Bhattacharyya at IISc](http://drona.csa.iisc.ernet.in/~chiru/){:target="_blank"}. It’s a grant of thirty thousand USD per annum
for three years. What we are finding is that current state of art is not
anywhere close to being good enough for the practical problems that we are
dealing with and we’re collaborating with the best in the industry to push the
frontiers of both, theory and practice of machine learning. 

**ML-India:** Do you have any take on talent pool that India is
producing through university?

**Manish:** I am very optimistic. I was positively surprised by the kind of
response that we got for the research challenge. Two out of the top ten
entries were very neat peace of work which were totally new ideas on
how to solve that problem. We have a special program called [budding
scientist program](http://www.xrci.xerox.com/xerox-budding-scientists){:target="_blank"} where we give undergraduates a two year
appointment and very challenging problems to work on and then encourage them to
pursue a PhD after that. The rationale is that many of these undergraduates
have no idea what is out there in the industry and are easily attracted by high
paying corporates, many of which are not exciting technically. Such a program
helps retain those academically inclined within academia. One of the students we
recently offered already had one journal paper and submitting a paper at [NIPS](https://en.wikipedia.org/wiki/Conference_on_Neural_Information_Processing_Systems){:target="_blank"}.
He had applied deep neural networks to automatically differentiate between
Beethoven and Bach with over 95% accuracy. I find it very encouraging that you
have such amazing talent coming out of our schools.
