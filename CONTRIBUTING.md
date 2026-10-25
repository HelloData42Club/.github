# Contributing to HelloData

Thank you for taking the time to contribute! This project is maintained by the HelloData. Every contribution, from fixing a typo to writing a full module are very helpfull.

Please read this guide before opening an issue or a pull request. It keeps the project consistent and saves everyone time.

## Table of contents

1. [Code of Conduct](#code-of-conduct)
2. [Ways to contribute](#ways-to-contribute)
3. [Getting started](#getting-started)
4. [Workflow](#workflow)
5. [Branch naming](#branch-naming)
6. [Commit messages](#commit-messages)
7. [Pull requests](#pull-requests)
8. [Review process](#review-process)
9. [Content standards](#content-standards)
10. [Definition of Ready and Definition of Done](#definition-of-ready-and-definition-of-done)
11. [Project board](#project-board)
12. [Getting help](#getting-help)

## Code of Conduct

This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold it. Report unacceptable behavior to 'hellodataclub42@gmail.com'.

## Ways to contribute

- **Report a problem**: a mistake in a subject, a broken dataset link, an unclear instruction.
- **Propose something**: TODO
- **Improve existing content**: clarify a subject, add hints, improve a solution.
- **Review pull requests**: reading someone else's work is a valuable and needed contribution.
- **Improve the tooling and documentation**: scripts, CI, README, Wiki.

> [!TIP]
> Some issues are simple and will be mark as such, do not hesitate to do them if it's your first contribution !

> [!WARNING]
> We must choose what are the different "things" that will be done and that require contribution
## Getting started

1. **Fork** the repository (external contributors) or **clone** it directly (organization members).
2. Clone your copy:
   ```bash
   git clone https://github.com/HelloData42Club/<repo>.git
   cd <repo>
   ```
3. Set up your environment
4. And take the pre-commit hook
> [!NOTE]
> The environment and pre-commit hook may be different for each projet

## Workflow

1. **Find or create an issue.** Every change starts from an issue, so the work is discussed before it is done. Comment on it to say you are taking it, and wait for a maintainer to assign it to you.
2. **Create a branch** from `main` (see [Branch naming](#branch-naming)). You can use the *Create a branch* button in the issue's **Development** panel to link them automatically.
3. **Make your changes** in small, focused commits (Each block of change should result in a commit). 
4. **Open a pull request** against `main` and link the issue.
5. **Address review feedback**, then a maintainer merges.

Never push directly to `main`. It is protected and only changes through reviewed pull requests.

## Branch naming

Use the pattern `<type>/<short-description>`, in lowercase with hyphens.

| Type | Use for | Example |
|---|---|---|
| `feat` | New module, exercise or feature | `feat/module-02-sql-subject` |
| `fix` | Correction of an error | `fix/ex01-dataset-link` |
| `docs` | Documentation only | `docs/update-readme-prerequisites` |
| `chore` | Tooling, CI, maintenance | `chore/add-linter-config` |

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<optional scope>): <short summary in the imperative>
```

Examples:

```
feat(module-01): add dataset
fix(ex03): correct expected output in subject
docs: add contribution to the changelog
chore(ci): run markdown lint on pull requests
```

Rules:
- Keep the summary under 100 character.
- Use the imperative mood ("add", not "added").
- Explain the *why* in the commit body when it is not obvious.

## Pull requests

- Keep them **small and focused**: one topic per PR.
- Fill in the **pull request template** completely (If you fell the need to add an important part, you're free to do so).
- Link the issue with `Closes #<number>` so it is closed automatically on merge.
- Make sure all automated checks pass.
- When the PR's ready make it correct.
- Add screenshots or sample output when the change is visual or numeric.

## Review process

- Every PR needs **at least one approval** from a maintainer before merging.
- If no one answer your PR, fell free to send a message in the discord.
- Reviewers: be nice and professional, the reviewed work will really help HelloData. 
- Authors: respond to the comments. Do not take feedback personall.
- PRs are merged using **squash and merge** to keep the history clean. (Every commit are united in one commit on main)

## Content standards

### Subjects and exercises

> [!WARNING]
> We must make a template/todo for the different "thing" that one can do.

### Folder structure

> [!WARNING]
> We must discus of the structure style of the different project.

### Code style

- Follow the language style of the project.
- Make sure that you follow the style requirement of the project.

> [!NOTE]
> Each project have it's languages, and each language have it's coding style.

> [!IMPORTANT]
> Make sure to follow your project style and the architecture choice !

### Datasets

- Only use datasets whose license allows redistribution, and credit the source.
- Do not commit large files. Link to the source.
- Never include personal or sensitive data, make sure it's legal.

### Writing

- Write in **English** to keep the content accessible to everyone, if needed you can discus in French in the **Discussion** canal.
- Use short sentences and plain words.
- Check spelling before submitting.

## Definition of Ready and Definition of Done

### Definition of Ready (an issue can move to *Ready*)

- [ ] The title is clear and starts with a verb.
- [ ] The description explains the goal and the context.
- [ ] Acceptance criteria are listed.
- [ ] Labels, milestone and estimated size are set.
- [ ] No unresolved dependency or blocker.

It is your job to make sure that your issues make sense and add something.

### Definition of Done (an issue can move to *Done*)

- [ ] The change meets all acceptance criteria.
- [ ] The content has been tested (code runs, instructions are reproducible).
- [ ] Documentation and `CHANGELOG.md` are updated.
- [ ] Automated checks pass.
- [ ] The PR is approved and merged into `main`.

## Project board

We track work on our GitHub Project board. Each issue moves through these columns:

| Status | Meaning |
|---|---|
| **Backlog** | Captured, not yet prioritized |
| **Ready** | Clear and prioritized, available to take |
| **In progress** | Someone is actively working on it |
| **In review** | A pull request is open and awaiting review |
| **Done** | Merged and closed |

Please keep an issue's status up to date when you work on it.

## Getting help

- **Questions about the content or the project**: open a thread in [Discussions](https://github.com/orgs/HelloData42Club/discussions).
- **Real-time chat**: `<our-discord-link>`.
- **Private matters**: `HelloDataClub42@gmail.com`.

Thank you for helping make HelloData better!
