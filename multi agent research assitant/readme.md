# Multi-Agent Research Assistant

## Vision

The Multi-Agent Research Assistant is an Agentic AI system where multiple specialized agents collaborate to solve complex research problems.

Instead of one AI doing everything, different agents handle different responsibilities and work together to produce higher-quality results.

---

## Problem Statement

Research often requires multiple steps:

* Information gathering
* Analysis
* Summarization
* Verification
* Final reporting

A single agent can become overloaded.

A multi-agent system divides responsibilities among specialized agents.

---

## Agent Architecture

User Query
↓
Orchestrator Agent
↓
Research Agent
Analysis Agent
Fact Check Agent
Summarizer Agent
↓
Final Report

---

## Agent Responsibilities

### Research Agent

Collects information from available sources.

Responsibilities:

* Gather data
* Identify key concepts
* Extract important facts

---

### Analysis Agent

Analyzes collected information.

Responsibilities:

* Identify patterns
* Compare findings
* Generate insights

---

### Fact Check Agent

Validates information.

Responsibilities:

* Verify claims
* Detect inconsistencies
* Improve reliability

---

### Summarizer Agent

Creates the final response.

Responsibilities:

* Organize findings
* Create concise summaries
* Generate final reports

---

## Workflow Types Demonstrated

### Sequential Workflow

Research
↓
Analysis
↓
Fact Check
↓
Summary

---

### Parallel Workflow

Research Agent
Analysis Agent
Fact Check Agent

Run simultaneously.

Results are combined before generating the final answer.

---

## Technologies

* Google ADK 2.0
* Gemini
* MCP
* Agent Runtime
* Google Cloud

---

## Skills Used

### Research Skill

Information gathering and extraction.

### Analysis Skill

Pattern recognition and reasoning.

### Fact Verification Skill

Validation and consistency checking.

### Summarization Skill

Report generation and communication.

---

## Future Features

* Web Search Integration
* MCP Tool Support
* Research Memory
* Citation Generation
* Knowledge Graph Integration
* Agent-to-Agent Communication

---

## Learning Outcomes

Through this project I learned:

* Multi-Agent Architectures
* Agent Collaboration
* Sequential Workflows
* Parallel Workflows
* Task Delegation
* Agent Skills Design

---

## Example Workflow

User:
"Explain the future of Agentic AI"

↓

Research Agent gathers information.

↓

Analysis Agent identifies major trends.

↓

Fact Check Agent validates claims.

↓

Summarizer Agent generates the final report.

↓

User receives a structured answer.

---

## Status

Currently in design and architecture phase as part of Google's 5-Day Agentic AI Course.
