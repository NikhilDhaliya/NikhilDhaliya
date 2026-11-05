# Nikhil Dhaliya

21. Dev turned founder, building [Getvik](https://getvik.com) for Indian creators.

[nikhildhaliya.me](https://nikhildhaliya.me) · [Threads](https://www.threads.com/@thecodexe) · [X](https://x.com/thecodexe) · [Email](mailto:nikhildhaliya@getvik.com)

## Building now

| | | |
| :--- | :--- | :--- |
| **[Getvik](https://getvik.com)** | A monetization tool for Indian creators: auto-DMs, a store and UPI checkout. | 3,300+ users |
| **HQ** | Chat and tasks for our team, with Claude as a member. | Internal |

## Agent infra

| | | |
| :--- | :--- | :--- |
| **Studio** | Claude Code on my laptop and cloud VMs, one git repo. Hooks pull at session start, then commit, push and union-merge after every turn. Modal GPUs for TTS, Remotion for rendering. | Laptop + cloud |
| **Central memory** | Markdown memory shared by multiple Claude Code accounts and cloud sessions. One fact per file, an index auto-loaded every session, and a lint hook for size budgets, repeats and broken links. | Multiple accounts |
| **Usage failover** | Watches each account's 5-hour usage. At 95%, the session writes a handoff and resumes on the account with the most room. | Hook |
| **account-watch** | Live usage, sessions and background jobs across every account, in a status band and a side pane. | Claude Code plugin |

## Open source

| | | |
| :--- | :--- | :--- |
| **[Framewright](https://github.com/NikhilDhaliya/framewright)** | An AI-native video editor for Linux, with an MCP server for agents. | GPLv3 |
| **[YouTube MCP](https://github.com/NikhilDhaliya/youtube-mcp)** | A private, read-only YouTube connector for Claude. | MIT |
| **[Lovewall](https://github.com/NikhilDhaliya/lovewall)** | Testimonials: collect with one link, show them anywhere with one line. Free to self-host. | AGPL-3.0 |
| **[devmem](https://github.com/NikhilDhaliya/devmem)** | Scans a codebase and writes context files for AI tools. | CLI |
| **[ideacli](https://github.com/NikhilDhaliya/ideacli)** | Save and recall ideas without leaving the terminal. | CLI |
| **[monilog-sdk](https://www.npmjs.com/package/monilog-sdk)** | Error monitoring and logging, with alerts in Slack. | npm |

## Earlier

| | | |
| :--- | :--- | :--- |
| **[Ideatosystem](https://ideatosystem.com)** | Turns a raw idea into a full system design. Got $2,000 from Google for Startups. | 800+ users |
| **Formhook** | A backend for website forms. | Shut down |
| **Pagepeek** | Analytics for Notion pages. | Shut down |
| **ScreenCheap** | A Loom alternative with no time limit. | Shut down |
| **Chronicut** | Script in, finished faceless documentary out. | Shut down |

## Stack

Next.js, TypeScript, Node.js, Postgres, Docker, Linux.
