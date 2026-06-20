# Day 4 - Security & Evaluation

## Concepts Learned

Day 4 focused on making AI agents safe, reliable, and production-ready.

An agent is not useful if it is insecure.

An agent is not trustworthy if it cannot be evaluated.

---

## Agent Security

Google introduced multiple layers of security for AI systems.

### Infrastructure Security

Protect servers, containers, and runtime environments.

### Data Security

Protect sensitive user information and credentials.

### Model Security

Protect prompts, instructions, and model interactions.

### Runtime Security

Protect generated code and tool execution.

### Identity & Access

Grant only the permissions required for a task.

### Observability

Track what the agent is doing.

### Governance

Maintain policies, compliance, and audit trails.

---

## Human-in-the-Loop

Important actions should require human approval.

Examples:

* Expense approvals
* Production deployments
* Financial transactions
* Database changes

Workflow:

Agent
↓
Recommendation
↓
Human Approval
↓
Execution

---

## MCP Security Risks

Potential risks include:

### MCP Spoofing

A malicious MCP server pretends to be a trusted tool.

### Data Leakage

Sensitive information is exposed to unauthorized systems.

### Unauthorized Tool Usage

Agents use tools beyond their intended permissions.

---

## Slopsquatting

AI may hallucinate package names.

Example:

Agent suggests a package that does not exist.

An attacker later creates the package and distributes malware.

Prevention:

* Use trusted repositories
* Verify package sources
* Pin package versions

---

## Sandboxing

Generated code should run inside isolated environments.

Examples:

* Containers
* Virtual Machines
* Sandboxes

Benefits:

If something fails, the host system remains safe.

---

## Evaluation

Evaluation measures whether an AI system is performing correctly.

### Key Evaluation Dimensions

1. Intent Satisfaction
2. Functional Correctness
3. Visual Correctness
4. Cost Efficiency
5. Code Quality
6. Trajectory Quality
7. Self Repair

---

## Observability

Observability helps developers understand:

* What the agent is doing
* Why decisions were made
* Where failures occurred

Without observability, debugging becomes difficult.

---

## Key Learning

A successful AI system is not just intelligent.

It must also be:

* Secure
* Observable
* Reliable
* Measurable
* Human-supervised when necessary

Security and evaluation are essential for deploying AI agents in real-world environments.
