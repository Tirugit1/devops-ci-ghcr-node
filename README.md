DevOps CI project (Node.js + GHCR)

This repository is a skeleton for a CI/CD pipeline using GitHub Actions and publishing container images to GitHub Container Registry (GHCR).

Structure created:
- src/ (sample Express app)
- .github/workflows/ci.yml (build & test)
- .github/workflows/publish-ghcr.yml (build + push to GHCR)
- Dockerfile, .dockerignore, .gitignore

Quick start:
1. Edit code in src/
2. Push to GitHub and enable workflows
3. To publish to GHCR: ensure repository permissions allow packages: write (GITHUB_TOKEN) or create a PAT and set it to secrets.GHCR_PAT. See .github/workflows/publish-ghcr.yml for usage.

License: add your own
