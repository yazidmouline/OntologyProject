# Ontology Report: An ontology to help city planners make cities greener

## IA 301 Logics and Symbolic AI

## Yazid Mouline and Jérémy Perez

The ontology designed serves as a guide for city planners for accurate tree planting, relying on different characteristics of trees, and giving the potential use of a tree species. In the pdf report you will find:
- a thorough description of the ontology, design decisions and the problem it tackles.
- an ontology graph
- Classes, data properties and object properties
- asserted ontology and inferred ontology after using the HermiT reasoner

Here, you will find the MIRO facts:

### A. Basics

#### A.1 Ontology name

An ontology to help city planners make cities greener

#### A.2 Ontology owner

Yazid Mouline and Jérémy Perez from Télécom Paris.

#### A.3 Ontology license

 Creative Commons Attribution 3.0 (CC BY 3.0)

#### A.4 Ontology URL

https://github.com/yazidmouline/OntologyProject/TreePlannerOntology.owl

#### A.5 Ontology repository

https://github.com/yazidmouline/OntologyProject

#### A.6 Methodological framework

The ontology was developed using the guide Ontology101 from Protégé: https://protege.stanford.edu/publications/ontology_development/ontology101.pdf

### B. Motivation

#### B.1 Need

One of the United Nations Sustainable Development Goals is: Make cities and human settlements inclusive, safe, resilient and sustainable. One of its aspects consist in promoting sustainable land-use planning and management. It is then vital to include systematically trees and vegetation in our cities. Trees help clean the air, cool temperatures transforming murderous cities into a soothing habitat.


#### B.3 Target audience

United Nations: Department of Economic and Social Affairs. Sustainable development.

### C. Scope, requirements, development community

#### C.1 Scope and coverage

Our ontology aims to answer to the question: For a given use (Park, Coastal, Transport Corridor...) which tree species should I plant ?

#### C.2 Development community

This ontology is designed by Yazid Mouline and Jérémy Perez, two master students from Institut Polytechnique de Paris.

#### C.3 Communication

- yazid.mouline@gmail.com
- jeremy.perez@telecom-paris.fr

### D. Knowledge acquisition

#### D.1 Knowledge acquisition methodology

The knowledge in this ontology was inspired from the article: Hirons, A.D. and Sjöman, H. (2019) Tree Species Selection for Green Infrastructure: A Guide for Specifiers, Issue 1.3. Trees & Design Action Group.

#### D.2 Source knowledge location

http://www.tdag.org.uk/species-selection-for-green-infrastructure.html

#### D.3 Content selection

We focused on key attributes for different tree species separating them into categories: Environmental Tolerance, Morphology, Ornamental Qualities.

### E. Ontology content

#### E.1 Knowledge Representation language

OWL

#### E.2 Development environment

Protégé

#### E.3 Ontology metrics

- Number of classes: 85
- Number of properties: 11
- Number of axioms: 446

#### E.4 Incorporation of other ontologies

None

#### E.5 Entity naming convention

Naming scheme inspired from the article Tree Species Selection for Green Infrastructure.

#### E.6 Identifier generation policy

Prefix or Suffix depending on meaning.

#### E.7 Entity metadata policy

Needs to be more developed.

#### E.8 Upper ontology

None

#### E.9 Ontology relationships

The relationships used are mainly of sublcasses. We then created properties between the classes Tree and Attribute. These properties allow to define for each tree its properties. Then, we created relationships between Tree and PotentialUse based on these properties.

#### E.10 Axiom patterns 

To fill out the subclasses of PotentialUSe, we wrote axioms based on properties. Using the reasoner, it filled out these classes accordingly. More details in the pdf report.

## F. Managing Change

### F.1 Sustainability plan 

For the moment, there is no plan to update the ontology.

#### F.2 Entity deprecation strategy 

No class should be deleted from the ontology.

#### F.3 Versioning policy

Updated versions will be named according to a date format DD-MM-YYYY.

### G. Quality Assurance

#### G.1 Testing

The ontology is logically consistent. However, it gives sometimes results that are not complete nor accurate. This is why it needs updating, adding more entities, adding more properties and maybe even fuzziness.

### G.2 Evaluation

The ontology gives satisfactory results, but as said above it may need some development for it to have more interesting use. For the moment, the information it provides is still basic, but with added features, it could give much more interesting results.

### G.3 Example of use

In the pdf report.

### G.4 Institutional endorsement

No endorsement.


### G.5 Evidence of use

None
