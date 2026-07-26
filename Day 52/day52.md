# Day 52 – System Design & Technical Architecture

## Overview

Day 52 of the **AB Talks 60-Day Claude AI Challenge** focused entirely on designing the technical foundation of the **LifeLink** capstone project.

Although no application code was written today, this was one of the most important milestones of the project. Instead of rushing into development, the entire system was carefully planned—from architecture and database design to API contracts, user flows, AI prompts, and project structure.

The objective was to eliminate uncertainty before implementation so that every feature built in the coming days directly supports the project requirements.

---

# Why Design Before Development?

Many software projects become difficult to maintain because architecture decisions are made while coding.

Today's goal was to answer every major technical question before writing a single line of application code:

* How will the frontend communicate with the backend?
* How should the database be structured?
* What APIs are required?
* How will Claude AI analyse emergency requests?
* What screens are needed?
* How should users move through the application?
* How should the project be organised for future development?

With these questions answered, implementation can now focus entirely on building rather than redesigning.

---

# Project Progress

## LifeLink – AI-Powered Emergency Healthcare Coordination Platform

LifeLink helps patients during medical emergencies by intelligently recommending the most appropriate healthcare resources.

The planned workflow allows patients to:

* Submit emergency requests
* Share emergency details in natural language
* Automatically capture their location
* Receive AI-generated urgency classification
* View ranked recommendations for hospitals, blood banks, and verified donors
* Track emergency request progress through the application

---

# Technical Design Completed

## System Architecture

A complete architecture was designed explaining how each major component communicates.

The design includes:

* Frontend application
* Firebase Authentication
* Cloud Firestore
* Claude AI integration
* Recommendation workflow
* Data flow between all services

This architecture serves as the blueprint for development.

---

## Database Design

The complete Firestore database schema was designed before implementation.

The schema includes collections for:

* Users
* Emergency requests
* Hospitals
* Blood banks
* Blood donors
* AI recommendations
* Emergency status tracking

Each collection was validated against the project requirements to ensure every feature has a supporting data model.

---

## API Design

Every planned API endpoint was documented before development.

Each endpoint includes:

* Purpose
* Request format
* Response format
* Validation rules
* Error handling
* Expected behaviour

Designing the API first ensures consistency across the application during implementation.

---

## UI Planning

Every application screen was planned before coding.

The complete user flow includes:

* Login
* Dashboard
* Raise Emergency
* AI Recommendation Results
* Emergency Tracking
* Profile Management
* Request History

Each screen exists because it satisfies a specific requirement from the Product Requirements Document.

---

## AI Prompt Design

The Claude AI prompts were drafted before implementation.

Prompt templates were prepared for:

* Emergency urgency classification
* Resource recommendation
* Recommendation reasoning

Preparing prompts early allows the AI workflow to remain consistent throughout development.

---

## Project Structure

The repository structure was organised to support scalable development.

Initial folders were prepared for:

* Documentation
* Design resources
* Application code
* Components
* Libraries
* Public assets

This structure will be used throughout the remaining days of the capstone.

---

# Documentation Produced

Today's work resulted in a complete technical documentation package, including:

* ARCHITECTURE.md
* SCHEMA.md
* API.md
* UI-WIREFRAMES.md
* PROJECT-STRUCTURE.md
* prompts.md
* mock-data.md
* Updated Implementation Blueprint
* Project Log
* LinkedIn Progress Report

Together, these documents become the technical reference for the rest of the project.

---

# Key Learnings

* Architecture should be designed before implementation.
* A well-designed database reduces future rework.
* API-first planning simplifies frontend and backend integration.
* Wireframing improves user experience before development begins.
* Well-prepared AI prompts produce more consistent AI behaviour.
* Good documentation speeds up future development.

---

# Outcome

By the end of Day 52, LifeLink had a complete technical foundation ready for development.

The project now includes:

* Finalised system architecture
* Validated Firestore database schema
* Complete API specifications
* Planned user interface and navigation
* AI prompt templates
* Organised project structure
* Updated implementation blueprint

With planning complete, the project is now ready to move into implementation.

The next milestone is setting up the development environment, integrating Firebase, and beginning the first functional version of LifeLink.

---

# Prompt Used

```text
Day 2 – System Design & Technical Architecture

Continue building the LifeLink capstone project from the approved Product Requirements Document and Implementation Blueprint.

Act as my software architect, senior backend engineer, and technical mentor.

Today's objective is to complete every major technical design decision before writing application code.

Guide me step by step through:

• Creating and organising the GitHub repository
• Designing the complete system architecture
• Creating the Firestore database schema
• Defining every API endpoint with request, response, validation and error handling
• Designing all application screens and user flows
• Drafting Claude AI prompt templates for urgency classification and recommendation reasoning
• Preparing realistic mock data for development
• Organising the project folder structure
• Updating the implementation blueprint if design improvements are discovered

For every manual task:

- Explain each step using the actual GitHub interface, terminal commands, buttons and menus.
- Wait for my confirmation and screenshots before continuing.
- Never assume a step has been completed.

Before finishing:

Generate all design documentation in Markdown format, verify consistency across every document, and ensure the implementation blueprint remains the single source of truth for the remainder of the capstone.

Do not write application code today.

The goal is to complete a production-quality technical design so development can begin immediately on the next day.
```

---

**This prompt is reusable for anyone who wants to complete the system design phase of a software project before implementation. It emphasises architecture-first development, structured documentation, API planning, database design, and AI workflow preparation to build a strong foundation for future development.**
