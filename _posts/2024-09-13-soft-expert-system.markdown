---
title: Soft Expert System
date: 2024-09-13 20:00:00 +0530
categories: [LLM]
tags: [llm, idea]
description: Explore Soft Expert Systems, an evolution of traditional expert systems using large language models (LLMs).
keywords: soft expert system, expert systems, agents, intelligent agents, LLM, AI, reasonable agents
---

Rule-based systems, or what we've traditionally called expert systems, were an early AI approach to bottle up human expertise into if-then statements. They've carved out niches in areas like medical diagnostics or fixing machinery, but let's be honest, their reach has been somewhat limited.

These systems work well when the problem's as straightforward as a flowchart. But throw in the messiness of real life—ambiguity, context, or just plain old common sense—and they start to falter, showing their limits.

Now, Large Language Models (LLMs) provide an interesting alternative. Unlike classical logical engines, they can read and apply rules written in everyday language, grasp a broader context, and even attempt common-sense reasoning—although, let's not kid ourselves, they're not infallible. 

By integrating LLMs as the "interpreter" within a broader system—one that includes a comprehensive list of heuristics, knowledge bases, workflows, and mechanisms to translate real-world situations into textual context—it's possible to build systems capable of solving many problems that were previously intractable with classical expert systems. Let's call such a system a **"Soft Expert System."**

In a Soft Expert System, the LLM serves as the **engine** or **interpreter** that processes textual representations of problems and applies natural-language rules to generate solutions. This is analogous to how classical expert systems used logical engines (like Prolog) to interpret formal rules. Here, the LLM interprets and reasons with rules expressed in natural language.

However, the LLM is just one component of the Soft Expert System. The overall system includes:

- **Rule Sets and Knowledge Bases**: Collections of heuristics and domain-specific knowledge expressed in natural language, which provide the information the LLM needs to reason effectively.
- **Context Representation**: Mechanisms to translate real-world situations into textual context that the LLM can process. This involves summarising relevant information and presenting it in a form the LLM can understand.
- **Workflows and Processes**: Structures like tree-of-thought reasoning, synthesis steps, or other frameworks that guide the LLM's processing and problem-solving. These workflows help manage complex reasoning tasks and break them down into manageable steps.
- **Interaction Management**: Systems to handle inputs and outputs, maintain state, and interact with external systems or users as needed. This ensures that the Soft Expert System can operate effectively within its environment.

## Definitions

A few terms to discuss these concepts more precisely:

### Reasonable Agents

A **Reasonable Agent** is an intelligent system that:

- **Communicates Through Text**: Interacts using text-based input and output.
- **Thinks Like a Human**: Possesses common sense and can reason about problems similarly to human thought processes.
- **Understands Natural Language**: Interprets and applies rules written in everyday language.
- **Operates Within Practical Limits**: Can process a manageable amount of information at one time (e.g., a few thousand to tens of thousands of words).

### Tractable Problems

**Tractable Problems** are challenges that a Reasonable Agent can effectively solve. These problems share the following characteristics:

- **Text-Based Interaction**: The problem can be fully expressed and addressed using text alone, without needing images, sounds, or physical actions.
- **Manageable Rule Set**: Solving the problem requires a reasonable number of common-sense rules—typically in the hundreds or low thousands.
- **Limited Context Size**: All necessary information can be contained within a manageable amount of text.

### Intractable Problems

**Intractable Problems** exceed the capabilities of a Reasonable Agent within a Soft Expert System. They may involve:

- **Multimodal Interaction**: Requiring inputs or outputs beyond text, such as visual or auditory data.
- **Excessive Rule Complexity**: Necessitating an impractically large number of specific rules due to numerous exceptions and variations.
- **Extensive Context Requirements**: Demanding more information than can be reasonably processed in text form.