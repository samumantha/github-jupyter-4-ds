# How to organize a group's work

## GitHub organizations

Should I start a repository under my account or open a new organization?
- Single-person projects often start under own account.
- It is no problem to move a project from own namespace to an organization later.
- When starting a larger project with several people, possibly several affiliations, an organization may be a better start.
- If this is a GitHub pages project, then it will matter for the URL:
  `myuser.github.io/myproject/` vs. `ourorg.github.io/ourproject/`.

Should I add everybody as collaborator?
- If you are a handful of project collaborators it probably makes sense to add everybody as collaborators.
- But one does not have to be a *collaborator* to contribute (anybody can send contributions to public projects).
- External contributors don't have to be added.

---

## Organizational permissions

- Organizations have **owners** and **members**.
- Owners can add additional members and delete repositories.
- Members can also be organized into teams.
- We recommend to write-protect the default branch and protect it against force-pushes and accidental deletions.

---

## GitHub or GitLab?

- GitHub: probably better integrations (with services like Zenodo), probably more visibility (more users).
- GitLab: more features, you can also self-host, more advanced continuous integration.
- Your own university's GitLab: most control, local support, but limited visibility and you might lose access when you move on.
- [Nordic GitLab](https://coderefinery.org/repository/): easier collaboration across organizations and national borders, visibility within Nordics.

---

## Direct commits or pull requests?

- For single-person projects: direct pushes.
- If you have somebody who can help you with code review: use pull requests.
- For projects with 2 or more persons: agree on applying all changes via pull requests
  and create a new branch for every change.


---

## Small vs. large changes


- Small changes or agreed upon improvements can be worked on directly.
- For larger changes first open an issue and describe your idea and collect feedback.
- Alternative: if you already have a larger change half-finished but you are unsure whether you are on the right
  track, open a **draft pull request**. These are meant to share unfinished drafts and collect suggestions.
