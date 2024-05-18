# Pipeline Exquis

Pipeline Exquis is an imaginative code experiment carried out by Hina, Megan and Juliet in preparation of the conference [Code as Conversation: Transmedia Dialogues Around Critical Code Studies](https://www.cdh.cam.ac.uk/events/37778/) on 1 June 2024 in Cambridge.

Pipeline Exquis is a machine learning [pipeline](https://en.wikipedia.org/wiki/Pipeline_(computing)) version of [Cadavre Exquis](https://en.wikipedia.org/wiki/Exquisite_corpse) (Exquisite Corpse), the cafe game/surrealist method. [Here](#1-from-cadavre-exquis-to-pipeline-exquis) is described how the Cadavre Exquis is adopted exactly.

In addition to making a Pipeline Exquis for the fun of it (like making a Cadavre Exquis for the fun of it), the experiment was set up to reflect on some theoretical questions relating to ML development. These questions are introduced [here](#2-theoretical-considerations), and a set of relevant terms and concepts is listed up in the [glossary](#glossary).

## 1. From Cadavre Exquis to Pipeline Exquis

In this section, first the process of creating a Cadavre Exquis is described stepwise. Then, the same steps are adopted to match the process of creating an ML pipeline. 

### Cadavre Exquis

In the Cadavre Exquis, a figure is drawn in three parts from top to bottom on a rectangular sheet of paper:
1. Head
2. Upper body
3. Lower body

The creation of the Cadavre Exquis proceeds as follows:
1. Designer1, Designer2, Designer3 and a rectangular piece of paper are collected
2. Designer1:
	1. draws **head** on +/- **upper** 1/3 of paper
	2. folds **head** away such that it can't be seen by Designer2 and Designer3
	3. draws two tick marks of the outlines of the neck, where Designer2 will continue the upper body
3. Designer2:
	1. draws **upper body** on +/- **middle** 1/3 of paper
	2. folds **upper body** away such that it can't be seen by Designer1 and Designer3
	3. draws two tick marks of the outlines of the hips, where Designer3 will continue the lower body
4. Designer3:
	1. draws **lower body** on +/- **lower** 1/3 of paper
5. The paper is unfolded and Designer1, Designer2 and Designer3 admire their collective work.

### Pipeline exquis

In the Pipeline Exquis, a machine learning pipeline is coded in three parts from raw data to deployment in a github repository:
1. Data collection and preprocessing
2. Data modelling
3. Model deployment

The development of the Pipeline Exquis proceeds as follows:
1. Coder1, Coder2, Coder3 are added to github repository
2. Coder1
	1. creates **raw_dataset.csv** and **data_preprocessing.py**
	2. writes preprocessed data to **preprocessed_data.csv** such that it can't be seen by Coder2 and Coder3
	3. writes down information in division_of_labour.md about preprocessed_data.csv with which Coder2 will continue the data modelling
3. Coder2
	1. creates **data_modelling.py**
	2. writes model to **model.csv** such that it can't be seen by Coder1 and Coder3
	3. writes down information in division_of_labour.md about model.csv with which Coder3 will continue the model deployment
4. Coder3
	1. creates **model_deployment.py**
5. All the files are opened and/or the deployment file is run, and Coder1, Coder2 and Coder3 admire their collective work.

## 2. Theoretical considerations

*This was the text I originally submitted for the conference. I'll add to this section later.*

Back in 2018, Crawford and Joler drew attention to the material reality of seemingly immaterial AI systems by mapping out its production process from start to finish. Part of this material reality is the involved labor, not only of developers, but for example also of workers labeling data or users generating feedback data. This has led to concerns such as fair labor conditions for click workers and platform workers, and transparency and privacy protection in collection of user data. What has not been questioned, is the effects of divisions of labor as such on the resulting AI products. **Can we understand the specific configuration of workers (e.g., their amount, their tasks, their material and communicative means) of the AI production process to affect the resulting AI system in any possible (epistemological/ethical/technical) way?** To address this question, I propose an experiment which is inspired by the surrealist method of the _cadavre exquis_. To create a poem or a drawing, a group of artists follows a strict procedure in which one after the other adds their part to the artwork, without communicating with the others or seeing what the others have added before. The result of their work can be considered the expression of the subconscious (as the surrealists did), or simply as fun or nonsensical. For the experiment I propose, I will follow this procedure together with at least two collaborators to produce a "pipeline exquis". During the conference, we will present the pipeline, and take it as a point of reference in which a peculiar, “isolated” configuration of workers is imposed, to reflect on the question at stake.

## 3. Reflection

[ ... ]

## Glossary

*I will add to/modify this section later. Feel free to add as well!*

**Cadavre Exquis**

**Division of labour and labour**

Issues in division of labour have been: "deskilling: the diminsihing of know-how/knowledge in labourers ", and "alienation".

**Labour in production of "AI"**

For labour issues much attention has been drawn to gig workers/click workers/data subjects.

On the other hand, the programmer appears to be a new working class of high-skilled labourers, but that can move between jobs/domains easily.

Divsion of labour on the development side can take place through ticketing/agile scrumboard.

Bits of functionality are bitten off, to be produced.

**Machine learning pipeline**

ML pipelines follow a cannonical structure.

Data / cleaning / preprocessing / exploration / modeling / deployment

**Machine learning pipeline and division of labour**

Combination of clear structure of code, comments, chat, ticketing, testing/code review enables division of labour.  

**The product**

Software is less and less provided as a final end product, instead, it is to receive continuous updates. (How does this generally work in software companies?)

**Code as a cultural product**

Critical code studies.