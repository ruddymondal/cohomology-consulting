+++
title = "Our Method"
description = "From classical operations research to adaptive graph intelligence to structural coherence analysis."
layout = "page"
+++

# Our Method

We combine three layers into a single coherent methodology:

1. A **standard operations research (OR) engine** to optimise workloads and resources.  
2. An **adaptive graph intelligence layer** (GCN-style) to keep priorities and risk assessments current.  
3. A **structural coherence analysis** layer that uses rigorous topology-style tools to expose contradictions in the underlying operating model.

---

## 1. Operations Research Engine

### 1.1 Problem framing

We start by turning your informal complaints into a precise optimisation problem:

- What are the **decision variables**?

  - Assignment of people and labs to projects.  
  - Selection or scheduling of projects.  
  - Trigger points for approvals and reviews.

- What are the **constraints**?

  - Headcount and skills.  
  - Lab and equipment capacity.  
  - Budget limits and time windows.  
  - Regulatory or contractual requirements.

- What are the **objectives**?

  - Strategic impact (weighted value of projects).  
  - Throughput and time-to-completion.  
  - Risk balance across portfolios.

### 1.2 Model construction

We then:

- Encode the problem as one or more mixed-integer or linear programs.  
- Add constraint programming where scheduling is complex.  
- Build simulation hooks to test scenarios and uncertainty.

### 1.3 Analysis and outputs

From these models, we:

- Find optimal or near-optimal staffing and portfolio configurations.  
- Generate load and overload metrics by team, lab, and role.  
- Run “what if” scenarios:

  - “What if we hire in this capability?”  
  - “What if we pause this category of projects?”  
  - “What if we lift this constraint?”

This gives you a defensible baseline: a clear map from your current commitments and constraints to feasible and efficient operating configurations.

---

## 2. Adaptive Graph Intelligence Layer

### 2.1 Graph construction

We represent your organisation as a graph:

- **Nodes**: people, teams, labs, projects, committees, resources.  
- **Edges**: task assignments, dependencies, approvals, shared constraints, data flows.

Each node and edge carries features such as:

- Current workload and utilisation.  
- Historical delay and conflict data.  
- Role type and responsibility.  
- Position in the OR-derived optimal configurations.

### 2.2 Learning and scoring

On top of this graph, we train graph-based models to:

- Learn embeddings for nodes and edges that encode their structural role and stress level.  
- Predict risk scores for overload, delay, or conflict.  
- Rank nodes and edges by criticality for throughput and resilience.

### 2.3 Integration with decision-making

We use these scores to:

- Flag emerging hotspots before they become failures.  
- Guide attention and escalation.  
- Feed priority signals back into the OR engine so that new optimisation runs automatically weight the right parts of the system.

The result is a fast, adaptive layer that keeps your planning and monitoring aligned with how your structure actually behaves over time.

---

## 3. Structural Coherence Analysis

### 3.1 Structural mapping

We then focus on the deeper question:

> Under your current definitions of objectives, KPIs, and rules, is coherent execution even possible?

To answer this, we:

- Identify the key units, mandates, KPIs, and shared constraints.  
- Build a graph of units and their interfaces (where they must agree or interact).  
- Attach structured state spaces to each unit (local obligations, capacities, targets) and to each interface (shared responsibilities).

### 3.2 Coherence analysis

Using this model, we:

- Determine where local objectives and rules admit globally consistent solutions.  
- Detect loops of constraints and KPIs that cannot be satisfied together under shared limitations.  
- Separate **execution problems** (solvable by better management and resource allocation) from **structural impossibilities** (unsolvable without changing the rules).

### 3.3 Intervention design

For each identified impossibility or fragile structure, we:

- Identify the minimal set of KPIs, mandates, or interfaces that need to change.  
- Use OR and graph models to quantify impact and trade-offs.  
- Package proposals into implementable structural changes:

  - KPI rewrites.  
  - Mandate realignments.  
  - Adjusted decision rights and approval flows.

This ensures that when you optimise portfolios and monitor risk, you are operating within an operating model that is capable of coherence rather than silently forcing failure.

---

## 4. Putting it together

Our methodology is deliberately layered:

- The **OR engine** ensures that, given a coherent model, you use your resources well.  
- The **graph intelligence layer** keeps your view of stress and priority current without constant rebuilding.  
- The **structural coherence analysis** ensures that the entire configuration is capable of working as a whole.

Each layer is valuable on its own.  
Together, they give you a rigorous, adaptive, and explainable way to design and maintain a structure that can actually deliver on its commitments.

