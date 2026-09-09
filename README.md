<img alt="Tiammomo: agent systems, developer infrastructure, and production software" src="./assets/profile-hero-anime.webp" width="100%">

<p align="center">
  <a href="https://tiammomo.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-Explore-6D4CC7?style=flat-square&logo=githubpages&logoColor=white"></a>
  <a href="https://github.com/search?q=author%3Atiammomo%20is%3Apr%20is%3Amerged%20is%3Apublic%20-user%3Atiammomo%20merged%3A%3E%3D2026-01-01&amp;type=pullrequests"><img alt="81 merged public PRs in 2026 as of 2026-09-09" src="https://img.shields.io/badge/Open_source-81_merged_PRs-2563A9?style=flat-square&logo=github&logoColor=white"></a>
  <img alt="China, UTC+8" src="https://img.shields.io/badge/China-UTC%2B8-0F766E?style=flat-square&logo=googlemaps&logoColor=white">
</p>

## Hello, I'm Tiammomo

I'm an engineer working on **agent algorithms** and the systems around them. My current work focuses on how agents plan and split work, choose tools and models, retrieve useful memory, coordinate with other agents, and learn from execution traces.

I care about the unglamorous parts too: evaluation, durable state, recovery, observability, and safety boundaries. A useful agent should be able to explain what it did and recover when something goes wrong.

## Agent work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Planning and orchestration</h3>
      <p>I decompose long tasks, route tools and models, and coordinate specialized agents.</p>
      <p><code>Python</code> · <code>structured outputs</code> · <code>tool protocols</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>Learning from runs</h3>
      <p>I turn execution trajectories into reusable skills and memory, then retrieve them with ranking, clustering, and vector search.</p>
      <p><code>RAG</code> · <code>Milvus</code> · <code>PostgreSQL</code> · <code>Redis</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Evaluation and runtime</h3>
      <p>I replay failures, enforce deterministic contracts, profile hot paths, and keep interrupted runs resumable.</p>
      <p><code>Python</code> · <code>Rust</code> · <code>Docker</code> · <code>Prometheus</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>Product surfaces</h3>
      <p>I expose agent state, evidence, and evaluation results in workflows people can inspect and control.</p>
      <p><code>TypeScript</code> · <code>React</code> · <code>Next.js</code> · <code>FastAPI</code></p>
    </td>
  </tr>
</table>

## Open-source work

As of **2026-09-09**, I've landed **81 pull requests across 5 public repositories outside my personal namespace** in 2026. My contributions focus on agent runtimes, learning from execution traces, evaluation, incremental indexing, and desktop/mobile reliability.

| Project | Merged PRs | Selected contributions |
| --- | ---: | --- |
| [SkillNerds/xskill](https://github.com/SkillNerds/xskill) | [49](https://github.com/SkillNerds/xskill/pulls?q=is%3Apr%20author%3Atiammomo%20is%3Amerged%20merged%3A%3E%3D2026-01-01) | [Logical Task / Task Attempt runtime](https://github.com/SkillNerds/xskill/pull/326), [incremental Atom vector indexes](https://github.com/SkillNerds/xskill/pull/310), and [paired evaluation replay](https://github.com/SkillNerds/xskill/pull/385). |
| [makecindy/cindy](https://github.com/makecindy/cindy) | [26](https://github.com/makecindy/cindy/pulls?q=is%3Apr%20author%3Atiammomo%20is%3Amerged%20merged%3A%3E%3D2026-01-01) | [Provider routing](https://github.com/makecindy/cindy/pull/2636), [assistant message boundaries](https://github.com/makecindy/cindy/pull/2617), and [desktop-to-mobile session sync](https://github.com/makecindy/cindy/pull/1492). |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | [4](https://github.com/bytedance/deer-flow/pulls?q=is%3Apr%20author%3Atiammomo%20is%3Amerged%20merged%3A%3E%3D2026-01-01) | [Bounded HTTP waits](https://github.com/bytedance/deer-flow/pull/5315), [document outlines](https://github.com/bytedance/deer-flow/pull/5281), and [Tavily response handling](https://github.com/bytedance/deer-flow/pull/5280). |
| [deer-flow/llm-space](https://github.com/deer-flow/llm-space) | [1](https://github.com/deer-flow/llm-space/pulls?q=is%3Apr%20author%3Atiammomo%20is%3Amerged%20merged%3A%3E%3D2026-01-01) | [Import DeerFlow run-event JSONL files](https://github.com/deer-flow/llm-space/pull/126). |
| [LazyAGI/LazyLLM](https://github.com/LazyAGI/LazyLLM) | [1](https://github.com/LazyAGI/LazyLLM/pulls?q=is%3Apr%20author%3Atiammomo%20is%3Amerged%20merged%3A%3E%3D2026-01-01) | [Custom Excel column joiners for RAG](https://github.com/LazyAGI/LazyLLM/pull/1270). |

Counts include public PRs authored by `tiammomo` and merged since 2026-01-01, excluding repositories owned by `tiammomo`. [Browse merged PRs](https://github.com/search?q=author%3Atiammomo%20is%3Apr%20is%3Amerged%20is%3Apublic%20-user%3Atiammomo%20merged%3A%3E%3D2026-01-01&type=pullrequests) · [Dated inventory and all 81 PRs](docs/github-activity-2026-09-09.md).

## Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tiammomo/RepoSteward">RepoSteward</a></h3>
      <p>A local-first control plane for coding agents: repository understanding, durable task state, isolated verification, and human-reviewed Issue-to-PR workflows.</p>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white">
        <img alt="RepoSteward stars" src="https://img.shields.io/github/stars/tiammomo/RepoSteward?style=flat-square&amp;label=stars&amp;color=2563A9">
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tiammomo/ModelPort">ModelPort</a></h3>
      <p>A self-hosted model gateway for small teams, connecting local and cloud providers with routing, scoped access, budgets, and request evidence.</p>
      <p>
        <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&amp;logo=rust&amp;logoColor=white">
        <img alt="ModelPort stars" src="https://img.shields.io/github/stars/tiammomo/ModelPort?style=flat-square&amp;label=stars&amp;color=2563A9">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tiammomo/QuantPilot">QuantPilot</a></h3>
      <p>A financial research application built on a general Data Agent and the PI Agent runtime, combining real market data, governed execution, and validated interactive workspaces.</p>
      <p>
        <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white">
        <img alt="QuantPilot stars" src="https://img.shields.io/github/stars/tiammomo/QuantPilot?style=flat-square&amp;label=stars&amp;color=2563A9">
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tiammomo/RoutePilot">RoutePilot</a></h3>
      <p>A multi-agent travel workspace for sourced answers, itinerary planning, validation, and versioned replanning with durable execution.</p>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white">
        <img alt="RoutePilot stars" src="https://img.shields.io/github/stars/tiammomo/RoutePilot?style=flat-square&amp;label=stars&amp;color=2563A9">
      </p>
    </td>
  </tr>
</table>

Also building [Evolvable User Memory](https://github.com/tiammomo/evolvable-user-memory) for evidence-based memory and attributable feedback, and [Mamoji](https://github.com/tiammomo/Mamoji) for expense, budget, and approval workflows. [All public repositories](https://github.com/tiammomo?tab=repositories).

## GitHub Roast

<p align="center">
  <a href="https://ghfind.com/u/tiammomo?ref=badge">
    <img alt="GitHub Roast 评分卡" src="https://ghfind.com/api/card/mini/tiammomo?variant=radar&amp;theme=dark&amp;lang=zh">
  </a>
</p>

<p align="center">
  <sub>Build patiently. Verify relentlessly. Keep what works.</sub>
</p>
