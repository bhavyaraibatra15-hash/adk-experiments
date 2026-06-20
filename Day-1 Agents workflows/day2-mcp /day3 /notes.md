# Day 3 - Agent Skills

## Concepts Learned

### What Is A Skill?

A skill is a reusable package of expertise that an agent can load when needed.

A skill can contain:

* Instructions
* Knowledge
* Workflows
* References
* Tools

Skills help agents perform specialized tasks without loading unnecessary information.

---

## Why Skills Matter

Without skills:

Agent loads everything at once.

Problems:

* Large context
* Higher token usage
* Slower responses
* More confusion

With skills:

Agent loads only the expertise needed for the current task.

Benefits:

* Faster execution
* Better accuracy
* Lower costs

---

## Progressive Disclosure

Progressive Disclosure means loading information gradually.

Level 1:
Skill Name

Level 2:
Skill Instructions

Level 3:
References, Assets, and Supporting Files

Only the required information is loaded.

---

## Skills vs MCP

### Skill

Provides expertise.

Example:

Satellite Analysis Skill

Teaches the agent how to analyze satellite data.

### MCP

Provides access.

Example:

Google Drive MCP

Allows the agent to access files.

Simple Rule:

Skill = Know How

MCP = Access

---

## Procedural Memory

Skills store procedures.

Example:

How to review an expense report.

How to analyze a launch mission.

How to generate a hackathon idea.

This is different from storing facts.

---

## Meta Skills

Meta Skills help create or improve other skills.

Example:

A skill that generates new reusable skills from successful workflows.

---

## Real World Example

Bharat Antariksh Agent

Skills:

* ISRO Research Skill
* Satellite Analysis Skill
* Space Education Skill
* Mission Explorer Skill

The agent activates only the skill required for the user's request.

---

## Key Learning

Many problems that previously required multiple agents can now be solved using a single agent equipped with multiple specialized skills.

Skills make agents more efficient, reusable, and scalable.
