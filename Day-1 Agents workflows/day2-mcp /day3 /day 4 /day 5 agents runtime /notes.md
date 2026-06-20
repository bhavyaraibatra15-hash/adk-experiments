# Day 5 - Agent Runtime, Deployment & Spec-Driven Development

## Concepts Learned

Day 5 focused on moving from building agents to deploying production-ready agent systems.

The goal is not just to create an agent.

The goal is to create agents that can run reliably in real-world environments.

---

## Agent Runtime

Agent Runtime is Google's managed environment for running AI agents.

Benefits:

* Scalability
* Reliability
* Security
* Monitoring
* Logging
* Production Deployment

Instead of running an agent only on a local machine, Agent Runtime allows agents to operate continuously in the cloud.

Workflow:

Local Agent
↓
Agent Runtime
↓
Production Environment

---

## Agents CLI

Agents CLI is Google's command-line tool for building and managing agents.

Common Uses:

* Create projects
* Scaffold agents
* Run evaluations
* Deploy agents
* Monitor deployments

Examples:

agents-cli scaffold

agents-cli eval run

agents-cli deploy

agents-cli info

---

## Ambient Agents

An Ambient Agent operates continuously in the background.

Instead of waiting for user prompts, it reacts to events automatically.

Examples:

* Expense Approval Agent
* Security Monitoring Agent
* Email Processing Agent
* Customer Support Agent

Workflow:

Event
↓
Agent Triggered
↓
Decision
↓
Action

---

## Expense Approval Agent Example

Expense Submitted
↓
Parse Expense Data
↓
Check Threshold

If Amount < $100
↓
Auto Approve

If Amount ≥ $100
↓
Risk Analysis (Gemini)
↓
Human Approval
↓
Record Outcome

Key Learning:

Business rules should remain in code.

The LLM should be used only for reasoning tasks.

---

## Spec-Driven Development (SDD)

Google introduced Spec-Driven Development as a modern software engineering approach.

Traditional Development:

Idea
↓
Write Code
↓
Deploy

Spec-Driven Development:

Specification
↓
AI Agent
↓
Generate Code
↓
Test
↓
Deploy

The specification becomes more important than manually writing every line of code.

---

## What Makes A Good Specification

A strong specification defines:

* Goal
* Requirements
* Architecture
* Workflow
* Security
* Testing
* Deployment

Example:

Goal:
Build an Expense Approval Agent.

Framework:
Google ADK 2.0

Model:
Gemini 3.1 Flash Lite

Workflow:
Graph Workflow API

Deployment:
Agent Runtime

Authentication:
Google Cloud Project

---

## ADK 2.0 Workflow Graphs

Google ADK 2.0 uses graph-based workflows.

Components:

### Nodes

Individual tasks.

Examples:

* Parse Expense
* Risk Review
* Human Approval

### Edges

Connections between nodes.

### RequestInput

Human-in-the-loop interaction.

Used when user approval is required.

---

## Deployment Flow

Developer
↓
ADK Agent
↓
Agents CLI
↓
Agent Runtime
↓
Production Agent

Benefits:

* Managed Infrastructure
* Automatic Scaling
* Monitoring
* Logging

---

## Key Learning

The future of AI engineering is not only writing code.

It is:

* Designing workflows
* Writing specifications
* Building secure systems
* Evaluating performance
* Deploying production-ready agents

A successful AI engineer thinks like a system architect rather than only a programmer.
