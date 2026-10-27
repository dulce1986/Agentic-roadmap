# Agentic Roadmap

A Linear-connected roadmap app concept for a CX organization: ~100 projects across 8 engineering teams, organized by **Big Rock** themes, run day-to-day by a small team of agents.

**Live demo:** open `index.html` in a browser (single self-contained file). Mock UI — all data is sample data.

## Views

- **Roadmap (home)** — the exec page: a 60-second TL;DR, headline KPIs (Overall Automation Rate and Automated CSAT, trailing 4 weeks), Biweekly Update with comments, and Trade-off decisions
- **Big Rocks / By PM / Timeline** — the same projects grouped by theme, by PM, or on a Gantt, all sharing Linear status chips and points-based team capacity
- **Impact** — a Ranked by Impact table (every initiative shows its expected move in **bps** on automation rate and automated CSAT), with all charts below it in the same view
- **New Submission** — stupid-easy intake: one box, the agent does the paperwork, checks "already on the roadmap," previews impact and routing confidence
- **My Submissions** — track your own items by their Linear status
- **PM Routing** — the low-confidence inbox: a few high-level owners route in one tap; every tap teaches the agent
- **Journey & Agents** — each initiative's agent-stamped journey, and the six agents at work

## The agents (one job each)

1. **Intake & Routing** — cleans submissions, dedupes, routes to the right team (learns from past roadmap; a team-ownership map overrides history)
2. **Impact & Ranking** — scores and ranks: `Score = (total expected bps × confidence %) ÷ effort points × priority (P0 ×1.5, P1 ×1.25, P2 ×1.0)`
3. **Evidence** — attaches support volume, usage, customers, revenue
4. **Sync** — keeps the roadmap equal to Linear truth; flags drift
5. **Attention** — finds stalls, slips, blockers
6. **Digest** — writes the plain-English updates

## Notes

- Statuses shown are **Linear project statuses**; agent work appears only as an activity log
- Team capacity is measured in **points** (S=1, M=2, L=4, XL=8), learned from what teams actually shipped — never raw project counts
- Opens in light mode; moon toggle in the header for dark
