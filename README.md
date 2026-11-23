<p align="center">
  <a href="https://escadreai.com/?utm_source=github.readme"><img src="https://escadreai.com/assets/escadre-lockup.svg" alt="Escadre" height="56"></a>
</p>

<h3 align="center">Run Claude Code, Codex and Mistral Vibe side by side.<br>Know which result matches what you asked.</h3>

<p align="center">
  <a href="https://escadreai.com/?utm_source=github.readme#access"><b>Get the Mac beta</b></a> ·
  <a href="https://escadreai.com/multi-agent?utm_source=github.readme">How it works</a> ·
  <a href="https://escadreai.com/compare?utm_source=github.readme">Compare</a> ·
  <a href="https://escadreai.com/guides?utm_source=github.readme">Guides</a>
</p>

<p align="center">
  <a href="https://escadreai.com/multi-agent?utm_source=github.readme"><img src="https://escadreai.com/assets/press/escadre-ph-s1.jpg" alt="Escadre running three features at once, each with its own coding agent and branch, with one release held because the agent did more than asked" width="860"></a>
</p>

Escadre is a desktop app for building software with the coding agent you already use. Each feature gets its own agent, its own branch and its own pull request, so several run at the same time without overwriting each other. When an agent finishes, Escadre compares the result with your request and tells you in plain words whether it matches. If the agent did more, less or something else, Escadre holds the release until you decide.

This repository only hosts the macOS builds. Escadre's source code is not public.

## What you get

- **Several agents, one project.** Claude Code, Codex and Mistral Vibe, mixed as you like: pick the agent per feature.
- **"Does it match what I asked?"** For every feature, what you asked next to what the agent did, with the gaps spelled out.
- **A yes before anything irreversible.** Deleting data, touching production or spending money always waits for you, whatever the agent's own settings.
- **A gate before release.** A feature that drifts from your request isn't released until you say so.
- **One project map for every agent.** Escadre keeps a map of where things live, the conventions and the decisions already made, so four features still feel like one app.
- **Your code, your agent, your account.** Escadre has no model and no account of its own, and never sees your passwords or keys.

Built for people who started with an app builder like Lovable, Bolt or Replit and now keep going on their own code with a coding agent.

## Download

The beta is free and runs on **macOS with Apple silicon (M1 and later)**. Windows and Linux come later.

1. Leave your email at **[escadreai.com](https://escadreai.com/?utm_source=github.readme#access)**: the download link and install guide arrive right away. We use it to tell you about new versions.
2. Or grab the latest `.zip` from **[Releases](https://github.com/IronLight/escadre-releases/releases/latest)**.

### First launch

The beta isn't signed by Apple yet, so macOS blocks it the first time.

1. Unzip, move **Escadre** to Applications and open it once.
2. Open **System Settings → Privacy & Security**, scroll to Security and click **Open Anyway** next to Escadre.
3. Confirm with your Mac password. You only do this once.

If macOS still refuses, run this in Terminal:

```bash
xattr -dr com.apple.quarantine /Applications/Escadre.app
```

### Updating

The beta doesn't update itself yet. Download the new version from [Releases](https://github.com/IronLight/escadre-releases/releases) and replace the app in Applications. Your projects aren't affected: Escadre keeps its notes in a `.escadre` folder inside each project.

## Questions

**Which agents does it support?**
Claude Code, Codex and Mistral Vibe, several at once in one project. Each runs on your own account, as it would in your terminal.

**How is it different from Claude Code's desktop app, Conductor or Cursor?**
They help you run agents and read diffs. Escadre adds the check those tools leave to you: whether each result is what you asked for. See the [sourced comparisons](https://escadreai.com/compare?utm_source=github.readme), including where the other tools win.

**Does Escadre send my code anywhere?**
No. Your code stays on your machine and with the agent you chose. Escadre has no copy of it.

**Is it open source?**
No. Escadre is a proprietary app built on the open source base of VS Code (Code-OSS, MIT license). This repository holds installers only.

## Learn more

- [Run several coding agents in parallel](https://escadreai.com/multi-agent?utm_source=github.readme)
- [Claude Code GUIs in 2026: what exists and who each one suits](https://escadreai.com/guides/best-claude-code-gui?utm_source=github.readme)
- [How to run several Claude Code agents in parallel](https://escadreai.com/guides/run-claude-code-agents-in-parallel?utm_source=github.readme)
- [How to check what your coding agent actually changed](https://escadreai.com/guides/check-what-your-coding-agent-changed?utm_source=github.readme)

## Feedback

Something broke or felt confusing? Open an [issue](https://github.com/IronLight/escadre-releases/issues) or write to [hello@escadreai.com](mailto:hello@escadreai.com).

---

<sub>Escadre is an independent project, in beta. Claude Code is a trademark of Anthropic, Codex of OpenAI and Mistral Vibe of Mistral AI; Escadre is not affiliated with them. Visual Studio Code is a trademark of Microsoft; Escadre is not affiliated with Microsoft.</sub>
