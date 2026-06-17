# <img src="logo/grimoire.svg" width="32" height="32" align="center" style="margin-right: 8px;" /> AllCodex Documentation

This repository contains the official documentation source code for the AllCodex worldbuilding platform. The live documentation site is published at [docs.allcodex.allmaker.dev](https://docs.allcodex.allmaker.dev).

This site contains guides, concepts, API specifications, and configuration parameters for all three services in the AllCodex ecosystem.

**[Visit the Live Documentation](https://docs.allcodex.allmaker.dev)**


## AI-assisted writing

Set up your AI coding tool to work with Mintlify:

```bash
npx skills add https://mintlify.com/docs
```

This command installs Mintlify's documentation skill for parsing tools such as Claude Code, Cursor, and Windsurf. The skill includes component references, writing standards, and workflows.

See the [parsing tools guides](/ai-tools) for tool-specific setup.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes on your machine. Run this command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install the GitHub app from the [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from the repository to the deployment. Pushing to the default branch deploys changes to production.

## Need help?

### Troubleshooting

- If your development environment does not run: Run `mint update` to get the latest CLI version.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
