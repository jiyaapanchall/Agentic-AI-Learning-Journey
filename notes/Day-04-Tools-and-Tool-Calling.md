# Day 04 — Tools and Tool Calling in AI Agents

## 1. What are Tools?

Tools are external capabilities that an AI agent can use to perform tasks, retrieve information or interact with other systems.

An LLM can generate responses, but it may need external tools to access live information or perform certain operations.

## 2. Examples of Tools

- Search Tool: Finds information from the internet.
- Calculator: Performs mathematical calculations.
- Database: Stores and retrieves information.
- Calendar: Interacts with calendar events.
- Code Execution Tool: Runs code in an appropriate environment.
- PDF Reader: Extracts information from PDF documents.

## 3. What is Tool Calling?

Tool calling is the process through which an AI model requests the use of a particular tool to complete a task.

For example, if a user asks for the average of 80, 90 and 70, the model may request a calculator tool.

The tool performs the calculation and returns the result to the application, which can then provide the final answer.

## 4. Basic Tool Calling Workflow

1. User provides a request.
2. AI model understands the task.
3. Model decides whether a tool is needed.
4. Model requests a tool call with the required inputs.
5. The application executes the tool.
6. The tool returns a result.
7. The AI model uses the result to generate a response.

## 5. Tool vs Tool Calling vs Tool Result

| Term | Meaning |
|---|---|
| Tool | An external capability |
| Tool Calling | Requesting the use of a tool |
| Tool Result | Output returned by the tool |

## 6. CareerPilot AI Example

In my planned CareerPilot AI project, different tools could help with different operations:

- PDF reader: Extract text from resumes.
- LLM: Understand skills and experience.
- Database: Store user progress.
- Job search API: Retrieve job descriptions.
- Document generator: Create learning roadmaps.

## 7. Important Considerations

- Tools should be selected according to the task.
- Tool inputs and outputs should be validated.
- Tools may fail or return incomplete information.
- Sensitive actions should have appropriate user permission and confirmation.
- An AI agent should not assume a tool succeeded without checking its result.

## 8. Key Takeaways

- Tools extend what an AI agent can do.
- Tool calling allows an AI model to request external capabilities.
- The application or agent system executes the requested tool.
- Tool results can be used to generate the final response.
- Permissions and validation are important when using tools.

## 9. What I Learned Today

Today, I learned what tools are and how AI agents use tool calling to perform tasks beyond generating text.

I also explored examples such as search tools, calculators, databases and code execution tools.

I connected these concepts to my planned CareerPilot AI project to understand how tools can be used in a real-world application.

## Questions I Still Have

- How does an AI model know which tool to select?
- How are tools connected to an LLM?
- What happens when a tool fails?

---

**Learning Status:** Day 04 Completed  
**Next Topic:** Context and Memory in AI Agents.
