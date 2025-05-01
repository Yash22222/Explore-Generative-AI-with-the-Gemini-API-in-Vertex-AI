## **Introduction to Function Calling with Gemini**

### **Overview**
This lab introduces the powerful capability of **function calling** in Gemini via **Vertex AI**, enabling the model to **trigger external tools, APIs, or functions** based on natural language input. Gemini is not only used for generating text but also for **orchestrating logic**, **retrieving real-time data**, and **automating workflows** through external function execution.

### **Key Objectives**
- Understand the **concept of function calling** in LLMs.
- Implement **structured tools** and **function schemas** Gemini can invoke.
- Configure Gemini to **auto-call appropriate functions** based on user input.
- Chain together **model outputs and external function executions**.
- Use **ToolConfig** in Python to connect Gemini with external Python functions.

### **Concepts Covered**
- **Tool Use**: Define external tools/functions that Gemini can call.
- **Function Schema**: Declare input/output formats for tools.
- **Function Calling Flow**: Prompt → Gemini detects intent → Calls function → Returns result.
- **Multi-turn tool use**: Maintain context across several calls.

### **Tasks Performed**
1. **Define and Register Tools**
   - Create Python functions for tasks like math operations, weather lookup, etc.
   - Register them with Gemini using the **Vertex AI SDK**.

2. **Function Calling Trigger**
   - Gemini automatically calls the correct function based on **user prompt intent**.
   - Demonstrated with examples like `"What's the square root of 144?"`

3. **Response Handling**
   - Gemini receives function results and **formats user-friendly replies**.
   - Combines LLM reasoning with **structured outputs**.

4. **Tool Chaining**
   - Gemini can call **multiple tools** in sequence.
   - Showcases the potential for **AI agents and automation**.

### **Tools Used**
- **Vertex AI Workbench**
- **Gemini 1.5 Flash**
- **Vertex AI Python SDK** (`Tool`, `FunctionDeclaration`, `ToolConfig`)
  
### **Skills Gained**
- Define and integrate custom functions with Gemini.
- Enable Gemini to interact with external data sources or logic.
- Build the foundation for **AI agents, chatbots, and tool-augmented assistants**.
