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

![WISDOM Modules](OntologyDiagrams/Module1_stress_conditions.png)

*Figure 1. Represents stress-related conditions, including stressors, non-stress conditions, and stress responses, together with their relationships to experimental activities.*

![WISDOM Modules](OntologyDiagrams/Module2_activities.png)

*Figure 2. Captures experimental phases and their connections to stress conditions, stressors, and observations, providing contextual information for recorded measurements.*

![WISDOM Modules](OntologyDiagrams/Module3_observable_properties.png)

*Figure 3. Defines physiological, behavioral, and environmental properties that can be observed independently of the sensors or measurement data used to capture them.*

![WISDOM Modules](OntologyDiagrams/Module4_sensors.png)

*Figure 4. Describes wearable sensor types and their associations with the physiological, behavioral, and environmental properties they observe.*

![WISDOM Modules](OntologyDiagrams/Module5_person.png)

*Figure 5. Distinguishes study subjects, human observers, and experimenters, representing their respective roles within stress experiments and observations.*

![WISDOM Modules](OntologyDiagrams/Module6_recordings.png)

*Figure 6. Organizes physiological recordings, annotation records, signal channels, and observations to provide a semantic representation of multimodal stress measurement data.*

### CQs

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


## Ontology Editors

Lennart Mackert, Simon Burbach, Paul Schreiber, Maria Maleshkova

## License

All resources are licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International.