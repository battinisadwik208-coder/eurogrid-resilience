# Devpost submission copy — EuroGrid

## Project title
EuroGrid

## Tagline
A human-controlled AI coordination layer for Europe’s interconnected essential services.

## Inspiration
A flood, rail outage, heatwave, or supply disruption rarely stays inside one city. European services depend on cross-border infrastructure, but the information needed to coordinate a response is scattered across agencies, operators, and languages.

## What it does
EuroGrid turns regional updates into a shared resilience board. It highlights high-risk dependencies, explains why a dependency is prioritised, and produces a source-aware briefing for human teams. It does not automatically reroute services or execute operational actions.

## How we built it
The prototype is a self-contained HTML/CSS/JavaScript application with a fixed scenario. It demonstrates a regional situation board, dependency-aware prioritisation, confidence labels, and a human-confirmation boundary. A production version would add approved data feeds, graph-based dependency analysis, multilingual generation, access controls, and audit logs.

## Why it matters for Europe
European mobility, health, energy, and public services are interconnected. EuroGrid is designed to help local teams coordinate across borders without removing accountability from the people responsible for each decision.

## Challenges we ran into
Resilience tooling must be useful under pressure without becoming an opaque automated command system. We made the recommendation explainable and explicitly require human confirmation before any operational action.

## Accomplishments
We built a working browser prototype that communicates the product workflow clearly and demonstrates a realistic cross-border disruption scenario.

## What's next
Connect verified public and operator feeds, add multilingual briefings, introduce a dependency graph, support regional permissions, and test the workflow with municipalities and infrastructure operators.

## Technology stack
HTML, CSS, JavaScript. Planned: event-stream ingestion, graph analysis, language-model summarisation, and secure audit storage.

## Demo instructions
Open `index.html` and select **Generate briefing**.
