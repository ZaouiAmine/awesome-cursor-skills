# Awesome Cursor Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [skills](https://docs.cursor.com/agent/skills) for [Cursor](https://cursor.com), the AI code editor.

Cursor Skills are reusable `SKILL.md` instruction files that teach the AI agent how to perform specific tasks — from setting up analytics to scaffolding entire projects. They live in `.cursor/skills/` (personal) or project directories and are automatically discovered by the agent.

## Contents

- [Featured](#featured)
- [Skill Collections](#skill-collections)
- [Official Plugins with Skills](#official-plugins-with-skills)
- [Analytics & Monitoring](#analytics--monitoring)
- [Infrastructure & Deployment](#infrastructure--deployment)
- [Databases](#databases)
- [Frontend & UI](#frontend--ui)
- [Backend & API](#backend--api)
- [DevOps & CI/CD](#devops--cicd)
- [Security](#security)
- [Productivity & Workflow](#productivity--workflow)
- [Code Quality](#code-quality)
- [Cursor Rules (Related)](#cursor-rules-related)
- [Resources](#resources)
- [Contributing](#contributing)

---

## Featured

Standout skills and collections that are especially useful across many projects.

- [PostHog Skills](https://github.com/PostHog/skills) - Official PostHog skills for adding analytics, feature flags, and event tracking to any project.
- [VoltAgent Awesome Agent Skills](https://github.com/VoltAgent/awesome-agent-skills) - 1,000+ skills from official dev teams (Anthropic, Google Labs, Sentry, Vercel) and the community. One of the largest collections available.
- [Antigravity Awesome Skills](https://github.com/sickn33/antigravity-awesome-skills) - 1,370+ installable agentic skills with CLI installer (`npx antigravity-awesome-skills --cursor`), bundles, and workflows.
- [Figma Plugin](https://cursor.com/marketplace/skills/figma) - Official Cursor plugin with skills for translating Figma designs into production code.
- [Datadog Plugin](https://cursor.com/marketplace/skills/datadog) - Query logs, metrics, traces, and dashboards through natural conversation.
- [Stripe Plugin](https://cursor.com/marketplace/skills/stripe) - Best practices, API/SDK upgrade guidance, and Stripe MCP server integration.

## Skill Collections

Large repositories containing many skills organized by category.

- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) - 1,000+ skills from official teams and community contributors.
- [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) - 1,370+ skills with CLI installer, bundles, and workflows.
- [skillcreatorai/Awesome-Agent-Skills](https://github.com/skillcreatorai/Awesome-Agent-Skills) - Curated collection with CLI tool (`npx ai-agent-skills`) for installation.
- [aussiegingersnap/cursor-skills](https://github.com/aussiegingersnap/cursor-skills) - Focused Cursor-specific skill collection with MCP server setup.
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) - 220+ skills compatible with Cursor and other coding agents.

## Official Plugins with Skills

Skills bundled with official Cursor marketplace plugins. Install via **Cursor Settings > Plugins**.

- [Figma](https://cursor.com/marketplace/skills/figma) - Design-to-code workflows and design system management.
- [Linear](https://cursor.com/marketplace/skills/linear) - Manage issues, projects, documents, and sprints.
- [Slack](https://cursor.com/marketplace/skills/slack) - Search channels, send messages, and perform Slack actions.
- [Datadog](https://cursor.com/marketplace/skills/datadog) - Query logs, metrics, traces, and dashboards.
- [Stripe](https://cursor.com/marketplace/skills/stripe) - Payment integration best practices and API guidance.
- [Firebase](https://cursor.com/marketplace/skills/firebase) - Backend and AI infrastructure with Firebase.
- [Shopify](https://cursor.com/marketplace/skills/shopify) - GraphQL, Liquid, and UI extension code generation.
- [dbt Labs](https://cursor.com/marketplace/skills/dbt-labs) - Data modeling, analytics engineering, and semantic layer metrics.
- [Sentry](https://cursor.com/marketplace/skills/sentry) - Error tracking and performance monitoring integration.
- [Vercel](https://cursor.com/marketplace/skills/vercel) - Deployment, preview, and Next.js optimization skills.
- [Svelte](https://cursor.com/marketplace/skills/svelte) - Svelte development, MCP, and component skills.
- [Elastic](https://cursor.com/marketplace/skills/elastic) - Elasticsearch, Kibana, Observability, and ES|QL docs.
- [Postman](https://cursor.com/marketplace/skills/postman) - Full API lifecycle management from inside Cursor.
- [Sanity](https://cursor.com/marketplace/skills/sanity) - CMS integration with agent skills, rules, and commands.
- [Langfuse](https://cursor.com/marketplace/skills/langfuse) - LLM tracing, prompt management, and evaluation.
- [CockroachDB](https://cursor.com/marketplace/skills/cockroachdb) - Schema exploration, SQL optimization, and distributed DB management.
- [Encore](https://cursor.com/marketplace/skills/encore) - Backend services in TypeScript/Go with automatic infrastructure.
- [AWS Amplify](https://cursor.com/marketplace/skills/aws-amplify) - Full-stack apps with authentication, data models, and storage.
- [AWS Serverless](https://cursor.com/marketplace/skills/aws-serverless) - Design, build, deploy, and debug serverless applications.
- [Pendo](https://cursor.com/marketplace/skills/pendo) - Analytics for account health, feature adoption, and session replays.
- [GitLab](https://cursor.com/marketplace/skills/gitlab) - Issues, merge requests, and pipeline management.
- [Sourcegraph](https://cursor.com/marketplace/skills/sourcegraph) - Code search and navigation skills with MCP.
- [Miro](https://cursor.com/marketplace/skills/miro) - Read board context, create diagrams, and generate code from whiteboards.
- [Cloudinary](https://cursor.com/marketplace/skills/cloudinary) - Media asset management, transformations, and optimization.

## Analytics & Monitoring

- [PostHog/skills](https://github.com/PostHog/skills) - Official PostHog skills for analytics, feature flags, session replay, and LLM analytics.
- [PostHog/ai-plugin](https://github.com/PostHog/ai-plugin) - PostHog AI plugin for Cursor and other coding agents.
- [Amplitude Skills](https://cursor.com/marketplace/skills/analyze-dashboard) - Dashboard analysis, chart deep-dives, account health, and experiment design.

## Infrastructure & Deployment

- [Vercel Plugin](https://cursor.com/marketplace/skills/vercel) - Deploy, preview, and optimize Next.js applications.
- [Firebase Plugin](https://cursor.com/marketplace/skills/firebase) - Prototype, build, and run apps with Firebase backend.
- [AWS Amplify Plugin](https://cursor.com/marketplace/skills/aws-amplify) - Full-stack AWS apps with guided workflows.
- [AWS Serverless Plugin](https://cursor.com/marketplace/skills/aws-serverless) - Serverless application lifecycle management.
- [Encore Plugin](https://cursor.com/marketplace/skills/encore) - Automatic infrastructure for TypeScript and Go backends.
- [Turbopuffer Plugin](https://cursor.com/marketplace/skills/turbopuffer) - Vector and full-text search database integration.

## Databases

- [CockroachDB Plugin](https://cursor.com/marketplace/skills/cockroachdb) - Schema exploration, query optimization, and distributed cluster management.
- [dbt Labs Plugin](https://cursor.com/marketplace/skills/dbt-labs) - Data modeling, analytics engineering, unit testing, and job troubleshooting.
- [Appwrite Plugin](https://cursor.com/marketplace/skills/appwrite) - Backend-as-a-service with database, auth, and storage skills.

## Frontend & UI

- [Figma Plugin](https://cursor.com/marketplace/skills/figma) - Design-to-code translation and design system workflows.
- [Svelte Plugin](https://cursor.com/marketplace/skills/svelte) - Svelte development skills and MCP integration.
- [shadcn/ui Skill](https://github.com/hzm0321/real-time-fund/blob/main/.cursor/skills/shadcn/SKILL.md) - Managing shadcn components — adding, searching, debugging, styling, and composing UI.
- [Meta Reality Labs Plugin](https://cursor.com/marketplace/skills/meta-reality-labs) - Quest and Horizon OS development, debugging, and performance tracing.

## Backend & API

- [Postman Plugin](https://cursor.com/marketplace/skills/postman) - API lifecycle management, collection syncing, test generation, and security auditing.
- [Stripe Plugin](https://cursor.com/marketplace/skills/stripe) - Payment integration patterns, webhook handling, and SDK usage.
- [Chargebee Plugin](https://cursor.com/marketplace/skills/chargebee) - Billing operations, API integration, and webhook handling.
- [Shopify Plugin](https://cursor.com/marketplace/skills/shopify) - Shopify developer tools for GraphQL, Liquid, and extensions.
- [Circle Plugin](https://cursor.com/marketplace/skills/circle) - Stablecoin payments, cross-chain transfers, and smart contracts.

## DevOps & CI/CD

- [CLI for Agents Plugin](https://cursor.com/marketplace/skills/cli-for-agents) - Patterns for designing CLIs that coding agents can run reliably.
- [Agent Compatibility Plugin](https://cursor.com/marketplace/skills/agent-compatibility) - Repo compatibility scans for AI agents.
- [Astronomer Plugin](https://cursor.com/marketplace/skills/astronomer) - Data engineering, warehouse exploration, pipeline authoring, and Airflow integration.

## Security

- [Runlayer Plugin](https://cursor.com/marketplace/skills/runlayer) - Security policies, secret protection, and audit trails for MCPs and skills.

## Productivity & Workflow

- [Linear Plugin](https://cursor.com/marketplace/skills/linear) - Issue tracking, project management, and document management.
- [Slack Plugin](https://cursor.com/marketplace/skills/slack) - Slack channel search, messaging, and actions.
- [ClickUp Plugin](https://cursor.com/marketplace/skills/clickup) - Task management, time tracking, and collaboration.
- [Miro Plugin](https://cursor.com/marketplace/skills/miro) - Board reading, diagram creation, and code generation from whiteboards.
- [Box Plugin](https://cursor.com/marketplace/skills/box) - Content management, AI Q&A, summarization, and extraction.
- [Plain Plugin](https://cursor.com/marketplace/skills/plain) - Support threads, customer management, and help center articles.
- [Superpowers Plugin](https://cursor.com/marketplace/skills/superpowers) - Core skill library for TDD, debugging, and collaboration patterns.

## Code Quality

- [Omni Plugin](https://cursor.com/marketplace/skills/omni) - Analytics exploration, querying, model building, and dashboard creation.
- [Braintrust Plugin](https://cursor.com/marketplace/skills/braintrust) - AI evaluation, experiments, and evaluation logs.
- [Parallel Plugin](https://cursor.com/marketplace/skills/parallel) - Web search, content extraction, and deep research.
- [Tavily Plugin](https://cursor.com/marketplace/skills/tavily) - Web search, crawling, deep research, and URL discovery.

## Cursor Rules (Related)

Cursor Rules (`.cursorrules` / `.cursor/rules/`) are complementary to skills — rules are always-on conventions, skills are on-demand workflows.

- [PatrickJS/awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules) - The most comprehensive collection of `.cursorrules` files, categorized by framework and language.
- [sanjeed5/awesome-cursor-rules-mdc](https://github.com/sanjeed5/awesome-cursor-rules-mdc) - Curated `.mdc` format rules with a generator tool.
- [tugkanboz/awesome-cursorrules](https://github.com/tugkanboz/awesome-cursorrules) - Showcases modern Cursor Rules system with MDC format.

## Resources

### Learning

- [Cursor Skills Documentation](https://docs.cursor.com/agent/skills) - Official docs on creating and using skills.
- [Cursor Marketplace](https://cursor.com/marketplace) - Browse and install official plugins with bundled skills.
- [Agent Skills Specification](https://agentskills.io) - The open standard for defining agent capabilities.
- [Deep Dive SKILL.md](https://abvijaykumar.medium.com/deep-dive-skill-md-part-1-2-09fc9a536996) - In-depth walkthrough of the SKILL.md format.

### Directories

- [cursor-skills GitHub Topic](https://github.com/topics/cursor-skills) - Browse community repos tagged with cursor-skills.
- [AgentDepot.dev](https://agentdepot.dev/) - Open-source explorer for agents, skills, and rules.
- [CursorDirectory](https://cursor.directory/) - Community directory for Cursor rules and configurations.
- [skills.sh](https://skills.sh/) - Leaderboard and directory for popular skill repositories.

### Tools

- [npx skills](https://github.com/skillcreatorai/Awesome-Agent-Skills) - CLI to search, install, and manage skills.
- [npx antigravity-awesome-skills --cursor](https://github.com/sickn33/antigravity-awesome-skills) - Installer for 1,370+ skills.
- [PostHog/context-mill](https://github.com/PostHog/context-mill) - Assemble context for AI agents into Agent Skills-compliant packages.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

If you know of a great Cursor skill that isn't listed here, please open a PR. Include:
- A link to the skill or repository
- A brief description of what it does
- Which category it belongs to
