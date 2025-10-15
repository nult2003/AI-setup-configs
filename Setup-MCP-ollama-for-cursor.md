You use one of 2 methods:
# Method 1: 
- Install mcp-ollama:
  uvx mcp-ollama
- Config in the cursor. Add MCP
{
  "mcpServers": {
    "ollama": {
      "command": "uvx",
      "args": [
        "mcp-ollama"
      ]
    }
  }
}
# Method 2:
- Install mcp-ollama:
  pip install mcp-ollama
- Config in the cursor. Add MCP
{
  "mcpServers": {
    "ollama": {
      "command": "python",
      "args": [
        "-m",
        "mcp_ollama"
      ]
    }
  }
}

# If MCP work on the cursor, you'll see the green circle and display 3 tools: list_models, show_model, and ask_model
