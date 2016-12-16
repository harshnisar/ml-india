---
layout: post
title: "ML-India interview series - Dr. Nitin Gupta, Assistant Professor, IIT Kanpur"

excerpt: "Nitin is an assistant professor at IIT Kanpur. He graduated from IIT Kanpur in 2004 with a B.Tech. in computer science and an interest in biology. He then joined the Ph.D program in bioinformatics and systems biology at the University of California, San Diego (UCSD). After completing his PhD in 2009, he spent a few months in a cognitive neuroscience lab at UCSD, and then moved to the National Institutes of Health as a post-doc to learn electrophysiology. He specializes in systems neuroscience, olfaction, computational biology. His research interest lies in understanding the fundamental mechanisms used by neural circuits for processing information.
"
tags: [india, machine learning, data science, interview, priya, IIIT-H, International Institute of Information Technology Hyderabad]
comments: true

tags_relevant: [interview]
---


<img src="/images/008067e.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> <br> [Nitin](http://iitk.ac.in/new/nitin-gupta){:target="_blank"} is an assistant professor at IIT Kanpur. He graduated from IIT Kanpur in 2004 with a B.Tech. in computer science and an interest in biology. He then joined the Ph.D program in bioinformatics and systems biology at the University of California, San Diego (UCSD). After completing his PhD in 2009, he spent a few months in a cognitive neuroscience lab at UCSD, and then moved to the National Institutes of Health as a post-doc to learn electrophysiology. He specializes in systems neuroscience, olfaction, computational biology. His research interest lies in understanding the fundamental mechanisms used by neural circuits for processing information.



<br>
Nitin on..

- <a href="#key"> Key learnings at IIIT-H </a>
- <a href="#proj"> Her PhD project </a>
- <a href="#state"> Current state of ML space in India  </a>

<br>

**ML India:** How did you
get into the field of neuroscience?

**Nitin:** I had always
been interested in the philosophical aspects of how we think and how we are
able to remember things. Initially, it was just a curiosity. But while I was
pursuing my B.Tech in computer science, I got exposed to biology through some
coursework and projects. I enjoyed these and also started reading about the [Human
Genome project](https://en.wikipedia.org/wiki/Human_Genome_Project){:target="_blank"}. I wanted to learn more, so I opted for graduate studies in [Bioinformatics](https://en.wikipedia.org/wiki/Bioinformatics){:target="_blank"}[- a subject which is deeply connected to computer science](https://en.wikipedia.org/wiki/Bioinformatics){:target="_blank"}. During this period, I continued
exploring topics in [neuroscience](https://en.wikipedia.org/wiki/Neuroscience) . After my Ph.D, I thought I might as
well switch fields since I was spending so much time on neuroscience. I got an
opportunity to do my post-doctoral studies in neuroscience and I took it. I’ve
been into this field ever since.

**ML India:** Could you let us
know of some of the fundamental problems in neuroscience that are being solved
today?

**Nitin:** Over the
years, neuroscience has become a vast field and people are working at many
levels to understand the brain. One could categorize the studies into three
levels. One is at the ‘molecular/cellular’ level. People conducting studies at
this level are trying to understand the composition of our nervous system and
answer questions like “What are neurons made of?” and “What are the individual chemical
molecules present in neurons that determine how they function?”. Another is at
the ‘circuits and systems’ level, where people are trying to understand the
circuits connecting neurons.<img src="https://www.ucsfhealth.org/images/brain_image.png" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:45%"> Consider the functioning of the visual system when
someone sees an object - light travels to the retina, from which the
information then goes through a bunch of nerves to the primary visual cortex
V1. It then moves to V2, V3 and so on. People have been interested in
understanding this underlying complex structure and how information is
communicated in such systems. The third level is ‘cognitive neuroscience’ where
people are trying to broadly model the functioning of higher level activities
like decision making and thinking. Researchers are investigating if there exists
a correlation between specific functions of the brain’s parts and the behavior
displayed.

This subject can also
be categorized as _fundamental_ and _applied_. Researching chemicals
that trigger certain responses in the brain, or chemicals that can be used to
manipulate the brain’s activity to relieve someone from a disorder, is an
example of applied neuroscience. However, most of the research that is
happening is in the fundamental domain.

**ML India:** Have we had any
major breakthroughs in the last 20-30 years?

**Nitin:** In terms of
basic understanding, yes, we’ve gotten many new insights. The biggest
breakthrough came around 50 years ago which gave a clearer understanding of the
activity of neurons. [Hodgkin
and Huxley](https://en.wikipedia.org/wiki/Hodgkin%E2%80%93Huxley_model){:target="_blank"}, who got the Nobel prize for this work, answered how information is <figure> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Hodgkin-Huxley.svg/350px-Hodgkin-Huxley.svg.png" caption="" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"><figcaption>Fig:Hodgkin and Huxley Model</figcaption> </figure>
converted into electrical pulses and determined the equations of such a
transfer while considering the concentration of ions inside and outside the
neuron. The visual system was the first to be studied in detail. [Hubel and
Weisel](http://knowingneurons.com/2014/10/29/hubel-and-wiesel-the-neural-basis-of-visual-perception/){:target="_blank"}, again Nobel
laureates, analyzed how the visual cells perceived an image, not as a whole,
but as a set or combination of dots and lines. In recent years, a lot of work
has been done using [FMRI](https://en.wikipedia.org/wiki/Functional_magnetic_resonance_imaging){:target="_blank"}. Over the past 20 years or so, people
have identified broader areas in the brain that are responsible for different
activities. Another area of work has been in identifying the connections
between different neurons in the brain, and how those connections exist. There
are millions of neurons in an animal’s brain, and billions in a human one. A
lot of work towards building the experimental tools to study them is being
done. And this has been a major challenge for neuroscientists. Our ability to
detect neuron activity and analyze its existence using non-invasive methods has
improved vastly but is still very limited. One of the more recent developments
has been in [optical recording](https://en.wikipedia.org/wiki/Optical_recording){:target="_blank"} and [optogenetics](https://en.wikipedia.org/wiki/Optogenetics){:target="_blank"}. Traditionally, people use electrodes,
metal wires or glass capillaries with some electrolyte to read neuron activity,
but this is invasive in nature and can only read a small number of neurons.
More recently, scientists have started using optical imaging, where a chemical
is put into the brain which changes its fluorescence whenever an activity takes
place in that region. One can then use just a microscope to image the activity
of a large number of neurons. Academics have also developed proteins that can change
the activity of specific neurons by illuminating them.

**ML India:** In this canvas,
how would you place your work?

**Nitin:** I’m currently
working on the ‘molecular’ and ‘systems’ levels. The majority of work in [my lab](https://sites.google.com/site/labofneuralsystems/){:target="_blank"} is being done on olfactory systems.
That can be described as work done in systems neuroscience. We’re trying to
analyze how different smells are processed in the brain. We are using insects
as our model systems because they are easy to experiment on, they have a very
well developed sense of smell and their olfactory systems are similar in
organization to that in humans. Specifically, I’m trying to understand how
certain smells become attractive or repulsive to mosquitoes. It has been
observed that mosquitoes use our body’s smell as one of the cues for finding
us. In addition to sensing heat levels and using their visual features, smell
plays an important role. Different smells of people can determine whether
mosquitoes will bite them. Our work might help in producing more effective
repellents which are less harmful to humans.

**ML India:** How does your
training in computer science come into the picture?

**Nitin:** There are many
ways in which computer science is useful. One area is the analysis of
experiments. Experimental tools generate a lot of data and one needs the
knowledge of data analysis techniques to make sense of it. For instance,
neuroscience routinely involves electrical recording, which generates data for
neurons over a period of time. Techniques like feature detection, noise removal
from the data, deconvolution, prediction using machine learning, unsupervised
clustering, visualization and other handy tools from computer science and electrical
engineering immediately follow. For instance, while recording electrical
activity in neurons, we can sometimes put the electrode outside the neuron to
pick up activity from other neighboring neurons as well. Within a single trace,
we obtain a mixed activity of neurons. Analyzing such traces would typically
involve the usage of some of the techniques mentioned above.

The other area is
modeling or simulations of neuro-systems. Based on the knowledge that we have
about how neurons function, we can make a computer representation of a neural
circuit. Each neuron can be represented by a node whose voltage can be governed
by a certain set of differential equations. The neurons are connected based on
the considered configuration and we can then provide it input and observe the
overall activity of the network to look for any patterns that may be occurring.
This kind of modeling predicts the behavior of such specific networks.

**ML India:** What are some of
the other projects going on in your lab?

**Nitin:** We recently started
working in the applied cognitive area. In this work, we are not doing
fundamental discoveries but are using what is known to alleviate a disease. For
instance, people who have depression use medication for relief, and some people
use psychotherapy. Although therapy has no side effects, there is a lot of
stigma around it which makes people reluctant to go to a therapist. As a
result, researchers have tried to develop a computer-based method for
delivering therapy to patients. This would reduce the problems of inaccessibility
of a therapist while overcoming the stigma. We are working on such systems with
some renowned therapists so that the therapy can be delivered efficiently. This
will involve some traditional content of therapy for the patients along with some
interactive features to make it more personalized. This will eventually also
involve machine learning to match and personalize interventions with the
patients’ personalities. Once developed, this software will be made available
on our website- [treadwill.org](https://www.treadwill.org/){:target="_blank"}.

**ML India:** It seems from
this conversation that experimental analysis trumps theoretical studies in
neuroscience. Which is unlike the case in, say, computer science.

**Nitin:** Yes, that is <img src="https://s30.postimg.org/hd4hpqhdd/quote.jpg" caption="" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%">
accurate. Neuroscience is at a stage where we are still severely limited by
experimental data. I think that our understanding of different parameters of
neurons and of different types of neurons is very limited. We have a long way
to go before we have sufficient data on various parts of the brain.

 
**ML India:** You talked about
the human genome project. Any other grand initiatives which are happening in
the field of neuroscience?

**Nitin:** There are a
few big initiatives happening. One is called the [BRAIN
initiative](https://www.whitehouse.gov/share/brain-initiative){:target="_blank"} by the US government which is trying to accelerate brain research
through innovative neurotechnology. The idea, again, is to focus on developing
new techniques using recent tools of nanotechnology and in developing optical
techniques to record and manipulate the activity of the neuron. Another is a
Europe-wide project called the [Human Brain Project](https://www.humanbrainproject.eu/){:target="_blank"}. It is partly dedicated to developing<img src="https://pbs.twimg.com/profile_images/660035391442042880/v7RkSosC.png" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:20%">
new technologies and is partly into developing computer models to incorporate
all the experimental data that exists currently. There is a group at [Janelia
research farms](http://www.hhmi.org/programs/biomedical-research/janelia-research-campus){:target="_blank"}, which is a campus of the Howard Hughes Medical Institute, that has set
up an institute to focus primarily on neuroscience. They are using the [_Drosophila
(_a small fly_) _](https://en.wikipedia.org/wiki/Drosophila){:target="_blank"} model system to map most of the neurons in the brain.
They are using genetic tools to examine neurons’ structure and activities and
their role in determining various behaviors in animals. I think this will
become very powerful in the coming years.

**ML India:** Your thoughts on
the current state of the art being pursued in India? Are there any fundamental
problems being chased down and hunted by the groups in India?

**Nitin:** I think
neuroscience is a growing field. It is really small in India in comparison to
the traditional fields of biochemistry and biophysics. There are a few
academics doing very good work. For example, Prof. [Upinder Bhalla](https://www.ncbs.res.in/faculty/bhalla){:target="_blank"} at [NCBS](https://www.ncbs.res.in/){:target="_blank"} is working on memory. At my institute,
IIT Kanpur, there are two other people working in this field. [Dr. S Ganesh](http://www.iitk.ac.in/bsbe/s-ganesh){:target="_blank"} is working on the molecular and
cellular aspect of the [Lafora disease](https://en.wikipedia.org/wiki/Lafora_disease){:target="_blank"}, a form of epilepsy, and he is trying
to understand and identify the causal proteins. [Dr.
Jonaki Sen](http://www.iitk.ac.in/bsbe/jonaki-sen){:target="_blank"}, who is into developmental neuroscience, is studying how neurons
develop and form connections as an animal grows in age.

**ML India:** Where do you
think India can improve? Any low hanging initiatives that you think can we can
target to push the envelope in neuroscience?

**Nitin:** Since the
neuroscience community in India is very small currently and geographically
dispersed, it is certainly desirable to hold regular meetings and discussions
to come up with interesting new ideas. In terms of projects, I think science is
very global today, so I don’t think there are any low hanging initiatives
specifically for India. In applications, there are a few areas where adaptation
to the Indian context will be very useful. Our project to deliver computerized
behavioral therapy for depression is an example. Funding is not a problem in
India currently. One problem that I feel is the lack of high-quality students.
I have been fortunate to get really good students, but in general, the number
of applicants we get is small. Many good students take up industrial jobs or go
abroad. Also, my kind of work requires students who are comfortable with
engineering concepts as well as have an interest in biology, and it is not easy
to find such students.

**ML India:** What are the
future steps in your research?

**Nitin:** We’ll continue
working primarily in the areas of olfaction and mosquito behavior. We are
thinking of starting some work on genetic modifications of mosquitoes so that
we can use optical manipulation tools on them. In the cognitive domain, we may
expand to other disorders beyond depression and will try to make our tools
smarter.

**ML India:** What would you
recommend to a non-biologist aiming to enter this field and get a sense of it?

**Nitin:** There are
plenty of online courses available today for students who are interested in
neuroscience. One particular course that I liked is ‘[Fundamentals
of Neuroscience](https://www.edx.org/course/fundamentals-neuroscience-part-1-harvardx-mcb80-1x-0){:target="_blank"}’ taught by a professor at Harvard. Also, labs in India are open to
interested people with an engineering background who want to learn more about
this field and are willing to spend some time. Year-long projects at these labs
will very helpful to students who are looking to get a cross-disciplinary
experience.

**ML India:** Any closing
thoughts?

**Nitin:** Engineering
students and professionals who are interested in biological fields should not
hesitate in exploring this as a career option. People usually think that it
will be really difficult to succeed in this field since they haven’t studied
biology in high school and college, and that switching fields won’t be a wise
decision to take. I knew nothing about biology before I switched fields. I
learned everything on the fly, and speaking from personal experience, I think
that it’s easier to study biology after engineering than going the other way.
So people need not be afraid of entering this field. Also, it is a really good
time to be in neuroscience research. With some great research happening in this
field, students and researchers will learn a lot!

 
**ML India:** Thank you
for your time, Nitin. Best wishes from ML-India for your future work.

 
