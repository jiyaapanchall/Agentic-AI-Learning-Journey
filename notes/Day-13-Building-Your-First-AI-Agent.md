# Day 13 — Building Your First Simple AI Agent in Python

## Objective
Understand how a simple AI-agent-style program makes decisions and uses tools.

## What is an AI Agent?
An AI agent is a system that works towards a goal by understanding a request, deciding what to do, and using tools when needed.

## Chatbot vs Agent
- A chatbot mainly responds to user messages.
- An agent can plan steps and use tools to complete tasks.
- An agent may evaluate results and decide what to do next.

## What is a Tool?
A tool is a function or external capability an agent can use to perform a task.

Examples:
- Calculator
- Web search
- File reader
- Progress tracker

## Our Python Mini Agent
We created a simple career assistant with two tools:

1. `suggest_python_resources()` — suggests Python learning activities.
2. `calculate_progress()` — calculates task completion percentage.

The `career_agent()` function checks the user's message, selects a tool using simple conditions, executes it, and returns the result.

## Agent Workflow
1. Receive the user's request.
2. Understand the request.
3. Select an appropriate tool.
4. Execute the tool.
5. Return the result.

## Important Learning
This is a rule-based prototype, not a fully LLM-powered agent. A real AI agent can use an LLM to interpret requests and choose tools more flexibly.

## Key Takeaway
I learned how Python functions can act as tools and how a simple decision-making workflow can connect user requests with those tools.

## Next Step
Explore how an LLM can make tool-selection decisions instead of relying only on fixed `if-else` conditions.
