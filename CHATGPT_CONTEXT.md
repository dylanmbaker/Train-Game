# Train-Game: Repository Context for ChatGPT

Last reviewed: 2026-09-13 (America/Chicago)

## Purpose of this document

This file is a self-contained briefing on the current Train-Game repository. It is intended to be supplied to ChatGPT as project context for planning and discussion. It describes what is actually present in the repository, identifies incomplete decisions, and avoids inventing requirements that have not yet been documented.

Because this is a snapshot, it should be updated whenever the repository gains meaningful requirements, designs, code, decisions, or team-process documentation.

## Project summary

- Repository name: `Train-Game`
- Remote repository: `https://github.com/dylanmbaker/Train-Game`
- Default and current branch: `main`
- Current reviewed commit: `d00e245a5cdeb5f1e50f4f37f44f783fa4027f3b`
- Current implementation status: planning/documentation scaffold only
- Course context: CS 598 Senior Project 1
- Current deliverable: Assignment 1, Project Initiation Foundations
- Assignment 1 target due date: 2026-09-13 at 11:59 PM CT
- Application source code: none yet
- Tests, build scripts, dependency manifests, configuration, and assets: none yet
- License: not specified

Despite the repository name, the current files do not define what kind of train game is being made. The gameplay, platform, technology stack, visual direction, business model, scope, and delivery schedule remain undecided or undocumented.

## Team and stated responsibilities

The README assigns the following roles:

| Team member | Responsibilities |
| --- | --- |
| Justin | Documentation, quality assurance, front end |
| Chas | Team lead, back end, front end |
| Dylan | Documentation, back end, quality assurance |

These are broad areas of ownership. The repository does not yet define specific deliverables, decision authority, review assignments, or task status for each person.

## Repository contents

### `README.md`

The README is a project-planning template. It contains sections for:

- team roles and responsibilities;
- project brand kit and identity guidelines;
- repository setup;
- contribution guidelines;
- AI usage logging and policy;
- market feasibility analysis; and
- a project business case.

Most sections contain headings or blank fields rather than completed decisions.

### `readmeprof.md`

This local reference contains the instructor's complete semester schedule, assignment requirements, examples, and FAQ. Assignment 1 requires team roles, a brand kit, repository setup, a contribution guide, an AI log and policy, market feasibility analysis, and a business case. The file also establishes that Semester 1 focuses on requirements, design, architecture, and planning; full-scale implementation occurs in Semester 2.

The local file is reference material and is not intended to be committed or pushed.

### `AI_LOG.md`

The AI log contains an empty table with these columns:

1. Date
2. Team Member
3. Tool & Version
4. Prompt / Query Summary
5. Output Received & Intended Use
6. Human Verification & Modifications Made

The log now records material AI assistance used to create structural project documentation. The instructor requires logging for architecture, algorithm design, starter code generation, and structural content generation; basic syntax searches do not require entries.

### `.gitignore`

The file contains only a newline, so it currently ignores nothing. It will need entries appropriate to the technology stack once that stack is selected.

## Documented planning areas

The repository identifies these areas as work that needs to be defined:

### Brand identity

The planned brand kit should specify:

- official project name;
- logo assets;
- color palette with HEX/RGB values;
- typography standards; and
- broader identity standards for marketing and UI/UX.

None of these fields has been completed.

### Repository and contribution process

The README calls for:

- repository workflow standards;
- branch naming conventions;
- pull-request procedures;
- code-review requirements;
- commit-message formats;
- branch-protection rules; and
- repository access permissions.

The local repository does not document any of these policies yet. A GitHub remote and `main` branch exist, but the local files do not establish whether GitHub settings such as branch protection are configured.

### AI usage policy

The intended policy should cover approved generative-AI tools, transparency, logging of prompts and outputs, human verification, and modifications made after generation. At present, only the empty log template exists; there are no written rules defining what use is permitted or how detailed entries should be.

### Market feasibility

The README requests analysis of:

- existing commercial or open-source solutions;
- target audiences;
- competitors; and
- the project's value proposition.

No analysis has been added.

### Business case

The proposed business case has placeholders for:

- an introduction explaining the problem and project justification;
- customers and competitors;
- innovation, expected impact, and return on investment; and
- formal role statements.

None of these sections contains substantive content yet.

## Git history at the time of review

| Date | Commit | Author | Change |
| --- | --- | --- | --- |
| 2026-08-30 | `403a050` | Dylan Baker | Created the repository with a one-line README |
| 2026-08-30 | `28fd593` | Dylan Baker | Added `AI_LOG.md` |
| 2026-08-30 | `f779805` | Justin1117 | Expanded the README into the current planning template |
| 2026-09-13 | `d00e245` | Dylan Baker | Added `.gitignore` |

Before this context file was created, local `main` matched `origin/main` and the working tree was clean.

## Facts that are not yet known

ChatGPT should treat all of the following as open questions rather than settled requirements:

- What is the core game concept and player objective?
- Is this a simulation, management game, puzzle game, action game, educational game, or another genre?
- Who is the intended audience?
- Which platforms should be supported: browser, desktop, mobile, console, or something else?
- Is the game single-player, local multiplayer, online multiplayer, or some combination?
- What is the intended session length and progression loop?
- Is there a narrative, setting, or historical theme?
- What makes this project different from existing train games?
- Which programming language, engine, framework, database, and hosting platform will be used?
- What front-end/back-end boundary is required, if any?
- What are the minimum viable product features?
- What accessibility, performance, privacy, security, and browser/device requirements apply?
- What additional course constraints or grading details apply beyond the requirements in `readmeprof.md`?
- Will the project be open source, and under which license?
- How will work be tracked and assigned?
- What visual identity and user-interface style should be used?
- What AI tools and uses are approved, and how should AI-assisted work be logged?

## Recommended next decisions

The most useful next step is to write a short product brief before selecting the stack or implementing features. That brief should establish:

1. A one-sentence game pitch.
2. The target player and target platform.
3. The core gameplay loop.
4. Three to five features required for the first playable version.
5. Features explicitly deferred until later.
6. A basic interaction or screen flow.
7. Constraints such as deadlines, grading requirements, team experience, and available services.
8. A technology choice justified by those requirements.
9. Team ownership and the first milestone.

After those decisions, the team can replace the README placeholders with real project documentation, add contribution rules, configure `.gitignore`, scaffold the application, and create meaningful tests around game behavior.

## Guidance for ChatGPT when using this file

- Separate confirmed repository facts from suggestions.
- Do not infer gameplay merely from the name `Train-Game`.
- Ask for missing product requirements before proposing a detailed architecture.
- If assumptions are needed for brainstorming, label them clearly and make them easy to replace.
- Keep recommendations realistic for a three-person team with overlapping front-end, back-end, documentation, and QA roles.
- When proposing work, connect each task to an owner, dependency, and observable completion criterion.
- Treat this file's reviewed date and commit hash as freshness markers. If the repository has changed since then, request an updated snapshot or current file contents.

## Source boundary

This briefing is based only on the repository files and local Git metadata available on 2026-09-13. It does not claim knowledge of conversations, assignment instructions, tickets, GitHub settings, unpublished designs, or plans that are not stored in this repository.
