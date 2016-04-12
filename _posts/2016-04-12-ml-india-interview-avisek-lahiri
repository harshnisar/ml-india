---
layout: post
title: "ML-India interview series - Mr. Avisek Lahiri, doctoral student, Indian Institute of Technology-Kharagpur (IIT-KGP)"
excerpt: "We interviewed Mr. Avisek Lahiri, who is a doctoral student at IIT Kharagpur. He joined IIT Kharagpur in 2013 as a master's student in computer vision lab, where he worked on reducing video related errors in video conferences.
After having worked in the field of [computer vision](https://en.wikipedia.org/wiki/Computer_vision){:target="_blank"}, machine learning caught his attention and he joined the same department as a PhD student. He is a recipient of many awards and accolades like the Google India PhD Fellowship, Viterbi India internship, ACM India sponsorship and a research fellowship from ISRO, among others. "
tags: [india, machine learning, data science, interview, avisek lahiri, IIT-KGP]
comments: true

tags_relevant: [interview]
---

<img src="https://sites.google.com/site/aviseklahiri/_/rsrc/1428328988283/home/photo.jpg" align='left' style="margin-right:4px;width:30%">

[Mr. Avisek](https://sites.google.com/site/aviseklahiri/home){:target="_blank"} is a doctoral student at IIT Kharagpur. He joined IIT Kharagpur in 2013 as a master's student in computer vision lab, where he worked on reducing video related errors in video conferences.
After having worked in the field of [computer vision](https://en.wikipedia.org/wiki/Computer_vision){:target="_blank"}, machine learning caught his attention and he joined the same department as a PhD student. He is a recipient of many awards and accolades like the Google India PhD Fellowship, Viterbi India internship, ACM India sponsorship and a research fellowship from ISRO, among others.
<br>
<br>
<br>
Avisek's current work is based on ‘[multiview assisted adaptive boosting algorithms](https://books.google.co.in/books?id=ffdICAAAQBAJ&pg=PA128&lpg=PA128&dq=multiview+assisted+adaptive+boosting+algorithms&source=bl&ots=H3vL6KcPWV&sig=B1FmCHR9ufcr_Cu6gVw_krThDZM&hl=en&sa=X&redir_esc=y#v=onepage&q=multiview%20assisted%20adaptive%20boosting%20algorithms&f=false){:target="_blank"}’ for computer vision. We interviewed Avisek to pick his brain on his work at IIT Kharagpur. 

**ML-India** - Thanks for taking out the time for this discussion. We would like to start off by understanding your journey into research. What motivated you to join IIT Kgp and pursue research?

**Avisek** - My bachelor's degree was just like that of any typical student in India. I focused on academics and did well there but was not able to get a break in research. However, there were many concepts that captured my imagination as an undergraduate, which I wanted to explore in greater depth. So, I decided to pursue higher studies. With that aim in mind, I joined IIT Kgp as a master’s student and started working on a project to reduce transmission errors in videos (using geophones sequence). The right balance of curriculum and lab work at IIT Kgp provided me a great opportunity to bootstrap my career in research. Later, I did an internship at the [computer vision lab at the University of Southern California](http://iris.usc.edu/usc-computer-vision.html){:target="_blank"}, where I explored the field and observed different interesting areas of research in it. During this period, machine learning caught my fascination and I started working in computer vision and decided to continue my journey as a PhD student here.

**ML-India**: What motivated you to leave your earlier research on video transmission and move completely to machine learning?

**Avisek**: During my masters, while I was working on the video transmission project, my professor, Dr. Prabir Kumar Biswas, and I wanted to explore if we could use computer vision techniques to reduce errors in transmitting videos. So, I started reading papers on computer vision and was impressed by the practicality and usefulness of this field. I came across machine learning and started studying it in more detail. I found courses on machine learning to be really useful in getting started. The programming assignments helped me realize the practicality and usefulness of the theory. I think that was the turning point and I discussed with my professor about changing my project from video transmission to something that aligned to my interest in machine learning and computer vision. Hence, I started working on the image caption project and later continued working on the same project for my PhD.

<a href="#">[Top]</a>

**ML-India**: Great, can you please elaborate a bit about your present research project? 

**Avisek**: In simple words, the problem that we are trying to solve is - Given an image, what is it all about? Examples include an image of a playground, or an image illustrating a classroom, etc. Humans can summarize a complex image in simple words without much thought but this is a hard problem for a machine.

This problem is not new and has been an active area of interest to computer vision community since its inception years. However, the techniques used earlier were not fruitful in solving this problem with the required accuracy. Earlier research had focused on low level features like intensity change or the gradient of colors in an image. They used techniques such as graph theory, which saturated and was not able to provide non-incremental benefits. However, research in deep learning has sparked a new interest in this topic and people are coming up with interesting and innovative ideas to solve this problem.

Our brains don't scan an image multiple times looking for each and every detail in deciding what the image is all about. Instead, we simply look for distinguishable features (objects/scenes) in the image and push away unnecessary details. Using these distinguishable features, our brain takes a call. For instance, if we see a playground and a bat, it’s enough to say that the image is about cricket. Our brains don’t need to focus on the shape and size of the playground. This is the idea we are trying to encode algorithmically. We want to train machines to figure out what salient features are important. Machine learning is used to extract actual contextual information and push away the unimportant details in the image. For instance, in an image describing a barber’s shop, if an algorithm can figure out that there are some pairs of scissors lying around, half of the job is already done.

The next job is to measure the accuracy of the technique. The standard and most reliable way of measuring performance of captions is to ask human experts to subjectively label the usefulness of each description, given an image. The automatically generated descriptions can then be rated on quality based on these human ratings using automated correlation metrics such as the [BLEU score](https://en.wikipedia.org/wiki/BLEU){:target="_blank"}.

Regarding the state of the art, a recently published [JMLR](http://jmlr.org/){:target="_blank"}  paper ‘[Show, Attend and Tell](http://jmlr.org/proceedings/papers/v37/xuc15.pdf){:target="_blank"}’ proposed an approach of using used RNNs to outperform previous algorithms on two popular datasets.

<a href="#">[Top]</a>

**ML-India**: This is a very interesting problem but how do you get your data annotated? This is a problem in supervised machine learning, meaning it depends on a lot of labeled information?

**Avisek**: Well, this is a major challenge we face. One can start with standard, good quality and freely available datasets like [MSCOCO](http://mscoco.org/){:target="_blank"} and train a deep learning network. But once you dive deep into this field, data becomes the main challenge.   

Success of the methods that we talked about depends a lot on richly annotated images, acquiring which is both time-consuming and expensive. There are some easy-to-go sources like[ ImageNets](https://en.wikipedia.org/wiki/ImageNets){:target="_blank"}, where you can find a lot of images weakly tied to a particular topic. However, you need really high quality data and most of the data available on ImageNets is noisy.

Solving the image captioning problem using low or limited data is the recent ‘hot cake’ in vision community. One direction where researchers have seen positive improvement is ‘visual recognition under weak supervision’. Some researchershave tried [weakly supervised domain generalization techniques](http://docplayer.net/14088459-Visual-recognition-by-learning-from-web-data-a-weakly-supervised-domain-generalization-approach.html){:target="_blank"} for visual recognition using loosely labeled images and videos found on web and have got good [results](https://pdfs.semanticscholar.org/09d0/448308061d322d05744c7680de247a6e6f0e.pdf){:target="_blank"}.

There are other ways of using previous knowledge or knowledge in other domains using learning techniques like ‘[transfer learning](ftp://ftp.cs.wisc.edu/machine-learning/shavlik-group/torrey.handbook09.pdf){:target="_blank"}’, ‘[multitask task learning](http://www.cs.cornell.edu/~caruana/mlj97.pdf){:target="_blank"}’ and ‘[semi supervised learning](http://www.morganclaypool.com/doi/abs/10.2200/S00196ED1V01Y200906AIM006){:target="_blank"}’. We are also exploring these fields and have seen some promising results.

**ML-India**:  What are some other problems being solved in your lab?

**Avisek**: Although all the projects in our lab are centered on computer vision, the scope of these projects is really diverse. One group of students is working on medical image analysis, which is different from  traditional computer vision in the sense that you work with images of CT-scans and X-rays. One particular application being worked on is cancer detection using mammogram images as an input. Another interesting project on which a bunch of students are working is studying the dynamics of bacteria. The project is interdisciplinary and requires working on nano-scale images using specialized equipment. Then, there are other projects related to pattern recognition in signal processing. One of the projects includes detecting the health of railway lines by analyzing the wave patterns generated in them.

<a href="#">[Top]</a>

**ML-India**:  What are your thoughts on the current ecosystem to study machine learning in India? Do you think a congenial environment exists between academia and industry to foster the growth of machine learning?

**Avisek**: In general, research in machine learning is getting really hot in India. I have seen a tremendous increase in the activities related to machine learning during my two-and-a-half years here at IIT Kgp. We have an increasing number of workshops, seminars and talks on topics ranging from data analytics to social network analysis. There is an equal participation from academia, and an industry of a number of innovative ML-based startups coming out of IITs is also on the rise. We have [Hyper Verge](http://hyperverge.co/){:target="_blank"}, a startup from IIT Madras, which works on deep learning on images and videos. [Skin Curate](http://www.skincurate.com/){:target="_blank"}, spawned from the electrical department of IIT Kgp is working on skin cancer research and is one of the first movers in this domain.  

One area, in my opinion, where we need improvement is foreign collaborations in research. I think if students get a chance to spend time in labs outside India, say a year at foreign universities or industries, they can really bring in new ideas and a culture of innovation. Currently one needs to get special permissions from professors and institutes, which becomes a hurdle. Instead, we should start programs that encourage such participation which can be really good for research in Indian universities.

**ML-India**: Which are the organizations that your lab actively collaborates with?

**Avisek**: - We collaborate with both government organizations and some big names in the industry. Many projects, including my video transmission project, are directly funded by government organizations like [DRDO](http://www.drdo.gov.in/){:target="_blank"} and [ISRO](http://www.isro.gov.in/){:target="_blank"}. Also we have some projects in which we collaborate with scientists in research labs of private companies such as Google and Intel.

**ML-India**: What do you spend time on, besides your research work?

**Avisek**: - Besides research, I work as a teaching assistant for an undergraduate Analog Electronics course. I get to interact with some motivated undergraduates in the lab and QA classes, as part of my TA duty, and I cherish this experience. You can actually learn a lot from them. We also take a couple of undergraduate interns, who are motivated for research, and a lot of times they bring good ideas. I also spend an hour at the gym every day – After all, health is wealth. 

<a href="#">[Top]</a>

**ML-India**: What are your future plans? Would you like to continue your work in academia or move to industry research?

**Avisek**: Right now, I will focus on writing a good thesis for my PhD and will try to join a good post-doc position later. With post doc positions available in industry labs nowadays, one can get a flavor of large scale applied research problems. Later on, after spending 5-10 years in the industry, I wish to return to academia and continue my independent research.

  
**ML-India**: Thank you for your time, Avisek. All the very best to you from ML-India!

<a href="#">[Top]</a>







