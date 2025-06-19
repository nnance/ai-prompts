# AI Prompts

This repository contains prompt templates and agent instructions for agent workflows and multi-agent systems.

## Deep Research Agents (Anthropic)

This directory contains agent instructions for orchestrating advanced research workflows using Anthropic-based agents. The agents are designed to collaborate in a multi-agent system to efficiently answer complex research queries, leveraging both web and internal tools.

## Directory Structure

```
deep-research/
  anthropic/
    citations_agent.md
    research_lead_agent.md
    research_subagent.md
```

## Agent Roles

- **citations_agent.md**  
  Provides instructions for an agent that adds accurate, non-intrusive citations to synthesized research reports, following strict formatting and placement rules.

- **research_lead_agent.md**  
  Defines the behavior of the lead research agent responsible for high-level planning, task breakdown, subagent delegation, and synthesis of research findings into a final report.

- **research_subagent.md**  
  Outlines the process for subagents tasked with executing specific research objectives, including planning, tool selection, iterative research loops, and efficient use of available resources.

## Usage

These prompt templates are intended for use in AI research orchestration platforms or as part of a multi-agent research system. Each `.md` file contains detailed, structured instructions that guide the behavior of the respective agent roles.

- Integrate these prompts into your agent orchestration framework.
- The lead agent coordinates the research process, delegates tasks to subagents, and synthesizes results.
- Subagents execute focused research tasks using web and internal tools.
- The citations agent enhances the final report with precise citations.

## Key Features

- Modular, role-based agent design for scalable research workflows.
- Emphasis on efficient tool usage, parallelization, and high-quality information gathering.
- Strict guidelines for citation placement and research reporting.
- Designed for extensibility with additional internal tools (e.g., Slack, Asana, Google Drive).

## License

See [LICENSE](LICENSE) for details.