# softwarefordev

I’m Jim. This is where I keep side-project tools for people who build software, especially while working with an AI assistant.

Essays on technology, teamwork, and leadership are at [Jim’s Rules](https://jimsrules.com). Warning: opinions abound there. Viewpoints there are Jim's own.

## Projects

The first tool is a Cursor and Github Copilot chat exporter, in Python and in .NET. Both turn a local agent chat into a page you can keep. The command is `ai-chat-export`. It only reads the chat store.

| Project | What it is |
| --- | --- |
| [ai_chat_export](https://github.com/softwarefordev/ai_chat_export) | Python 3.11+ CLI. `ai-chat-export`, or `python -m ai_chat_export` from a checkout. |
| [ai_chat_export_net](https://github.com/softwarefordev/ai_chat_export_net) | The same exporter as a .NET 10 console app, so it runs without a Python install. |

Run either with no arguments and it opens a picker for chats. The list shows title, workspace, and time. Left and right switch between all chats and the current workspace.

HTML is the default. The page follows the chat: the prompt you typed, then the assistant’s visible text. The page lists user turns, and each entry jumps to that turn. `--markdown` writes Markdown instead. `--detail` adds the conversation summary and command blocks. `--tools` adds one caption per tool call. `--verbose` adds system text, injected context, reasoning, and raw tool output.

Both repositories are [MIT](https://github.com/softwarefordev/ai_chat_export/blob/main/LICENSE.MD) licensed.

## Writing and Links

- [Jim’s Rules](https://jimsrules.com) is where Jim's essays live. The focus is teams, people, and getting work done.
- [jimleonardo.com](https://www.jimleonardo.com/) is where Jim's fiction lives.
- Reach Jim on [LinkedIn here](https://www.linkedin.com/in/jimleonardo).
- [https://softwarefordev.com/](https://softwarefordev.com/) is the homepage for softwarefordev.
