# Contributing through your own fork

[Back to project index](README.md) · [Work plan](WORK_PLAN.md)

The main group repository is **https://github.com/ahmet360/archetype_design_persusion** and its default branch is **`main`**. Team members contribute through forks and pull requests; they do not receive collaborator access to this repository.

## 1. Fork the group repository

Open the main group repository and click **Fork**. Select your own GitHub account. Keep `main` as the starting branch.

This group repository is itself a fork of the instructor's starter. If GitHub says you already have a fork in this repository network, use that existing fork and set its local `upstream` remote to the group repository below. You do not need a second fork.

## 2. Clone your fork and connect to the group repository

Replace `YOUR-USERNAME` with your GitHub username. If your fork has a different repository name, use its actual clone URL and change the following cd command to the actual folder name.

```bash
git clone https://github.com/YOUR-USERNAME/archetype_design_persusion.git
cd archetype_design_persusion
git remote add upstream https://github.com/ahmet360/archetype_design_persusion.git
git fetch upstream
git switch -c your-topic-branch upstream/main
```

If an `upstream` remote already exists, check `git remote -v` and use `git remote set-url upstream https://github.com/ahmet360/archetype_design_persusion.git` if it points elsewhere.

**Remote meanings:** `origin` is your fork; `upstream` is the group's `ahmet360/archetype_design_persusion` repository.

## 3. Record an issue and complete your assigned pages

[GitHub Issues](https://github.com/ahmet360/archetype_design_persusion/issues) are enabled. Create an issue with the owner, reviewer, exact file paths, and a completion checklist. Link it from the PR and your About page. Do not invent or backdate issue numbers. Follow the current [assignment](assignment.md) and [templates](reference/page-templates.md).

Use the role assignments in [WORK_PLAN.md](WORK_PLAN.md). Replace the TODOs in your pages, add specific examples and sources, and review the Markdown preview. The page headings are suggested organization, not an additional grading rubric.

Check for existing work before replacing a template. Tim's Explorer and Hero research is already merged through PR #7; the earlier PR #1 was closed as redundant. Continue from the group main.

## 4. Commit and push to your fork

Stage only the files you worked on. This example stages the Explorer page; use your own paths and branch name.

```bash
git status
git diff
git add brand-archetypes/explorer.md
git commit -m "Complete Explorer archetype research"
git push -u origin your-topic-branch
```

Do not push to `upstream`. Your changes belong in your fork until the group reviews your pull request.

## 5. Open a pull request into the group repository

On GitHub, open a pull request and use **compare across forks** if needed. Confirm all four fields:

| Field | Required value |
| --- | --- |
| Base repository | `ahmet360/archetype_design_persusion` |
| Base branch | `main` |
| Head repository | Your own fork |
| Compare branch | Your topic branch |

Because the group repository is a fork, GitHub may suggest the instructor's repository as the base. Explicitly select **the group's repository** before submitting.

Describe which pages you completed, check the **Files changed** tab, and create the pull request. Address review comments by committing and pushing further changes to the same branch in your fork. The repository owner reviews and merges the pull request.

## 6. Keep future work current

Before starting the next contribution, commit or otherwise safely save your current work, then:

```bash
git fetch upstream
git switch -c your-next-topic upstream/main
```

For an existing topic branch, bring in new group changes with `git merge upstream/main`, resolve any conflicts, and push to your fork again.

## Sync your fork after group merges

On your fork's GitHub page, choose **Sync fork → Update branch** for main and verify that the source is the group repository. If GitHub reports conflicts, do not discard your commits.

For a local clone, save unfinished changes safely, confirm that upstream points to the group repository, and use:

```bash
git fetch origin
git fetch upstream
git switch main
git merge --ff-only origin/main
git merge upstream/main
git push origin main
```

If the fast-forward step fails or Git reports conflicts, stop and reconcile the branches before pushing. Do not force-push or reset away work. Branch names and the current folder must match your clone.

Ahmet cannot update a teammate's fork without write permission; each owner performs this sync. Local topic branches may also need a merge from upstream/main.

## Repository owner

GitHub does not let the owner fork their own repository. The owner can create a topic branch in this group repository and open a pull request from that branch into `main`. Other members use their own forks as described above.
