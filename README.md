# Zero to Agent: an Agentic Scrum kit for the GitHub Copilot app

## What this is
This is a template each team copies.
It has six custom agents, one for each step of an Agentic Scrum sprint.
Example prompts are in prompts/.
The worked case in CASE.md is Brunch & Burn Rate, a fictional team mapping competitors in Paris.

## Get your own copy
The driver of each team clicks "Use this template", then "Create a new repository".
In the GitHub Copilot app, next to Projects, click + and choose "GitHub repository", then pick that copy.
Without a GitHub copy: Code, Download ZIP, unzip, then add the folder with "Local folder or repository".
Everyone needs a GitHub account, Git and the GitHub Copilot app for Windows, macOS or Linux, signed in. Copilot Free is enough.

## Start every session the same way
Choose Environment "This computer" and Workspace "Current checkout", so each new session sees the work of the previous one.
Keep tool permissions on "Ask every time" or "Assisted". Never use "Approve all", /allow-all-tools or /yolo.

## Watch your AI credits
Type /usage in the app before the first prompt, after each story and at the end, and copy what it shows into docs/budget.md.
A prompt count does not show how many credits you used. Autopilot on a large task uses the most.
A new session for each story keeps the context short.

## Your six agents
| Step | Agent | Who drives it | Mode | Output |
|---|---|---|---|---|
| Sprint 0 | Sprint 0 | AI Product Owner and FinOps Agent Manager | Interactive | Charter, HITL matrix, budget with stop rules, first cost estimate |
| Planning | Planning | AI Product Owner | Plan | Spec, backlog and expected costs |
| Daily Sync | Daily Sync | AI Orchestrator and FinOps Agent Manager | Interactive | Latest /usage reading, drift, cuts |
| Delivery | Delivery | Agent Designer | Plan then Autopilot or Interactive | App, one story at a time |
| Dual Demo | Dual Demo | AI QA Evaluator | Interactive | Done check, demo script, cost report |
| Retro | Retro | Whole team | Interactive | Retro notes and one change |

## How to call an agent
Use the agent picker in the prompt box, or type /agent. Work on one story per session.

## Rules
Use fictional data only. Log every prompt in docs/prompt-log.md, for traceability, not for cost.

## Sprint timeline
Sprint 0 takes 10 minutes. Then run a 40-minute build sprint: Planning from 0 to 5, Delivery wave 1 from 5 to 25, Agent and Cost Sync from 25 to 30, Delivery wave 2 from 30 to 35, and Done check from 35 to 40. Then run the Dual Demo, two minutes per team, and the Retro, five minutes.

## Reuse this kit
Follow the last section of CASE.md. Ten ready ideas are in CASE-LIBRARY.md.

## If the map stays blank in the Paris case
The list, the figures and the chart still work. Ask the facilitator.

## Credits
Map data from OpenStreetMap contributors, tiles from OpenFreeMap and OpenMapTiles, shown on the map by MapLibre. All competitor data is fictional.
