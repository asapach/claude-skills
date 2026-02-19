# Claude Skills

A collection of custom skills for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## Skills

### [continuous-code-review](./continuous-code-review/)

A pair programming navigator that reviews your in-progress work and provides conversational guidance. It gathers git context, reads your changed files, and gives feedback the way a colleague sitting next to you would — focused on what matters most, in plain prose.

**Triggers on:** "check my progress", "what do you think?", "review what I have so far", "pair with me", "look at my changes", `/continuous-code-review`

## Installation

```bash
claude install-skill <github-url>/continuous-code-review
```

## License

MIT
