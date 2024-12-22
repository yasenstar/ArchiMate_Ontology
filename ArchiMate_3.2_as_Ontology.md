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

### Behavior elements can be used to model logical components, the corresponding physical components can then be modeled using active structure elements

### Supports the concept of realization

### Logical and physical application components can be defined as metamodel-level specializations of the application component element

## 3.7/3.8/3.9 More on ArchiMate Language

### ArchiMate Language intentionally does not support a difference between types and instances.

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

## 4.5 Composite Elements

### 4.5.1 Grouping

### 4.5.2 Location

# 05. Relationships and Relationship Connectors

## Figure 21: Overview of Relationships

## 5.1 Structural Relationships

### 5.1.1 Composition Relationship

### 5.1.2 Aggregation Relationship

### 5.1.3 Assignment Relationship

### 5.1.4 Realization Relationship

### 5.1.5 Semantics of Structural Relationships

## 5.2 Dependency Relationships

### 5.2.1 Serving Relationship

### 5.2.2 Access Relationship

### 5.2.3 Influence Relationship

### 5.2.4 Association Relationship

### 5.2.5 Semantics of Dependency Relationships

## 5.3 Dynamic Relationships

### 5.3.1 Triggering Relationship

### 5.3.2 Flow Relationship

### 5.3.3 Semantics of Dynamic Relationships

## 5.4 Other Relationships

### 5.4.1 Specialization Relationship

### 5.4.2 Semantics of Other Relationships

## 5.5 Relationship Connectors

### 5.5.1 Junction

## 5.6 Summary of Relationships

## 5.7 Derivation of Relationships

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

### 7.2.1 Resource

## 7.3 Behavior Elements

### 7.3.1 Capability

### 7.3.2 Value Stream

### 7.3.3 Course of Action

## 7.4 Example

## 7.5 Summary of Strategy Elements

## 7.6 Relationships with Motivation and Core Elements

# 08. Business Layer

# 09. Application Layer

# 10. Technology Layer

# 11. Relationships Between Core Layers

# 12. Implementation and Migration Layer

# 13. Stakeholders, Architecture Views, and Viewpoints

# 14. Language Customization Mechanisms

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
