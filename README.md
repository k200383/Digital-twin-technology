# Digital Twin Technology

A research-and-development based project focused on creating a Digital Twin model of our university basement using 3D modelling tools and Microsoft Azure Digital Twins.

## Project Overview

Created a Digital Twin model of our university basement using 3D modelling tools such as Sketchup and Blender, then deployed it on Microsoft Azure using Azure Digital Twins. The Digital Twin instances were developed using DTDL JSON files, by splitting the basement model into five models: Building Facade, Lobby, Passageway, Office, Computer Lab. The JSON files were uploaded on Microsoft Azure as Digital Twin instances and links were created between the Digital Twin 3D model and the Digital Twin instances. The frontend was created using HTML Pug, and the aim of the application was to tell the user whether their proposed construction was feasible or not.

## Research Component

For the research part of our project, we wrote a research paper involving a literature review of 16 recent research papers on Digital Twins, along with an analysis of the extent to which we were able to implement the Digital Twin and the challenges associated with it.

## System Architecture

### 3D Modeling
- **Tools Used:** Sketchup and Blender
- **Target:** University basement layout
- **Output:** Detailed 3D model for digital twin implementation

### Digital Twin Models
The basement was divided into five separate DTDL models:
- **Building Facade** - External structure representation
- **Lobby** - Main entrance and reception area
- **Passageway** - Corridors and connecting areas
- **Office** - Administrative spaces
- **Computer Lab** - Technical laboratory areas

### Azure Digital Twins Implementation
- **Platform:** Microsoft Azure Digital Twins
- **Model Format:** DTDL (Digital Twin Definition Language) JSON files
- **Deployment:** Digital Twin instances uploaded to Azure
- **Integration:** Links established between 3D models and Digital Twin instances

### Frontend Application
- **Technology:** HTML Pug
- **Purpose:** Construction feasibility assessment
- **Functionality:** Evaluates proposed construction projects for feasibility

## Project Structure

```
Digital-twin-technology/
├── data/                   # DTDL JSON files
│   ├── BuildingFacade.dtdl.json
│   ├── Lobby.dtdl.json
│   ├── Passageway.dtdl.json
│   ├── Office.dtdl.json
│   └── ComputerLab.dtdl.json
├── models/                 # 3D model files
├── docs/                   # Research documentation and thesis
└── README.md
```

## Key Features

- **Multi-Space Modeling:** Comprehensive digital representation of university basement
- **Cloud Integration:** Deployed on Microsoft Azure Digital Twins platform
- **Research-Based:** Backed by literature review of 16 research papers
- **Practical Application:** Real-world construction feasibility assessment
- **Modular Design:** Separate DTDL models for different basement areas

## Technology Stack

- **3D Modeling:** Sketchup, Blender
- **Cloud Platform:** Microsoft Azure Digital Twins
- **Model Definition:** DTDL (Digital Twin Definition Language)
- **Frontend:** HTML Pug
- **Data Format:** JSON

## Research Findings

Our research paper includes:
- Literature review of 16 recent Digital Twin research papers
- Implementation analysis of our Digital Twin system
- Documentation of challenges encountered during development
- Assessment of Digital Twin technology capabilities and limitations

## Use Case

The application serves as a decision-support tool for construction planning, allowing users to:
- Input proposed construction modifications
- Receive feasibility assessments based on the digital twin model
- Make informed decisions about basement renovations or expansions
