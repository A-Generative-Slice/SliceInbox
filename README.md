# LiteLab Inbox Management System (MCP Workspace)

An autonomous Model Context Protocol (MCP) workspace serving as the **Executive AI Chief of Staff** for LiteLab. It provides secure routing and inbox management across four separate Zoho Mail channels.

## Features
- **4-Inbox Architecture**: Separates commercial, design enquiry, administration, and executive communications.
- **Auto-routing Rules**: Built-in instructions directing the AI agent to interact with the correct mail tools based on context.
- **Easy Portability**: Sanitized templates to easily migrate configurations to other computers.

## Directory Structure
- `agent_instructions.md` — Core instructions and routing rules for the AI Chief of Staff.
- `.gitignore` — Excludes sensitive local credential files from git.
- `.env.example` — Template for local email settings.
- `.agents/mcp_config.json.example` — Template for MCP server setups.
- `ceo_setup_instructions.md.example` — Step-by-step migration guide for the CEO's PC.

## Installation & Setup

1. **Clone the repository** to your local workspace directory.
2. **Rename Example Templates**:
   - Copy `.env.example` to `.env` and fill in your actual Zoho Mail passwords.
   - Copy `.agents/mcp_config.json.example` to `.agents/mcp_config.json` and fill in your App Passwords.
3. **Configure your client**:
   - Follow the detailed steps in [ceo_setup_instructions.md.example](./ceo_setup_instructions.md.example) to load the MCP servers on your AI assistant.
