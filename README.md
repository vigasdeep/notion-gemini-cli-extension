# Trust, Minimal Permissions, and Authorizing the Extension

This extension only requests the minimal permissions required to access your Notion workspace via the Notion API. You authorize the extension by following the Notion account flow during configuration—the credentials remain local to your machine and are never uploaded anywhere.

# Notion Gemini CLI Extension

This is a CLI extension for Google's Gemini, enabling interaction with Notion workspaces directly from the command line. Quickly fetch, create, or update Notion pages and databases using natural language.

## Features

- Fetch content from Notion databases or pages
- Create and update pages in Notion
- Query Notion using natural language

## Installation

Install the extension via the Gemini CLI:

```bash
gemini extensions install https://github.com/vigasdeep/notion-gemini-cli-extension
```


You will be prompted to authorize access to your Notion workspace. Follow the instructions in your terminal.

## Uninstall

To uninstall the extension, run:

```bash
gemini extensions uninstall notion
```


## Support & Development

Please [open an issue](https://github.com/vigasdeep/notion-gemini-cli-extension/issues) for bugs, feature requests, or support. Pull requests are welcome.
