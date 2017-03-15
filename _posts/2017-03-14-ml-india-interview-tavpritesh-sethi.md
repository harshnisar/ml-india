---
layout: post
title: "ML-India interview series - Dr. Tavpritesh Sethi, Assistant Professor, IIIT Delhi"

excerpt: "Dr. Tavpritesh is a physician-scientist working at the interface of data science and medicine. He received his M.B.B.S from Government Medical College, Amritsar and PhD from CSIR-Institute of Genomics and Integrative Biology, Delhi. His core expertise is in translating physiological and clinical insights into machine learning models and data-science pipelines. He has received MIT-India TR35 Young Innovator Award for developing an exquisitely sensitive marker for early airway disease and Wellcome Trust/DBT India Alliance Early Career Award for his current focus on forecasting critical outcomes in Pediatric Intensive Care Units. He has a strong clinical base at All India Institute of Medical Sciences, New Delhi and has joined IIITD with a long term vision of co-creating next generation medicine through interfacing of core clinical, biological and computational disciplines.
"
tags: [india, machine learning, data science, interview, priya, IIIT-H, International Institute of Information Technology Hyderabad]
comments: true

tags_relevant: [interview]
---


<br>
<img src="/images/sss.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> [Tavpritesh](https://www.iiitd.ac.in/tavpritesh){:target="_blank"} is an assistant professor at [IIIT-Delhi](http://www.iiitd.ac.in/){:target="_blank"}, and a physician-scientist working at the interface of Data-science and Medicine. He received his M.B.B.S from Government Medical College, Amritsar and PhD from CSIR-Institute of Genomics and Integrative Biology, Delhi. His research interests are- big-data for clinical decision support, machine learning for critical care and community medicine, human physiology. His core expertise is in translating physiological and clinical insights into machine learning models and data-science pipelines. He has recently been appointed as an assistant professor at [Stanford School of Medicine](http://med.stanford.edu/){:target="_blank"}.


<br><br>
Tavpritesh on..

- <a href="#proj"> His recent projects  </a>
- <a href="#tech"> ML techniques used in his work </a>
- <a href="#advice"> Changing scenario of publishing work in ML and medicine  </a>

<br>

 

**ML India:** Could you give us a brief on your background? How is it that you got into medicine and then steered into being a machine learning practitioner as well?

  

**Tavpritesh:** I completed my MBBS around 10 years back from the [Government Medical College, Amritsar](http://gmc.edu.in/){:target="_blank"}. Although it was not a research-intensive course, it was clear to me that we needed to have more precise definitions of disease diagnosis and treatment regimes. This motivated me to get into research and understand human health and related diseases better. Hence I enrolled for a Ph.D. program at [CSIR-Institute of Genomic Research and Integrative Biology](https://www.igib.res.in/){:target="_blank"}. I was fortunate to work in a lab where a culture of questioning the status-quo was encouraged.  Various aspects of this research were being led by [Dr. Mitali Mukerji](https://www.healthgrades.com/dentist/dr-mitali-mukherjee-yylkk){:target="_blank"}, [Dr. Anurag Agrawal](https://www.healthgrades.com/physician/dr-anurag-agarwal-33m75){:target="_blank"} and [Prof. Samir K. Brahmachari](http://samirbrahmachari.rnabiology.org/){:target="_blank"}. It was with these mentors that I understood the importance of ‘why’ and not only ‘how’ in science which got me hooked to deeper principles of data analytics, machine learning and statistics. My acquaintance with ML was more out of a gradual realization that statistical tools and techniques used at that time didn’t effectively model how our bodies dynamically behaved and evolved, The assumptions of statistics, often fail when applied to complex functioning of the human body. I realized that there were methods that address the complex relationships between various organ systems but a combination of expert physiology and these was under-utilized. That was the background on how I developed an interest to apply ML in solving biological problems.

  

**ML India:** That’s great! What was the problem statement where you were analyzing such a non-linear behavior?

  

**Tavpritesh:** We were trying to figure out how we could capture small-airway diseases earlier than it could be diagnosed through available methods. We were doing this through working with a very interesting technique that measures mechanical impedance of the respiratory tree in response to alternating pressure impulses, analogous to electrical impedance in AC circuits I was inspired by the amazing research in nonlinear features of heart rate variability and that’s when I realized that the behavior of these respiratory signals could be understood in a similar way.<img src="/images/mit.png" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%"> This led to calculation of an index for small-airway diseases which was very sensitive to small airway diseases, something which was (and is) quite difficult to achieve if detailed behavior is not explored. This work was recognized and I was awarded the [MIT TR-35 India Innovators under 35](http://www2.technologyreview.com/tr35/profile.aspx?TRID=1381){:target="_blank"}, 2013 award. This encouragement reaffirmed my belief in combining data science, physiology and clinical understanding to develop a potent toolkit for healthcare.

  

**ML India:** Is it common for students to pursue a Ph.D. after an MBBS? 

  

**Tavpritesh:** No, a Ph.D. after an MBBS is not a very popular option. I do see students at some medical institute who are really motivated to do research after their undergraduate degrees. However, career tracks of this kind are infrequent in India.  I am optimistic though that the picture is gradually changing.  Medical students are now routinely running into data and modeling challenges in healthcare. However,  we need to support such interdisciplinary research and that could be one step taken by our medical and engineering education institutes. 

  

**ML India:** What are the initiatives and institutes that currently promote such interdisciplinary research in medicine?

  

**Tavpritesh:** There are a few places which are open to these options. Apart from [IGIB](https://www.igib.res.in/){:target="_blank"} where I graduated from, [National Center for Biological Sciences](https://www.ncbs.res.in/)  [Indian Institute of Science in  Bangalore](http://www.iisc.ac.in/){:target="_blank"} and [National Institute of Immunology and Translational Health Sciences and Technology Institute](http://www.igdtuw.ac.in/){:target="_blank"} in Delhi are attractive options. However, these are all isolated labs or institutes. There are no specific enrollment programs for medical students on a broader scale as far as I know. On the funding front, I believe that the Wellcome Trust-DBT Alliance is the only program that specifies a clinical research and public health research track. We do need more such initiatives and programs to attract young scientists to pursue studies in this area. 
 

 <a name="proj"></a>  

**ML India:** Could you elaborate more on your transition from your Ph.D. to your more recent projects. And how ML is an important component of your work?

**Tavpritesh:** Medicine and data science need to be bridged seamlessly, given how the two areas have evolved. This thought drove the projects that I took up after I completed my Ph.D. The current project that I am working on addresses predictive modeling in the intensive care environment. Big data is constantly flowing through ICUs and gets flushed once in 2-3 days depending on a hospital’s storage capabilities. We have now built a first-of-its-kind Pediatric resource in India warehousing high-resolution data at the resolution ranging from 15-seconds, 1-second and real-time waveforms of body vitals. This combined with laboratory investigations, blood culture reports and hospital stay etc, we have launched this warehousing pipeline for what we call [SAFE-ICU (Sepsis Advanced Forecasting Engine)](http://www.wellcomedbt.org/fellowsprofile/dr-tavpritesh-sethi-235){:target="_blank"} for ICUs which is supported by the Wellcome Trust/DBT India Alliance. 

  

The idea behind the project is to employ a machine learning/AI framework which raises an alarm or detects the onset of sepsis, one of the most life-threatening conditions in the ICU. We aim to detect sepsis 24-72 hours before its clinical suspicion. <img src="/images/wellcome.png" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">Setting up the warehouse though wasn’t without challenges.It took us 3-4 months in just setting up the automation pipeline to get the data out of the machines at the resolution that we desired. Writing programs that communicate with devices through protocols was entirely new to me, but it gave us an opportunity to understand the systems from the ground up. However, now I think we have hit a sweet spot where we have a small yet inclusive team of a clinical expert, a software programmer, and data scientist.  

**ML India:** In medicine, the general issue for data-driven practitioners is the availability of data. What is your take on what’s happening in the global space, if not in India, on exposing such data so that researchers can come up with new solutions? Do you think this data can be made freely available in the future?

  

**Tavpritesh:** That involves more than just one challenge. Everyone realizes this need for conducting serious research in this area and the availability of medical data is a major bottleneck. <img src="https://s27.postimg.org/uwod6y3zn/mimic.jpg" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:15%">Cross talk between datasets and models is the next challenge. And of course, privacy is the biggest concern while making such data openly available. This issue is slowly coming to effect in India as well. One good resource site is [MIMIC](https://mimic.physionet.org/){:target="_blank"}, an initiative by MIT, which hosts freely available data sets on critical care. Mechanisms like data encryption, identity stripping and anonymizing are the first steps but are just the beginning of a bigger challenge for data-science. which is data harmonization. There is a need to make vendors interact with each other so that they can provide data interfaces which can be harmonized.and therefore combined to be used for research. 

> **"There is a need for good success stories in this field"**
>-Tavpritesh

Another challenge is variability. I believe it arises at two levels - one from noise in data we collect from equipment; another is variation in human subjects. The first comes from from the different configurations of machines and a general lack of technological awareness of medical devices. The second is real noise in human physiology. Data that we typically discard as noise does have some physiological meaning and significance, and identifying this potentially insightful signals becomes a part of the research statement. Variability in patients can be overcome by stratifying or clustering data. We could come up with data science tools and applications that make clusters out of the data such that variability within these clusters decreases. Such techniques have been applied in medicine before and have also been successful. For instance, in cancer treatments, stratification of drug response has been shown by using some important variables like gene signatures.

  

Finally, the last challenge is to create good models that really work, Another big challenge is accepting that such data can prove useful in improving healthcare. There is a need for good success stories to come out of such research which will help shed light on the need to bring data science into mainstream medicine health care and that will convince the policy makers. 

  

**ML India:** That’s great to know. Any other projects that you would like to talk about which involved analyzing data at scale?

**Tavpritesh:** I did a project while I was doing my Ph.D., which involved data of around two lakh patients. This data was collected in a single day by an organization called[Chest Research Foundation](http://www.crfindia.com/){:target="_blank"}, led by Dr. Sundeep Salvi in Pune. My Ph.D. co-advisor Dr. Anurag Agrawal, collaborates with [Dr. Sundeep Salvi](http://www.cahrd-network.org/consultation/dr-sundeep-salvi-md-dnb-phd/){:target="_blank"} who is passionate about making a community-wide difference to the respiratory health in India and this study was called ‘POSEIDON’(Prevalence of symptoms on a single Indian healthcare day at a nationwide scale). For me, this was a perfect opportunity to look at diseases from systems perspective within this amazing data resource because we know that diseases and symptoms are connected. <img src="https://s28.postimg.org/ykhoev4lp/crf.png" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">I conducted an association networks analysis on this massive data to gain a systemic picture of what was happening among the Indian population across various age groups. We saw the emergence of community structures. Just like social networks, disease networks also have a community structure where diseases of certain types co-occur. We looked at pseudo-longitudinal data where we divided people into age groups, and we saw how structures were merging or coming apart between age and population.

The data was telling us stories. An interesting community health insight that we gained was the merging of anemia and female reproductive symptoms in the reproductive age groups. The merging of these two communities ended in in older age groups affirming something we’ve known for a while now - “anemia caused by menstrual disturbances is a huge problem in general all across India. The visualization of community mergers also showed how cardiovascular diseases and diabetes eventually start co-occurring and merging into one network structure in the aged segment of the population ages. 

> **"The data was telling us stories."** 
> -Tavpritesh

More recently, we are trying to move more towards causal networks where, instead of association, we have causal structures and we can infer which nodes are the drivers behind disease symptoms. Such a thorough analysis will help curate a very rich knowledge bank of diseases and its associated symptoms in a data-driven way.

  <a name="tech"></a>

**ML India:** Fantastic! What are some techniques in machine learning that you commonly get to use in your work?

  

**Tavpritesh:** We use a mix of techniques ranging from classical statistical tools to deep learning. It's not one particular tool or technique that we use, but I do have preferences. For instance, I prefer Bayesian networks since it allows causal inferences. For longitudinal datasets, we sometimes have to resort to techniques like [mixed effect models](https://www.mathworks.com/help/stats/linear-mixed-effects-models.html){:target="_blank"} incorporating random effects into machine learning algorithms is still work in progress in the community at large.We also use unsupervised methods in machine learning, but at the core of all data-exercises, we like to have sound physiological hypotheses that serve as positive and negative controls to keep our compass calibrated. I believe, in the world of data, it is too easy to drift into inferences that may not be true or physiologically relevant at all, that is where the clinical expertise helps maintain sanity.

  

**ML India:** Is interpretability an important aspect in your analyses?

**Tavpritesh:** At this point of time, interpretability is not a concern in the majority of my work. We are focusing on accuracy of predictions for guiding interventions. Later, we have a phase in our SAFE-ICU-project where the models have to be tested in a pilot randomized controlled trial setting. Hence, the success of these models depends on how accurately these models perform. Interpretability does become a requirement in some use-cases and there we use techniques that we can provide insights into the black-box models. Google’s [Glassbox](https://www.glassboxdigital.com/){:target="_blank"} is a great example of that.

  

**ML India:** You mentioned data-trials. What is your take on the regulatory environment in India? How confident/mature are we in rolling out such life-critical systems into production, to be used in everyday cases?.

  

**Tavpritesh:** It is an extremely critical aspect. I’m not aware of specific efforts. I’m sure there are discussions happening regarding this at the policy-level in organizations developed nations where data-science has started penetrating clinical practice. Awareness about such regulations would definitely be kept in mind by every data science practitioner in the field of medicine.

  <a name="advice"></a>  

**ML India:** In academic publishing, do you see any changes in the outlook by established publications in medicine towards this emerging field?

**Tavpritesh:** I do see a change in that space, and it is heartening. We are seeing more papers that involve data science activities being published in core medical journals. <img src="/images/jm.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">For example, a couple of years back, [The New England Journal of Medicine](http://www.nejm.org/){:target="_blank"}, had come out with an editorial that talked about how the next 100 years of medicine will be shaped by experts’ knowledge which will be supplemented with, and in some cases, replaced by predictive models. So I see a positive growth in terms of papers being published in the journals. We also have now, the [Tripod set of guidelines](https://www.equator-network.org/reporting-guidelines/tripod-statement/){:target="_blank"} for medical papers, which lists a set of 22 criteria that papers on data science and machine learning models should report, something similar to the MIAME criteria that eventually became a rule for reporting any Microarray-based study. It improves reproducibility and the standard of reliability of the data-science in medicine. It addresses aspects like the transparent and clear explanations of development cohort, validation cohort, cross-validation strategies employed etc. I consider this as a welcome sign because it indicates that the community is now more receptive towards having ML as a more structured component in the publications. 

  

**ML India:** What are the venues of publications that you generally seek out for your work?

  

**Tavpritesh:** For any translational medicine studies, venues like [Science Translational Medicine](http://stm.sciencemag.org/){:target="_blank"} are the most attractive as these are also open to data-driven medicine.A game-changing approach in medicine might even find home in more prestigious journals like [NEJM](http://www.nejm.org/){:target="_blank"} or [Nature Medicine](http://www.nature.com/nm/index.html). [Journal of American Medical Informatics Association](http://jamia.oxfordjournals.org/){:target="_blank"} is another widely respected venue for clinical demonstrations of novel algorithms and strategies.  Then there are computer science venues like [KDD](http://www.kdd.org/){:target="_blank"} and [AAAI](http://www.aaai.org/){:target="_blank"}. The challenge that we face is hitting the right balance between computer science and medicine, which is what we are working on right now and gradually learning about.

  
  

**ML India:** Any other initiatives that you are aware of which promotes work at the intersection of machine learning and medicine?

  

**Tavpritesh:** Currently I am working at a very progressive department of Computational Biology at [Indraprastha Institute of Information Technology, Delhi](http://www.iiitd.ac.in/){:target="_blank"}. This place is actually transcending boundaries. I am aware of a few other places such as [IIT Gandhinagar](http://www.iitgn.ac.in/){:target="_blank"} which have Biomedical Engineering crossing boundaries. As I mentioned earlier, IGIB and [NIBMG](http://www.nibmg.ac.in/){:target="_blank"} are places where a clinical interfacing of quantitative and clinical disciplines is happening. However, I am not aware of any specific programs or initiatives that are interfacing medicine and machine learning. [C-DAC](https://cdac.in/){:target="_blank"} engages indirectly in this area - by providing different tools, pipelines and development of biological datasets. However, we need to have a larger number of structured courses on computational healthcare, which focus specifically on a data-intensive approach to clinical healthcare. I am not aware of any programs in India which address this area.

  

**ML India:** Great. Thanks a lot, Tavpritesh for taking time out to talk to ML-India. We wish you all the best in your research.
