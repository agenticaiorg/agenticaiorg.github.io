---
title: Design Principles
parent: Concepts
nav_order: 2.5
---

# Design Principles

## Action Awareness
Enables agents to assess their own state and performance, allowing for moment-by-moment adjustments.  This self-awareness allows agents to make moment-by-moment adjustments, correct errors, and optimize their behaviour.

## Completeness
Ensuring that all necessary information is included in the task decomposition. This prevents critical aspects from being overlooked.

## Human In The Loop (HITL)
Human-in-the-loop design principles might be incorporated to allow for human oversight and intervention in agent processes.

## Feedback Loop
Incorporating a Feedback Loop allows agents to learn from their actions and environmental responses, improving their performance over time.

## Memory
Agent stores and retrieves conversations, actions, and observations across various timescales. This allows them to learn from experience, maintain context, and make more informed decisions.

## Non-Redundancy
Avoiding unnecessary or duplicate content in sub-tasks. This reduces inefficiency and ensures that agents are not performing the same work.

## Reward Model
Consideration of a Reward Model is crucial when designing learning agents, as it shapes the agent's behaviour by defining what constitutes a desirable outcome.

## Solvability
Each sub-task should be independently and completely resolvable by at least one agent. This ensures that the system can effectively address all aspects of the problem.

## State Management
Effective State Management is necessary for agents to keep track of their plans, completed tasks, and the results of their actions.

## Termination Condition
Designing for Clear Termination Conditions is important to ensure agents (especially in multi-agent conversations) know when a task or interaction is complete.