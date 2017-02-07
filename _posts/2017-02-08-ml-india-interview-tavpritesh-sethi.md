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
<img src="https://s30.postimg.org/dd1fq8969/sss.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:30%"> [Tavpritesh](https://www.iiitd.ac.in/tavpritesh){:target="_blank"} is an assistant professor at [IIIT-Delhi](http://www.iiitd.ac.in/){:target="_blank"}, and a physician-scientist working at the interface of Data-science and Medicine. He received his M.B.B.S from Government Medical College, Amritsar and PhD from CSIR-Institute of Genomics and Integrative Biology, Delhi. His research interests are- big-data for clinical decision support, machine learning for critical care and community medicine, human physiology. His core expertise is in translating physiological and clinical insights into machine learning models and data-science pipelines. He has recently been appointed as an assistant professor at [Stanford School of Medicine](http://med.stanford.edu/){:target="_blank"}.


<br><br>
Tavpritesh on..

- <a href="#proj"> His recent projects  </a>
- <a href="#tech"> ML techniques used in his work </a>
- <a href="#advice"> Changing scenario of publishing work in ML and medicine  </a>

<br>

 

**ML India:** Could you give us a brief on your background? How is it that you got into medicine and then steered into being a machine learning practitioner as well?

  

**Tavpritesh:** I completed my MBBS around 10 years back from the [Government. Medical College, Amritsar](http://gmc.edu.in/){:target="_blank"}. Although it was not a research-intensive course, it was very clear to me that we needed to have more precise definitions of disease diagnosis and treatment regimes. This motivated me to get into research and understand human health and related diseases better. That made me pursue a Ph.D. at [CSIR-Institute of Genomic Research and Integrative Biology](https://www.igib.res.in/){:target="_blank"}. I was very fortunate to work in a lab where a culture of questioning the status quo was encouraged. I was really fortunate to get into a Ph.D. program and a lab which had projects run by [Dr Mitali Mukherjee](https://www.healthgrades.com/dentist/dr-mitali-mukherjee-yylkk){:target="_blank"} and [Dr. Anurag Agarwal](https://www.healthgrades.com/physician/dr-anurag-agarwal-33m75){:target="_blank"} - it was a very niche space that I had gotten into. My acquaintance with ML was more out of a gradual realization that statistical tools and techniques used at that time didn’t model well how our bodies dynamically behaved and evolved, The assumptions of statistics, for most times, were beginning to fail when we started looking at the functions of the human body. I found that the relationships between various organ systems and their related variables were nonlinear in nature. This made me consider machine learning algorithms, which model non-linearity well.That was how I developed an interest to apply ML in solving biological problems.

  

**ML India:** That’s great! What was the problem statement where you were analyzing such a non-linear behavior?

  

**Tavpritesh:** We were trying to figure if we can actually capture the small-airway diseases earlier than it was being diagnosed through traditional methods. We were working on some very interesting electric signals - like the impedance from the respiratory tree in being able to predict these diseases.We had also been looking up literature on other signals in the human body, like the heart rate feasibility (beating of the heart and its behaviour). <img src="https://s30.postimg.org/djv9h7dht/mit.png" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">This particular signal is generally noisy, and such noisy signals indicate a healthy heart. We were studying a combination of such features to help establish a relationship between the complexity of human body and the detection of small-airway diseases. This led to building an index for small-airway diseases using non-linear additive models over such features. This work was then recognized by the [MIT Tech Review’s Innovators under 35](http://www2.technologyreview.com/tr35/profile.aspx?TRID=1381){:target="_blank"} program. That reaffirmed my view that data science and principles of mathematics, when applied to problems in healthcare, can be a very potent toolkit.

  

**ML India:** Is it common for students to pursue a Ph.D. after an MBBS? 

  

**Tavpritesh:** Going for a Ph.D. after an MBBS is not a very popular option. However, I do know that students at some places are really motivated to do clinical-heavy research post their undergraduate degrees. I am optimistic though that the picture will change gradually. Students now routinely see the need for big data and modelling solutions to problems in healthcare. However, I do see a lack of clearly defined tracks for supporting such interdisciplinary research. That could be an area of focus for our education institutes. 

  

**ML India:** What are the initiatives and institutes that currently promote such interdisciplinary research in medicine?

  

**Tavpritesh:** [NCBS](https://www.ncbs.res.in/) is one such institute, [IISc, Bangalore](http://www.iisc.ac.in/){:target="_blank"} and [IGIT, New Delhi](http://www.igdtuw.ac.in/){:target="_blank"} also have similar facilities. But these are all isolated labs or institutes. There are no specific enrollment programs for students. On the funding front, I believe that the Wellcome Trust-DBT Alliance is the only program that specifies a clinical research and public health research track. We do need more such initiatives and programs to attract young scientists to pursue studies in this area. 

   <a name="proj"></a> 

**ML India:** Could you elaborate more on your transition from your Ph.D. to your more recent projects. And how ML is an important component of your work?

**Tavpritesh:** Medicine and data science need to be bridged seamlessly, given how the two areas have evolved. This thought drove the projects that I took up after I completed my Ph.D. The current project that I am working on looks at intensive care units’ databases. Big data is constantly flowing through ICUs. It is captured at resolutions ranging from 1 second to 1 minute. In India, this data gets flushed once in 2-3 days depending on a hospital’s storage capabilities. The data is preserved just to have a limited window of information on a patient. We have now built a first-of-its-kind resource where we have not only housed data like heart rates and pulse from signals in ICUs, but also other data like laboratory investigation, blood culture reports etc. So we are creating this resource in our current project called [SAFE (Sepsis Advanced Forecasting Engine)](http://www.wellcomedbt.org/fellowsprofile/dr-tavpritesh-sethi-235){:target="_blank"} for ICUs. 

  

The idea behind the project is to employ a machine learning framework which raises an alarm or detects the onset of sepsis, one of the most life-threatening conditions in the ICU. We are able to detect this condition around 48-72 hours before extant methods recognize it. <img src="https://s23.postimg.org/6yhppuh0b/wellcome.png" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">We started working on this after a grant proposal we wrote to the Wellcome Trust-DBT Alliance was approved. We began work from August 2015. It took us 3-4 months in just setting up the pipeline to get the data out of the machines. Since we have specific resolution requirements, this posed a big challenge. However, I think we had hit a sweet spot where we had a complete team of experts and advisors who collaborated in building the system to apply machine learning approaches and derive useful predictions. 

**ML India:** In medicine, the general issue for data-driven practitioners is the availability of data. What is your take on what’s happening in the global space, if not in India, on exposing such data so that researchers can come up with new solutions? Do you think this data can be made freely available in the future?

  

**Tavpritesh:** That involves more than just one challenge. Everyone the world over realizes that for conducting any kind of research in this area, the availability of data is a major bottleneck. <img src="https://s27.postimg.org/uwod6y3zn/mimic.jpg" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:15%">Its tough to build models and get harmonised data sets which can actually cross talk. Privacy is definitely one of the challenges in making such data openly available. <img src="https://s27.postimg.org/uwod6y3zn/mimic.jpg" align='right' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">This issue is slowly coming to effect in India as well. But this still can be worked around by mechanisms like identity stripping and anonymizing the data. One good resource site is [MIMIC](https://mimic.physionet.org/){:target="_blank"}, an initiative by MIT, which hosts freely available data sets on critical care.

> **"There is a need for good success stories in this field"**
>-Tavpritesh

The other concern is harmonizing the electronic health care sector. There is a need to make vendors interact with each other so that they can provide better machines, with a variety of data resolution options, which can then be used for research. Another big challenge is accepting that such data will be useful in improving healthcare. There is a need for good success stories to come out of such research, which will help shed light on the need to bring data science into health care and convince policy makers. Scholars who get trained in health care need to start looking at data as a resource to help patients. 

  

Another challenge is variability. I believe it arises at two levels - one from noise in data we collect from equipment; another is variation in human subjects. A lot of variability also arises at the procurement stage of these devices. Data that we typically discard as noise does have some physiological meaning and significance, and identifying this potentially insightful signals becomes a part of the research statement. Variability in patients can be overcome by stratifying or clustering data. We could come up with data science tools and applications that make clusters out of the data such that variability within these clusters decreases. Such techniques have been applied in medicine before and have also been successful. For instance, in cancer treatments, stratification of drug response has been shown by using some important variables like gene signatures.

  

**ML India:** That’s great to know. Any other projects that you would like to talk about which involved analyzing data at scale?

**Tavpritesh:** I did a project while I was doing my Ph.D, which involved data of around two lakh patients. This data was collected in a single day by an organization called [Chest Research Foundation](http://www.crfindia.com/){:target="_blank"}, Pune. My Ph.D. advisor Dr. Anurag Aggarwal, collaborated with [Dr. Sundeep Salvi](http://www.cahrd-network.org/consultation/dr-sundeep-salvi-md-dnb-phd/){:target="_blank"}, a respiratory physician and a researcher who is passionate about understanding community health in India. We were looking at free sources of such data.<img src="https://s28.postimg.org/ykhoev4lp/crf.png" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%"> I concluded that we can start looking at the data from a system’s perspective since we know that diseases and symptoms are connected and these connections change across age groups. This was called the ‘POSEIDON study’(Prevalence of symptoms on a single Indian healthcare day on a nationwide scale). My contribution to this was in studying this data from the lens of network analysis. My aim was to gain a systemic picture on what was happening among the Indian population across various age groups. In the Bayesian networks we built, we found associations among different symptoms, we saw the emergence of community structures. Just like social networks, disease networks also have a community structure where diseases of certain types co-occur. We looked at pseudo-longitudinal data where we divided people into age groups, and we saw how structures were merging or coming apart between age and population.

> **"The data was telling us stories."** 
> -Tavpritesh

An interesting community health insights that we gained was the merging of anemia and female genitalia related symptoms in the reproductive age groups, which got separated in older age groups. This affirmed something we’ve known for a while now - of how anemia caused by menstrual disturbances is one of the widespread conditions in India. The data was clearly showing how these associate and deform in the reproductive age groups. We also began to see how cardiovascular diseases and diabetes start to co-occur and merge into one network structure as the population ages. 

  

More recently, we are trying to move more towards causal networks where, instead of association, we have causal structures and we can infer which nodes are the drivers behind disease symptoms. Such a thorough analysis will help curate a very rich knowledge bank of diseases and its associated symptoms in a data-driven way.

<a name="tech"></a>

**ML India:** Fantastic! What are some techniques in machine learning that you commonly get to use in your work?

  

**Tavpritesh:** We use a mix of techniques ranging from classical statistical tools to building deep networks. It's not one particular tool or technique that I use, but I do have preferences. For instance, I prefer Bayesian networks since it allows causal inferences. For longitudinal datasets, we sometimes have to resort to techniques like [linear effect models](https://www.mathworks.com/help/stats/linear-mixed-effects-models.html){:target="_blank"}. We still have to make a headway into longitudinal data evaluation, which is not very mature in the medical domain at this point of time. We also use unsupervised methods in machine learning, and also make our own physiologically relevant tweaks in existing algorithms to address the medical problem in question.

  

**ML India:** Is interpretability an important aspect in your analyses?

**Tavpritesh:** At this point of time, interpretability is not a concern in the majority of my work. We are focusing on accuracy of predictions and medication. For example, we have a phase in our ICU-project where the models have to be tested as a pilot, and the success of these models depend on how accurately these models perform. Interpretability does become a requirement in some use-cases, but there are techniques that we can use to resolve it. We can change a variable, keeping the rest of the parameters fixed, to see how the model reacts and understand its behaviour. [Glassbox](https://github.com/google/glassbox){:target="_blank"}, launched by Google, is one of the techniques which executes such a process.  

  

**ML India:** You mentioned data-trials. What is your take on the regulatory environment in India? How confident/mature are we in rolling out such life-critical systems into production, to be used in everyday cases?.

  

**Tavpritesh:** It is an extremely critical aspect. I’m not aware of specific efforts. I’m sure there are discussions happening regarding this at the policy-level under the larger umbrella of applications involving data science. In our case, the proposal actually is to reveal the model outcomes to a randomized set of medical experts and then just leave it there. We cannot influence human experts’ mode of treatment or the treatment regime. We are just building a knowledge system and trying to build insights into what the physiology says through models. Such regulations should be kept in mind by every data science practitioner in the field of medicine.

 <a name="advice"></a>  

**ML India:** In academic publishing, do you see any changes in the outlook by established publications in medicine towards this emerging field?

**Tavpritesh:** I do see a change in that space, and it is heartening. We are seeing more papers that involve data science activities being published in core medical journals. <img src="https://s30.postimg.org/sivgipd6p/image.jpg" align='left' style="margin-right:5px; margin-top:9px; margin-left:5px; width:25%">For example, a couple of years back, [The Journal of Medicine](http://www.nejm.org/){:target="_blank"}, had come out with an editorial that talked about how the next 100 years of medicine will be shaped by experts’ knowledge which will be supplemented with, and in some cases, replaced by predictive models. So I see a positive growth in terms of papers being published in the journals. Also, the [Tripod guideline](https://www.equator-network.org/reporting-guidelines/tripod-statement/){:target="_blank"} for medical papers, which lists a set of 22 criteria that new papers on data science and machine learning models should be essentially reporting on, is a useful regulation. It acts as the standard of reliability of the work being reported. It addresses aspects like the development cohort, validation cohort, cross-validation strategies employed etc. This is a welcome sign because it indicates that the community is now more receptive towards having ML as a more structured component in the publications. 

  

**ML India:** What are the venues of publications that you generally seek out for your work?

  

**Tavpritesh:** For our current work, we are looking at venues like [Science Translational Medicine](http://stm.sciencemag.org/){:target="_blank"} they come out routinely with machine learning oriented papers in medicine. Then there are more prestigious journals like [Nature Medicine](http://www.nature.com/nm/index.html){:target="_blank"}. These venues are now accessible to doctors and healthcare practitioners who incorporate machine learning concepts in their work. Then there is an abundance of venues that are computer science oriented like KDD and AAAI. The challenge that we face is hitting the right balance between computer science and medicine, which is what we are working on right now and gradually learning about. We plan to start publishing at these venues as well.

  
  

**ML India:** Any other initiatives that you are aware of which promotes work at the intersection of machine learning and medicine?

  

**Tavpritesh:** I am not aware of any specific initiatives that are interfacing medicine and machine learning. There are interesting programs addressing the broader area of informatics and biology - in departments like Biomedical Engineering and Biological Sciences at IIT Gandhinagar and a few other universities. [C-DAC](https://cdac.in/){:target="_blank"} engages indirectly in this area - by providing different tools, pipelines and development of biological datasets. However, we need to have a larger number of structured courses on computational healthcare, which focus specifically on a data-intensive approach to clinical healthcare. I am not aware of any programs in India which address this area.

  

**ML India:** Great. Thanks a lot, Tavpritesh for taking time out to talk to ML-India. We wish you all the best in your research.
