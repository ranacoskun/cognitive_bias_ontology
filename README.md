# Cognitive Bias  Ontology

Here you can find the documentation for the project "Cognitive Bias  Ontology," an ontology for cognitive biases developed for the Knowledge Representation and Knowledge Extraction course at the University of Bologna.

Working group: Irem Atmar, Rana Coskun, Francesco Alaimo, and Evgeniia Vdovichenko.

## Goal of the project
The aim of this project is to develop an ontology to model biases listed in the Cognitive Biases Codex. This involves creating an ontology for every bias to describe these cognitive phenomena and express relations between biases if they have them. 

Our group will focus on a specific part of this codex containing 18 biases from the sub-clusters “We notice things already primed in memory or repeated often” and “We edit and reinforce some memories after the fact”.

## What are cognitive biases?

### Britannica

Cognitive bias, systematic errors in the way individuals reason about the world due to subjective perception of reality. Cognitive biases are predictable patterns of error in how the human brain functions and therefore are widespread. Because cognitive biases affect how people understand and even perceive reality, they are difficult for individuals to avoid and in fact can lead different individuals to subjectively different interpretations of objective facts.

### Wikipedia

A cognitive bias is a systematic pattern of deviation from norm or rationality in judgment.[1] Individuals create their own "subjective reality" from their perception of the input. An individual's construction of reality, not the objective input, may dictate their behavior in the world. Thus, cognitive biases may sometimes lead to perceptual distortion, inaccurate judgment, illogical interpretation, and irrationality.[2][3][4]

## What is the Cognitive Bias Codex?
Created by John Manoogian III and Buster Benson, this document serves as a valuable tool for visually representing all known cognitive biases. The biases are arranged in a circle, divided into four clusters, each representing a specific group of cognitive biases:

1. What should we remember? - Biases that affect our memory of people, events, and information.

2. Too much information - Biases that influence how we perceive certain events and individuals.

3. Not enough meaning - Biases that arise when we have insufficient information and need to fill in the gaps.

4. Need to act fast - Biases that impact our decision-making processes.

We studied and modeled 18 biases from the two groups trying to describe how they work, what they are and how they are connected between each other.

### Cluster "Too much information"

Sub-cluster: We notice things already primed in memory or repeated often

- Availability heuristic

- Attentional bias

- Illusory truth effect

- Mere-exposure effect 

- Context effect

- Cue-dependent forgetting

- Mood-congruent memory

- Frequency illusion

- Baader-Meinhof Phenomenon 

- Empathy Gap

- Omission bias 

- Base rate fallacy 

### Cluster "What should we remember?"

Sub-cluster: We edit and reinforce some memories after the fact

- Spacing effect 

- Suggestibility

- False memory

- Cryptomnesia

- Source confusion 

- Misattribution of memory

## Methodology

This section explains the process and methodology used to create specific ontologies for various cognitive biases. The approach included several steps: 

1. Literature Search

2. Ideation and Design

3. Ontology development and modeling

4. Documentation and visualization

The full project documentation is available here https://cbi-ontology.gitbook.io/cbi-ontology/methodology 

### Literature Search

The initial step involved an extensive literature search to gather information on the cognitive bias concept. The literature review helped in understanding the underlying theories and categorizations of cognitive biases along with providing a foundation for ontology development. This was mostly done using online sources (e.g. Wikipedia, DecisionLab) and large language models (LLMs) to extract and gain information on each bias. 

Ideation and Design
After the literature review, all the information obtained was collected in a Miro board to carry out the ideation phase. The next step was to start designing the ontologies. For the design and development steps, the eXtreme Design (XD) methodology was employed. It is used to identify the main requirements for each ontology through Competency Questions (CQs) and iteratively designing small ontology modules like the divide and conquer method [1].

In the ideation and design phases, LLMs were used to accomplish the initial steps of the given XD methodology flow. The outputs helped us to get to know the project context, create user stories, and extract CQs from requirements. The whole conversations with LLMs can be found under the Developed Ontologies section for each bias.

### Ontology Development and Modeling

The development phase involved creating detailed ontologies for each cognitive bias using Ontology Design Patterns (ODPs) and the principles of XD, in accordance with XD methodology flow. ODPs are reusable solutions for common ontology design problems. In this project, Content ODPs were particularly used as they can be easily adapted to XD methodology and can be directly reused by importing them into the ontology under development[2]. Then, 

The development process included:

- Importing and specializing relevant ODPs according to the requirements of each context

- Using Framester frames as an ontological resource and integrating these frames into the ontologies created

- Creating new classes and properties as needed and ensuring they fit seamlessly with existing ones.

- Utilizing Protégé for knowledge management and for creating and editing CBI ontologies.

- Continuous testing and validation through SPARQL queries to ensure the ontologies met the defined CQs.

### Documentation and Visualization

The final step involved documenting the ontology development process and visualizing the results:

- Detailed documentation was maintained for each step using GitBook, including literature sources, design decisions, and modeling choices.

- Visualization tools like draw.io and Graffoo were used to create UMLs of the ontologies, showing classes and their relationships.

- All ontologies were saved in ".owl" format and hosted on GitHub, providing a referenceable URI for each module.

This structured methodology ensured a comprehensive and flexible approach to developing ontologies for cognitive biases, facilitating collaboration and integration of individual modules into a cohesive whole.
