<div align="center">

<h1>Hi, I'm Dan Vanderboom 👋</h1>

<b>Founder of <a href="https://www.criticalinsight.ai/CognOS.html">Critical Insight</a> · building CognOS, an operating system for AI agents</b><br/>
<sub>Distributed systems · cognitive architectures · the structure of intelligent systems</sub>

<br/><br/>

<a href="https://www.linkedin.com/in/danvanderboom"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://www.criticalinsight.ai/CognOS.html"><img src="https://img.shields.io/badge/CognOS-criticalinsight.ai-5B47FB?style=flat" alt="CognOS"/></a>
<a href="https://criticalinsights.substack.com"><img src="https://img.shields.io/badge/Substack-Overspecified-FF6719?style=flat&logo=substack&logoColor=white" alt="Substack"/></a>
<a href="https://www.youtube.com/@CognOSAgents"><img src="https://img.shields.io/badge/YouTube-CognOS%20Agents-FF0000?style=flat&logo=youtube&logoColor=white" alt="YouTube"/></a>
<a href="mailto:dan@criticalinsight.ai"><img src="https://img.shields.io/badge/Email-dan%40criticalinsight.ai-00D9C0?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

---

## What I'm building

**[CognOS](https://www.criticalinsight.ai/CognOS.html)** is a runtime that makes AI agents safe to run in production. Agents, workflows, tools and policies are declared as versioned YAML resources, Kubernetes-style, and the runtime enforces them: every tool call passes through an admission pipeline, every model call is budgeted and recorded, memory carries provenance, and humans approve what policy says they must. It runs on .NET and Orleans, self-hosted, across Azure, AWS, GCP or air-gapped.

I build it with a hierarchical organization of AI coding agents, held to the same discipline CognOS imposes on its own agents. The platform is the proof of its own thesis.

- 🧠 **[Reactive Composite Memory (RCM)](https://github.com/critical-insight-ai/rcm-spec)** — an open design pattern for populating, composing and governing context for AI agents. RCM is to context lifecycle what REST is to web APIs. 177-page spec · [9-minute explanation](https://www.youtube.com/watch?v=Sf32vqAgLr8)
- 🎙️ **Agentic Horizons** — a podcast researched, scripted and produced by a team of six named agents running on CognOS, unattended. Publishing begins once intro and outro music land.
- 📺 **[CognOS Agents on YouTube](https://www.youtube.com/@CognOSAgents)** — short explainers of the ideas behind CognOS, made with NotebookLM before the platform existed. The thinking came first; the runtime caught up.
- ✍️ **Overspecified** — a Substack on the structure of intelligent systems: compression, hierarchy, governance, sparse activation, and why one person can now run an organization of agents. https://criticalinsights.substack.com

## Ideas I keep returning to

- Governance can't be bolted onto an agent runtime afterwards. It has to be the thing the runtime is organized around.
- Intelligence is mostly a *systems* property. The interesting failures of agents are runtime failures, not model failures.
- Declarative beats imperative wherever the declaration can be verified. YAML that the runtime refuses is worth more than code that silently does the wrong thing.
- Memory is the half of cognition we keep forgetting to design.
- Actors are the right abstraction for anything that has to stay alive, remember, and be addressed by name. I've been building on Orleans since 2016.

## Before CognOS

Twenty-five years of shipping software, from Silicon Valley startups to Fortune 500 enterprises, choosing the jobs by what I wanted to understand next: supply-chain systems installed in 45+ countries, mobile field software, Orleans actor clusters ingesting live IoT sensor data from oil-drilling rigs, a cloud platform running ML over drone, robot and acoustic data, and finally generative-AI architecture work that made the gap CognOS fills impossible to ignore.

## Open source

| Repo | What it is |
|---|---|
| [Aetherium](https://github.com/danvanderboom/Aetherium) | A server-authoritative multiplayer simulation engine on .NET 10, Orleans and SignalR: procedural worlds from dungeons to planets, continuous speed-based simulation, AI agents with memory, and a semantic perception protocol so any renderer (terminal, Unity, Unreal) can bind to it. Games are data; three ship with it. |
| [rcm-spec](https://github.com/critical-insight-ai/rcm-spec) | The Reactive Composite Memory specification: how context for AI agents is populated, composed and governed over its lifecycle |
| [H3.NET](https://github.com/danvanderboom/H3.NET) | A pure .NET port of Uber's H3 hexagonal geospatial indexing library |
| [Xamarin-Forms-TreeView](https://github.com/danvanderboom/Xamarin-Forms-TreeView) | A TreeView layout control for Xamarin.Forms, back when cross-platform mobile was the hard problem. ⭐ 67 |
| [ChessDotNet.AI](https://github.com/danvanderboom/ChessDotNet.AI) | Pluggable chess-playing agents and Monte Carlo search tooling from 2019, before "agent" meant a language model |
## Toolbox

<div align="center">
<table>
  <tr>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="40" height="40" alt="C#"/><br/><b>C#</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" width="40" height="40" alt=".NET"/><br/><b>.NET</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript"/><br/><b>TypeScript</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" alt="Python"/><br/><b>Python</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="40" height="40" alt="Azure"/><br/><b>Azure</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="40" height="40" alt="AWS"/><br/><b>AWS</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="40" height="40" alt="GCP"/><br/><b>GCP</b></td>
  </tr>
  <tr>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="40" height="40" alt="Kubernetes"/><br/><b>Kubernetes</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" height="40" alt="Docker"/><br/><b>Docker</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="40" height="40" alt="Terraform"/><br/><b>Terraform</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL"/><br/><b>PostgreSQL</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" width="40" height="40" alt="Kafka"/><br/><b>Kafka</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" width="40" height="40" alt="Grafana"/><br/><b>Grafana</b></td>
    <td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40" alt="React"/><br/><b>React</b></td>
  </tr>
</table>
</div>

<sub>Plus Orleans (virtual actors), OpenTelemetry, Helm, and more LLM providers than I'd like to admit.</sub>

## Elsewhere

📻 Extra Class amateur radio operator, KE0EZL

<!--
Optional: live GitHub stats. These count PUBLIC activity by default; most of my commits are in a
private org, so they will under-count unless "Include private contributions" is on in
Settings > Profile > Contributions & Activity. Uncomment once that looks right.

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=danvanderboom&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub stats"/>
  <img src="https://streak-stats.demolab.com?user=danvanderboom&theme=tokyonight&hide_border=true" height="165" alt="GitHub streak"/>
</div>
-->
