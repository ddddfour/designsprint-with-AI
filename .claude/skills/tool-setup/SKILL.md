---
name: tool-setup
description: >-
  Set up and configure tools and integrations needed for the design sprint,
  including MCP server connections (Figma, including FigJam and Figma Make)
  and design token tooling. Use this skill when a team member needs help
  connecting to an MCP server, verifying tool connections, or setting up any
  sprint tool.
---

# Tool Setup

## MCP Server Configuration

### Pre-configured (in `.mcp.json`)

These servers are available to everyone working in this repo:

#### Figma MCP (Remote)
- **URL:** `https://mcp.figma.com/mcp`
- **First-time auth:**
  1. Start Claude Code in this repo
  2. Type `/mcp` and select `figma`
  3. Select "Authenticate"
  4. Click "Allow Access" in the browser
  5. Confirm "Authentication successful" in Claude Code
- **Capabilities:** Read design files, extract variables and tokens, generate code from frames, Figma Make (turn live UI into Figma frames), and FigJam boards
- **FigJam:** Use a FigJam file as the shared workshop board for How Might We notes, Crazy 8s, dot voting, and storyboards. This is the remote stand-in for a physical wall, and a useful copy of the wall even when the team is in the same room.
- **Rate limits:** Dev/Full seats on paid plans have per-minute rate limits. Starter/View/Collab seats are limited to 6 tool calls/month.

#### Fetch MCP
- **Command:** `npx -y @modelcontextprotocol/server-fetch`
- **No auth needed** - works immediately
- **Capabilities:** Fetch web content as HTML, JSON, plain text, or Markdown
- **Prerequisite:** Node.js must be installed (`node --version` to verify)

## Verification Checklist

Run through this checklist at the start of the sprint:

1. **Claude Code running:** `claude` launches successfully in the repo
2. **Figma MCP:** `/mcp` shows `figma: connected` (after auth)
3. **Fetch MCP:** `/mcp` shows `fetch: connected`
4. **Node.js available:** `node --version` returns a version (required for MCP servers)
5. **FigJam board:** A FigJam file exists for workshop activities, or the team has a physical wall and will photograph it
6. **Git access:** `git status` shows clean working tree

## Troubleshooting

### MCP server not connecting
- Restart Claude Code after any `.mcp.json` changes
- Check Node.js is installed: `node --version`
- For Figma: ensure you have a Figma account with appropriate permissions
- Check timeout: `MCP_TIMEOUT=10000 claude` for slower connections

### Figma authentication failed
- Clear and retry: `/mcp` > figma > Authenticate
- Ensure popup blocker is not blocking the auth window
- Try the Figma desktop app alternative: `claude mcp add --transport http figma-desktop http://127.0.0.1:3845/mcp`
