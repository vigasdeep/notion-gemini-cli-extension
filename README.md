# Notion - Gemini CLI Extension

**🚧 Project in development – commands and features below are proposed and not yet implemented. 🚧**

The Notion Gemini CLI Extension aims to connect your Notion workspace with the Gemini CLI, enabling command-line and AI-assisted workflows for Notion.

## Project Goals

- **Authenticate with Notion** from the command line.
- **List and view Notion pages/databases**.
- **Query, summarize, and edit Notion content** using Gemini-powered natural language.
- **Automate Notion workflows** via CLI and AI.

## Planned Features

- Secure OAuth authentication with Notion.
- Command-line listing and viewing of Notion content.
- Natural language queries against your Notion workspace.
- Page and database creation/editing from the CLI.
- Integration with Gemini for automation and smart actions.

## Installation

You can install this extension into your Gemini CLI environment using:

```bash
gemini extensions install https://github.com/vigasdeep/notion-gemini-cli-extension
```

_Note: This extension is in development. Installation will add the extension to your Gemini CLI, but available commands may be limited or nonfunctional until initial releases are made._

## Enabling the Extension

After installation, you can verify that the extension is enabled by listing your installed extensions:

```bash
gemini extensions list
```

You should see `notion-gemini-cli-extension` in the output.

## Example Commands (Proposed)

_Note: These commands are planned, not yet implemented._

```bash
# Authenticate with Notion
gemini notion auth

# List pages
gemini notion list pages

# Search Notion content
gemini notion query "Show my recent meeting notes"

# Create a Notion page
gemini notion create page --title "Todo List" --parent <parent_id>
```

## Contributing

This project is in early development, and all contributions, issue reports, and ideas are welcome!  
If you are interested in helping to define the CLI design or build new features, please open an issue or pull request.

## License

MIT

---

*This extension is not affiliated with Notion Labs Inc. “Notion” and related marks are trademarks of Notion Labs Inc.*
