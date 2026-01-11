# HealthSense_AI

AI-Driven Multi-Agent Healthcare System with n8n

## Overview

HealthSense AI is an intelligent, multi-agent healthcare system built using n8n to provide personalized, context-aware health insights while ensuring medical accuracy and compliance.

## Features

A modular, advanced multi-agent system that can:
- Book doctor appointments
- Compare hospitals and find emergency services
- Retrieve diagnostic test recommendations
- Fully orchestrated using a Coordinator Agent on n8n to route user queries to specialized healthcare agents intelligently

## Problem Statement

Users want to:
- Find available doctors and book appointments
- Compare hospitals based on specialization, services, and emergency availability
- Get diagnostic test recommendations

### Example User Queries

- "Find an available dermatologist this week."
- "Which hospitals near me have cardiology departments?"
- "What tests should I take for persistent headaches?"

## Dataset

| Dataset Fields | Description | Details |
|----------------|-------------|---------|
| **Doctors Info** | Name, Specialization, Contact Details | Basic doctor profiles including specialty and contact info |
| **Doctors Slots** | Doctor Name, Available Appointment Times | Available slots linked to each doctor |
| **Hospital Information** | Hospital Name, Specialties, Address, Ratings | Hospital profiles with services offered and ratings |
| **Emergency Data** | Hospital Name, Ambulance Availability, Emergency Availability | List of hospitals with ambulance and ER readiness |
| **Lab Tests Information** | Test Name, Preparation Instructions | Diagnostic test details with preparation guidelines |

## Technology Stack

- **Platform**: n8n (Low-code/No-code automation)
- **Architecture**: Multi-agent system with Coordinator Agent
- **AI**: Natural Language Processing for query routing

## License

IK Projct work for n8n platform

[Add license information here]
