# socai

**Browser-grounded social research, from captured evidence to source-linked
reports.**

[Website][site] · [socai][socai-repo] · [Jev Social][jev-repo] ·
[Discord][discord]

## Jev Social

**One research goal → Jev typed routing → socai CLI → real browser evidence →
a cited report.**

Jev Social is a lightweight, MIT-licensed reference app for Instagram, TikTok,
and LinkedIn research. It uses Jev only for bounded decisions, keeps social-site
work inside the local socai CLI, streams post cards as evidence arrives, and
preserves links back to the source.

[View the project][jev-site] · [Watch the recorded run][jev-replay] ·
[Privacy and data flow][jev-privacy] · [Read the source][jev-repo] ·
[Star Jev Social][jev-repo]

[![GitHub stars](https://img.shields.io/github/stars/socai-io/jev-social?style=social)][jev-repo]

Install the versioned Agent Skill for Codex:

```bash
gh skill install socai-io/jev-social jev-social@v0.1.13 --agent codex --scope user
```

[![Jev Social routes a research goal and streams captured social evidence into
a report][jev-demo]][jev-repo]

## socai CLI

**A local agent that actually reads social media.**

socai drives the signed-in Chrome session you already use to research
Xiaohongshu, Douyin, TikTok, Instagram, and LinkedIn. It can search, open posts,
expand comments, read profiles, capture media, run OCR or transcription, and
retain reviewable artifacts. The portable Agent Skill keeps agent-driven research read-only; direct CLI actions stay explicit and user-invoked.

[Visit socai.io][site] · [Get the desktop app][socai-release] ·
[Use the CLI][socai-cli]

[![socai research flow from browser discovery through reasoning to structured
findings][socai-banner]][socai-repo]

## More from socai

- [dsh-socai][dsh-repo] — a DeepSeek Harness plugin for socai research tools.
- [Jev Social launch notes][jev-launch] — architecture, current limits, and ways
  to contribute.

We welcome reproducible bug reports, platform fixtures, and small integrations
that keep evidence inspectable.

[discord]: https://discord.gg/CpQdA7bwt8
[dsh-repo]: https://github.com/socai-io/dsh-socai
[jev-demo]: https://raw.githubusercontent.com/socai-io/jev-social/main/docs/jev-social.gif
[jev-launch]: https://github.com/socai-io/jev-social/discussions/6
[jev-replay]: https://socai-io.github.io/jev-social/recorded-run/
[jev-privacy]: https://socai-io.github.io/jev-social/privacy/
[jev-repo]: https://github.com/socai-io/jev-social
[jev-site]: https://socai-io.github.io/jev-social/
[site]: https://socai.io/
[socai-banner]: https://raw.githubusercontent.com/socai-io/socai/main/docs/assets/socai-readme-banner.png
[socai-cli]: https://github.com/socai-io/socai#command-line
[socai-release]: https://github.com/socai-io/socai/releases/latest
[socai-repo]: https://github.com/socai-io/socai
