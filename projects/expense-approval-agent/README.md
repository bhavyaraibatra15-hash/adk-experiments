# Expense Approval Agent

## Overview

The Expense Approval Agent is an Ambient AI Agent designed to automate expense review and approval workflows.

The system receives expense reports, evaluates business rules, performs AI-powered risk analysis, and routes high-value expenses for human approval.

This project is inspired by Google ADK 2.0 Graph Workflows and Human-in-the-Loop systems.

---

## Problem Statement

Organizations process hundreds of expense reports every month.

Manual review is:

* Time-consuming
* Error-prone
* Expensive
* Difficult to scale

An intelligent agent can automate routine approvals while escalating risky transactions.

---

## Workflow Architecture

Expense Event
↓
Parse Expense Data
↓
Threshold Check

If Amount < $100
↓
Auto Approve
↓
Record Outcome

If Amount ≥ $100
↓
Gemini Risk Analysis
↓
Human Approval
↓
Record Outcome

---

## Technologies

### AI

* Gemini 3.1 Flash Lite

### Framework

* Google ADK 2.0

### Workflow

* Graph Workflow API
* Nodes
* Edges
* RequestInput

### Cloud

* Google Cloud
* Agent Runtime

---

## Key Concepts Demonstrated

### Ambient Agents

The agent continuously listens for incoming expense events.

### Human-in-the-Loop

High-risk expenses require human approval before execution.

### Rule-Based Decision Making

Business rules remain in Python code.

Example:

Amount < $100 → Auto Approve

### LLM Reasoning

Gemini is used only for contextual risk assessment.

---

## Future Features

* Email Notifications
* MCP Integration
* Expense Dashboard
* Cloud Run Deployment
* Audit Trail Database
* Multi-Level Approvals

---

## Learning Outcomes

Through this project I learned:

* ADK 2.0 Workflow Graphs
* Human-in-the-Loop Systems
* Ambient Agent Design
* Agent Runtime Concepts
* AI Governance and Security

---

## Status

Currently in design and prototyping phase as part of Google's 5-Day Agentic AI Course.
