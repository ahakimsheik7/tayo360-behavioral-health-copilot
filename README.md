# Tayo360 Behavioral Health Documentation Copilot

## Overview

Tayo360 Behavioral Health Documentation Copilot is an AI-powered workflow system designed to help behavioral health clinics reduce documentation time, improve follow-up, and increase operational visibility.

This system works alongside existing Electronic Health Record (EHR) systems such as Procentive, enhancing workflows without replacing them.

## Problem

Behavioral health providers often struggle with:

* Time-consuming documentation (FA, ITP, DA, progress notes)
* Missed follow-ups and overdue tasks
* Limited visibility into client progress
* Administrative overload

## Solution

Tayo360 provides:

* AI-assisted documentation generation
* Real-time tracking dashboard using Google Sheets
* Automated workflow management using n8n
* Smart notifications for staff follow-up
* Structured AI agents powered by Salesforce Agentforce

## Core Features

* Functional Assessment (FA) Generator
* Individual Treatment Plan (ITP) Drafting
* Diagnostic Assessment (DA) Support
* Progress Note Summarization
* Client Workflow Tracking Dashboard
* Automated Email Notifications
* Completion Percentage Tracking

## System Architecture

### Input Layer

* Intake forms
* Staff input
* Voice input (future integration with Vapi)

### Processing Layer

* AI generation using ChatGPT / Claude
* Workflow orchestration using Agentforce
* Automation engine using n8n

### Output Layer

* Structured documentation drafts
* Google Sheets dashboard updates
* Email notifications to staff

## Tech Stack

* AI: ChatGPT, Claude
* Automation: n8n
* Orchestration: Salesforce Agentforce
* Database / Dashboard: Google Sheets
* Notifications: Email (Gmail)

## MVP Scope

The initial MVP focuses on:

* FA generation
* Client tracking dashboard
* Email notification system
* Basic workflow automation

## Demo Scenario

1. A new client intake is entered
2. AI generates a Functional Assessment (FA)
3. The system updates the Google Sheets dashboard
4. Staff receives an email notification
5. Admin monitors completion status in real-time

## Business Value

* Reduces documentation time
* Improves compliance and follow-up
* Increases staff efficiency
* Provides real-time operational visibility

## Roadmap

* Add ITP and DA automation
* Build advanced reporting dashboard
* Integrate read-only data from EHR systems
* Add SMS and voice notifications
* Develop secure HIPAA-compliant infrastructure
* Expand to full AI workflow platform

## Status

🚧 MVP in development

## Author

Abdulhakim Sheik
Founder, Tayo360

## License

This project is for portfolio and demonstration purposes.
