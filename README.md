# Pipeline Exquis

Pipeline Exquis is an imaginative code experiment carried out by Hina Vuijk, Megan Leal Causton and Juliet van Rosendaal in preparation of the conference [Code as Conversation: Transmedia Dialogues Around Critical Code Studies](https://www.cdh.cam.ac.uk/events/37778/) on 1 June 2024 in Cambridge. This conference is situated in the field of [critical code studies](#glossary).

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

*This was the text originally submitted for applying for the conference.*

Back in 2018, Crawford and Joler drew attention to the material reality of seemingly immaterial AI systems by mapping out its production process from start to finish. Part of this material reality is the involved labor, not only of developers, but for example also of workers labeling data or users generating feedback data. This has led to concerns such as fair labor conditions for click workers and platform workers, and transparency and privacy protection in collection of user data. What has not been questioned, is the effects of divisions of labor as such on the resulting AI products. **Can we understand the specific configuration of workers (e.g., their number, their tasks, their material and communicative means) of the AI production process to affect the resulting AI system in any possible (epistemological/ethical/technical) way?** To address this question, I propose an experiment which is inspired by the surrealist method of the _cadavre exquis_. To create a poem or a drawing, a group of artists follows a strict procedure in which one after the other adds their part to the artwork, without communicating with the others or seeing what the others have added before. The result of their work can be considered the expression of the subconscious (as the surrealists did), or simply as fun or nonsensical. For the experiment I propose, I will follow this procedure together with at least two collaborators to produce a "pipeline exquis". During the conference, we will present the pipeline, and take it as a point of reference in which a peculiar, “isolated” configuration of workers is imposed, to reflect on the question at stake.

## 3. Reflection

Questions for reflection:
- Was it hard to work on a part with the limited amount of information that was given to you?
- What do you think are the effects of this method on the final product?
- What change in method would be required to improve the product?
- To what extent do you think this method corresponds to real life practices in AI development?
- Is there something unique to a division of labour for AI systems, compared to a division of labour for other technological objects such as cars?
- Is the production of (ML) code more similar to the production of technological objects such as cars, or the production of writing in natural language?

### Notes discussion 20 May 2024:

-	Most important reveal: what the data was about
-	For Juliet
	- Created the context
	- Acknowledge an extra preceding step in the division of labor: of the police officers collecting data
		- Why did they collect certain data and others not?
		- What kind of model would they like to use?
-	For Hina
	- Fine; no notion of what data was about, but that is also not of major interest
	- Ended up using variables that J considered not very useful
-	For Megan
	- “Death calculator”
	- Frustrating; no notion of context, so neither of potential use
	- Issues with code; turned out due to package versions
-	Questions
	- Did it work? Yes and no, depends on your notion of “work”.
		- Yes in the sense that we could coordinate and rely on a shared frame of reference
		- No in the sense that the code worked but the prediction was not accurate
	- What would making a non-sensical dummy pipeline teach us about sensical real life pipeline?
		- It is clear where context is needed, basically at the interface with the real world
			- Data preprocessing
			- Model deployment
		- To relate this to critical code studies
			- Basic assumption code is not only functional but also meaningful
			- Would that mean that code is meaningful in a different way in part 1 and 3 than it is in part 2?

### Notes Megan:

The places of conflict or for further reflection seem to be: tick marks & crease marks & choices made in terms of the software used (versions etc). what is interesting is that this kind of exercise segments accountability or documentation, therefore in full the choices made are not necessarily synced to throughout the whole pipeline (especially in step 1 vs model deployment where biases could ocurr...)
To what extent do you think this method corresponds to real life practices in AI development? There are 2 streams of communication going on here. 1 is through the game, the other(s) I suppose are the more technical communication streams which ocurr as technical logs etc. In this case this superficiality remains, however human agency is removed even more (and in this case as designer 3 not having access to documentation, notes and insight that ocurr in data collection and choices made by designer 2 leaves you blindsided and purely playing with abstract numbers and structures. Only by coding through error are you able to problem solve to receive some kind of "result". "result" here being whatever looks like a result based on your past experience (more statistically in this example rather than anything).

## Glossary

**Critical Code Studies**: "Critical code studies is the application of the hermeneutics of the humanities to the interpretation of the extra-functional significance of computer source code. “Extra” here does not mean “outside of” or “apart from” but instead it refers to a significance that is “growing out of” an understanding of the functioning of the code." (Marino & Douglass, 2023) Critical code studies treats code as a cultural product that should thus be included in critical cultural analysis.

**Cadavre Exquis**: Cadavre Exquis (Exquisite Corpse) was a term used by artists working in surrealism for a method they employed for collectively creating a work of art. According to the surrealists, this method let them access the subconscious. The method was and is known in other contexts, for example, it was a popular "party game" in the salons of the Victorians. Since, in this method, the process of creating a work of art is broken down in steps performed by different individuals, the method implies a certain division of labour.

**Division of labour**: "The division of labour is the separation of the tasks in any economic system or organization so that participants may specialize." (wiki) Critical themes in the divison of labour, specifically since industrialization, have been for example: the deskilling of workers, and the alienation of workers from the product of their labour and the "act of production".

**Marginalized labour in the production of AI systems**: While (commercial) presentations of AI emphasize independence of human intervention, several authors have critiqued deleting the reality of the extensive amount of labour exploited for creating these systems. These authors refer mainly to gig workers, which can be considered professional data subjects, informal datasubjects, and of course clickworkers. These workers are often payed minimal wages, if they are compensated for their labour at all.

**High skilled labour in the production of AI systems**: AI production does not only increase the demand for a new group of marginalized workers, but also for a new group of high skilled workers: software developers. 

**Division of labour in the production of AI systems**: I think of two ways in which division of how division of labour in AI production can be characterized. First, division of labour through different phases, in which each part is taken care of by groups differing in skill set, e.g. data production by low skilled workers / model development by high skilled technical workers / model deployment by high skilled non technical workers. Second, division of labour within the developing phase, in which on the one hand the the structure of the software pipeline *imposes a certain order* of steps which can be divided amongst workers, and on the other hand tools such as scrumboards and online hosting of code *organizes and enables* carrying out the separate steps. 

**Machine learning pipeline**: A machine learning pipeline contains the various stages of data processing required to produce an ML system. These steps can be broken down in various levels of detail. E.g. IBM identifies data collection, data preprocessing, feature engineering, model selection, model training, model evaluation, model deployment, monotoring and maintenance.

**AI system as a product**: Software is provided less and less in the form of an end product, and more and more in the form of a subscription service. As developers continue to update the software, the product becomes "dynamic", continuously changing. In AI systems, this is relevant when features need to be updated or when new data is available.
