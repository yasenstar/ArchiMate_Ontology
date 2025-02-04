 ArchiMate 3.2 as Ontology

# 01. Introduction

## My Post in LinkedIn - Basic Ontology

## ArchiMate Objective

### This standard is the specification of the ArchiMate Enterprise Architecture modeling language, a visual language with a set of default iconography for describing, analyzing, and communicating many concerns of Enterprise Architectures as they change over time

### The standard provides a set of entities and relationships with their corresponding iconography for the representation of Architecture Descriptions.

### The ArchiMate ecosystem also supports an exchange format in XML which allows model and diagram exchange between tools

## ArchiMate Overview

### An Enterprise Architecture is typically developed because key people have concerns that need to be addressed by the business and IT systems within an organization

#### Such people are commonly referred to as the “stakeholders” of the Enterprise Architecture.

#### The role of the architect is to address these concerns by identifying and refining the motivation and strategy expressed by stakeholders, developing an architecture, and creating views of the architecture that show how it addresses and balances stakeholder concerns

#### Without an Enterprise Architecture, it is unlikely that all concerns and requirements are considered and addressed

### The ArchiMate Enterprise Architecture modeling language provides a uniform representation for diagrams that describe Enterprise Architectures

#### It includes concepts for specifying inter-related architectures, specific viewpoints for selected stakeholders, and language customization mechanisms.

#### It offers an integrated architectural approach that describes and visualizes different architecture domains and their underlying relations and dependencies.

#### Its language framework provides a structuring mechanism for architecture domains, layers, and aspects.

#### It distinguishes between the model elements and their notation, to allow for varied, stakeholder-oriented depictions of architecture information

### The language uses service-orientation to distinguish and relate the Business, Application, and Technology Layers of Enterprise Architectures, and uses realization relationships to relate concrete elements to more abstract elements across these layers.

# 02. Definitions

## ArchiMate Community - Discussion Board

# 03. Language Structure

## 3.1 Design Consideration

### A key challenge in the development of a general metamodel for Enterprise Architecture is to strike a balance between the specificity of languages for individual architecture domains and a very general set of architecture concepts, which reflects a view of systems as a mere set of inter-related entities.

### The design of the ArchiMate language started from a set of relatively generic concepts

### The most important design restriction on the language is that it has been explicitly designed to be as small as possible, but still usable for most Enterprise Architecture modeling tasks.

### Sample discussion: Information/Data Modeling Extensions

## 3.2 Top-Level Language Structure

### Building Class Structure in Protege

## 3.3 Layering of the ArchiMate

### Core Layer: Business, Application, Technology

### Main Relations: Serving, Realizing

## 3.4/3.5 ArchiMate Core vs. Full Framework

### Link with TOGAF

## 3.6 (1) ArchiMate Abstraction

### The distinction between an external (black-box, abstracting from the contents of the box) and internal (white-box) view is common in system design.

#### The external view depicts what the system has to do for its environment

#### The internal view depicts how it does this.

### The distinction between behavior and active structure is commonly used to separate what the system must do and how the system does it from the system constituents (people, applications, and infrastructure) that do it.

#### In modeling new systems, it is often useful to start with the behaviors that the system must perform

#### In modeling existing systems, it is often useful to start with the people, applications, and infrastructure that comprise the system, and then analyze in detail the behaviors performed by these active structures

### The distinction between conceptual, logical, and physical abstraction levels

#### Conceptual elements represent the information the business finds relevant

#### Logical elements provide logical structure to this information for manipulation by information systems

#### Physical elements describe the storage of this information

#### Reference: TOGAF Enterprise Metamodel

##### c220: The TOGAF Standard - 10th Edition

#### Reference: Essential EAS Meta Model

## 3.6 (2) ArchiMate Abstraction Modeling

### g21e: How to Use the ArchiMate® Modeling Language to Support the TOGAF® Standard

### Three ways of modeling in ArchiMate

#### Behavior elements can be used to model logical components, the corresponding physical components can then be modeled using active structure elements

#### Supports the concept of realization

#### Logical and physical application components can be defined as metamodel-level specializations of the application component element

### ArchiMate Language intentionally does not support a difference between types and instances.

## 3.7/3.8/3.9 More on ArchiMate Language

### ArchiMate Concepts and Notation

### Use of Nesting, Colors, and Notations Cues

# 04. Generic Metamodel

## 4.1 Behavior and Structure Elements

### Figure 4: Hierarchy of Behavior and Structure Elements

### Figure 5: Behavior and Structure Elements Metamodel

### 4.1.1 Active Structure Elements

### 4.1.2 Behavior Elements

### 4.1.3 Passive Structure Elements

## 4.2 Specializations of Structure and Behavior Elements

### Figure 12: Specialization of Core Elements

## 4.3 Summary of Structure and Behavior Elements

## 4.4 Motivation Elements
 (see:About Zachman Framework)
### ? why not cover "Constraint" which in Archi tool

## 4.5 Composite Elements
 (see:3.2 Top-Level Language Structure)
### 4.5.1 Grouping

### 4.5.2 Location
 (see:About Zachman Framework)
# 05. Relationships and Relationship Connectors

## Figure 21: Overview of Relationships

## 5.1 Structural Relationships

### 5.1.1 Composition Relationship

#### UML2 Specification
 (see:5.1.2 Aggregation Relationship5.4.1 Specialization Relationship)
### 5.1.2 Aggregation Relationship

### 5.1.3 Assignment Relationship

#### ArchiMate 2.1 Specification

### 5.1.4 Realization Relationship

### 5.1.5 Semantics of Structural Relationships
 (see:5.3.1 Triggering Relationship)
## 5.2 Dependency Relationships

### 5.2.1 Serving Relationship

### 5.2.2 Access Relationship

### 5.2.3 Influence Relationship

### 5.2.4 Association Relationship

### 5.2.5 Semantics of Dependency Relationships
 (see:5.3.2 Flow Relationship)
## 5.3 Dynamic Relationships

### 5.3.1 Triggering Relationship

#### Triggers in PMBOK

### 5.3.2 Flow Relationship

### 5.3.3 Semantics of Dynamic Relationships

## 5.4 Other Relationships

### 5.4.1 Specialization Relationship

#### Added in Archi 4.9

### 5.4.2 Semantics of Other Relationships

## 5.5 Relationship Connectors

### 5.5.1 Junction

## 5.6 Summary of Relationships

## 5.7 Derivation (推导) of Relationships
 (see:B.2 Derivation Rules for Valid Relationships)
### Example 17: Deviation from a Chain of Relationships

# 06. Motivation Elements

## 6.1 Motivation Element Metamodel

## 6.2 Stakeholder, Driver, and Assessment

### 6.2.1 Stakeholder

### 6.2.2 Driver

### 6.2.3 Assessment

### 6.2.4 Example

## 6.3 Goal, Outcome, Principle, Requirement, and Constraint

### 6.3.1 Goal

### 6.3.2 Outcome

### 6.3.3 Principle

### 6.3.4 Requirement

### 6.3.5 Constraint

### 6.3.6 Example

## 6.4 Meaning and Value

### 6.4.1 Meaning

### 6.4.2 Value

### 6.4.3 Example

## 6.5 Summary of Motivation Elements

## 6.6 Relationships with Core Elements

# 07. Strategy Layer

## 7.1 Strategy Elements Metamodel

## 7.2 Structure Elements

### 7.2.1 Resource (Who)

## 7.3 Behavior Elements

### 7.3.1 Capability (What)

### 7.3.2 Value Stream (Why)

### 7.3.3 Course of Action (How)

## 7.4 Example

### Example 21: Capability, Resource, and Course of Action

### Example 22: Value Stream with Capability

## 7.5 Summary of Strategy Elements

## 7.6 Relationships with Motivation and Core Elements

# 08. Business Layer

## 8.1 Business Layer Metamodel

## 8.2 Active Structure Elements

### 8.2.1 Business Actor

### 8.2.2 Business Role

### 8.2.3 Business Collaboration

### 8.2.4 Business Interface

### 8.2.5 Example (23)

## 8.3 Behavior Elements

### 8.3.1 Business Process

### 8.3.2 Business Function

### 8.3.3 Business Interaction

### 8.3.4 Business Event

### 8.3.5 Business Service

### 8.3.6 Example

## 8.4 Passive Structure Elements

### 8.4.1 Business Object

### 8.4.2 Contract

### 8.4.3 Representation

### 8.4.4 Example

## 8.5 Composite Elements

### 8.5.1 Product

### 8.5.2 Example

## 8.6 Summary of Business Layer Elements

# 09. Application Layer

## 9.1 Application Layer Metamodel

## 9.2 Active Structure Elements

### 9.2.1 Application Component

### 9.2.2 Application Collaboration

### 9.2.3 Application Interface

### 9.2.4 Example

## 9.3 Behavior Elements

### 9.3.3 Application Process

### 9.3.1 Application Function

### 9.3.2 Application Interaction

### 9.3.4 Application Event

### 9.3.5 Application Service

### 9.3.6 Example

## 9.4 Passive Structure Elements

### 9.4.1 Data Object

### 9.4.2 Example

## 9.5 Summary of Application Layer Elements

# 10. Technology Layer

## 10.1 Technology Layer Metamodel

## 10.2 Technology Active Structure Elements

### 10.2.1 Node

### 10.2.2 Device

### 10.2.3 System Software

### 10.2.4 Technology Collaboration

### 10.2.5 Technology Interface

### 10.2.6 Path

### 10.2.7 Communication Network

### 10.2.8 Example

## 10.3 Technology Behavior Elements

### 10.3.1 Technology Function

### 10.3.2 Technology Process

### 10.3.3 Technology Interaction

### 10.3.4 Technology Event

### 10.3.5 Technology Service

### 10.3.6 Example

## 10.4 Technology Passive Structure Elements

### 10.4.1 Artifact

### 10.4.2 Example

## 10.5 Physical Elements Metamodel

## 10.6 Physical Active Structure Elements

### 10.6.1 Equipment

### 10.6.2 Facility

### 10.6.3 Distribution Network

## 10.7 Physical Passive Structure Elements

### 10.7.1 Material

## 10.8 Example

## 10.9 Summary of Technology Layer Elements

# 11. Relationships Between Core Layers

## 11.1 Alignment of the Business Layer and Lower Layers

## 11.2 Alignment of the Application and Technology Layers

## 11.3 Example

# 12. Implementation and Migration Layer

## 12.1 Implementation and Migration Elements Metamodel

## 12.2 Implementation and Migration Elements

### 12.2.1 Work Package

### 12.2.2 Deliverable

### 12.2.3 Implementation Event

### 12.2.4 Plateau

### 12.2.5 Gap

### 12.2.6 Example

## 12.3 Summary of Implementation and Migration Elements

## 12.4 Relationships

## 12.5 Relationships with Other Aspects and Layers

# 13. Stakeholders, Architecture Views, and Viewpoints

## 13.1 Introduction

## 13.2 Stakeholders and Concerns

## 13.3 Architecture Views and Viewpoints

## 13.4 Viewpoint Mechanism

### 13.4.1 Defining and Classifying Viewpoints

### 13.4.2 Creating the View

## 13.5 Example Viewpoints

# 14. Language Customization Mechanisms

## 14.1 Adding Attributes to ArchiMate Concepts

## 14.2 Specialization of Concepts

### 14.2.1 Examples of Specializations of Business Layer Elements (Informative)

### 14.2.2 Examples of Specializations of Application Layer Elements (Informative)

### 14.2.3 Examples of Specializations of Technology Layer Elements (Informative)

### 14.2.4 Examples of Specializations of Physical Elements (Informative)

### 14.2.5 Examples of Specializations of Motivation Elements (Informative)

#### «  »

Left pointing double angle quotation mark:
Unicode: U+000AB
HTML entity: &laquo; – HTML code: &#171;
PC keystroke: ALT+0171

Right pointing double angle quotation mark
Unicode: U+000BB
HTML entity: &raquo; – HTML code: &#187;
PC keystroke: ALT+0187

### 14.2.6 Examples of Specializations of Strategy Elements (Informative)

### 14.2.7 Examples of Specializations of Implementation and Migration Elements (Informative)

### 14.2.8 Examples of Specializations of Composite Elements (Informative)

### 14.2.9 Examples of Specializations of Relationships and Relationship Connectors (Informative)

# Appendix A: Summary of Language Notation

## A.1 Core Elements

## A.2 Motivation, Strategy, Implementation and Migration Elements

## A.3 Relationships and Relationship Connectors

# Appendix B: Relationships (Normative)

## B.1 Specialization of Derivation Rules

## B.2 Derivation Rules for Valid Relationships

### B.2.1 Valid Derivation for Specialization Relationships

### B.2.2 Valid Derivations for Structural Relationships

### B.2.3 Valid Derivation for Dependency Relationships

### B.2.4 Valid Derivations for Dynamic Relationships

## B.3 Derivation Rules for Potential Relationships

### B.3.1 Potential Derivation for Specialization Relationships

### B.3.2 Potential Derivation for Structural and Dependency Relationships

#### Appendix B: Relationships (Normative)

##### B.1 Specialization of Derivation Rules

##### B.2 Derivation Rules for Valid Relationships

###### B.2.1 Valid Derivation for Specialization Relationships

###### B.2.2 Valid Derivations for Structural Relationships

###### B.2.3 Valid Derivation for Dependency Relationships

###### B.2.4 Valid Derivations for Dynamic Relationships

##### B.3 Derivation Rules for Potential Relationships

###### B.3.1 Potential Derivation for Specialization Relationships

###### B.3.2 Potential Derivation for Structural and Dependency Relationships

###### B.3.3 Potential Derivation for Dependency Relationships

###### B.3.4 Potential Derivation for Dynamic Relationships

###### B.3.5 Potential Derivation Rule for Grouping

##### B.4 Restrictions on Applying Derivation Rules

##### B.5 Relationship Tables

##### B.6 Grouping, Plateau, and Relationships Between Relationships

### B.3.3 Potential Derivation for Dependency Relationships

### B.3.4 Potential Derivation for Dynamic Relationships

### B.3.5 Potential Derivation Rule for Grouping

## B.4 Restrictions on Applying Derivation Rules

## B.5 Relationship Tables

## B.6 Grouping, Plateau, and Relationships Between Relationships

# Appendix C: Example Viewpoints

## C.1 Basic Viewpoints in the ArchiMate Language

### Category: Composition

#### C.1.1 Organization Viewpoint

##### Sample (Visual-Paradigm)

#### C.1.2 Application Structure Viewpoint

##### Sample (SparxSystems)

#### C.1.3 Information Structure Viewpoint

##### Sample 1 (Visual-Paradigm)

##### Sample 2 (SparxSystems)

#### C.1.4 Technology Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

#### C.1.5 Layered Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

#### C.1.6 Physical Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

### Category: Support

#### C.1.7 Product Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

#### C.1.8 Application Usage Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

#### C.1.9 Technology Usage Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

### Category: Cooperation

#### C.1.10 Business Process Cooperation Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

#### C.1.11 Application Cooperation Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

### Category: Realization

#### C.1.12 Service Realization Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

#### C.1.13 Implementation and Deployment Viewpoint

##### Example 1 (Visual-Paradigm)

##### Example 2 (SparxSystems)

## C.2 Motivation Viewpoints

### C.2.1 Stakeholder Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.2.2 Goal Realization Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.2.3 Goal Contribution Viewpoint

#### Example 1 (Qualiware)

#### Example 2 (ResearchGate)

### C.2.4 Principles Viewpoint

#### Example 1 (Qualiware)

#### Example 2 (SparxSystems)

### C.2.5 Requirements Realization Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.2.6 Motivation Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

## C.3 Strategy Viewpoints

### C.3.1 Strategy Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.3.2 Capability Map Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.3.3 Value Stream Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.3.4 Outcome Realization Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.3.5 Resource Map Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

## C.4 Implementation and Migration Viewpoints

### C.4.1 Project Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.4.2 Migration Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

### C.4.3 Implementation and Migration Viewpoint

#### Example 1 (Visual-Paradigm)

#### Example 2 (SparxSystems)

# Appendix D: Relationship to Other Standards, Specifications, and Guidance Documents

## D.1 The TOGAF Framework

## D.2 The BIZBOK Guide

## D.3 The ArchiMate Language and Other Modeling Languages

## D.4 BPMN

## D.5 UML

## D.6 BMM

# Appendix E: Changes from Version 2.1 to Version 3.2

## E.1 Changes from Version 2.1 to Version 3.0.1

## E.2 Changes from Version 3.0.1 to Version 3.1

## E.3 Changes from Version 3.1 to Version 3.2

# Some Reference Resources

## OpenGroup Online ArchiMate 3.2 Spec

## OpenGroup ArchiMate 3.2 Online SinglePage

## ArchiMate 3.2 Starter Pack (Orbus)

## ArchiMate 3.2 Overviews PDFs (R&A)

## Changes Analysis on ArchiMate 3.2 (GEL)

## ArchiMate 3.2 Reference (goodea.eu)

## ArchiMate 3.2 Introduction Poster (BOC)

## What's New in ArchiMate 3.2 (Visual Paradigm)

## Nice book: Mastering ArchiMate 3.2 Edition (Gerben Wierda)

## About Zachman Framework

## SWRL: A Semantic Web Rule Language
 (see:B.1 Specialization of Derivation Rules)
### Referen: SWRL in Protege

### Video 38 of "Ontology Practice - Build pizza.owl in Protege

## ArchiMate Viewpoints

### Visual-Paradigm Sample Viewpoints
 (see:Appendix C: Example Viewpoints)
### Architecture Views and Viewpoints (Sparx)

### QualiWare (need login)
