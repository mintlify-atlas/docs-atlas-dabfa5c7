# Claude Analytics Documentation

Documentation for Claude Analytics, a personal analytics dashboard for Claude Code sessions.

## About

Claude Analytics visualizes your Claude Code usage, sessions, costs, tokens, tools, and prompts with 100% client-side processing. Your data never leaves your browser.

Visit the [documentation site](https://docs.claude-analytics.com) to learn more.

## Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation locally:

```bash
npm i -g mint
```

Run the development server from the root of your documentation:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Project Structure

- `index.mdx` - Landing page
- `introduction.mdx` - Introduction and overview
- `quickstart.mdx` - Getting started guide
- `setup/` - Setup guides (local mode, hosted mode, export data)
- `features/` - Feature documentation
- `guides/` - Usage guides
- `reference/` - Technical reference and API documentation

## Publishing Changes

Changes pushed to the default branch are automatically deployed to production.

## Need Help?

- [Mintlify documentation](https://mintlify.com/docs)
- [Claude Analytics repository](https://github.com/1shanpanta/claude-analytics)
