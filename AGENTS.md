> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- The product is **Hookline**, a fictional webhook delivery platform. Use `hookline.example` domains only.
- "Your app" is the system that sends events; "your customers" or "consumers" receive webhooks.
- Use "application" (one per customer), "endpoint" (a URL), "event type", "message" (one event), and "attempt" (one delivery try).
- Use "workspace" not "organization" or "project", and "member" not "user" for people on a workspace.
- Reuse content from `snippets/` (prerequisites, warnings, retry schedule, signature code) instead of duplicating it.

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
