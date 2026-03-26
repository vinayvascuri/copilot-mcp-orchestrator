# Copilot-MCP-Orchestrator


# ![](https://img.shields.io/badge/Enterprise_AI_Agent_with_Model_Context_Protocol_(MCP)_%26_DocuSign-blue?style=for-the-badge)

Developed a next-generation AI Agent using Microsoft Copilot Studio and the Model Context Protocol (MCP) to automate document lifecycle management. By leveraging MCP, this project bypasses the complexity of traditional custom connectors and Power Automate flows, utilizing a standardized "client-server" architecture to provide the LLM with direct, stateful access to DocuSign’s enterprise tools.

🛠️ Technical Stack

**Orchestration:** Microsoft Copilot Studio (Preview)

**Protocol:** Model Context Protocol (MCP) by Anthropic

**Integration:** DocuSign MCP Server (Developer Sandbox)

**Deployment:** Microsoft Teams & M365 Copilot


🏗️ **Architecture & Implementation**

The project follows the MCP standard to create a seamless link between the AI host and external data:

**MCP Host:** Configured Copilot Studio as the primary host to coordinate AI reasoning and tool execution.

**MCP Server Connection:** Established a secure connection to a DocuSign Developer Sandbox via the MCP server, enabling a set of standardized "Tools" (GetTemplates, SendEnvelope, GetAccountDetails).

**Standardization vs. Traditional Flows:** Unlike legacy REST API connectors that require manual T-SQL or DAX-like logic for data transformation, MCP allows the agent to understand the tool's schema natively, reducing development time and improving reliability.

🌟 **Key Features**

**Zero-Code Document Routing:** The agent can identify, populate, and send DocuSign templates (e.g., Lease Agreements or RFPs) based on simple natural language prompts.

**Dynamic Context Retrieval:** Ability to query active templates, account statuses, and envelope history in real-time within a chat interface.

**Cross-Platform Deployment:** Published the agent to Microsoft Teams, allowing for enterprise-wide document management directly within the collaboration workspace.

**📈 Business Impact**

**Reduced Integration Complexity:** Eliminated the need for complex Power Automate "Apply to Each" loops and JSON parsing.

**Enhanced User Experience:** Shifted document workflows from manual portal navigation to a conversational AI interface.

**Future-Ready Scalability:** The MCP framework allows for the easy addition of other servers (e.g., ServiceNow, GitHub, Google Drive) using the same standardized protocol.


### 🎥 Implementation Roadmap
1. **Infrastructure:** Initialized Copilot Studio Preview & MCP Host.
2. **Integration:** Connected DocuSign MCP Server & Sandbox.
3. **Configuration:** Built-out signature templates & automated routing.
4. **Validation:** Compared MCP efficiency against legacy Flow connectors.
5. **Deployment:** Published to Microsoft Teams for enterprise use.


<img width="1576" height="820" alt="image" src="https://github.com/user-attachments/assets/2fdb0cc3-2bb1-4a6f-98dd-62d68361fe74" />

<img width="1241" height="919" alt="image" src="https://github.com/user-attachments/assets/f7f48e2a-4b1e-4764-b711-bdb699701b23" />



