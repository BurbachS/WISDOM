# WISDOM-Stress

WISDOM-Stress is an ontology for the semantic representation of human stress in the context of wearable- and sensor-based stress experiment data. The ontology was developed as part of a master's thesis and is designed to structure relevant concepts such as stress conditions, stressors, activities, sensors, observations, physiological signals, records, annotations, and biomarker-related information.

The main goal of WISDOM-Stress is to provide a structured semantic model that supports the representation of human stress in experimental settings, especially where physiological and contextual data are collected using wearable devices and sensors.

## Repository Contents

This repository contains the main ontology, evaluation material, AI-generated comparison ontologies, graphical module representations, and selected sample data used as input for AI-supported ontology generation.

### Ontology

This folder contains the main WISDOM-Stress ontology in Turtle format.

The ontology models, among others:

- stress-related and no-stress-related conditions
- acute and chronic stressors
- experimental activities and phases
- subjects, observers, and human observers
- physiological, motion, audio, and camera-based sensors
- observable properties such as heart rate, EDA, skin temperature, SpO2, and acceleration
- physiological records and signal channels
- observations and time-series observations
- annotations and biomarker assays

### Competency Questions

This folder contains the competency questions used to evaluate the ontology.

The competency questions were designed to assess whether the ontology can represent and answer relevant domain-specific requirements. They cover core areas such as stress conditions, stressors, activities, sensors, observable properties, physiological records, observations, annotations, and biomarker assays.

The evaluation matrix documents whether each competency question is answerable based on the current ontology structure.

### AI-Generated Ontologies

This folder contains four AI-generated ontologies that were created as part of an additional comparative evaluation step.

The AI-generated ontologies were produced based on different input strategies, including:

- ontology development standards
- competency questions
- sample subject data from the application domain
- a combined input approach

The AI-generated ontologies were used to compare different modelling outcomes with the manually developed WISDOM-Stress ontology. The comparison focuses on modelling scope, conceptual structure, domain alignment, granularity, and the representation of wearable- and sensor-based stress experiment data.

### AI Input Sample Data

The folder `ai-input-sample-data` contains selected sample data that were used as input for AI-supported ontology generation.

The sample data consist of example datasets from three subjects and were used to provide the AI system with concrete domain-specific input from wearable- and sensor-based stress experiment data. These data supported the generation of the sample-data-based ontology and the combined-input ontology.

The purpose of including these files is to document the input basis used during the AI-supported ontology generation process and to make the comparative evaluation more transparent.

### Graphical Representations

This folder contains graphical module representations of the WISDOM-Stress ontology.

The visualizations are intended to support the understanding of the ontology structure and show how the main modules of the ontology are connected. They provide an overview of central classes, subclass hierarchies, and selected relationships between relevant ontology components.

## Purpose of the Repository

The repository documents the development and evaluation of the WISDOM-Stress ontology. It provides the ontology file itself as well as supporting materials used during the evaluation process.

The repository serves as a transparent documentation basis for:

- ontology development
- competency-question-based evaluation
- technical and conceptual validation
- comparison with AI-generated ontology variants
- graphical representation of ontology modules
- documentation of selected AI input material

## Evaluation Approach

The ontology was evaluated using multiple complementary approaches.

First, the ontology was checked for logical consistency using a reasoner in Protégé. This step was used to identify modelling inconsistencies and improve the conceptual structure of the ontology.

Second, the ontology was evaluated using competency questions. The competency questions define requirements that the ontology should be able to represent or answer. An evaluation matrix was created to document the coverage of these questions.

Third, selected competency questions were technically validated using SPARQL queries. This step was used to test whether relevant ontology structures can be queried explicitly.

Finally, WISDOM-Stress was compared with four AI-generated ontologies to assess differences in modelling scope, structure, granularity, and domain alignment. For two of these AI-generated ontologies, selected subject-based sample datasets were used as part of the input material.

## Technologies

The ontology and evaluation material are based on Semantic Web technologies and related tools:

- OWL
- RDF
- Turtle
- SPARQL
- Protégé
- SOSA/SSN concepts
- Graphical ontology visualization

## Author

Lennart Mack

## License

No license has been specified yet.
