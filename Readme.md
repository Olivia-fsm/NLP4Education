# ***Literature Review:*** NLP for Education 

## NLP Tasks/Keywords
- Summarization
- Simplification
- Question Answering
- Question Generation
    - Free-answer Question
        - Factoid Question
        - Causal Question
    - MCQ
- Retrieval
- Domain-specific
- Second-language Learning
- Writing Assessment
- Grammar/Spelling Error Correction
- Peer Review
- Dialogue
- Interactive Evaluation
- Active Learning

### Category by Task


| T1-Extraction | T2-AbsSummarization | T3-Simplification | T4-Enrichment | T5-Negation |
| ------------- | ------------------- | ----------------- | ------------- | ----------- |
|               |                     |                   |               |             |
| Text          | Text                | Text              |               |             |

### Categorized by Domain


| Language | Scientific | Math | Not-Specified    |
| -------- | ---------- | ---- | ---------------- |
|          |            |      |     |
|          |            |      |     |



## Previous Special-Topic Samples
**[Including Signed Languages in Natural Language Processing](https://aclanthology.org/2021.acl-long.570.pdf)**
*Kayo Yin, Amit Moryossef, Julie Hochgesang, Yoav Goldberg, Malihe Alikhani*
***[ACL-2021]***

**[Towards Faithfully Interpretable NLP Systems: How should we define and evaluate faithfulness?](https://aclanthology.org/2020.acl-main.386.pdf)**
*Alon Jacovi, Yoav Goldberg*
***[ACL-2020]***


## Survey Paper
[**A Review on Question Generation from Natural Language Text**](https://dl.acm.org/doi/pdf/10.1145/3468889)
*Ruqing Zhang, Jiafeng Guo, Lu Chen, Yixing Fan, Xueqi Cheng*
***[ACM Transactions on Information Systems, 2021]***

[**Automatic question generation and answer assessment: a survey**](https://telrp.springeropen.com/articles/10.1186/s41039-021-00151-1)
*Bidyut Das, Mukta Majumder, Santanu Phadikar, Arif Ahmed Sekh*
***[Research and Practice in Technology Enhanced Learning-2021]***

[**A Systematic Review of Automatic Question Generation for Educational Purposes**](https://link.springer.com/content/pdf/10.1007/s40593-019-00186-y.pdf) 
*Ghader Kurdi, Jared Leo, Bijan Parsia, Uli Sattler, Salam Al-Emari*
***[International Journal of Artificial Intelligence in Education-2020]***

[**Putting Humans in the Natural Language Processing Loop: A Survey**](https://aclanthology.org/2021.hcinlp-1.8/)
*Zijie J. Wang, Dongjin Choi, Shenyu Xu, Diyi Yang*
***[EACL-2021]***

## Dataset & Benchmark
[**Scisummnet: A large annotated corpus and content-impact models for scientific paper summarization with citation networks**](https://arxiv.org/abs/1909.01716) 
*Michihiro Yasunaga, Jungo Kasai, Rui Zhang, Alexander R Fabbri, Irene Li, Dan Friedman, and Dragomir R Radev*
***[AAAI-2019]***

[**What Should I Learn First: Introducing LectureBank for NLP Education and Prerequisite Chain Learning**](https://ojs.aaai.org//index.php/AAAI/article/view/4638)
*Irene Li, Alexander R. Fabbri, Robert R. Tung, Dragomir R. Radev*
***[AAAI-2019]*** [[dataset](https://github.com/Yale-LILY/LectureBank)]

**[Multi-Task Identification of Entities, Relations, and Coreference for Scientific Knowledge Graph Construction](https://aclanthology.org/D18-1360/)**
*Yi Luan, Luheng He, Mari Ostendorf, Hannaneh Hajishirzi*
***[EMNLP-2018]***

**[LearningQ: A Large-Scale Dataset for Educational Question Generation](https://www.semanticscholar.org/paper/LearningQ:-A-Large-Scale-Dataset-for-Educational-Chen-Yang/b9c859e211e36849cc8bc3a41bc2d7dc28eb84cd)**
*Guanliang Chen, Jie Yang, G. Houben*
***[ICWSM-2018]*** [[code](https://github.com/AngusGLChen/LearningQ)]

## Educational Taxonomy
Evaluating the quality of learning: The SOLO taxonomy (Structure of the Observed Learning Outcome).

Taxonomy of educational objectives

# Categorize by Purpose
## Assist Human Reading Comprehension
[1976] [Automatic question generation from text—An aid to independent study](https://dl.acm.org/doi/10.1145/800107.803459)
    --- [*Improve independent study of reading materials]

[2009] [Generating Instruction Automatically for the Reading Strategy of Self-Questioning](https://www.semanticscholar.org/paper/Generating-Instruction-Automatically-for-the-of-Mostow-Chen/0e0d47e73f9f0e59024078db966470c2d4483b72) 
    ---[**mention Reading Strategy*] 

[2017] [Learning to Ask: Neural Question Generation for Reading Comprehension](https://aclanthology.org/P17-1123/) 
    --- [*Seq2Seq*]
    
[Difficulty controllable question generation for reading comprehension](https://arxiv.org/abs/1807.03586)
> Difficulty-controllable Question Generation (DQG)


[2020] [Exploring Artificial Jabbering for Automatic Text Comprehension Question Generation](https://www.semanticscholar.org/paper/Exploring-Artificial-Jabbering-for-Automatic-Text-Steuer-Filighera/aa9ff171f2ff169a05076d26dc28e0af519d35c3)
> **Flaw Analysis** on existing AQG for promote reading comprehension


[2021] [***preprint***] [I Do Not Understand What I Cannot Define: Automatic Question Generation With Pedagogically-Driven Content Selection](https://www.semanticscholar.org/paper/I-Do-Not-Understand-What-I-Cannot-Define%3A-Automatic-Steuer-Filighera/a0fd69c2540158fe79ff8cdba3d36a71e737211a)
> The  paper  introduces  a  novel  **pedagogically  meaningful content  selection  mechanism**  to  find  question-worthy  sentencesand  answers  in  arbitrary  textbook  contents.  We  conducted  an empirical  evaluation  study  with  educational  experts,  annotating 150 generated questions in six different domains. Results indicatea high linguistic quality of the generated questions. Furthermore, the  evaluation  results  imply  that  the  majority  of  the  generated questions inquire central information related to the given text and may  foster  text  comprehension  in  specific  learning  scenarios.




## Writing Support
[2012] [G-Asks: An Intelligent Automatic Question Generation System for Academic Writing Support](https://www.semanticscholar.org/paper/G-Asks:-An-Intelligent-Automatic-Question-System-Liu-Calvo/64403390bdd1c72cffba1fb4d9db742df63384ea)
> This is the **first project**, to our knowledge, that contributes a system for **generating content-specific questions that support writing**. 
> *[When students are asked to write a literature review or an essay, the purpose is often not only to
develop disciplinary communication skills, but also to learn and reason from multiple documents. This involves skills such as sourcing (i.e., citing sources as evidence to support arguments) and information integration (i.e., presenting the evidence in a cohesive and persuasive way).]*



## Knowledge Acquisition & Active Learning
[1998] [Learning concepts by asking questions](https://www.semanticscholar.org/paper/LEARNING-CONCEPTS-BY-ASKING-QUESTIONS-Sammut-Banerji/b2e3e096c613f49bcaca3ce9baf019621eea7ff8)
> Marvin, which **uses concepts it has learned previously to learn new concepts**. The program forms hypotheses about the concept being learned and tests the hypotheses by asking the trainer questions. Learning begins when the trainer shows Marvin an example of the concept to be learned. The program determines which objects in the example belong to concepts stored in the memory. A description of the new concept is formed by using the information obtained from the memory to generalize the description of the training example.

[2017] [Question generation for language learning: From ensuring texts are read to supporting learning.](https://aclanthology.org/W17-5038/)
> we want to broaden the perspective on the different functions questions can play in FLTL and discuss **how automatic question generation can support the different uses**. We **discuss two types of questions serving this purpose**, how they can be generated automatically; and we report on a crowd-sourcing evaluation comparing automatically generated to manually written questions targeting particle verbs, a challenging linguistic form for learners of English.



## Knowledge Assessment
[2006][FAST: An automatic generation system for grammar tests](https://aclanthology.org/P06-4001/)
> ***manually-designed patterns, Grammar Test***

[2010] [Good Question! Statistical Ranking for Question Generation](https://aclanthology.org/N10-1086/)
> Overgenerate and Ranking by a **binary logistic classifier(?)**

[2012] [Generating Grammar Exercises](https://www.semanticscholar.org/paper/Generating-Grammar-Exercises-Perez-Beltrachini-Gardent/55764527c23884152df9e35b67adea78aaba7190)
> Language Learning

[2013] [Discriminative Approach to Fill-in-the-Blank Quiz Generation for Language Learners](https://aclanthology.org/P13-2043/)

[2016] [Automatic generation of short answer questions for reading comprehension assessment](https://www.semanticscholar.org/paper/Automatic-generation-of-short-answer-questions-for-Huang-He/8e6a476fe9c1fcbff96499fb28a50117ee285294)

[2017] [Automatic Generation of English Reference Question by Utilising Nonrestrictive Relative Clause](https://pdfs.semanticscholar.org/0ed4/9ef7d10d7324e1e076fb8e11ed0202328bc6.pdf)


[2017] [Factual open cloze question generation for assessment of learner’s knowledge](https://educationaltechnologyjournal.springeropen.com/articles/10.1186/s41239-017-0060-3#citeas)
> **automatic factual open cloze question generation system** ; The sentences are considered as informative based on **part-of-speech tags and certain rules**.

[1999] [A web-based system for automatic language skill assessment: Evaling](https://aclanthology.org/W99-0410/)
> Linguistic Exercise Design for Native French Language Assessment

[2018] [Compiling Questions into Balanced Quizzes about Documents](https://dl.acm.org/doi/10.1145/3269206.3269298)



## Instruction/Feedback Generation


## Adaptive Learning
[**Question Generation for Adaptive Education**](https://aclanthology.org/2021.acl-short.88.pdf)
*Megha Srivastava, Noah Goodman*
***[ACL-2021]***

[2018] [Learning to Automatically Generate Fill-In-The-Blank Quizzes](https://aclanthology.org/W18-3722/)

## MATH
[2017] [Intelligent Math Tutor: Problem-Based Approach to Create Cognizance](https://www.semanticscholar.org/paper/Intelligent-Math-Tutor:-Problem-Based-Approach-to-Gupta-Gantayat/9ea420d1a2a88b6bc1d86c1b09753fe20349aaa0)
> we built a tool called Intelligent Math Tutor (IMT), which **automatically generates mathematical word problems** such that teachings from other subjects from a given curriculum can also be incorporated. 
> our tool is the first of its kind tool which **explicitly blends knowledge from multiple dissociated subjects** and uses it to enhance the cognizance of its learners.

## Programming
[On the Use of Semantic-Based AIG to Automatically Generate Programming Exercises](https://dl.acm.org/doi/10.1145/3159450.3159608)


## NO PARTICULAR EDUCATIONAL PURPOSE
[2011] [Automatic Question Generation using Discourse Cues](https://www.semanticscholar.org/paper/Automatic-Question-Generation-using-Discourse-Cues-Agarwal-shah/3ceb9bc0dd1056257e3b2002cb6fd5b81ae1e54c)
> we present a system that automatically generates questions from natural language text **using discourse connectives**. We explore the usefulness of the discourse connectives for Question Generation (QG) that looks at the problem beyond sentence level. Our work divides the QG task into content selection and question formation. Content selection consists of finding the relevant part in text to frame question from while question formation involves sense disambiguation of the discourse connectives, identification of question type and applying syntactic transformations on the content. The system is evaluated manually for syntactic and semantic correctness.

[2016] [Infusing NLU into Automatic Question Generation](https://aclanthology.org/W16-6609.pdf)

[Deep Questions without Deep Understanding](https://www.semanticscholar.org/paper/Deep-Questions-without-Deep-Understanding-Labutov-Basu/a04cc4321dd221ed5056174c60c7ab074e573a4f)
> ontologycrowd-relevance workflow, consisting of
first representing the original text in a
low-dimensional ontology, then crowdsourcing candidate question templates aligned with that space, and finally ranking potentially relevant templates for a
novel region of text. 

[2018] [Answer-focused and Position-aware Neural Question Generation](https://aclanthology.org/D18-1427/)

[2018] [Paragraph-level neural question generationwith maxout pointer and gated self-attention networks](https://aclanthology.org/D18-1424/)

[2019] [**Key Phrase Extraction for Generating Educational Question-Answer Pairs**](https://cs.stanford.edu/people/ebrun/papers/Keyphrase_for_education.pdf)
***[Proceedings of the Sixth ACM Conference on Learning @ Scale-2019]***
> Generate Keyphrase as the candidates first, then generate question. No particular evaluation of educational value.


[**Automatically Generating Cause-and-Effect Questions from Passages.**](https://aclanthology.org/2021.bea-1.17/)
*Katherine Stasaski, Manav Rathod, Tony Tu, Yunfang Xiao, and Marti A. Hearst.*
***[ACL-2021]***
> We build a **pipeline that extracts causal
relations** from passages of input text, and feeds
these as input to a state-of-the-art neural question generator. The extractor is based on prior work that classifies causal relations by linguistic category. This work results in a new, publicly available ***collection of cause-and-effect questions***

**[Improving Question Generation With to the Point Context](https://aclanthology.org/D19-1317.pdf)**
*Jingjing Li, Yifan Gao, Lidong Bing, Irwin King, Michael R. Lyu.*
***[EMNLP-2019]***

<!-- [**Curio SmartChat : A system for Natural Language Question Answering for Self-Paced K-12 Learning**](https://www.semanticscholar.org/paper/Curio-SmartChat-:-A-system-for-Natural-Language-for-Raamadhurai-Baker/8cdb4514340b36993d06ca022fbfaf9e2f63123e)
*Srikrishna Raamadhurai, R. Baker, Vikraman Poduval*
***[BEA@ACL-2019]*** -->


**[Harvesting paragraph-level question-answer pairs from wikipedia](https://aclanthology.org/P18-1177/)**
*Xinya Du, Claire Cardie*
***[ACL-2018]***

**[Leveraging Context Information for Natural Question Generation](https://aclanthology.org/N18-2090/)**
*Linfeng Song, Zhiguo Wang, Wael Hamza, Yue Zhang, Daniel Gildea*
***[ACL-2018]***

***[Paragraph-level Neural Question Generation with Maxout Pointer and Gated Self-attention Networks](https://aclanthology.org/D18-1424/)***
*Yao Zhao, Xiaochuan Ni, Yuanyuan Ding, Qifa Ke*
***[EMNLP-2018]***

***[Capturing Greater Context for Question Generation](https://arxiv.org/abs/1910.10274)***
*Luu Anh Tuan, Darsh J Shah, Regina Barzilay*
***[AAAI-2020]***

**[How to Ask Good Questions? Try to Leverage Paraphrases](https://aclanthology.org/2020.acl-main.545/)**
*Xin Jia, Wenjie Zhou, Xu SUN, Yunfang Wu*
***[ACL-2020]***

**[PathQG: Neural Question Generation from Facts](https://aclanthology.org/2020.emnlp-main.729/)**
*Siyuan Wang, Zhongyu Wei, Zhihao Fan, Zengfeng Huang, Weijian Sun, Qi Zhang, Xuanjing Huang*
***[EMNLP-2020]***

**[Joint Passage Ranking for Diverse Multi-Answer Retrieval](https://aclanthology.org/2021.emnlp-main.560.pdf)**
*Sewon Min, Kenton Lee, Ming-Wei Chang, Kristina Toutanova and Hannaneh Hajishirzi*
***[EMNLP-2021]***

**[Improving Unsupervised Question Answering via Summarization-Informed Question Generation](https://aclanthology.org/2021.emnlp-main.340/)**
*Chenyang Lyu, Lifeng Shang, Yvette Graham, Jennifer Foster, Xin Jiang and Qun Liu*
***[EMNLP-2021]***

**[Asking It All: Generating Contextualized Questions for any Semantic Role](https://aclanthology.org/2021.emnlp-main.108.pdf)**
*Valentina Pyatkin, Paul Roit, Julian Michael, Yoav Goldberg, Reut Tsarfaty and Ido Dagan*
***[EMNLP-2021]***

**[Perhaps PTLMs Should Go to School – A Task to Assess Open Book and Closed Book QA](https://openreview.net/pdf?id=vtZzRb1471-)**
*Manuel Ciosici, Joe Cecil, Dong-Ho Lee, Alex Hedges, Marjorie Freedman and Ralph Weischedel*
***[EMNLP-2021]***


[**Distractor Analysis and Selection for Multiple-Choice Cloze Questions for Second-Language Learners**](https://aclanthology.org/2020.bea-1.10/)
*Lingyu Gao, Kevin Gimpel and Arnar Jensson.*
***[BEA@ACL-2021]***

[**Automatic Distractor Generation for Multiple Choice Questions in Standard Tests**](https://aclanthology.org/2020.coling-main.189.pdf)
*Zhaopeng Qiu, Xian Wu*
***[CoLing-2020]***

[**Predicting the Difficulty and Response Time of Multiple Choice Questions Using Transfer Learning**](https://aclanthology.org/2020.bea-1.20/)
*Kang Xue, Victoria Yaneva, Christopher Runyon and Peter Baldwin.*
***[BEA@ACL-2020]***

[**On the Application of Transformers for Estimating the Difficulty of Multiple-choice Questions from Text**](https://aclanthology.org/2021.bea-1.16/)
*Luca Benedetto, Giovanni Aradelli, Paolo Cremonesi, Andrea Cappelli,Andrea Giussani, and Roberto Turrin.*
***[BEA@ACL-2020]***

[**Using Linguistic Features to Predict the Response Process Complexity Associated with Answering Clinical MCQs**](https://aclanthology.org/2021.bea-1.23/)
*Victoria Yaneva, Daniel Jurich, Le An Ha, and Peter Baldwin.*
***[BEA@ACL-2021]***

[**When Retriever-Reader Meets Scenario-Based Multiple-Choice Questions**](https://aclanthology.org/2021.findings-emnlp.84/)
*ZiXian Huang, Ao Wu, Yulin Shen, Gong Cheng and Yuzhong Qu*
***[EMNLP-2021]***

[**GooAQ: Open Question Answering with Diverse Answer Types**](https://www.semanticscholar.org/paper/GooAQ%3A-Open-Question-Answering-with-Diverse-Answer-Khashabi-Ng/0a36cbfb05e60758d49aa10685460ed9afd96977)
*Daniel Khashabi, Amos Ng, Tushar Khot, Ashish Sabharwal, Hannaneh Hajishirzi and Chris Callison-Burch*
***[EMNLP-2021]***


---


### Distractor Generation 
**[Distractor Generation for Multiple Choice Questions Using Learning to Rank](https://aclanthology.org/W18-0533/)**
*Chen Liang, Xiao Yang, Neisarg Dave, Drew Wham, Bart Pursel, C. Lee Giles*
***[NAACL-2018]***

# Evaluation
[2016] [How do machine-generated questions compare to human-generated questions?](https://telrp.springeropen.com/articles/10.1186/s41039-016-0031-7)
> Bio-domain Question generation evaluation. Result shows no difference from AQG and human-generated question


[2017] [Evaluation of automatically generated pronoun reference questions](https://aclanthology.org/W17-5008/)
> Pronoun reference questions are multiple choice questions that ask test takers to choose an antecedent of a target pronoun in a reading passage from four options. The evaluation was performed from two perspectives: the perspective of English teachers and that of English learners. Item analysis suggests that **machine-generated questions achieve comparable quality with human-made questions**. Correlation analysis revealed a strong correlation between the scores of machine-generated questions and that of human-made questions.

## Difficulty Controllability
[2016] [Item Difficulty Analysis of English Vocabulary Questions](https://www.semanticscholar.org/paper/Item-Difficulty-Analysis-of-English-Vocabulary-Susanti-Nishikawa/e1e261a17db59bf9385d6db002cdbf79b7846946)





# Advanced Subtask Formulation
## Conversation/Feedback Generation
[2020] [Review-based question generation with adaptive instance transfer and augmentation](https://aclanthology.org/2020.acl-main.26/)

[2020] [Generating clarifying questions in conversational search systems] (https://dl.acm.org/doi/10.1145/3340531.3418513)

## QA/QG as Interpretability Tool
[2020] [Asking and answering questions to evaluate the factual consistency of summaries](https://aclanthology.org/2020.acl-main.450.pdf)


## Knoledge Graph 
[2017] [Knowledge Questions from Knowledge Graphs](https://dl.acm.org/doi/abs/10.1145/3121050.3121073)

## Extractive Summarization
**[The Effect of Pretraining on Extractive Summarization for Scientific Documents](https://aclanthology.org/2021.sdp-1.9/)**
*Yash Gupta, Pawan Sasanka Ammanamanchi, Shikha Bordia, Arjun Manoharan, Deepak Mittal, Ramakanth Pasunuru, Manish Shrivastava, Maneesh Singh, Mohit Bansal, Preethi Jyothi*
***[NAACL-2021]***

## Simplification
[**Metaphors in Text Simplification: To change or not to change, that is the question.**](https://aclanthology.org/W19-4444/)
*Yulia Clausen and Vivi Nastase.*
***[BEA@ACL-2019]***

[**Text Simplification by Tagging.**](https://arxiv.org/abs/2103.05070)
*Kostiantyn Omelianchuk, Vipul Raheja, and Oleksandr Skurzhanskyi.*
***[EACL-2021]*** [[code](https://github.com/grammarly/gector)]

[**Interpreting Neural CWI Classifiers’ Weights as Vocabulary Size**](https://aclanthology.org/2020.bea-1.17/)
*Yo Ehara.*
***[BEA@ACL-2020]***

## Content Enrichment
[**An Empirical Investigation of Neural Methods for Content Scoring of Science Explanations**](https://aclanthology.org/2020.bea-1.13/)
*Brian Riordan, Sarah Bichler, Allison Bradford, Jennifer King Chen, Korah Wiley, Libby Gerard and Marcia C. Linn.*
***[BEA@ACL-2020]***

## Arguement Mining
[**"Sharks are not the threat humans are": Argument Component Segmentation in School Student Essays.**](https://arxiv.org/abs/2103.04518)
*Tariq Alhindi and Debanjan Ghosh.*
***[EACL-2021]***

## Domain Knowledge
[**Equipping Educational Applications with Domain Knowledge.**](https://aclanthology.org/W19-4448.pdf)
*Tarek Sakakini, Hongyu Gong, Jong Yoon Lee, Robert Schloss, JinJun Xiong and Suma Bhat.*
***[BEA@ACL-2019]***
[[dataset](http://bit.ly/dexter-dataset-acl)]

[**Training and Domain Adaptation for Supervised Text Segmentation.**](https://aclanthology.org/2021.bea-1.11/)
*Goran Glavaš, Ananya Ganesh, and Swapna Somasundaran.*
***[EACL-2021]***

## Error Generation
[**Artificial Error Generation with Fluency Filtering.**](https://aclanthology.org/W19-4408/)
*Mengyang Qiu and Jungyeul Park.*
***[BEA@ACL-2019]***

## Learning Outcome
[**From Receptive to Productive: Learning to Use Confusing Words through Automatically Selected Example Sentences**](https://aclanthology.org/W19-4447/)
*Chieh-Yang Huang, Yi-Ting Huang, Mei-Hua Chen and Lun-Wei Ku.*
***[ACL-2019]***

## Interactive Analysis
[**Virtual Pre-Service Teacher Assessment and Feedback via Conversational Agents**](https://aclanthology.org/2021.bea-1.20/)
*Debajyoti Datta, Maria Phillips, James P. Bywater, Jennifer Chiu, Ginger S. Watson, Laura Barnes, and Donald Brown.*
***[BEA@ACL-2021]***

[**B-Pref: Benchmarking Preference-Based Reinforcement Learning**](https://arxiv.org/abs/2111.03026)
*Kimin Lee, Laura Smith, Anca Dragan, Pieter Abbeel*
***[NeurIPS-2021]***

[**Towards Interactive Language Modeling**](https://maartjeth.github.io/assets/documents/interactive_language_modeling.pdf)
*Maartje ter Hoeve et al.*
***[preprint]***


## Other Generation Tasks
**[Automated curriculum generation through setter-solver interactions](https://openreview.net/forum?id=H1e0Wp4KvH)**
*Sebastien Racaniere, Andrew Lampinen, Adam Santoro, David Reichert, Vlad Firoiu, Timothy Lillicrap*
***[ICLR-2020]***


# Future Direction
- Difficulty Control
    - [2016-Item Difficulty Analysis of English Vocabulary Questions](https://www.semanticscholar.org/paper/Item-Difficulty-Analysis-of-English-Vocabulary-Susanti-Nishikawa/e1e261a17db59bf9385d6db002cdbf79b7846946)
    - 
- Evaluation
    - [2017-Evaluation of automatically generated pronoun reference questions](https://aclanthology.org/W17-5008/)