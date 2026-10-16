# Turning in work

Each deliverable is turned in as one row in the lab's Notion submissions database. Every member adds their own row, even when the work is a team's.

| Field | What goes in it |
| --- | --- |
| Name | Your name |
| Week | The week number |
| Doc | Link to your Google Doc: the one-page writeup (Weeks 4–7), or the slides or paper (Weeks 8–10) |
| Repo | Link to the commit you are turning in |

To get a commit link, open the commit on GitHub and copy the URL. It shows the repo as it was at the deadline.

Share the Google Doc so both leads can comment on it.

## The one-page writeup (Weeks 4–7)

Keep it to one page. Use this outline:

- **Name and week**, for example "Jane Doe — Week 5".
- **What you did.** A few sentences.
- **Results.** What happened, with a number, output, or figure if you have one.
- **Stuck on or unsure about.** Anything a lead should help with.

In Weeks 8–10 the slides or paper replace the writeup.

## The repo

- **Weeks 4–5:** your own repo, which you create in Week 4.
- **Weeks 6–10:** one shared repo per team.

Either way:

- Use a folder per week (`week-4/`, `week-5/`, ...).
- Add a short `README.md` at the top that says how to run the code.
- Make the repo public, or add both leads as collaborators.

## API keys

- Load your key from a `.env` file, for example `OPENROUTER_API_KEY=...`, and add `.env` to your repo's `.gitignore` before your first commit. This repo's [`.gitignore`](../.gitignore) is a good starting point.
- Never paste a key into code, a notebook output, or your writeup.
- If you commit a key by accident, tell a lead right away so they can revoke it. Deleting the file in a later commit does not remove it from git history.

## TBD

- The link to the Notion database.
