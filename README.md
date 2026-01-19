# Awesome Ralph [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources about Ralph (aka Ralph Wiggum), the AI coding technique that runs AI coding agents in automated loops until specifications are fulfilled.

Ralph is a technique created by [Geoffrey Huntley](https://ghuntley.com) for autonomous AI coding. The core concept is elegantly simple:

```bash
while :; do cat PROMPT.md | claude-code ; done
```

**Key principles:**
- Run an AI agent repeatedly until a PRD/specification is complete
- Progress persists in files and git history, not in context
- Each iteration starts fresh with clean context
- Use "backpressure" (tests, lints, type checks) to validate work
- Philosophy: *"Sit on the loop, not in it"*

## Contents

- [Official Resources](#official-resources)
- [Implementations](#implementations)
  - [Claude Code Plugins](#claude-code-plugins)
  - [Standalone Implementations](#standalone-implementations)
  - [Multi-Agent Systems](#multi-agent-systems)
- [Tutorials & Guides](#tutorials--guides)
- [Articles & Blog Posts](#articles--blog-posts)
- [Podcasts & Videos](#podcasts--videos)
- [Community](#community)
  - [Hacker News Discussions](#hacker-news-discussions)
  - [Tools & Directories](#tools--directories)
- [Related Tools](#related-tools)
- [Contributing](#contributing)

## Official Resources

- [Ralph](https://ghuntley.com/ralph/) - The original blog post by Geoffrey Huntley introducing the Ralph technique.
- [Everything is a Ralph Loop](https://ghuntley.com/loop/) - Follow-up post exploring the philosophy and applications of the loop pattern.
- [How to Ralph Wiggum](https://github.com/ghuntley/how-to-ralph-wiggum) - Official how-to repository with examples and best practices.
- [Anthropic's Ralph Wiggum Plugin](https://github.com/anthropics/claude-code/tree/main/plugins/ralph-wiggum) - Official Claude Code plugin from Anthropic.

## Implementations

### Claude Code Plugins

- [ralph-claude-code](https://github.com/frankbria/ralph-claude-code) - Claude Code implementation with intelligent exit detection for knowing when the PRD is complete.

### Standalone Implementations

- [ralph](https://github.com/snarktank/ralph) - Autonomous AI agent loop for PRD completion with clean implementation.
- [ralph](https://github.com/iannuttall/ralph) - Minimal file-based agent loop focusing on simplicity.
- [ralph-playbook](https://github.com/ClaytonFarr/ralph-playbook) - Comprehensive guide and playbook for implementing Ralph loops effectively.

### Multi-Agent Systems

- [ralph-orchestrator](https://github.com/mikeyobrien/ralph-orchestrator) - Multi-backend support for running Ralph across different AI providers.
- [ralph-loop-agent](https://github.com/vercel-labs/ralph-loop-agent) - Vercel's implementation for the AI SDK ecosystem.
- [multi-agent-ralph-loop](https://github.com/alfredolopez80/multi-agent-ralph-loop) - Multi-agent orchestration for complex projects requiring parallel work streams.

## Tutorials & Guides

- [11 Tips for AI Coding with Ralph Wiggum](https://www.aihero.dev/tips-for-ai-coding-with-ralph-wiggum) - Practical tips for getting the most out of Ralph loops.
- [Running AI Coding Agents for Hours, Not Minutes](https://dev.to/sivarampg/the-ralph-wiggum-approach-running-ai-coding-agents-for-hours-not-minutes-57c1) - Guide on extending agent runtime with the Ralph approach.
- [Ralph Wiggum Guide](https://github.com/JeredBlu/guides/blob/main/Ralph_Wiggum_Guide.md) - Community-written comprehensive guide.
- [Awesome Claude - Ralph Wiggum](https://awesomeclaude.ai/ralph-wiggum) - Resource page with additional tips and configuration examples.

## Articles & Blog Posts

- [How Ralph Wiggum Went from The Simpsons to the Biggest Name in AI](https://venturebeat.com/technology/how-ralph-wiggum-went-from-the-simpsons-to-the-biggest-name-in-ai-right-now) - VentureBeat coverage on the cultural phenomenon.
- [A Brief History of Ralph](https://www.humanlayer.dev/blog/brief-history-of-ralph) - Historical overview of the technique's development and adoption.
- [Ralph Wiggum and AI Coding Loops](https://www.ishir.com/blog/312751/ralph-wiggum-and-ai-coding-loops-from-springfield-to-real-world-software-automation.htm) - From Springfield to real-world software automation.
- [Ralph Wiggum Explained: The Claude Code Loop That Keeps Going](https://blog.devgenius.io/ralph-wiggum-explained-the-claude-code-loop-that-keeps-going-3250dcc30809) - Technical explainer of how and why it works.
- [2026: The Year of the Ralph Loop Agent](https://dev.to/alexandergekov/2026-the-year-of-the-ralph-loop-agent-1gkj) - Predictions and analysis of the Ralph loop's impact on development.

## Podcasts & Videos

- [Inventing the Ralph Wiggum Loop - Dev Interrupted](https://linearb.io/dev-interrupted/podcast/inventing-the-ralph-wiggum-loop) - Podcast interview with Geoffrey Huntley discussing the origins and philosophy.
- [Inventing the Ralph Wiggum Loop (Transcript)](https://devinterrupted.substack.com/p/inventing-the-ralph-wiggum-loop-creator) - Full transcript of the Dev Interrupted episode.
- [Ralph Wiggum Coding Agent Power Tools - BoundaryML](https://boundaryml.com/podcast/2025-10-28-ralph-wiggum-coding-agent-power-tools) - Deep dive into tooling and advanced techniques.
- [Ralph Wiggum AI Agent Explained - Startup Ideas Podcast](https://www.podscan.fm/podcasts/the-startup-ideas-podcast/episodes/ralph-wiggum-ai-agent-explained-amp-how-to-use-it) - Accessible introduction for founders and builders.

## Community

### Hacker News Discussions

- [Original HN Discussion](https://news.ycombinator.com/item?id=44565028) - The discussion that helped popularize the technique.
- [Tips Discussion](https://news.ycombinator.com/item?id=46547129) - Community tips and experiences thread.
- [Ralph from First Principles (Video)](https://news.ycombinator.com/item?id=46587275) - Discussion around educational video content.
- [What Happens After Ralph Wiggum?](https://news.ycombinator.com/item?id=46632445) - Exploring the future of autonomous coding patterns.

### Tools & Directories

- [Vibe Coding - Ralph Wiggum Loop](https://vibecoding.app/tools/ralph-wiggum-loop) - Tool directory entry with quick-start resources.

## Related Tools

- [Advanced Context Engineering for Coding Agents](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents) - Techniques for optimizing context windows and prompts for autonomous agents.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
