---
layout: post
title: "ML-India interview series - Dr. Shivaram Kalyanakrishnan (IIT-Bombay) discusses the AI100 Report that he was a part of"

excerpt: "Shivaram is an Assistant Professor in the Department of Computer Science and Engineering, Indian Institute of Technology Bombay. He specialises in artificial intelligence. His areas of interest are sequential decision making, multiagent learning, multi-armed bandits, and humanoid robotics. Application domains of his research include robot soccer, computer games, and online advertising.
"
tags: [india, machine learning, data science, interview, mayank, IIT-B, indian institute of technology bombay]
comments: true

tags_relevant: [interview]
---


<img src="https://www.cse.iitb.ac.in/~shivaram/pictures/shivaramkalyanakrishnan-2012.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> Shivaram is an Assistant Professor in the [Department of Computer Science and Engineering](http://www.cse.iitb.ac.in/){:target="_blank"}, [Indian Institute of Technology Bombay](http://www.iitb.ac.in/){:target="_blank"}. He specialises in artificial intelligence. His areas of interest are sequential decision making, multiagent learning, multi-armed bandits, and humanoid robotics. Application domains of his research include robot soccer, computer games, and online advertising.

We have a conversation with Shivaram on recent developments that have aimed to study the ramifications of AI on our society and make such knowledge mainstream. With many popular names in the industry being vocally critical of AI and its fast-changing role in our lives, early September witnessed the AI100 report being released - work done by a visionary group put together by Microsoft Research’s Eric Horvitz to study and chronicle the impact of AI on our society as we live through it. Late September witnessed a similar attempt. Christened [‘Partnership on AI’](http://www.partnershiponai.org/){:target="_blank"}, it was an effort by four IT giants - Google, Facebook, IBM and Microsoft to join hands and come out with a framework for the “safe and correct use” of AI.
  

The [AI100 report](https://ai100.stanford.edu/2016-report){:target="_blank"} is a long-term investigation of the field of Artificial Intelligence (AI) and its influences on people, their communities, and society. It considers the science, engineering, and deployment of AI-enabled computing systems. This is the report of [2015 Study Panel](https://ai100.stanford.edu/people){:target="_blank"}. Such reports are slated to be released every 5 years, with a separate study panel, for the next 100 years to be able to consistently track AI’s advances and its impact on our society. <img src="https://i.imgsafe.org/08f20c5114.jpg" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> The Study Panel reviews AI’s progress in the years following the immediately prior report, envisions the potential advances that lie ahead, and describes the technical and societal challenges and opportunities these advances raise, including in such areas as ethics, economics, and the design of systems compatible with human cognition. The overarching purpose of the One Hundred Year Study's periodic expert review is to provide a collected and connected set of reflections about AI and its influences as the field advances. The studies are expected to develop syntheses and assessments that provide expert-informed guidance for directions in AI research, development, and systems design, as well as programs and policies to help ensure that these systems broadly benefit individuals and society.   

We chatted with Shivaram in particular about this report, how he got involved in its preparation and also his thoughts on how this field was advancing. 


Shivaram on..

- <a href="#key"> Key learnings from the report </a>
- <a href="#vehicles"> Efforts to teach automated vehicles morality </a>
- <a href="#india_prob"> How AI and ML are placed in solving some problems specific to India </a>

<br>

**ML-India:** Hello Shivaram. Thanks for taking time out for this interview with ML-India. To start things off, it would be great if you could give us an overview of the reason for coming out with this report. What is its importance at this stage of our societal evolution?

  

**Shivaram:** Thanks. AI as a field, though contrary to popular notion, has existed in various forms for more than 50 years now and is in no way a recent phenomenon. However, only recently have the full effects and utilities of AI become commonplace. Some of these technologies today are a part of our everyday lives. The fact that this technology has entered our homes and lives has resulted in many public figures critiquing it. We have the likes of Stephen Hawking and Elon Musk [quoting](http://www.inc.com/tess-townsend/elon-musk-open-ai-safe.html){:target="_blank"} to the effect that AI could end mankind. This creates a lot of hyperbole and rhetoric around this topic. With this as a backdrop, the founders of this study, [Eric and Mary Horvitz](http://research.microsoft.com/en-us/um/people/horvitz/){:target="_blank"}, established a fund to conduct a sober and systematic assessment of the state of AI. Eric put together a standing committee which was tasked to pick a group of AI scientists to deliberate upon this topic and provide an unbiased view on the prospects, future and the consequences of AI on our society at large. By isolating it from the general hype and sensationalism that this topic attracts from the media, this was an attempt at making it a more academic and rigorous exercise, aimed at influencing serious discourse about this topic. That’s the genesis behind this study.

  
  

**ML-India:** That’s a really nice initiative. How was this group of AI scientists put together?

**Shivaram:** The top rung of the organizational structure was a standing committee which was put together by Eric and Mary Horvitz. These [men and women](https://ai100.stanford.edu/people){:target="_blank"} have significantly addressed problems in AI and related engineering fields and have influenced generations of researchers thereafter. They discussed and finalised who would comprise the study panel, whose task it would be to delve into the nuances of this issue. They selected [Prof. Peter Stone](https://www.cs.utexas.edu/~pstone/){:target="_blank"} from UT Austin to chair the study panel. Along with other researchers, Prof. Stone, who was my doctoral advisor at UT Austin, suggested that I be on this panel, given the strong overlap in my area of expertise.

<img src="https://i.imgsafe.org/0a865765ad.png" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:27%">
**ML-India:** I see. The AI100 report talks about 7-8 major areas such as transportation and education. Were researchers picked from each of these fields given their expertise in it to finally form the study panel?


**Shivaram:** Not quite. The group was quite a generic one consisting of researchers who have long dabbled with AI and its flavours. In the course of fleshing out the details of this report, we finalised on the 8 verticals that we eventually decided to cover.

  

**ML-India:** One observation is that the study panel mostly has academics and not many from the industry. Does it put the work done and report produced at the risk of being too pedantic?

**Shivaram:** I don’t agree that having an academic-heavy study panel would disconnect it from reality. Moreover, the panel does have 3-4 eminent researchers, like [Rodney Brooks](https://people.csail.mit.edu/brooks/){:target="_blank"} from MIT(and also Rethink Robotics), [Astro Teller](https://www.linkedin.com/in/astroteller){:target="_blank"} from Google X and [Oren Etzioni](https://homes.cs.washington.edu/~etzioni/){:target="_blank"} from Allen AI, who have spent their recent years majorly collaborating with or contributing to the industry. Having said that, I do agree that industry practitioners would bring in very relevant perspectives for a study of this sort. Industry, after all, plays the key role of translating ideas into products and services for society. At one of the study panel’s internal meetings, in fact I had recommended that future study panels have greater representation from industry.

  
<a name="key"></a>
**ML-India:** Sure. In your view, what are the key learnings from this report?

**Shivaram:** Right. As I’d mentioned earlier, when we got around the first time and started with this study, we really hadn’t earmarked what would be the specific areas we’d be studying. After much deliberation and discussions, we finally chose to dig deeper into the following eight areas –  transportation, healthcare, education, low-resource communities, public safety and security, employment and workplace, home/service robots, and entertainment. I must add here, and this is important, that this is by no means an exhaustive list. You’ll notice that some obvious areas like military applications are not one of our focus areas. That’s a thesis in itself. Given our everyday interactions with AI, we wanted to shed light on areas that would impact us on a daily basis in the immediate future.

Based on this study, I think the overarching summary which one could take home would be –

**There’s no existential threat from AI at least for the next 20-30 years.** From where we are today, to what is needed in systems to truly be a threat to our society in an explicit way, we can confidently assert that this is very unlikely to happen in the next 20-30 years. So this is not something our immediate generations need to worry about, contrary to what the [popular media claims](http://www.express.co.uk/news/science/668886/AI-major-threat-microsoft-artificial-intelligence){:target="_blank"}.

**Regulatory mechanisms are splintered and there is an immediate need for administrative streamlining to recognize and foster efforts in this field.** We are now at a point where the technology and science of AI have moved beyond our textbooks and are now part of our daily lives. By and large, these technologies (think of web search, social networks, ridesharing apps, recommender systems) have benefitted our quality of living, and have therefore been accepted by society with open arms. But where we lack today is governments keeping pace with this fact. Currently, the policy formulation and regulatory mechanisms are fairly splintered  - for instance we have in the USA an FDA (Food and Drug Administration) tackling issues of using AI in medicine while we have the department of transportation and the FAA (Federal Aviation Administration) scratching their heads about issues of AI in transportation and space. The bedrock of these issues is largely similar – which calls for governments to revise how they are approaching this subject. It would make sense for governments to come up with a more centralised approach in accepting, addressing and creating a dialogue with all relevant stakeholders. The government, as the regulator, must hence be staffed at all levels with personnel who are trained to critically evaluate and audit AI systems.

  

**ML-India:** That’s very true. In your opinion, any one of these eight areas that you feel most strongly about and would want to comment on?

**Shivaram:** Well, I think I feel quite strongly about all these areas that’ve been covered. Most relevant and of immediate consequence is, I guess, transportation. The rate at which innovation is happening is just fantastic – needing this entire support system of understanding its consequences etc. wanting to be fleshed out. I think this area will soon demand our collective attention.

  
<a name="vehicles"></a>
**ML-India:** Any thoughts on efforts to teach automated vehicles morality along the lines of [MIT’s moral machines](http://moralmachine.mit.edu/){:target="_blank"}? 

**Shivaram:** Right, that’s a great question. Traditionally, AI courses in universities have almost always been accompanied by courses on morality and ethics. It’s very nascent and is being addressed as we speak. <img src="https://i.imgsafe.org/08fffd329e.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> I think software systems will have to evolve and be able to follow agreed upon protocols and frameworks to handle these use-cases. Thinking of having a governing body to certify such software may be one solution. However, if one thinks closely about present day systems – such as certifying software being shipped out in commercial planes or a subway train, industries which control hundreds of lives each day, no such governing body exists. It is also true that [formal verification](https://en.wikipedia.org/wiki/Formal_verification){:target="_blank"}, a branch of computer science where you mathematically prove that your software works as intended, is heavily adapted by these specific industries. So there are no easy answers. These topics--at the intersection of philosophy, technology, and law--are bound to come up for discussion as AI progresses into the next couple of decades.

  

**ML-India:** And this puts us in a particularly tight spot as a society given that I don’t think we know the right answers to these hard questions and the decisions we’d have made had we been in those situations.

**Shivaram:** Absolutely. That’s the best part of AI. We are victims of the [AI effect](https://en.wikipedia.org/wiki/AI_effect){:target="_blank"}! We first thought building a machine to beat man in a complex game like chess was the holy-grail for AI. Today, a grad student would think twice before announcing automated chess as her area of study – it’s done and dusted. We constantly want to move towards building machines which imitate the finer aspects that characterize us as humans. It’s only going to get harder here on. Medicine is again an area where there would be many such hard questions which would need answers. Let’s wait and watch how things unfold.

  
  

**ML-India:** Post the publication of this report, has there been any response from the US government? Any comments or acknowledgement from them?

**Shivaram:** Well the US government has been very receptive of the developments that are going on in this space. I don’t think they got back to specifically comment on this report, but their [office of science and technology policy (OSTP)](https://www.whitehouse.gov/administration/eop/ostp){:target="_blank"} (OSTP) definitely is very aware of the developments happening. In fact, they have recently released their own report on [Preparing for the Future
of AI](https://www.whitehouse.gov/blog/2016/10/12/administrations-report-future-artificial-intelligence){:target="_blank"}, which makes references to the AI100 report. I think it’s been a very pro-active role they’ve taken so far.



**ML-India:** Any particular efforts in India that you’re aware in this regard?

**Shivaram:** One must note that not all these issues which we’ve listed out in the report are immediately applicable to the Indian context. For instance, we’re a long way away from having autonomous cars on our streets given our current infrastructure. But there are other aspects like education and health which are very pertinent. While I’m not aware of any real conversation or initiative from the government yet, it is important that policy-makers in India soon step in. I’m hopeful that these would be gradual steps we’ll be taking once these technologies enter our everyday lives.

  
<a name="india_prob"></a>
**ML-India:** And your opinion on how AI and ML are placed in solving some problems specific to India?

**Shivaram:** Oh, I’m very excited about it. I think our geography and culture presents to us a gold-mine of interesting problems for us to tackle. For instance, speech and natural language research has so many problems which need to be addressed in the Indian context. There’s a high bias of information being in English, which presents an unwanted barrier to information assimilation. Similarly, crowd-sourcing and mechanism design is again an area which I personally feel very strongly about. There are enormous opportunities which government agencies can offer given the data trail they have to deal with. Likewise, computational sustainability is again an upcoming area which can help provide tangible benefits to our environment. [Prof. Milind Tambe](http://teamcore.usc.edu/tambe/){:target="_blank"}  from USC has shown remarkable ways to use AI and ML to help fight poachers! The possibilities are limitless. This is fertile ground for high-quality research and development to happen.

  

**ML-India:** Great! Any closing thoughts for our readers?

**Shivaram:** AI is a wonderful field for several reasons. It’s a field which calls for diverse areas of expertise - hard math, policy, ethics, engineering and many more. And we are in the middle of a period that the field is really beginning to blossom and to deliver results across a variety of domains. That simply makes the possibilities limitless. Many of us are inclined to address socially relevant problems but are often at a loss how to translate will to action. Today nearly every sector--be it education, environment preservation, business development, manufacturing and production, media and communication, healthcare, or transportation--presents problems that admit AI-based solutions. And the primary resource required to work on such problems is intellectual capital--ideas and software. I would like to call out to all young students of computer science and engineering to focus on fundamental knowledge and innovations in this space. There’s simply a lot to be done for which fresh, smart talent is needed.

  

**ML-India:** Thanks a lot for taking time out for this Shivaram! We look forward to subsequent reports from the AI100 study group!
