# Mempipe plugins

Plugins that connect AI coding tools to [Mempipe](https://www.mempipe.ai), where your documents, notes and CSV files live in Spaces.

## Claude Code

Mempipe Notebook (the `mempipe` plugin) connects Claude Code to every Space your Mempipe account belongs to. Claude Code can then:

- list your Spaces, browse their folders and search them;
- read PDFs and Markdown notes, and cite the exact passage in Mempipe;
- run SQL over your CSV files;
- with write access, save and replace Markdown notes and delete a file you name.

### Install

In your terminal:

```bash
claude plugin marketplace add mempipe/plugins
claude plugin install mempipe@mempipe
```

Or inside Claude Code, run `/plugin marketplace add mempipe/plugins`, then `/plugin install mempipe@mempipe`.

### Sign in

Start Claude Code, run `/mcp`, and choose `plugin:mempipe:mempipe`. Your browser opens Mempipe. Sign in, then approve access. Tick write access on that page only if you want Claude Code to save notes.

You need a Mempipe account. Sign up at [mempipe.ai](https://www.mempipe.ai).

### Notes

- Claude Code runs in a terminal, so the notebook's file library, which opens beside the chat in ChatGPT, does not show here. Ask your question, and Claude Code searches and reads your files.
- To connect a single Space instead of your whole account, see [Connect Claude Code to Mempipe](https://www.mempipe.ai/help/agents/connect-claude-code/).
- PDFs and CSV files are added in the [Mempipe web app](https://app.mempipe.ai).

## License

The files in this repository are licensed under the [Apache License 2.0](LICENSE). The license grants no rights to the Mempipe name or logo. Using Mempipe through these plugins is governed by Mempipe's [terms](https://www.mempipe.ai/terms/).

## Support

Email [hello@mempipe.ai](mailto:hello@mempipe.ai). See also the [help center](https://www.mempipe.ai/help/), [privacy policy](https://www.mempipe.ai/privacy/) and [terms](https://www.mempipe.ai/terms/).
