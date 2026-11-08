# Reelium agent skill

An agent skill that lets Claude Code and other agents run Reelium for you: find the moments in your
Twitch stream that your audience reacted to, frame and trim them, render captioned vertical clips,
and post them to YouTube Shorts, TikTok or Instagram Reels.

It drives your own Reelium account through Reelium's MCP server. You sign in through the browser,
choose which permissions the agent gets, and set what it may do without asking. Reelium enforces
both on its side.

## Install

```
npx skills add ReeliumAI/skills
```

Then connect the server:

```
claude mcp add --transport http reelium https://reelium.ai/api/mcp
```

Run `/mcp` and sign in. Setup for other clients: <https://reelium.ai/mcp/claude>

## What's in it

- [`reelium/SKILL.md`](reelium/SKILL.md): how to connect, the clip loop, and the rules an agent
  follows.

Reelium: <https://reelium.ai>
