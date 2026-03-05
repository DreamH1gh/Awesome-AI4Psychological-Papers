# Awesome-AI4Psychological-Papers

The organization of papers is discussed in our survey: <br>
[From Pre-trained Models to Large Language Models: A Comprehensive Survey of AI-Driven Psychological Computing](https://www.baidu.com/). 

If you find any relevant academic papers that have not been included in our research, please submit a request for an update. We welcome contributions from everyone.

If any suggestions or mistakes, please feel free to let us know via email at **chenhy1018@gmail.com**. We appreciate your feedback and help in improving our work.

If you find our survey useful for your research, please cite the following paper:

    @article{
    }

## 📒 Table of Contents
### 🤖 Tasks
- [AI-driven Psychological Computing Tasks](#ai-driven-psychological-computing-tasks)
    - [Classification & Regression](#classification--regression)
        - [PLM-based Papers](#plm-based-papers)
        - [LLM-based Papers](#llm-based-papers)
    - [Structured Relational](#structured-relational)
        - [PLM-based Papers](#plm-based-papers-1)
        - [LLM-based Papers](#llm-based-papers-1)
    - [Generative & Interactive](#generative--interactive)
        - [PLM-based Papers](#plm-based-papers-2)
        - [LLM-based Papers](#llm-based-papers-2)
### 📊 Datasets
- [Datasets of Tasks](#datasets-of-tasks)
    - [Classification Datasets](#classification-datasets)
    - [Regression Datasets](#regression-datasets)
    - [Structured Relational Datasets](#structured-relational-datasets)
    - [Generative and Interactive Datasets](#generative-and-interactive-datasets)

# AI-driven Psychological Computing Tasks

## Classification & Regression
Classification and regression tasks in psychological computing share common encoding architectures but differ in their output formulations. Classification tasks map inputs to discrete psychological categories through softmax layers, while regression tasks predict continuous severity scores or trait measurements through linear output layers. Both benefit from similar feature extraction strategies and domain adaptation techniques.
### PLM-based Papers

| Paper | Venue | Date |
| :----- | :--------------: | :------- |
| [Latent suicide risk detection on microblog via suicide-oriented word embeddings and layered attention](https://aclanthology.org/D19-1181/) | EMNLP &#124; IJCNLP | 2019-11 |
| [Personality Trait Detection Using Bagged SVM over BERT Word Embedding Ensembles](https://arxiv.org/abs/2010.01309) | arXiv | 2020-10 |
| [Depressionnet: A novel summarization boosted deep framework for depression detection on social media](https://arxiv.org/abs/2105.10878) | arXiv | 2021-05 |
| [Classification of mental illnesses on social media using RoBERTa](https://aclanthology.org/2021.louhi-1.7/) | Louhi | 2021-04 |
| [Towards automatic text-based estimation of depression through symptom prediction](https://link.springer.com/article/10.1186/s40708-023-00185-9) | Brain Informatics | 2023-02 |
| [Personality Prediction from Life Stories using Language Models](https://arxiv.org/abs/2506.19258) | arXiv | 2025-06 |
| [Using a fine-tuned large language model for symptom-based depression evaluation](https://www.nature.com/articles/s41746-025-01982-8) | npj Digital Medicine | 2025-10 |
| [Clinicalbert: Modeling clinical notes and predicting hospital readmission](https://arxiv.org/abs/1904.05342) | arXiv | 2019-04 |
| [BioBERT: a pre-trained biomedical language representation model for biomedical text mining](https://academic.oup.com/bioinformatics/article/36/4/1234/5566506) | Bioinformatics | 2019-09 |
| [PsychBERT: a mental health language model for social media mental health behavioral analysis](https://ieeexplore.ieee.org/document/9669469) | BIBM | 2021-12 |
| [MentalBERT: Publicly Available Pretrained Language Models for Mental Healthcare](https://aclanthology.org/2022.lrec-1.778/) | LREC | 2022-06 |
| [CASE: Efficient Curricular Data Pre-training for Building Assistive Psychology Expert Models](https://aclanthology.org/2024.findings-emnlp.925/) | EMNLP Findings | 2024-11 |
| [Multi-task Learning with Pre-trained Language Models for Mental Illness Screening](https://ieeexplore.ieee.org/abstract/document/10825698) | BigData | 2024-12 |
| [Multi task opinion enhanced hybrid BERT model for mental health analysis](https://www.nature.com/articles/s41598-025-86124-6) | Scientific Reports | 2025-01 |
| [Data Augmentation for Mental Health Classification on Social Media](https://aclanthology.org/2021.icon-main.19/) | ICON | 2021-12 |
| [Multimodal Fusion of BERT-CNN and Gated CNN Representations for Depression Detection](https://dl.acm.org/doi/abs/10.1145/3347320.3357694) | AVEC'19 | 2019-10 |
| [Multi-Modal and Multi-Task Depression Detection with Sentiment Assistance](https://ieeexplore.ieee.org/abstract/document/10444213) | ICCE | 2024-01 |
| [Temporal Multimodal Multitask Attention for Affective State Estimation in a Stressful Environment](https://ieeexplore.ieee.org/document/11195200) | TAFFC | 2025-10 |


### LLM-based Papers

| Paper | Venue | Date |
| :----- | :--------------: | :------- |
| [Validating the use of large language models for psychological text classification](https://www.frontiersin.org/journals/social-psychology/articles/10.3389/frsps.2025.1460277/full) | Frontiers in Social Psychology | 2025-02 |
| [Assessing the accuracy and consistency of large language models in triaging social media posts for psychological distress](https://www.sciencedirect.com/science/article/pii/S0165178125002318) | Psychiatry Research | 2025-09 |
| [Leveraging large language models for automated depression screening](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000943) | PLOS Digital Health | 2025-07 |
| [Systematic Evaluation of GPT-3 for Zero-Shot Personality Estimation](https://aclanthology.org/2023.wassa-1.34/) | WASSA | 2023-07 |
| [Large language models can infer psychological dispositions of social media users](https://academic.oup.com/pnasnexus/article/3/6/pgae231/7692212?login=false) | PNAS nexus | 2024-06 |
| [Large language models can infer personality from free-form user interactions](https://arxiv.org/abs/2405.13052) | arXiv | 2024-05 |
| [Investigating Large Language Models in Inferring Personality Traits from User Conversations](https://arxiv.org/abs/2501.07532) | arXiv | 2025-01 |
| [Decoding substance use disorder severity from clinical notes using a large language model](https://www.nature.com/articles/s44184-024-00114-6) | npj mental health research | 2025-02 |
| [GPT-4 shows potential for identifying social anxiety from clinical interview data](https://www.nature.com/articles/s41598-024-82192-2) | Scientific Reports | 2024-12 |
| [LlaMADRS: Prompting Large Language Models for Interview-Based Depression Assessment](https://arxiv.org/abs/2501.03624) | arXiv | 2025-01 |
| [Cognitive-Mental-LLM: Evaluating Reasoning in Large Language Models for Mental Health Prediction via Online Text](https://arxiv.org/abs/2503.10095) | arXiv | 2026-01 |
| [ExDoRA: enhancing the transferability of large language models for depression detection using free-text explanations](https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1564828/full) | Frontiers in Artificial Intelligence | 2025-05 |
| [Cascade Large Language Model via In-Context Learning for Depression Detection on Chinese Social Media](https://link.springer.com/chapter/10.1007/978-981-97-8487-5_25) | PRCV | 2024-11 |
| [XAI4LLM. Let Machine Learning Models and LLMs Collaborate for Enhanced In-Context Learning in Healthcare](https://arxiv.org/abs/2405.06270) | arXiv | 2025-07 |
| [Large language model performance versus human expert ratings in automated suicide risk assessment](https://arxiv.org/abs/1909.03193) | Scientific Reports | 2025-11 |
| [Leveraging Large Language Models for Digital Phenotyping: Detecting Depressive State Changes for Patients with Depressive Episodes](https://www.medrxiv.org/content/10.1101/2025.05.10.25327354v1.full.pdf) | medRxiv | 2025-05 |
| [Detecting neuropsychiatric fluctuations in Parkinson’s Disease using patients’ own words: the potential of large language models](https://www.nature.com/articles/s41531-025-00939-8) | npj parkinson's disease | 2025-04 |
| [Advancing Mental Health Pre-Screening: A New Custom GPT for Psychological Distress Assessment](https://ieeexplore.ieee.org/document/10835572) | CogMI | 2024-10 |
| [Explainable and Interactive LLMs-Augmented Depression Detection in Social Media](https://ieeexplore.ieee.org/abstract/document/11142667) | TCSS | 2025-08 |
| [Zero-shot Explainable Mental Health Analysis on Social Media by Incorporating Mental Scales](https://dl.acm.org/doi/10.1145/3589335.3651584) | WWW | 2024-05 |
| [Improving Alignment Between Human and Machine Codes: An Empirical Assessment of Prompt Engineering for Construct Identification in Psychology](https://arxiv.org/abs/2512.03818) | arXiv | 2025-12 |
| [Automating PTSD Diagnostics in Clinical Interviews: Leveraging Large Language Models for Trauma Assessments](https://aclanthology.org/2024.sigdial-1.55/) | SIGDIAL | 2024-09 |
| [PsyCoT: Psychological Questionnaire as Powerful Chain-of-Thought for Personality Detection](https://aclanthology.org/2023.findings-emnlp.216/) | EMNLP Findings | 2023-12 |
| [Empowering Psychotherapy with Large Language Models: Cognitive Distortion Detection through Diagnosis of Thought Prompting](https://aclanthology.org/2023.findings-emnlp.284/) | EMNLP Findings | 2023-12 |
| [Copiloting Diagnosis of Autism in Real Clinical Scenarios via LLMs](https://arxiv.org/abs/2410.05684) | arXiv | 2024-10 |
| [LLM-based semantic integration of stimulus–response pairs for depression detection in interview scenarios](https://www.sciencedirect.com/science/article/abs/pii/S0957417425037273) | EXPERT SYST APPL | 2026-03 |
| [Delving into the Depths: Evaluating Depression Severity through BDI-biased Summaries](https://aclanthology.org/2024.clpsych-1.2/) | CLPsych &#124; WS | 2024-03 |
| [Can Large Language Models Understand You Better? An MBTI Personality Detection Dataset Aligned with Population Traits](https://aclanthology.org/2025.coling-main.339/) | COLING | 2025-01 |
| [Mental-LLM: Leveraging Large Language Models for Mental Health Prediction via Online Text Data](https://dl.acm.org/doi/abs/10.1145/3643540) | IMWUT | 2024-03 |
| [Advancing depression detection on social media platforms through fine-tuned large language models](https://www.sciencedirect.com/science/article/abs/pii/S2468696425000126) | OSNEM | 2025-05 |
| [Systematic Evaluation of Machine-Generated Reasoning and PHQ-9 Labeling for Depression Detection Using Large Language Models](https://arxiv.org/abs/2505.17119) | arXiv | 2025-05 |
| [Predicting the Big Five Personality Traits in Chinese Counselling Dialogues Using Large Language Models](https://arxiv.org/abs/2406.17287) | arXiv | 2024-06 |
| [Zero-Shot Speech-Based Depression and Anxiety Assessment with LLMs](https://www.isca-archive.org/interspeech_2025/loweimi25_interspeech.pdf) | Interspeech | 2025-08 |
| [Traits Run Deep: Enhancing Personality Assessment via Psychology-Guided LLM Representations and Multimodal Apparent Behaviors](https://dl.acm.org/doi/10.1145/3746027.3762017) | MM | 2025-10 |

## Structured Relational

### PLM-based Papers

| Paper | Venue | Date |
| :----- | :--------------: | :------- |
| [Psycholinguistic Tripartite Graph Network for Personality Detection](https://aclanthology.org/2021.acl-long.326/) | ACL &#124; IJCNLP | 2021-08 |
| [Orders Are Unwanted: Dynamic Deep Graph Convolutional Network for Personality Detection](https://ojs.aaai.org/index.php/AAAI/article/view/26627) | AAAI | 2023-06 |
| [Building High-quality Psychology Knowledge Graphs from Text using REBEL](https://eudl.eu/doi/10.4108/eai.29-3-2024.2347315) | ICBBEM | 2024-06 |
| [KG-BERT: BERT for knowledge graph completion](https://arxiv.org/abs/1909.03193) | arXiv | 2019-09 |
| [A Painting Psychoanalysis Method Based on Image Caption and Knowledge Graph Reasoning](https://ieeexplore.ieee.org/document/11178550) | CCC | 2025-07 |

### LLM-based Papers

| Paper | Venue | Date |
| :----- | :--------------: | :------- |
| [Modeling Network Formation with LLM Agents: The Role of Demographics and Personality](https://www.cse.uoi.gr/~tsap/publications/AI4CSS-ICDM-2025.pdf) | AI4CSS-ICDM Workshop | 2025-11 |
| [Learning to Make Friends: Coaching LLM Agents toward Emergent Social Ties](https://arxiv.org/abs/2510.19299) | arXiv | 2025-10 |
| [Cognitive networks highlight differences and similarities in the STEM mindsets of human and LLM-simulated trainees, experts and academics](https://arxiv.org/abs/2502.19529) | arXiv | 2025-02 |
| [Feature Activated Dual-Perspective Heterogeneous Network for User Psychological Profiling Analysis](https://ieeexplore.ieee.org/document/11201176) | ISI | 2025-07 |
| [NetworkGames: Simulating Cooperation in Network Games with Personality-driven LLM Agents](https://arxiv.org/abs/2511.21783) | arXiv | 2025-11 |
| [AI-Enhanced Cognitive Behavioral Therapy: Deep Learning and Large Language Models for Extracting Cognitive Pathways from Social Media Texts](https://arxiv.org/abs/2404.11449) | arXiv | 2024-04 |
| [Psychological Counseling with Integration of Knowledge Graph and Multi-Agent Collaboration](https://link.springer.com/article/10.1007/s12204-024-2785-1) | Others | 2024-12 |
| [LLM-Based Prior Elicitation for Bayesian Graphical Modeling](https://osf.io/preprints/psyarxiv/k2twq_v1) | PsyArXiv | 2025-09 |
| [Automating psychological hypothesis generation with AI: when large language models meet causal graph](https://arxiv.org/abs/1909.03193) | Humanit Soc Sci Commun | 2024-07 |
| [Deconstructing Depression Stigma: Integrating AI-driven Data Collection and Analysis with Causal Knowledge Graphs](https://dl.acm.org/doi/10.1145/3706598.3714255) | CHI | 2025-04 |
| [Large language model powered knowledge graph construction for mental health exploration](https://www.nature.com/articles/s41467-025-62781-z) | Nature Communications | 2025-08 |
| [EvolvTrip: Enhancing Literary Character Understanding with Temporal Theory-of-Mind Graphs](https://arxiv.org/abs/2506.13641) | arXiv | 2025-06 |
| [RELATE-Sim: Leveraging Turning Point Theory and LLM Agents to Predict and Understand Long-Term Relationship Dynamics through Interactive Narrative Simulations](https://arxiv.org/abs/2510.00414) | arXiv | 2025-10 |
| [Teaching According to Students' Aptitude: Personalized Mathematics Tutoring via Persona-, Memory-, and Forgetting-Aware LLMs](https://arxiv.org/abs/2511.15163) | arXiv | 2025-11 |
| [Personality-guided Public-Private Domain Disentangled Hypergraph-Former Network for Multimodal Depression Detection](https://arxiv.org/abs/2511.12460) | AAAI | 2025-11 |
| [Reasoning Like Experts: Leveraging Multimodal Large Language Models for Drawing-based Psychoanalysis](https://dl.acm.org/doi/10.1145/3746027.3755744) | MM | 2025-10 |
| [Teaching According to Students' Aptitude: Personalized Mathematics Tutoring via Persona-, Memory-, and Forgetting-Aware LLMs](https://arxiv.org/abs/2511.15163) | AAAI Workshop | 2025-11 |

## Generative & Interactive

### PLM-based Papers

| Paper | Venue | Date |
| :----- | :--------------: | :------- |
| [Mental health question and answering system based on Bert model and knowledge graph technology](https://dl.acm.org/doi/10.1145/3500931.3501011) | ISAIMS | 2021-12 |
| [Knowledge Enhanced Reflection Generation for Counseling Dialogues](https://aclanthology.org/2022.acl-long.221/) | ACL | 2022-05 |
| [GREEN: Generative Retrieval-Enhanced Emotional Support Conversations](https://journals.sagepub.com/doi/10.1177/21582440251395922) | Sage Open | 2025-11 |
| [EmpBot: A T5-based Empathetic Chatbot focusing on Sentiments](https://arxiv.org/abs/2111.00310) | arXiv | 2021-10 |
| [Conversational Bots for Psychotherapy: A Study of Generative Transformer Models Using Domain-specific Dialogues](https://aclanthology.org/2022.bionlp-1.27/) | BioNLP | 2022-05 |
| [Improving mental health support response generation with event-based knowledge graph](https://knowledge-nlp.github.io/aaai2023/papers/006-MHKG-oral.pdf) | psychotherapy | 2023-02 |
| [Artificial Intelligence in Mental Health Care: The T5 Chatbot Project](https://arxiv.org/abs/1909.03193) | SNAMS | 2024-12 |
| [Towards Persona-Based Empathetic Conversational Models](https://aclanthology.org/2020.emnlp-main.531/) | EMNLP | 2020-11 |
| [PAL: Persona-Augmented Emotional Support Conversation Generation](https://aclanthology.org/2023.findings-acl.34/) | ACL Findings | 2023-07 |
| [A Multimodal Affective Interaction Architecture Integrating BERT-Based Semantic Understanding and VITS-Based Emotional Speech Synthesis](https://www.mdpi.com/1999-4893/18/8/513) | Algorithms | 2025-08 |

### LLM-based Papers

| Paper | Venue | Date |
| :----- | :--------------: | :------- |
| [ESCoT: Towards Interpretable Emotional Support Dialogue Systems](https://aclanthology.org/2024.acl-long.723/) | ACL | 2024-08 |
| [Rethinking the Alignment of Psychotherapy Dialogue Generation with Motivational Interviewing Strategies](https://aclanthology.org/2025.coling-main.136/) | COLING | 2025-01 |
| [Cause-Aware Empathetic Response Generation via Chain-of-Thought Fine-Tuning](https://arxiv.org/abs/2408.11599) | arXiv | 2024-08 |
| [MetaMind: Modeling Human Social Thoughts with Metacognitive Multi-Agent Systems](https://arxiv.org/abs/2505.18943) | arXiv | 2025-05 |
| [HealMe: Harnessing Cognitive Reframing in Large Language Models for Psychotherapy](https://aclanthology.org/2024.acl-long.93/) | ACL | 2024-08 |
| [Reframe Your Life Story: Interactive Narrative Therapist and Innovative Moment Assessment with Large Language Models](https://aclanthology.org/2025.emnlp-main.1245/) | EMNLP | 2025-11 |
| [MIND: Towards Immersive Psychological Healing with Multi-Agent Inner Dialogue](https://aclanthology.org/2025.findings-emnlp.499/) | EMNLP | 2025-11 |
| [SweetieChat: A Strategy-Enhanced Role-playing Framework for Diverse Scenarios Handling Emotional Support Agent](https://aclanthology.org/2025.coling-main.312/) | COLING | 2025-01 |
| [Self-chats from Large Language Models Make Small Emotional Support Chatbot Better](https://aclanthology.org/2024.acl-long.611/) | ACL | 2024-08 |
| [Polaris: A Safety-focused LLM Constellation Architecture for Healthcare](https://arxiv.org/abs/2403.13313) | arXiv | 2024-03 |
| [AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling](https://arxiv.org/abs/2501.09426) | arXiv | 2025-01 |
| [MultiAgentESC: A LLM-based Multi-Agent Collaboration Framework for Emotional Support Conversation](https://aclanthology.org/2025.emnlp-main.232/) | EMNLP | 2025-11 |
| [MAGI: Multi-Agent Guided Interview for Psychiatric Assessment](https://arxiv.org/abs/2504.18260) | arXiv | 2025-04 |
| [MENTALER: Toward Professional Mental Health Support with LLMs via Multi-Role Collaboration](https://ieeexplore.ieee.org/abstract/document/10822643) | BIBM | 2024-12 |
| [A Multi-Agent Dual Dialogue System to Support Mental Health Care Providers](https://arxiv.org/abs/2411.18429) | arXiv | 2024-11 |
| [PsychAdapter: adapting LLMs to reflect traits, personality, and mental health](https://www.nature.com/articles/s44387-026-00071-9) | npj Artificial Intelligence | 2026-03 |
| [Leveraging Large Language Models for Simulated Psychotherapy Client Interactions: Development and Usability Study of Client101](https://mededu.jmir.org/2025/1/e68056) | JMIR Medical Education | 2025-07 |
| [Cognitive reframing of negative thoughts through human-language model interaction](https://aclanthology.org/2023.acl-long.555/) | ACL | 2023-07 |
| [Towards Safety and Helpfulness Balanced Responses via Controllable Large Language Models](https://arxiv.org/abs/2404.01295) | arXiv | 2024-04 |
| [Deciphering Cognitive Distortions in Patient-Doctor Mental Health Conversations: A Multimodal LLM-Based Detection and Reasoning Framework](https://aclanthology.org/2024.emnlp-main.1256/) | EMNLP | 2024-11 |
| [Flexible Thinking for Multimodal Emotional Support Conversation via Reinforcement Learning](https://aclanthology.org/2025.findings-emnlp.70/) | EMNLP Findings | 2025-11 |
| [Towards multimodal empathetic response generation: A rich text-speech-vision avatar-based benchmark](https://dl.acm.org/doi/10.1145/3696410.3714739) | WWW | 2025-04 |
| [Reinforcing Trustworthiness in Multimodal Emotional Support Systems](https://arxiv.org/abs/2511.10011) | arXiv | 2025-11 |


## Datasets of Tasks
### Classification Datasets

| Dataset |  Domain  |   Size  | Link | 
|:--------:|:--------:|:--------:| :--------:|
| [Turkish Audio-Visual Bipolar Disorder corpus](https://ieeexplore.ieee.org/abstract/document/8470362)| Bipolar disorder | 352 vedios | [github](https://github.com/DreamH1gh/Awesome-AI4Psychological-Papers/edit/main/README.md) |
| [Tsanas et al.(2016)](https://pubmed.ncbi.nlm.nih.gov/27449555/) | Bipolar disorder | 130 participants | - |
| [Chikersal et al.(2021)](https://pubmed.ncbi.nlm.nih.gov/21102431/) | Depression | 138 participants | - |
| [Jacobson et al.(2021) ](https://pubmed.ncbi.nlm.nih.gov/35030442/) | Anxiety disorders | 32 participants | - |
| [PsySym](https://aclanthology.org/2022.emnlp-main.677.pdf) | Multi-disease | 8,554  sentences | [github](https://github.com/blmoistawinde/EMNLP22-PsySym) |
| [BDI-Sen](https://dl.acm.org/doi/10.1145/3539618.3591905) | Depression | 4,973K  sentences | [html](https://erisk.irlab.org/BDISen.html) |
| [MBTI](https://www.kaggle.com/datasets/datasnaek/mbti-type)| Personality | 8,675 participants | [kaggle](https://www.kaggle.com/datasets/datasnaek/mbti-type) |
| [AMIGOS](https://ieeexplore.ieee.org/document/8554112) | Personality | 40 participants | [html](https://www.eecs.qmul.ac.uk/mmv/datasets/amigos/) | [kaggle](https://www.kaggle.com/datasets/nsut123/amigos-dataset) |
| [MHHRI](https://ieeexplore.ieee.org/document/8003432) | Personality | 18 participants | [html](https://www.cl.cam.ac.uk/research/rainbow/projects/mhhri/dataset.html) |
| [Gómez-Zaragozá et al.(2023)](https://ieeexplore.ieee.org/document/10214624)  | Attachment styles | 199 participants | - |
| [Han et al.(2020)](https://www.sciencedirect.com/science/article/pii/S0950705120300459) | Personality | 400 participants | - |
| [PANDORA](https://aclanthology.org/2021.socialnlp-1.12/) | Personality | 10,288 participants | [html](https://aimagelab.ing.unimore.it/pandora/) |
| [Wang et al.(2021)临床笔记待敲定](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2786292)| Cognitive decline | 4950 sections | - |
| [ADHD-200](https://www.sciencedirect.com/science/article/pii/S105381191630283X) | ADHD subtype | 973 individuals | [html](https://fcon_1000.projects.nitrc.org/indi/adhd200/) |
| [AIBL](https://aibl.org.au/) | AD Progression | 1,112 participants | [html](https://www.aibl.csiro.au/adni/index.html) |
| [Hu et al.(2024)](https://www.sciencedirect.com/science/article/pii/S0165032724010735)| PTSD | 136 participants | - |
| [EATD](https://ieeexplore.ieee.org/abstract/document/9746569) | Depression | 162 participants | [github](https://github.com/speechandlanguageprocessing/ICASSP2022-Depression) | 
| [CLPsych 2015](https://aclanthology.org/W15-1204.pdf) | Depression | 1,746 participants | [github](https://github.com/clpsych/shared_task) |
| [RSDD](https://aclanthology.org/D17-1322.pdf) | Depression | 116,484 participants |[html](https://ir.cs.georgetown.edu/resources/rsdd.html) |
| [SMHD](https://aclanthology.org/C18-1126/) | Multi-disease | 20,406 participants | [html](https://ir.cs.georgetown.edu/resources/smhd.html) |
| [Nikhileswar et al.(2021)](https://ieeexplore.ieee.org/document/9591887)| Suicide, depression | 232k posts| [kaggle](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch) | 
| [DAIC](http://www.lrec-conf.org/proceedings/lrec2014/pdf/508_Paper.pdf) | Distress | 621 interviews | [html](https://dcapswoz.ict.usc.edu/) |
| [GLOBEM](https://physionet.org/content/globem/1.1/) | Depression, anxiety | 705 participants  | [html](https://the-globem.github.io/datasets/overview) |
| [StudentSADD](https://dl.acm.org/doi/10.1145/3534604) | Suicide, depression | 302 participants | [github](https://github.com/mltlachac/StudentSADD) |
| [Gaur et al.(2019)](https://dl.acm.org/doi/10.1145/3308558.3313698) | Suicide | 500 participants | [github](https://github.com/manasgaur/Knowledge-aware-Assessment-of-Severity-of-Suicide-Risk-for-Early-Intervention) |
| [SLOTH](https://dl.acm.org/doi/epdf/10.1145/3643554) | Depression,anxiety | 31 participants | [github](https://github.com/mltlachac/SLOTH) |
| [Petry et al.(2008)](https://pmc.ncbi.nlm.nih.gov/articles/PMC2738749/) | Gambl | 180 participants | - |
| [CLPsych 2016](https://aclanthology.org/W16-0312/) | Post Severity | 1,227 posts | [github](https://github.com/IKBLab/CLPsych2016) |
| [Thomas et al.(2001)](https://www.sciencedirect.com/science/article/pii/S0920996400001092#aep-section-id11) | Social skills | 135 participants | - |
| [Gong et al.(2019)](https://www.sciencedirect.com/science/article/pii/S1566253517307352) | Social anxiety | 52 participants | - |
| [Özpolat et al.(2009)](https://www.sciencedirect.com/science/article/pii/S036013150900061X#sec4) | Learning style | 40 participants | - |
| [Crockett et al.(2017)](https://www.sciencedirect.com/science/article/pii/S107158191630091X) | Learning style | 75 participants | - |
| [Lo et al.(2004)](https://bera-journals.onlinelibrary.wiley.com/doi/10.1111/j.1467-8535.2005.00437.x) | Learning style | 121 participants | - |
| [García et al.(2007)](https://www.sciencedirect.com/science/article/abs/pii/S0360131505001788) | Learning style | 27 participants | - |
| [Wu et al.(2008)](https://www.sciencedirect.com/science/article/abs/pii/S0957417407000619?via%3Dihub)| Learning disabilities | 284 participants | - |

