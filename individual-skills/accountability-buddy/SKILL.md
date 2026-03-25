---
name: accountability-buddy
description: Track any personal challenge (learning, fitness, building, creative, habits) with type-adaptive check-ins, progress logging, and cross-challenge insights. Use when starting a new challenge, checking in daily, viewing stats, or analyzing patterns across multiple goals.
---

<essential_principles>

## How This Skill Works

Think of this as a personal coach that adapts to what you're tracking. The same file structure works for any challenge - only the questions and content adapt.

### 1. Challenge Types

| Type | Best For | Check-in Focus |
|------|----------|----------------|
| **learning** | Courses, books, skills | Aha moments, milestones, resources |
| **building** | Projects, shipping | What shipped, blockers, tech decisions |
| **fitness** | Workouts, health | Exercises, body feel, PRs |
| **creative** | Art, writing, music | What created, inspiration, flow state |
| **habit** | Routines, consistency | Completion, feeling, streak |
| **custom** | Anything else | User-defined questions |

### 2. Core Philosophy

- **Bite-sized wins** → Even small progress counts. Log it.
- **Consistency > perfection** → Follow your mood, still log.
- **Context preservation** → Logging brings back context fast.

### 3. File Locations

All challenges stored in: `~/.claude/challenges/{challenge-name}/`
Active challenge tracked in: `~/.claude/challenges/.active`

</essential_principles>

<intake>

What would you like to do?

1. **Check in** to my active challenge
2. **Create** a new challenge
3. **View stats** for a challenge
4. **List** all my challenges
5. **Switch** active challenge
6. **Insights** across challenges

**Wait for response before proceeding.**

</intake>

<routing>

| Response | Workflow |
|----------|----------|
| 1, "check in", "daily", "log", "streak" | `workflows/check-in.md` |
| 2, "create", "new", "start" | `workflows/create-challenge.md` |
| 3, "stats", "progress" | `workflows/view-stats.md` |
| 4, "list", "show all" | `workflows/list-challenges.md` |
| 5, "switch", "change" | `workflows/switch-challenge.md` |
| 6, "insights", "patterns" | `workflows/insights.md` |

</routing>

<quick_commands>

| Command | Action |
|---------|--------|
| `/streak` | Check in to active challenge |
| `/streak-new` | Create a new challenge |
| `/streak-stats` | View progress and achievements |
| `/streak-list` | List all challenges |
| `/streak-switch [name]` | Switch active challenge |
| `/streak-insights` | Cross-challenge analysis |

</quick_commands>