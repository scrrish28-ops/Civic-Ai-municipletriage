# Civic-Ai-municipletriage
"Report the problem. Track the progress. Bulid the better city"

CivicTriage turns unstructured citizen complaints (text in any language, optional photo) into structured, prioritised tickets routed to the right municipal department.

- **Citizen page:** register (name, phone, email), report an issue, track your complaints and see resolution messages.
- **Officer desk:** sign in with an email ID, see tickets sorted by severity, start work, and resolve with a message (and optional photo) for the citizen.
- **AI triage:** category, severity with a one-line reason, department routing, duplicate merging.

## Run
Open `index.html` in a browser. Tickets are saved in the browser (localStorage). The AI step uses the Claude artifact runtime when hosted on claude.ai; elsewhere it falls back to keyword rules.

## Prototype limits
The officer password is hard-coded in the page source, so this is a demo, not real authentication.
