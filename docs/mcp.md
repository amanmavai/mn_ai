# Model Context Protocol
  - MCP is an open protocol that standardizes how applications provide context to LLMs.
  - is an open standard that enables developers to build secure, two-way connections 
  - between their data sources and AI-powered tools. 
  - The architecture is straightforward: developers can either expose their data through MCP servers or build AI applications (MCP clients) that connect to these servers.

# MCP Client
MCP Client = AI Assistant + MCP Protocol Support

So when we say "MCP client," we're really talking about AI assistants that can "speak MCP" - meaning they know how to:

Connect to MCP servers
Send standardized requests
Receive and process responses
Use the tools/data provided by MCP servers

## Regular AI Assistant (Non-MCP):

ChatGPT web interface → Can only work with what's built into it
Basic Claude without MCP → Limited to its training data and basic web search

## MCP Client (AI Assistant with MCP):

Claude Desktop → AI assistant that can connect to MCP servers
Zed with AI → Code editor's AI that can use MCP tools
Custom AI app built with MCP support → Your own AI assistant that can connect to MCP servers

## The key difference:
- **Regular AI assistants** are like smartphones without app stores - they can only do what's built-in
- **MCP clients** are like smartphones with app stores - they can extend their capabilities by connecting to MCP servers (like downloading apps)

# Jargon

- **MCP Hosts**: Programs like Claude Desktop, IDEs, or AI tools that want to access data through MCP
- **MCP Clients**: Protocol clients that maintain 1:1 connections with servers
- **MCP Servers**: Lightweight programs that each expose specific capabilities through the standardized Model Context Protocol
- **Local Data Sources**: Your computer’s files, databases, and services that MCP servers can securely access
- **Remote Services**: External systems available over the internet (e.g., through APIs) that MCP servers can connect to


# references
1. https://modelcontextprotocol.io/introduction