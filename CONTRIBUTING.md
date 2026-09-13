# Contributing to Train-Game

This guide defines how the Train-Game team plans, reviews, and merges work. The team may revise it as the project and technology stack become clearer.

## Repository workflow

1. Create or select a GitHub issue for the work.
2. Assign one primary owner. Add collaborators when another domain is involved.
3. Create a short-lived branch from the latest `main`.
4. Make focused commits and update relevant documentation and tests.
5. Open a pull request and link the issue.
6. Obtain at least one approval from someone other than the author.
7. Resolve review comments and ensure required checks pass.
8. Squash-merge the pull request, then delete its branch.

Direct commits to `main` should be limited to repository initialization or urgent recovery work agreed to by the team. Normal project work goes through pull requests.

## Naming conventions

### Branches

Use lowercase kebab-case in this format:

```text
<type>/<issue-number>-<short-description>
```

Allowed branch types:

| Type | Use |
| --- | --- |
| `feature` | New user-facing behavior |
| `fix` | Bug correction |
| `docs` | Documentation or research |
| `design` | Branding, wireframes, or visual assets |
| `test` | Test coverage or QA tooling |
| `refactor` | Internal code changes without changed behavior |
| `chore` | Configuration, dependencies, or maintenance |

Examples:

- `docs/12-market-feasibility`
- `design/18-project-logo`
- `feature/42-route-planning`
- `fix/57-save-game-loading`

When an issue number is not available, omit that segment: `docs/market-feasibility`.

### Commits

Use Conventional Commit-style messages:

```text
<type>(optional-scope): <imperative summary>
```

Keep the first line concise, begin the summary with a lowercase verb, and omit the final period. Use the body to explain motivation or tradeoffs when the title is insufficient.

Allowed commit types are `feat`, `fix`, `docs`, `design`, `test`, `refactor`, `chore`, and `ci`.

Examples:

- `docs(brand): define primary color palette`
- `feat(routes): add station selection`
- `fix(save): preserve unlocked routes`
- `test(timetable): cover conflicting arrivals`

### Pull requests

Use the same format as commit messages for pull-request titles. Describe the completed result, explain why it is needed, provide validation steps, and link the related issue with `Closes #<number>` when merging should close it.

Keep each pull request focused on one outcome. Split unrelated changes into separate issues and branches.

### Issues

Write issue titles as concise outcomes, such as `Define target player personas` or `Add keyboard navigation to route map`. Each issue should state:

- the desired result;
- why it matters;
- acceptance criteria;
- the primary owner; and
- known dependencies.

### Files and directories

- Use lowercase kebab-case for new documentation and asset names: `market-analysis.md`, `route-map-wireframe.png`.
- Keep conventional community filenames uppercase: `README.md`, `CONTRIBUTING.md`, `LICENSE`, and `CODE_OF_CONDUCT.md`.
- Give assets descriptive names instead of version names such as `final-v2`: use `logo-dark.svg` or `station-screen-mobile.png`.
- Store project documentation under `docs/` and visual assets under `assets/` once those directories are needed.
- Decide language-specific class, function, variable, and test naming after selecting the implementation stack; document those rules here before production coding begins.

## Pull-request review requirements

Every pull request requires one approval from a non-author. Request review according to the affected domain:

| Area | Primary reviewers |
| --- | --- |
| Front end and UI | Chas or Justin |
| Back end and data | Chas or Dylan |
| Documentation | Justin or Dylan |
| Quality assurance and tests | Justin or Dylan |
| Cross-cutting architecture | Chas plus one affected-domain owner |

Authors must not approve their own pull requests. Reviewers check correctness, clarity, scope, documentation, tests where meaningful, and alignment with current requirements.

## Definition of done

Work is ready to merge when:

- its acceptance criteria are satisfied;
- relevant documentation is current;
- meaningful verification has been completed and recorded in the pull request;
- generated files, secrets, and local environment files are excluded;
- required AI assistance is recorded in `AI_LOG.md`;
- review comments are resolved; and
- a non-author has approved the change.

## AI-assisted work

Follow [the AI usage policy](docs/ai-usage-policy.md). Structural writing, architecture, algorithms, and generated starter code must be logged in `AI_LOG.md`; basic syntax lookups do not need an entry.

