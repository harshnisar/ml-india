---
layout: post
title: "ML-India interview series - Dr. Preethi Jyothi, Assistant Professor, Indian Institute of Technology-Bombay (IIT-B), India"
excerpt: "Dr. Preethi Jyothi is an assistant professor at Indian Institute of Technology-Bombay (IIT-B), India. She completed her Ph.D. in speech recognition from the CSE department of Ohio State University, and did her B.Tech in computer science from NIT Calicut. She was a Beckman Postdoctoral Fellow at the University of Illinois at Urbana-Champaign. I obtained my Ph.D. from the CSE Department at The Ohio State University in 2013. Her research interests are broadly in the areas of automatic speech recognition and machine learning as applied to speech.
"
tags: [india, machine learning, data science, interview, mayank, IIIT-D, indraprashtha institute of information technology delhi]
comments: true

tags_relevant: [interview]
---


<img src="http://i66.tinypic.com/v83kut.png" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%">
[Dr. Preethi Jyothi](https://www.iiitd.edu.in/~mayank/){:target="_blank"} is an assistant professor at Indian Institute of Technology-Bombay (IIT-B), India. She completed her Ph.D. in speech recognition from the CSE department of Ohio State University, and did her B.Tech in computer science from NIT Calicut. She was a Beckman Postdoctoral Fellow at the University of Illinois at Urbana-Champaign. I obtained my Ph.D. from the CSE Department at The Ohio State University in 2013. Her research interests are broadly in the areas of automatic speech recognition and machine learning as applied to speech. 


Preethi on ..

 - <a href="#work_exp">Her problem statements during PhD</a>
 - <a href="#UIUC">Her work at UIUC</a>
 - <a href="#traits">Positives and challenges for ML enthusisasts</a>
 
 
<br><br>



**ML-India:** Could you brief us on your journey into research?

  

**Preethi:** My fascination with AI dates back to my undergraduate days. I did my B.Tech in Computer Science and Engineering from [NIT Calicut](http://www.nitc.ac.in/){:target="_blank"} in 2006. I was sure for a long time that I wanted to study further and pursue a Ph.D., possibly influenced by my parents both of whom have doctorates. Nevertheless, as I finished up at NIT Calicut, I went along with campus placements and joined [Oracle](https://www.oracle.com/){:target="_blank"} in Hyderabad as an Applications Engineer. After a few months in the job, I decided it was time to try and go back to school. <img src="http://i66.tinypic.com/16k2m4p.png" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> I joined the Ph.D. program at [The Ohio State University](https://www.osu.edu/){:target="_blank"} in 2007. Very early on in my Ph.D., I signed up to work with my eventual advisor, [Eric Fosler-Lussier](http://web.cse.ohio-state.edu/~fosler-lussier.1/){:target="_blank"}. His main area of expertise is [automatic speech recognition (ASR)](https://en.wikipedia.org/wiki/Speech_recognition){:target="_blank"} and areas related to spoken technology, and naturally, that became my main focus too. I completed my Ph.D., in 2013, with a thesis on pronunciation modeling in speech recognition. After my Ph.D., I got a [Beckman Postdoctoral fellowship](https://beckman.illinois.edu/research/fellows-and-awards/postdoctoral){:target="_blank"} at [UIUC](http://illinois.edu/){:target="_blank"}. This was an attractive position where I had complete flexibility in terms of research and collaborations.  I spent three years there working with [Mark Hasegawa-Johnson](http://www.ifp.illinois.edu/~hasegawa/){:target="_blank"}, [Lav Varshney](http://varshney.web.engr.illinois.edu/){:target="_blank"} and [Jennifer Cole](http://faculty.wcas.northwestern.edu/jennifer-cole/){:target="_blank"}. I completed my post-doc in August 2016, and joined [IIT Bombay](https://www.cse.iitb.ac.in/){:target="_blank"} soon after, in September.

  
<a name="work_exp"></a>
**ML-India:** What were the projects that you worked on during your Ph.D.?

  

**Preethi:** The work that I did during my Ph.D. followed two main threads. The first thread was focused on answering how we could discriminatively train language models, and how these models could be used to improve ASR. The high-level idea was to first learn a model for the errors produced by a standard ASR system and then to incorporate certain mechanisms to correct these errors. I started exploring this area early on in my Ph.D., with my initial papers following this approach. This also led to an internship at Google, where I worked with my mentor [Ciprian Chelba](https://research.google.com/pubs/author6342.html){:target="_blank"} on a distributed framework for large-scale discriminative language models.

  

The second thread of research during my Ph.D. focused on building improved pronunciation models for speech recognition. I started on this thread when I visited [Karen Livescu](http://www.ttic.edu/faculty/livescu/){:target="_blank"} for a summer, at [TTI](http://www.ttic.edu/){:target="_blank"}, a hidden gem of a place. Pronunciation model is the only component in a modern speech recognition system that is often designed by a linguistic expert, rather than learned from data. An expert-designed model can be used to specify the canonical pronunciations of words. But we wanted to model deviations from the canonical pronunciations. What kind of deviations from standard pronunciation tend to occur when people speak words? Karen, in her Ph.D. thesis, showed that a speech production model from linguistics - in terms of the movements or positions of the various articulators like lips, tongue etc. affect the sounds produced - holds promise. In collaboration with Karen and Eric, I worked on furthering these results. It turned out to be a challenging problem and led us to develop some novel techniques that combined two frameworks - [Finite State Transducers](https://en.wikipedia.org/wiki/Finite-state_transducer){:target="_blank"} (FST) and [Dynamic Bayesian Networks](https://en.wikipedia.org/wiki/Dynamic_Bayesian_network){:target="_blank"}. This paper won a best student paper award at INTERSPEECH. We also had a follow-up work in which we further developed some of the low-level techniques related to training FSTs. These results constituted my Ph.D. thesis.

  

**ML India:** What are your current research interests?

  

**Preethi:** One thing I am currently very interested in is to develop speech recognition systems in a low resource setting. The extent of resources one needs to build today’s state-of-the-art ASR system is not available for most languages in the world. To get around this, we would like to make the most of the little data and other linguistic resources one may have, by developing new resource-sensitive algorithmic techniques. Along similar lines, we would like to exploit the enormous amount of resources that is available for English to handle accented English and do it effectively without needing to collect large amounts of new data. When I was in the US, low resource ASR seemed like a question of academic interest, <img src="http://i65.tinypic.com/eakwid.png" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%">as one assumes that we will eventually have sufficient amount of data in any language that we care for. But when I came to India, I realized that it is an important practical problem too, as it is much more realistic to develop new algorithmic techniques than to wait and gather enough of these resources and then process them with existing techniques. Further, I believe that even when one commands large amounts of resources, developing techniques that are economical with their resources can provide us with new insights into the problem we are trying to solve, potentially leading to improvements across the board.

  
<a name="UIUC"></a>
**ML India:** Could you tell us about your work during your post-doc at UIUC?

  

**Preethi:** One of the things that I worked on while I was at UIUC, mainly in collaboration with Mark Hasegawa-Johnson, was what we called “mismatched transcription”. Typically, to obtain transcriptions of speech in a language for which we don’t have an ASR system yet, one has to rely on native speakers of that language. But this can be a major bottleneck for many languages. So our question was whether we can obtain reliable phonetic transcriptions from people whose native language is unrelated to the target language.

  

On the face of it, this is a rather outlandish idea with little hope of recovering much useful information. However, our idea was to play the same clip to several people and have them write down what they thought they heard; then, random errors would tend to cancel out, whereas systematic biases could be corrected using models that we can learn. We were pleasantly surprised that this idea could be made to work reasonably well. In a series of works with several collaborators, we showed that the mismatched transcriptions can be used to increase the accuracy of ASR systems trained on limited amounts of data.

  

Another problem I worked on, while at UIUC, was with Karen Livescu. We were trying to see if we could devise a correlation between the probability that a word gets misrecognized by an ASR system and the number of words that sound similar to it. This goes back to the problem of understanding ASR error that I was looking at right at the beginning of my Ph.D. It turns out that with the right measure of similarity, we can see that indeed such a correlation exists. Turning this into a tool to correct ASR errors remains an open problem that I would like to revisit at some point.

  

**ML India:** What’s your take on the current scenario of machine learning in India? Do you think it’s getting more vibrant?

  

**Preethi:** It’s definitely getting more vibrant now. There’s been a lot of progress in ML in India over the last few years, both in industry and academia. There is a rising trend of publications from Indian institutions appearing in top tier venues in ML research. Also, I think that the synergy between industry and academia will be an important factor in keeping ML research in India current and competitive with the state-of-the-art. Another interesting trend in ML in India (and elsewhere too) is that there seem to be a lot of self-taught ML enthusiasts, who make the community more vibrant.

  
 <a name="traits"></a>
ML India: What are some of the positives and challenges for an ML student or researcher in India?

  

**Preethi:** Companies like Microsoft, Google etc. support students working in ML in India with fellowships and awards, which in turn motivate them to put in extra efforts. So that’s a virtuous cycle. Also, in Indian academia, the faculty are less burdened by the need to attract funding, compared to, say the US.

  

One of the challenges that I feel we face as academic researchers in India, is the paucity of advanced computer infrastructure. This can be a major impediment to competing with our US colleagues. A related problem is the difficulty in attracting and retaining good Ph.D. candidates, especially when they have options outside the country. It would really uplift the Indian ML research front if we had more post-doc students and Ph.D.s staying and working in India.

  

**ML India:** Any other thoughts on how we can improve?

  

**Preethi:** I think this is a really exciting time to be an ML researcher. Initiatives like the ones taken up by ML India of holding meetups where ML-enthusiasts from across India can come together and discuss research could potentially foster meaningful collaborations.

  

It would help to bring students from universities abroad to intern in Indian academia. Research labs like MSR India are already doing this. I feel like IITs, IISc, IIITs and other top academic institutions could also try and work with these research labs to expand this initiative. This might lead to really good collaboration opportunities for everyone involved, and I think it will help the ecosystem stay dynamic.

  

**ML India:** How would you comment on the quality of graduate or undergraduate students that come to you for discussions or projects etc?

  

**Preethi:** Since I’ve only joined IIT-B recently, I don’t have a Ph.D. student yet, but I am currently working with several M.Tech and B.Tech students - about a dozen students in all. Fortunately, because of the popularity of ML, some of the best students in the department choose to work in this area. And given that CSE at IIT-B tends to attract the top students from JEE and GATE, the quality of these students is generally high.

  

**ML India:** Why did you decide to return to India after your Ph.D.? Did you wish to work in academia from early on?

  

**Preethi:** I was pretty keen on returning to India after my Ph.D. I believe that someone working in an area like mine can make important contributions in India. I wasn’t always sure I wanted to be in academia though. In fact, I was seriously considering an offer from a research lab. However, when I interviewed at IIT-B, I had a very positive experience which made me reconsider my options. Also, I liked the idea that I’d be able to work on my own problems and steer research in a direction that I would find interesting.

  

**ML India:** Are you working on other ML problems?

  

**Preethi:** There is a very active ML group at IIT Bombay, and I’ve started collaborating with several faculty members on a variety of interesting problems. For instance, in collaboration with [Pushpak Bhattacharya](https://www.cse.iitb.ac.in/~pb/){:target="_blank"}, who heads the CFILT lab at IIT-B, I’ve started looking at speech translation, i.e. translating speech in language A to text in language B. More generally, I’m interested in exploring the interaction between speech and text. I’ve also begun working on some generic ML problems that are not tied to any specific ML application.

**ML India:** Thanks a lot, Preethi, for taking time out to talk to ML India. We wish you all the best in your research.

 
