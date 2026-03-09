# Cortex Code for Snowflake Partners

Quick reference materials and examples to help Snowflake partners and ISVs build effectively with [Cortex Code](https://docs.snowflake.com/en/user-guide/cortex-code/cortex-code), Snowflake's AI coding assistant for the data ecosystem.

**[View the resources site](https://sfc-gh-rpettus.github.io/cortex-code-snowflake-isvs/)**

## What's Included

### Reference Materials (`docs/`)

- **[Quick Reference Card](https://sfc-gh-rpettus.github.io/cortex-code-snowflake-isvs/cortex-code-reference-card.html)** — 12-section cheat sheet covering commands, shortcuts, skills, MCP integration, Airflow & dbt workflows, agents, hooks, and configuration.
- **[Skills System Deep Dive](https://sfc-gh-rpettus.github.io/cortex-code-snowflake-isvs/cortex-code-skills-system.html)** — Visual reference for the progressive disclosure skill architecture, creation workflow, and bundled skill catalog.

### Examples (`examples/`)

Sample AGENTS.md files, custom skills, hooks configurations, and project templates for common ISV workflows. *(Coming soon)*

## Who Is This For?

Snowflake partners and ISVs who are:

- Building applications on the Snowflake platform
- Integrating with Snowflake-native tools (Cortex Analyst, Semantic Views, `#TABLE` syntax)
- Working with data ecosystem workflows (Airflow, dbt)
- Extending Cortex Code with custom skills, MCP servers, or hooks
- Setting up project-level configuration with AGENTS.md

## Topics Covered

- **Getting started** — installation, authentication, first session
- **Snowflake-native tools** — `#TABLE`, `/sql`, Cortex Analyst, Semantic Views
- **Data ecosystem workflows** — native Airflow and dbt plugin integration
- **Skills system** — progressive disclosure, skill creation with `$skill-development`
- **MCP integration** — connecting external tools via Model Context Protocol
- **Agents & subagents** — general-purpose, Explore, Plan, dbt-verify
- **Hooks & safety** — deterministic guardrails for tool execution
- **Configuration** — project layout, env vars, settings hierarchy

## Maintained By

Snowflake Partner Solutions Engineering
[randy.pettus@snowflake.com](mailto:randy.pettus@snowflake.com)