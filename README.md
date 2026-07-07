# 🚦 SafePath AI 3.0
## Multi-Agent QR-Based Urban Accessibility & Road Safety Assistant

> Built for the **Google AI Agents: Intensive Vibe Coding Capstone Project (Kaggle 2026)**

---

# 📖 Overview

SafePath AI 3.0 is an AI-powered multi-agent system designed to improve urban accessibility, emergency response, and responsible parking through anonymous QR-based communication.

Instead of immediately escalating illegally parked vehicles to authorities, SafePath AI enables citizens to anonymously communicate with vehicle owners while preserving the privacy of both parties.

The platform combines QR technology, AI reasoning, computer vision, historical incident intelligence, and governance analytics to promote safer cities.

---

# 🚨 Problem Statement

Unauthorized parking creates numerous real-world problems:

- 🚑 Ambulances unable to enter hospitals
- 🚶 Pedestrian pathways blocked
- 🏫 School entrances obstructed
- 🏢 Apartment gates blocked
- 🛍️ Commercial entrances inaccessible
- 🚦 Traffic congestion
- ⚠️ Delayed emergency response
- 😠 Conflicts between citizens and vehicle owners

Existing systems usually require direct confrontation or immediate police involvement.

SafePath AI introduces a privacy-preserving alternative.

---

# 💡 Proposed Solution

Every registered vehicle receives a unique QR Code.

The QR code is displayed on the windshield (similar to FASTag).

Whenever a citizen encounters an obstructing vehicle:

1. Scan the QR Code
2. Describe the issue
3. Upload supporting images (optional)
4. AI evaluates severity
5. Anonymous notification sent
6. Owner removes vehicle
7. Civic reward generated

Only when necessary does the system escalate the issue to authorities.

---

# 🔄 System Workflow

```text
                 Vehicle Owner
                      │
          Registers on SafePath AI
                      │
          Receives Unique QR Code
                      │
       QR Sticker Placed on Windshield
──────────────────────────────────────────────

Citizen encounters obstruction

          │
          ▼
     Scan QR Code

          │
          ▼
  SafePath AI Application Opens

          │
          ├──────────────┐
          │              │
          ▼              ▼
 Upload Image      Describe Issue

          │              │
          └───────┬──────┘
                  ▼
          Coordinator Agent
                  │
──────────────────────────────────────────────
                  │
                  ▼
              QR Agent
                  │
                  ▼
          Vehicle Information
                  │
                  ▼
           Vision Agent
       (Evidence Verification)
                  │
                  ▼
       Conversation Agent
                  │
                  ▼
          Decision Agent
        (Gemini Reasoning)
                  │
      ┌───────────┼────────────┐
      ▼           ▼            ▼
 Severity     Governance   Notification
   Agent         Agent         Agent
      │
      ▼
 Vehicle Owner Receives Anonymous Alert

      │
      ├───────────────┐
      ▼               ▼
Removes Vehicle    No Response

      │               │
      ▼               ▼
Gamification     Authority Escalation

      │
      ▼
 Analytics & Report Generation
```

---

# 🤖 Multi-Agent Architecture

```
                    Coordinator Agent
                           │
     ┌─────────────────────┼──────────────────────┐
     ▼                     ▼                      ▼
 QR Agent           Vision Agent        Conversation Agent
     │                     │                      │
     └──────────────┬──────┴──────────────────────┘
                    ▼
              Decision Agent
                    │
      ┌─────────────┼───────────────┐
      ▼             ▼               ▼
 Severity      Governance     Notification
   Agent          Agent            Agent
                    │
                    ▼
           Gamification Agent
                    │
                    ▼
             Analytics Agent
                    │
                    ▼
             Report Generator
```

---

# 🤖 AI Agents

## 🟢 Coordinator Agent

Coordinates the complete workflow and orchestrates all specialized agents.

---

## 🔵 QR Agent

Retrieves:

- Vehicle Number
- QR ID
- Owner ID
- Masked Contact
- Historical Incident References

---

## 🟠 Vision Agent

Acts as an evidence verification system.

It analyzes uploaded photographs to:

- verify obstruction
- validate evidence
- support authority escalation
- improve dispute resolution

---

## 🟣 Conversation Agent

Collects contextual information including:

- location
- obstruction type
- emergency status
- user observations

---

## 🔴 Decision Agent

Uses Google Gemini to combine:

- QR information
- conversation
- image evidence
- historical intelligence

to determine:

- severity
- priority
- recommended action
- escalation requirement

---

## 🟡 Notification Agent

Generates anonymous notifications while protecting the privacy of both users.

---

## 🟤 Governance Agent

Determines whether:

- citizen-owner communication is sufficient

or

- authority intervention becomes necessary.

---

## 🟢 Gamification Agent

Promotes responsible civic behaviour.

Quick response

↓

Reward Points

Repeated violation

↓

Negative Civic Score

---

## 🔵 Report Agent

Generates a structured AI incident report summarizing:

- incident
- evidence
- severity
- notification
- governance recommendation

---

# 📊 Datasets

The project utilizes multiple synthetic datasets including:

- Vehicle Registration Database
- QR Mapping Dataset
- Historical Incident Dataset
- Communication Logs
- Accessibility Risk Analysis
- Governance Recommendations
- Emergency Escalation Analysis
- Urban Hotspot Analysis
- AI Priority Dataset
- Machine Learning Feature Importance
- City Intelligence Dataset

---

# 🔒 Privacy First

SafePath AI follows a privacy-preserving architecture.

✔ Anonymous communication

✔ Masked phone numbers

✔ QR-based identity

✔ Evidence-based verification

✔ Secure owner lookup

---

# 🎯 Key Features

- Multi-Agent Architecture
- Google Gemini AI Integration
- QR-Based Vehicle Identification
- Anonymous Communication
- Evidence Verification
- Smart Governance
- Civic Gamification
- Accessibility Intelligence
- Urban Analytics Dashboard
- Historical Incident Intelligence

---

# 🛠 Technology Stack

- Python
- Google Gemini API
- Google AI Studio
- Pandas
- NumPy
- Scikit-learn
- React
- Synthetic Urban Governance Datasets

---

# 🚀 Future Scope

- Mobile Application
- Google Cloud Deployment
- Live QR Verification
- Smart City Integration
- CCTV Integration
- Automatic Obstruction Detection
- Predictive Urban Intelligence
- Real-Time Analytics Dashboard
- Multi-language Support
- Production-Grade Multi-Agent Deployment

---

# 🌍 Impact

SafePath AI aims to transform urban accessibility by enabling faster communication, safer emergency access, improved governance, and greater civic responsibility while respecting individual privacy.

Instead of replacing people, SafePath AI empowers citizens, vehicle owners, and authorities to collaboratively create safer and smarter cities.

---

## Built for

**Google AI Agents: Intensive Vibe Coding Capstone Project 2026**

Google AI Studio • Gemini • Multi-Agent Systems • Urban AI • Smart Governance
