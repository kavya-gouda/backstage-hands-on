# Backstage Hands-On — Study Material

A step-by-step, practical study plan for learning [Backstage](https://backstage.io/) from basics to advanced, aimed at DevOps engineers. Each hands-on is in its own directory with a README (knowledge base + implementation steps).

## Prerequisites

- Backstage running locally (e.g. `http://localhost:3000`) — initial setup is not covered here.
- Basic familiarity with YAML, Git, and the command line.

## Study Plan (Roadmap)

| # | Topic | Directory | Level |
|---|--------|-----------|--------|
| 01 | Understanding the Backstage UI & core concepts | [01-understanding-backstage-ui](./01-understanding-backstage-ui) | Basic |
| 02 | Software Catalog — entities, kinds, and relationships | 02-software-catalog-basics | Basic |
| 03 | Adding components to the catalog (register existing) | 03-register-components | Basic |
| 04 | Software Templates — create new components from templates | 04-software-templates | Basic |
| 05 | TechDocs — documentation-as-code | 05-techdocs-basics | Intermediate |
| 06 | Plugins — install and use existing plugins | 06-plugins | Intermediate |
| 07 | Custom plugin — build your first plugin | 07-custom-plugin | Intermediate |
| 08 | Integrations — GitHub, GitLab, etc. | 08-integrations | Intermediate |
| 09 | Custom API & backend | 09-custom-api | Advanced |
| 10 | Authentication & authorization | 10-auth | Advanced |
| 11 | Deployment & production considerations | 11-deployment | Advanced |

Work through the directories in order; each builds on the previous.

## How to Use This Repo

1. **One at a time** — Complete the README and exercises in `01-*`, then move to `02-*`, and so on.
2. **README in each directory** — Contains:
   - **Knowledge base**: Concepts and theory.
   - **Practical steps**: What to do in your running Backstage instance (and optionally in this repo).
3. **Push to GitHub** — Commit after each hands-on and push to your GitHub repo as study material.

## Repository Structure

```
backstage-hands-on/
├── README.md                    # This file — study plan & index
├── 01-understanding-backstage-ui/
│   └── README.md
├── 02-software-catalog-basics/
│   └── README.md
└── ... (further hands-on directories)
```

## License & Use

Use this material for personal learning and as reference. Backstage is under Apache 2.0; see [Backstage licensing](https://github.com/backstage/backstage/blob/master/LICENSE).

---

**Next step:** Open [01-understanding-backstage-ui](./01-understanding-backstage-ui/README.md) and complete the first hands-on.
