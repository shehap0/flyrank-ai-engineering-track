# CLAUDE.md

## Stack
- Frontend: React, TypeScript, Tailwind CSS, Three.js, GSAP
- Backend: ASP.NET Core, Entity Framework Core, SQL Server
- Tooling: Vite, Git, OpenCode (AI pair-programming tool)
- OS/environment: Fedora Linux

## Conventions
- Commits follow Conventional Commits (`feat:`, `fix:`, `docs:`, `chore:`) — no exceptions.
- Components are functional, hooks-based; no class components.
- Styling via Tailwind utility classes; avoid inline styles unless dynamic.
- Backend: repository pattern for data access, EF Core migrations committed alongside schema changes.
- Branch naming: `week-XX/description` for internship task branches.

## AI assistant rules
- Always explain non-trivial changes before applying them.
- Never commit directly — stage changes and let me review the diff first.
- When adding a feature, write it, then write/run a quick verification (test or manual check) before considering it done.