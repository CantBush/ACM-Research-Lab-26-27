# Submissions

Each deliverable is turned in as a pull request to this repo.

## Layout

```
submissions/
  <your-name>/
    week-4/
    week-5/
    ...
```

Use your first and last name in lowercase with a hyphen, for example `submissions/jane-doe/week-4/`.

## How to submit

1. Create a branch named `<your-name>/week-N`.
2. Add your work under `submissions/<your-name>/week-N/`. Include a short `README.md` that says what you did and how to run it.
3. Open a PR into `main` titled `Week N — <Your Name>`.
4. A lead reviews it and leaves comments. Address them, and the lead merges the PR.

## API keys

- Load your key from a `.env` file, for example `OPENROUTER_API_KEY=...`. The repo's `.gitignore` already excludes `.env`.
- Never paste a key into code, a notebook output, or a PR comment.
- If you commit a key by accident, tell a lead right away so they can revoke it. Deleting the file in a later commit does not remove it from git history.
