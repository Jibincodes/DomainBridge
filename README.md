# Domain Bridge — Interactive Prototype

A locally runnable, offline, six-screen prototype of the proposed Domain Bridge service for Sameh Mathew (MSc Business Information Systems, FHNW). Part of AI+ : Strategy & Consulting - Strategic Business Innovation - AS26 module.

## Start in 10 seconds

1. Extract the ZIP archive.
2. Double-click **index.html** (Chrome, Edge, Firefox, or Safari).
3. Use the left sidebar to explore the six-screen journey.

**No installation, web server, internet connection, login, npm, or account is required.**

## What works

- **1 Dashboard:** proactive curriculum-based guidance and editable career preference.
- **2 My Capability Journey:** clickable capability nodes, highlighted connections, evidence details, career-to-SQL journey.
- **3 Learning Bridge:** business-to-database mapping, SQL explanation, perspective selectors, illustrative reporting consequence.
- **4 Workbench:** editable SQL query, offline sample-data query evaluator, Run Query/Reset, correct and intentionally flawed joins, 4 levels of opt-in help, saved business explanation, transfer task.
- **5 Competency Evidence:** activity-dependent capability states, inspectable sources and caveats, exportable JSON evidence.
- **6 Practice Lab:** four-phase fictional retail consulting engagement, offline scripted stakeholder conversations, investigation/recommendation/presentation fields, progress gates, optional support, exportable simulated portfolio.
- **Settings:** data limitations, local exports and full demo reset.

## Important limitations

This is a **functional proof of concept**, not a deployed FHNW system. Any university integration, timetable, learning context, curriculum source label, client, stakeholder, and student activity are illustrative. The stakeholder is an **offline, rule-based simulation**, not a generative AI model.

The SQL editor runs the **supported SELECT / SUM / JOIN / GROUP BY reporting pattern on six fictional orders and four fictional customers**. It does not offer a complete general-purpose SQL engine. Change `ON c.region = o.sales_region` to `ON c.customer_id = o.customer_id` to correct the report. The original region-based join incorrectly allocates orders from other customers in the same region. The browser computes the output by joining actual sample rows; it does not merely switch hardcoded screen states.

The UI distinguishes curricular exposure, saved activity, in-app assistance, correct sample output, and independently verified competence. External AI assistance is not detectable. The simulated Practice Lab does not establish real consulting experience or job readiness.

## Progress and privacy

Browser local storage is used when allowed, retaining work on the same browser/device. If private mode disables storage, the application still works during the open session. The prototype sends no data to external services. Use **Settings → Export current evidence** to save the demo record, or **Reset all demo activity** to clear it.

## Suggested guided demonstration (5–10 minutes)

1. Dashboard → “Explore My Learning Bridge”.
2. My Capability Journey → select “SQL Joins”.
3. Learning Bridge → “Translate Business Logic into SQL” → “Apply This to a New Problem”.
4. Workbench → Run Query; observe the inflated region-join totals. Edit the `ON` line to match `customer_id`; Run Query again. Optionally request a hint, write an explanation and solve the transfer example.
5. Competency Evidence → click “Why do we say this?” on the cards to inspect evidence and limitations.
6. Practice Lab → ask Anna Keller a discovery question, save notes, investigate, recommend and present. Export the simulated portfolio.

## Files

- `index.html`: entire standalone application, styles, sample data, and interaction logic.
- `README.md`: this guide.

Designed for a wide 16:9 laptop viewport (1440 × 810) and responsive on narrower screens. All visuals are built from editable HTML/CSS; screenshots are not used as the interactive interface.
