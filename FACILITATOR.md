# Facilitator guide

1. Publish the kit: push this repository to GitHub as a public repository. In Settings, select Template repository. Share the link with the participants.
2. Dry run with a Copilot Free account: run every card once in order and note what /usage shows before and after each step, so you can tell teams what one story usually uses.
3. Check that the six agents appear in the agent picker. Ask Copilot "What are the project rules?" to check that it reads .github/copilot-instructions.md. If not, paste the rules into the app settings under Repositories, Instructions.
4. After the dry run, open app/index.html on a school laptop on the school network to check that unpkg.com and tiles.openfreemap.org are reachable.
5. What to check in each team: at Sprint 0, a first /usage reading, stop rules and a HITL matrix with real cases. At the sync, the latest /usage reading and the decision taken. At minute 35, the Definition of Done.
6. A reference backlog for the Paris case: S1 Agent, map with markers by segment. S2 Agent, card, figures and filters. S3 Hybrid, positioning chart and insights approved by the AI Product Owner. S4 Human, check every figure and name the white space. S5 Budget, /usage after each story and a stop when a rule fires.
7. Troubleshooting table:

| Problem | Try this |
|---|---|
| Agent missing from the picker | Open the repository root, check .github/agents and the .agent.md suffix, start a new session. |
| A session does not see earlier work | It ran in a new worktree, so start sessions with Workspace "Current checkout". |
| Blank map | WebGL may be off or the network may be blocked. The rest still works. |
| "Failed to fetch" or CORS error | The code uses fetch() or ES modules. Ask Delivery to load data with script tags. |
| Copilot adds a framework or npm | Reject the change and log it as drift. |
| Allowance used up | Switch to the reserve laptop, copy the whole folder through the shared folder, keep logging. |
| /usage is unclear | Open github.com/settings/billing, then AI usage. |
