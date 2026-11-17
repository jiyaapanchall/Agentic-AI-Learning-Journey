# Day 14 — LLMs and AI Tool Calling

## What is an LLM?
LLM stands for Large Language Model. It is an AI model trained on large amounts of text to understand and generate human-like language.

Examples:
- GPT
- Claude
- Gemini
- Llama

## What is Tool Calling?
Tool calling allows an AI model to request an external function or tool to perform a task.

For example, an AI assistant can request a calculator function to calculate a student's learning progress.

## Tool Calling Workflow
1. User sends a request.
2. LLM interprets the request.
3. LLM selects an appropriate tool.
4. Application validates and executes the tool call.
5. Tool returns its result.
6. LLM uses the result to generate a response.

## Rule-Based vs LLM-Based
- Rule-based systems use fixed conditions such as if-else statements.
- LLM-based systems can interpret natural language and propose suitable tool calls.
- LLM-based tool calling requires an application to execute and validate the requested function.

## Practical Learning
Created a simulated Python tool-calling workflow using a progress calculator.

The example demonstrates how a tool can be selected and executed, but it does not connect to a real LLM.

## Connection to CareerPilot AI
Potential tools include resume analysis, job description analysis, skill gap calculation, learning roadmap generation, and progress tracking.

## Key Takeaway
I learned how LLMs can work with external tools and how tool calling helps AI agents perform tasks beyond ordinary conversation.
