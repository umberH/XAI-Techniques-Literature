
# Explainable Artificial Intelligence (XAI) Literature

This is a continuous initiative aimed at bringing together noteworthy initiatives in the domain of comprehending, interpreting, explaining, and visualizing a pre-trained ML model. 

State-of-the-art Explainable Artificial Intelligence for Machine Learning Models.

This page provides the infomation about the available state-of-the-art XAI tools comprehensive list. This list can be helpful to understand the available XAI techniques and which domains are using XAI. We need XAI for all the types of the Machine learning models, the scope of explanations can vary with the models and the domains applicability. XAI is a way to widley adopt the AI in the models  doamins. XAI is applicable to all the blackbox models which are not transparent to the users. Its is applicable in all domains including but not limited to 


📝 Natural Language Processing
🖼️ Computer Vision
🗣️ Audio
🐙 Multimodal

# Conferences and venues with Special track for XAI
 * IJCAI [2017](),[2018](),[2019](),[2020](2022),[2022](https://sites.google.com/view/xai2022), [2023](https://sites.google.com/view/xai2023/home)
 * AAAI [2019](https://xaitutorial2019.github.io/), [2020](https://xaitutorial2020.github.io/), [2022](https://xaitutorial2022.github.io/)
 * ICML [FAT-ML](https://www.fatml.org/), (Workshop on Human Interpretability in Machine Learning) [2020](https://sites.google.com/view/whi2020/home)
 * DSAA [2022]
 * CVPR [2019](https://explainai.net/)
 * NIPS
 * ICAPS [Explainable Planning](https://xaip.mybluemix.net/)
 * AAMAS [2023](https://extraamas.ehealth.hevs.ch/index.html)
 * CHI
 * CIKM
 * FACCT
 * WWW

a generic search link to find [conferences Venues](http://www.wikicfp.com/cfp/call?conference=explainable%20ai)


# Types of XAI Technique
XAI techniques can be analyzed based on different dimension of the explanations. 
I will be organizing this list based on three categories. 
* XAI for Data (The model was used to analyze data, so Data Type Matters in this case)
* XAI for Opening the black Box (This category will have Model specific techniques)
* Posthoc Explanations of the Model (Model- agnostic and Post-hoc and Surrogate)
These explanations have a scope (Local/Global) which is based on the type of techniques

 
 These categories can be further subdivided. 
 We will divide these categories for elaboration purposes. 
 

# XAI Tools List

# List of Surveys in the Literature
## Systematic Liteature Surveys
| Paper Title | Domain | year | Link| Publication venue|
|---|---|---|---|---|
|Explainable Artificial Intelligence in the Medical Domain: A Systematic Review| Medical |2021||AMCIS|
|Explainable Artificial Intelligence: a Systematic Review |-|2020|[File](http://arxiv.org/abs/2006.00093)|Not Peer Reviewed|
|A Systematic Review of Explainable Artificial Intelligence in Terms of Different Application Domains and Tasks|-|2022|[File](https://www.mdpi.com/2076-3417/12/3/1353)|Multidisciplinary Digital Publishing Institute|
|Towards Human-Centred Explainable AI: A Systematic Literature Review|-|2021|[File]()||
|Evaluating the Quality of Machine Learning Explanations:A Survey on Methods and Metrics|-|2021|[File]()||

# Opportunities in XAI

# Selected Approaches Analysis

|Selected XAI Approaches   | Antehoc /Posthoc  | Explaination Methodlogy    | Target Audience       | Scope            | Explanation Evaluation  | Target Box   | Data Driven /Knowledge Driven|
|-------------:|---------:|---------------:|--------------:|-----------:|------------:|------:|----------:| 
|     TREPAN   | Posthoc  | Surrogate Model| Domain Experts| Global     | No          | NN    | Data-Driven|
|     DEEP RED | Posthoc  | Surrogate Model| Domain Experts| Global     | No          | NN    | Data-Driven|
| Distilling NN| Posthoc  | Surrogate Model| Domain Experts| Global     | No          | NN    | Data-Driven|
| DeepLIFT||||
|LRP||||
|Deep SHapley Additive exPlanations (Deep SHAP)
|CAM||
|LIME||




#People 

* Andreas Holzinger [Google Scholar](https://scholar.google.com/citations?user=BTBd5V4AAAAJ&hl=en), [Web](http://www.aholzinger.at/), [Research Group](https://human-centered.ai/)
* Cynthia Rudin [Google Scholar](https://scholar.google.com/citations?user=mezKJyoAAAAJ&hl=en), [Web](https://users.cs.duke.edu/~cynthia/home.html) 
* Fred Hohman [Google Scholar](https://scholar.google.com/citations?user=1w0TLT8AAAAJ&hl=en), [Web](https://fredhohman.com/), [Github](https://github.com/fredhohman)
* Marco Tulio Ribeiro [Google Scholar](https://scholar.google.com/citations?user=rmsIyGMAAAAJ&hl=en&oi=sra), [Web](https://homes.cs.washington.edu/~marcotcr/), [Github](https://github.com/marcotcr)
* Scott Lundberg [Google Scholar](https://scholar.google.ca/citations?user=ESRugcEAAAAJ&hl=en), [Web](https://scottlundberg.com/), [Github](https://github.com/slundberg)
* Fosca Giannotti [Google Scholar](https://scholar.google.com/citations?user=PKz_a_AAAAAJ&hl=en), [Web](http://kdd.isti.cnr.it/homes/giannotti), [Research Group](https://kdd.isti.cnr.it/) 
* Riccardo Guidotti [Google Scholar](https://scholar.google.it/citations?user=KZUaK6YAAAAJ&hl=en), [Web](https://kdd.isti.cnr.it/people/guidotti-riccardo), [Github](https://github.com/riccotti), [Research Group](https://kdd.isti.cnr.it/) 
* Angel Alexander Cabrera [Google Scholar](https://scholar.google.com/citations?user=r89SDm0AAAAJ&hl=en), [Web](http://cabreraalex.com/), [Github](https://github.com/cabreraalex)
* Mennatallah El-Assady [Google Scholar](https://scholar.google.de/citations?user=ZEGgJM4AAAAJ&hl=en), [Web](https://el-assady.com/), [Research Group](http://vialab.science.uoit.ca/research)
* Klaus-Robert Muller [Google Scholar](https://scholar.google.com/citations?user=jplQac8AAAAJ&hl=en), [Research Group](http://www.explain-ai.org)
* Wojciech Samek [Google Scholar](https://scholar.google.com/citations?user=7aQwO08AAAAJ&hl=en), [Research Group](http://www.explain-ai.org)
* Sebastian Lapuschkin [Google Scholar](https://scholar.google.de/citations?user=wpLQuroAAAAJ&hl=en), [Web](http://iphome.hhi.de/lapuschkin/), [Github](https://github.com/sebastian-lapuschkin), [Research Group](http://www.explain-ai.org)
* Przemyslaw Biecek [Google Scholar](https://scholar.google.com/citations?user=Af0O75cAAAAJ&hl=en), [Github](https://github.com/pbiecek/), [Research Group](https://mi2-warsaw.github.io/)
* Cecilia Panigutti [Google Scholar](https://scholar.google.com/citations?user=5ILF8RgAAAAJ&hl=en), [Web](https://kdd.isti.cnr.it/people/panigutti-cecilia), [Github](https://github.com/CeciPani), [Research Group](https://kdd.isti.cnr.it/) 
* Lior Wolf [Google Scholar](),
* Tim Miller[Google Scholar](),
* Riccardo Guidotti [Google Scholars](https://scholar.google.it/citations?user=KZUaK6YAAAAJ&hl=en), [Web](https://kdd.isti.cnr.it/people/guidotti-riccardo), [Github](https://github.com/riccotti), [Research Group](https://kdd.isti.cnr.it/) 
* Fosca Giannotti [Google Scholars](https://scholar.google.com/citations?user=PKz_a_AAAAAJ&hl=en), [Web](http://kdd.isti.cnr.it/homes/giannotti), [Research Group](https://kdd.isti.cnr.it/) 



