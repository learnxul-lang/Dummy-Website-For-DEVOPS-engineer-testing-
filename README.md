# DevOps Practical Competence Assessment

This repository is a practical assessment environment for testing a Junior DevOps Engineer or DevOps trainee on **Git, GitHub, collaboration workflows and CI/CD deployment**.

## Assessment overview

- **Type:** Practical / scenario-based
- **Recommended duration:** (Unknown)
- **Production branch:** `main`
- **Deployment target:** Vercel

The candidate is expected to determine the appropriate commands and workflow. This repository deliberately avoids providing a command-by-command solution.

## Candidate starting point

The repository contains a small static website:

- `index.html`
- `style.css`
- `app.js`
- `.env.example`
- `.gitignore`
- `notes.txt`

The initial website displays **Version 1.0**.

## Assessment documentation

### Candidate
- [Candidate Instructions](assessment/CANDIDATE-INSTRUCTIONS.md)
- [Submission Requirements](assessment/SUBMISSION-REQUIREMENTS.md)
- [README Questions](assessment/README-QUESTIONS.md)

### Assessor
- [Assessor Guide](assessor/ASSESSOR-GUIDE.md)
- [Collaboration Incident](assessor/INCIDENT-INSTRUCTIONS.md)
- [Marking Rubric](assessor/MARKING-RUBRIC.md)
- [Verification Checklist](assessor/VERIFICATION-CHECKLIST.md)

## Core competencies tested

The assessment covers local Git workflow, staging and commits, ignored files, GitHub remotes, branches, Pull Requests, merging, synchronising remote changes, conflict handling, repository history and automatic deployment.

The expected end-to-end model is:

**Working files → staging → local commit history → GitHub remote → feature branch → Pull Request → merge to main → automated deployment → live application**

## Security note

Only dummy assessment values may be used. Real credentials, passwords, API keys and production secrets must never be committed to this repository.
