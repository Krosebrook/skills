# Skills Library — Master Index

**Repository:** krosebrook/skills
**Mirrored at:** ChaosClubCo/skills
**Last Updated:** 2026-03-25
**Maintainer:** Kyle Rosebrook

## Directory Structure

skills/
- master-skills/MASTER_INDEX.md
- governance/GOVERNANCE.md
- governance/INDEX.md
- governance/ROLE_BUNDLES.md
- governance/SKILL_TEMPLATE.md
- working-skills/SKILLS-CATALOG.md
- plugins/kyle-os/.mcp.json
- individual-skills/README.md
- individual-skills/accountability-buddy/SKILL.md
- individual-skills/ai-agents-workflow/SKILL.md
- individual-skills/claude-agent-pack/SKILL.md
- individual-skills/design-system/SKILL.md
- individual-skills/int-ai-enablement-pm/SKILL.md
- individual-skills/int-data-analyst/SKILL.md
- individual-skills/kubernetes-deployment/SKILL.md
- individual-skills/kyle-vibe-coding/SKILL.md
- individual-skills/sparc-methodology-coach/SKILL.md
- individual-skills/skill-staff-engineer-v4/SKILL.md
- individual-skills/skill-staff-engineer-v4/references/agentic-patterns.md
- individual-skills/skill-staff-engineer-v4/references/cicd-template.md
- individual-skills/skill-staff-engineer-v4/references/observability.md
- individual-skills/skill-staff-engineer-v4/references/security-checklist.md
- individual-skills/skill-staff-engineer-v4/references/stack-defaults.md
- individual-skills/skill-staff-engineer-v4/workflows/audit-loop.md
- individual-skills/skill-staff-engineer-v4/workflows/implement.md

## Governance

governance/GOVERNANCE.md — Authoring standards, review process, versioning rules
governance/INDEX.md — Human-readable directory of all skills by category
governance/ROLE_BUNDLES.md — Pre-configured skill bundle recommendations by role
governance/SKILL_TEMPLATE.md — Blank SKILL.md template with all required frontmatter

## Working Skills

working-skills/SKILLS-CATALOG.md — Production-verified skills with install status and trigger phrases

## Plugins

plugins/kyle-os/.mcp.json — Kyle OS plugin MCP config: Cloudflare, Supabase, GitHub, PostHog, Sentry, n8n, Notion

## Individual Skills

accountability-buddy v1.0 Verified — triggers: "accountability", "daily check-in"
ai-agents-workflow v2.0 Verified — triggers: "build an MCP server", "create an AI agent"
claude-agent-pack v1.0 Verified — triggers: "subagent", "Task tool"
design-system v1.0 Verified — triggers: "design tokens", "component library"
int-ai-enablement-pm v1.0 Verified — triggers: "INT project", "AI enablement"
int-data-analyst v1.0 Verified — triggers: "data analysis", "SQL query"
kubernetes-deployment v1.0 Verified — triggers: "kubernetes", "k8s deployment"
kyle-vibe-coding v1.0 Verified — triggers: "vibe coding", "rapid prototype"
skill-staff-engineer-v4 v4.0 Verified — triggers: "staff engineer", "production build"
sparc-methodology-coach v1.0 Verified — triggers: "SPARC", "spec before code"

## skill-staff-engineer-v4 Detail

Flagship engineering skill. Progressive disclosure — SKILL.md loads sub-files on demand.
- SCOPE_MODE gating: LITE / STANDARD / FULL
- WSJF backlog prioritization
- Security-first: Zod, RLS, parameterized queries, OWASP LLM Top 10
- Agentic: tool output validation, MCP whitelist, prompt injection defense
- 6-persona audit loop as mandatory ship gate (P0 = no ship)
- CI/CD templates for GitHub Actions + Docker + Vercel/Cloudflare

## Cross-Reference by Use Case

Security-First Builds: skill-staff-engineer-v4/references/security-checklist.md, agentic-patterns.md, workflows/audit-loop.md
Agentic/MCP Systems: ai-agents-workflow, claude-agent-pack, skill-staff-engineer-v4/references/agentic-patterns.md
Structured Methodology: sparc-methodology-coach, skill-staff-engineer-v4/workflows/implement.md
Observability and CI/CD: skill-staff-engineer-v4/references/observability.md, cicd-template.md
INT Lane: int-ai-enablement-pm, int-data-analyst, skill-staff-engineer-v4
Kinsley/Personal: kyle-vibe-coding, accountability-buddy

## Versioning

Skills follow semver. Breaking trigger/field changes bump major. Additive content bumps minor. Fixes bump patch.

## Maintenance

All skills require a SKILL.md with valid YAML frontmatter.
Reference and workflow files must appear in SKILL.md under required_reading.
To add a skill: copy governance/SKILL_TEMPLATE.md, fill fields, add entry here and in SKILLS-CATALOG.md.