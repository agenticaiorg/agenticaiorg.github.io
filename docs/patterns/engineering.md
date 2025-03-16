---
title: Engineering
parent: Design Patterns
nav_order: 4.2
---

# Architecture & Engineering Patterns
These design patterns provide a way to think about and structure the development of Agentic AI systems, drawing on existing research and established concepts. The choice of which patterns to use will depend on the specific requirements and goals of the AI agent or multi-agent system being developed.

## Memory Management
How agents store and retrieve information
### Short-Term Memory
Maintaining context within a single interaction or task.
### Long-Term Memory
Storing and recalling information across multiple interactions or over time to personalize experiences.
### Entity Memory
Specialized memory for maintaining detailed information about specific entities.
### Team / Organization Memory
Aggregating the memory of related users within the boundary of a team or organization and storing it for further processing or planning by the agent.

## Task Decomposition and Planning Patterns 
How agents break down and address complex tasks.
### Hierarchical Planning
Breaking down goals into sub-goals and actions at different levels of abstraction.
### Means-Ends Analysis 
Identifying the difference between the current state and the desired goal and selecting actions to reduce this difference.
### Step-by-Step Planning
Creating a sequential plan where each step logically leads to the next.
### Dynamic Planning
Adapting plans in response to changes in the environment or user inputs.

## Tool Integration Patterns
Robust methods for agents to accurately and efficiently use external tools and APIs.
### Generalized Agents with Generic Tools
Designing generic agents that can perform wide variety of tasks.
### Specialized Agents with Specific Tools
Designing agents with a focused set of tools tailored to particular reasoning tasks.
### Agent as an API
Reusing an agent through an API across multiple applications.
