# Weldr — Tools for Teams That Ship

Marketing and documentation site for the Weldr ecosystem.

🌐 **Live site:** https://vonwao.github.io/weldr-site

## The Tools

| Tool | Description | Repo |
|------|-------------|------|
| **weld-sync** | Auto-commit, auto-merge, real-time team sync | [weldr-v3](https://github.com/vonwao/weldr-v3) |
| **code-chat** | AI-powered code editing in the browser | [code-chat](https://github.com/vonwao/code-chat) |
| **next-task** | AI task loop — ship while you sleep | Coming soon |

## Philosophy

- No PRs for 5-person teams
- AI is a teammate, not a tool
- Speed > ceremony
- Open source, own your stack

## Development

This is a static site. No build step needed.

```bash
# Local preview
npx serve .

# Or just open index.html in a browser
```

## Deployment

Hosted on GitHub Pages. Push to `main` to deploy.

## Structure

```
weldr-site/
├── index.html          # Main landing page
├── styles.css          # Global styles
├── tools/
│   ├── tool.css        # Tool page styles
│   ├── sync.html       # weld-sync page
│   ├── code-chat.html  # code-chat page
│   └── next-task.html  # next-task page
└── README.md
```

## License

MIT
