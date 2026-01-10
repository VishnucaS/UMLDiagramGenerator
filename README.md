# Automated UML Diagram Generator

Converting **Natural Language** Requirements into **UML Diagrams** Automatically

### Overview

In software development, requirements are often expressed in natural language, requiring designers to manually identify **entities, attributes, and relationships** to create UML diagrams. 
This process can be time-consuming, repetitive, and costly.

Our Automated UML Diagram Generator addresses this challenge by converting textual requirements directly into UML diagrams, making the design process faster, more accurate, and accessible to beginners.

#### Use Cases:

* Software designers: Speed up diagram creation and verify hand-drawn UML diagrams.

* Companies: Streamline requirement-to-diagram workflows.

* Beginners: Check the correctness of their UML designs.

### Features

* Accepts textual input (paragraphs or requirement descriptions)

* Generates multiple UML diagram types:

  - **Use Case Diagrams**

  - **Class Diagrams**

  - **Sequence Diagrams**

  - **Activity Diagrams**

* Built using **Python** in the **PyCharm IDE**

* Employs Natural Language Processing (NLP) to analyze text and extract meaningful entities, attributes, and relationships

* Constructs a **Domain-Specific Language (DSL)** model as an intermediate representation before generating UML diagrams

### How It Works

**The system consists of four main modules:**

**1. Preprocessing** – Clean and prepare textual requirement input

**2. Feature Extraction** – Identify key entities, relationships, and attributes based on selected diagram type

**3. DSL Model Generation** – Convert extracted features into a structured, intermediate representation

**4. UML Diagram Creation** – Generate UML diagrams from the DSL model

* This approach ensures high fidelity, accurately reflecting the original requirements in the generated diagrams.

### Benefits

* Reduces manual effort and time in UML diagram creation

* Improves accuracy and consistency of diagrams

* Helps beginners learn UML effectively

* Provides a reusable tool for companies and software teams
