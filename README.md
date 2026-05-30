# [PROJECT NAME]

One paragraph describing what this project does, who uses it, and where it runs.

## Quick start

```bash
npm ci
npm run dev
```

## Where the rules live

| Topic | Location |
|---|---|
| 5 gates, workflow, Day-1 checklist | [`lhuasheng/.github/CONTRIBUTING.md`](https://github.com/lhuasheng/.github/blob/main/CONTRIBUTING.md) |
| AI / Copilot rules (org-wide) | [`lhuasheng/.github/copilot-instructions.md`](https://github.com/lhuasheng/.github/blob/main/copilot-instructions.md) |
| AI / Copilot rules (this project) | `.github/copilot-instructions.md` |
| CI gate logic | [`lhuasheng/shared-sdlc`](https://github.com/lhuasheng/shared-sdlc) |
| Project-specific contributing notes | `CONTRIBUTING.md` |

## One-time repo setup

After creating this repo from the template:

1. **Add admin token secret** — Settings → Secrets → Actions → New secret:
   `REPO_ADMIN_TOKEN` (token must have repository administration write access)
2. **Run the bootstrap workflow** — Actions → **Setup — New Repo Bootstrap** → Run workflow
   (creates labels + branch protection)
3. **Add the API key secret** — Settings → Secrets → Actions → New secret:
   `ANTHROPIC_API_KEY`
4. **Fill in this README** — replace `[PROJECT NAME]` and the description above
5. **Update `.github/copilot-instructions.md`** — replace the stack placeholder
6. **Update `CONTRIBUTING.md`** — add any project-specific gate rules
