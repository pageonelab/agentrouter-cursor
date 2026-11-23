# AgentRouter for Cursor

Connect Cursor to AgentRouter to find provider tools, check current prices, approve a budget, and retrieve results and receipts. The plugin includes one remote MCP server and a skill for using it. Paid calls use the AgentRouter account you authorize.

## Install from GitHub

```sh
mkdir -p "$HOME/.cursor/plugins/local"
git clone https://github.com/pageonelab/agentrouter-cursor.git "$HOME/.cursor/plugins/local/agentrouter"
```

Restart Cursor or run **Developer: Reload Window**. Open **Customize** and look for **AgentRouter**. Connect the MCP server and complete the browser sign-in. Enterprise workspaces may require an administrator to enable local plugin imports. [Cursor local plugin guide](https://cursor.com/docs/plugins#test-plugins-locally)

Try a free preview:

> Use AgentRouter to find a Google search tool for US desktop results. Show its current price and required inputs. Stop before spending.

To run the search, give Cursor your keyword and a maximum spend. Ask for the source links, run ID and final charge. [AgentRouter MCP guide](https://docs.agentrouter.to/integrations/mcp?utm_source=cursor&utm_medium=plugin)

## License

The files in this repository are available under the [MIT License](LICENSE).
