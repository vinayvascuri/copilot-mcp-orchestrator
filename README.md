# Copilot-MCP-Orchestrator
Enterprise AI Agent with Model Context Protocol (MCP) &amp; DocuSign

Developed a next-generation AI Agent using Microsoft Copilot Studio and the Model Context Protocol (MCP) to automate document lifecycle management. By leveraging MCP, this project bypasses the complexity of traditional custom connectors and Power Automate flows, utilizing a standardized "client-server" architecture to provide the LLM with direct, stateful access to DocuSign’s enterprise tools.

🛠️ Technical Stack

**Orchestration:** Microsoft Copilot Studio (Preview)

**Protocol:** Model Context Protocol (MCP) by Anthropic

**Integration:** DocuSign MCP Server (Developer Sandbox)

**Deployment:** Microsoft Teams & M365 Copilot


🏗️ **Architecture & Implementation**

The project follows the MCP standard to create a seamless link between the AI host and external data:

MCP Host: Configured Copilot Studio as the primary host to coordinate AI reasoning and tool execution.

MCP Server Connection: Established a secure connection to a DocuSign Developer Sandbox via the MCP server, enabling a set of standardized "Tools" (GetTemplates, SendEnvelope, GetAccountDetails).

Standardization vs. Traditional Flows: Unlike legacy REST API connectors that require manual T-SQL or DAX-like logic for data transformation, MCP allows the agent to understand the tool's schema natively, reducing development time and improving reliability.

