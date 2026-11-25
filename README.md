# AgentRouter for Cursor

Connect Cursor to AgentRouter to find provider tools, check prices and retrieve results and receipts. The plugin includes one remote MCP server, the general AgentRouter skill and four research skills. Paid calls use the AgentRouter account you authorize.

## Install from GitHub

```sh
mkdir -p "$HOME/.cursor/plugins/local"
git clone https://github.com/pageonelab/agentrouter-cursor.git "$HOME/.cursor/plugins/local/agentrouter"
```

To update a Git installation, run `git -C "$HOME/.cursor/plugins/local/agentrouter" pull --ff-only`. Restart Cursor or run **Developer: Reload Window**. Open **Customize** and look for **AgentRouter**. Connect the MCP server and complete the browser sign-in. Enterprise workspaces may require an administrator to enable local plugin imports. [Cursor local plugin guide](https://cursor.com/docs/plugins#test-plugins-locally)

Try a free preview:

> Use AgentRouter to find a Google search tool for US desktop results. Show its current price and required inputs. Stop before spending.

You can also inspect the inputs and pricing for this example on the [Google organic search tool page](https://www.agentrouter.to/tools/dataforseo.serp_google_organic?utm_source=cursor&utm_medium=plugin).

To run the search, give Cursor your keyword. Include a USD cap if you want one. Ask for the source links, run ID and final charge. [AgentRouter MCP guide](https://docs.agentrouter.to/integrations/mcp?utm_source=cursor&utm_medium=plugin)

## Bundled skills

Ask in your own words or name a skill. The host uses its description to select the instructions.

| Skill | Try asking |
| --- | --- |
| [competitor-brief](skills/competitor-brief/SKILL.md) | Which alternatives do buyers mention on Reddit, and what made them switch? |
| [job-shortlist](skills/job-shortlist/SKILL.md) | Find three Toronto sales roles I can apply for today. Link the employer forms. |
| [growth-teardown](skills/growth-teardown/SKILL.md) | How does this product turn free users into referrals? Show where that happens. |
| [ugc-teardown](skills/ugc-teardown/SKILL.md) | Use my clip notes to write a 12-second Reel for this product, with two opening lines. |

## License

The files in this repository are available under the [MIT License](LICENSE).
