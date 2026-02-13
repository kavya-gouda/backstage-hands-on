# Hands-On 01 — Understanding the Backstage UI & Core Concepts

**Goal:** Get familiar with the Backstage UI and its main areas so you can navigate and understand what Backstage does before diving into the catalog, templates, and plugins.

---

## Knowledge Base

### What is Backstage?

Backstage is an **Internal Developer Portal (IDP)**. It gives developers (and DevOps) a single place to:

- **Discover** software (services, libraries, apps, docs).
- **Create** new components from templates.
- **Manage** and operate software (docs, CI/CD, runbooks).
- **Integrate** with existing tools (Git, Kubernetes, monitoring, etc.) via plugins.

### Core Concepts

| Concept | Description |
|--------|-------------|
| **Software Catalog** | A single source of truth for all software (services, websites, libraries). Each item is an *entity* (e.g. `Component`, `API`, `Template`). |
| **Software Templates** | Scaffolding to create new repos/components from templates (e.g. “Create a new microservice”). |
| **TechDocs** | Documentation that lives next to code (e.g. in the repo) and is rendered in Backstage. |
| **Plugins** | Extensions that add features (e.g. CI/CD, Kubernetes, cost, security). |

### Main UI Areas (Default Backstage)

- **Home** — Landing page; often links to “create”, “catalog”, “docs”.
- **Catalog** — Browse and search entities (components, APIs, templates, etc.).
- **Create** — Create new components from Software Templates.
- **Docs** — Browse and read TechDocs.
- **Search** — Global search across catalog and docs (if configured).
- **Settings** — User settings (e.g. theme, profile).

Understanding these areas is the foundation for the next hands-on (catalog, templates, TechDocs).

---

## Practical Steps

Do these in order on your **running Backstage instance** at `http://localhost:3000` (or your URL).

### Step 1: Open Backstage and Check the Home Page

1. Open your browser and go to `http://localhost:3000`.
2. Note the **left sidebar**: Home, Catalog, Create, Docs, Search, Settings.
3. On **Home**, identify:
   - Any “Quick links” or “Getting started” sections.
   - Any sample or default components/docs linked from the home page.

**Checkpoint:** You can name and describe each main menu item (Home, Catalog, Create, Docs, Search, Settings).

### Step 2: Explore the Catalog

1. Click **Catalog** in the sidebar.
2. See the list of **entities** (components, APIs, templates, etc.). A fresh install may have sample entities.
3. Click one entity and explore:
   - **Overview** tab (description, links, ownership).
   - **CI/CD** tab (if a plugin is installed).
   - **API** tab (if it’s an API entity).
   - **Dependencies** (if shown).
4. Use the **search/filter** in the catalog to find entities by name or kind.

**Checkpoint:** You can open a component from the catalog and describe what tabs and information you see.

### Step 3: Explore “Create” (Software Templates)

1. Click **Create** in the sidebar.
2. You should see one or more **templates** (e.g. “Create a new component” or similar).
3. Click a template and see:
   - Form fields (e.g. name, owner, repo).
   - Option to **create** a new repo/component (you can cancel or use a test org/repo if you have one).

**Checkpoint:** You know where to create new components and what a template form looks like.

### Step 4: Explore Docs (TechDocs)

1. Click **Docs** in the sidebar.
2. Browse the list of docs (there may be sample docs).
3. Open a doc and see:
   - Table of contents.
   - Rendered Markdown (and possibly MkDocs-style structure).

**Checkpoint:** You know where to find documentation and how it’s presented.

### Step 5: Use Search (if available)

1. Click **Search** or use the search bar.
2. Try searching for an entity name or a doc title.
3. See how results are grouped (e.g. catalog vs docs).

**Checkpoint:** You understand how global search works (or that it may need backend configuration later).

### Step 6: Optional — Document Your Own Notes

In this repo you can keep personal notes. For example, create a short file in this directory:

- `notes.md` — 2–3 sentences per UI area (Home, Catalog, Create, Docs, Search) on what you observed.

This helps you reinforce the concepts and have a reference for later hands-on.

---

## Completion Checklist

- [ ] Opened Backstage and identified all main sidebar areas.
- [ ] Opened at least one entity in the Catalog and explored its tabs.
- [ ] Opened Create and inspected at least one Software Template.
- [ ] Opened Docs and viewed at least one TechDoc.
- [ ] Tried Search (if available).
- [ ] (Optional) Added `notes.md` with your own summary.

---

## What’s Next?

In **02-software-catalog-basics** you will learn about **entities**, **kinds**, **specs**, and **relationships** in the Software Catalog, and how to describe components in YAML.

After finishing this hands-on, commit and push your changes (e.g. this README and any `notes.md`) to your GitHub repo, then move on to `02-software-catalog-basics`.
