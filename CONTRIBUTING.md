# Contributing to Akdeniz-CSE-Students

Thank you for helping improve learning resources for **Akdeniz University Computer Engineering students**. We welcome contributions such as lecture notes, solved examples, lab materials, project resources, and documentation improvements.

## Before You Start

- Be respectful and collaborative.
- Make sure your contribution is related to course learning materials or organization documentation.
- Avoid uploading copyrighted or private materials that you do not have permission to share.

## 1) Fork and Clone a Repository

1. Open the repository you want to contribute to.
2. Click **Fork** (top-right on GitHub).
3. Clone your fork locally:

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

4. Add the original repository as `upstream` (recommended):

```bash
git remote add upstream https://github.com/Akdeniz-CSE-Students/<repository-name>.git
git fetch upstream
```

## 2) Branch Naming Convention

Create a new branch for every contribution. Use descriptive names.

Recommended format:

- `feat/CSE-101-notes`
- `fix/CSE-201-week3-typo`
- `docs/CSE-332-readme-update`
- `chore/repo-cleanup`

Rules:

- Use lowercase when possible.
- Use hyphens (`-`) to separate words.
- Include course code when relevant.
- Keep branch names short and meaningful.

Create your branch:

```bash
git checkout -b feat/CSE-101-notes
```

## 3) Make Changes and Commit

- Keep changes focused and small.
- Update related documentation when needed.
- Verify file names and paths are clear.

### Commit Message Guidelines

Use clear, concise commit messages.

Suggested style:

- `feat: add CSE-102 lab 2 solutions`
- `fix: correct CSE-204 SQL example typo`
- `docs: improve CSE-320 setup instructions`

Tips:

- Start with a type: `feat`, `fix`, `docs`, `chore`, `refactor`.
- Use imperative tone ("add", "update", "fix").
- Keep subject line short and specific.

Commit and push:

```bash
git add .
git commit -m "feat: add CSE-101 lecture summaries"
git push origin feat/CSE-101-notes
```

## 4) Open a Pull Request (PR)

1. Go to your fork on GitHub.
2. Click **Compare & pull request**.
3. Set base repository to `Akdeniz-CSE-Students/<repository-name>`.
4. Add a clear title and description including:
   - What you changed
   - Why it is useful
   - Which course/semester it relates to
5. Submit the PR.

After opening a PR:

- Respond politely to review comments.
- Push follow-up commits to the same branch.
- Keep discussion focused on improving the contribution.

## 5) Request a New Course Repository

If a required course repository does not exist yet, open an issue in this `.github` repository.

- Go to **Issues** → **New issue**
- Select **New Course Repository Request**
- Fill in all requested fields (Course Code, Course Name, Semester, Year, Description)

A maintainer will review your request and create the repository if appropriate.

## 6) Code Style and Content Quality

Because this organization hosts materials from many courses and technologies, please follow these general rules:

- Keep formatting consistent within each file.
- Prefer readable, beginner-friendly examples.
- Use descriptive file and folder names.
- Remove personal/private data from shared files.
- Include brief usage notes when uploading code projects.

If a course repository already has its own style guide, follow that repository's rules first.

## Need Help?

If you are unsure where to contribute, open an issue and ask maintainers for guidance. We are happy to help new contributors.
