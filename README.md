# Nabhag Motivaras — Resume

This repository contains the source for my current software engineering resume and the career material used to maintain it.

The resume is aimed at engineering roles involving AI infrastructure, durable workflow execution, sandboxed runtimes, orchestration, and backend systems.

## Resume

The main document is [`resume.tex`](./resume.tex). It is an A4, single-page LaTeX resume with:

- clickable profile and project links
- a compact, recruiter-readable layout
- experience, projects, skills, and education sections
- a focus on systems, infrastructure, backend engineering, and applied AI

The document is designed to compile directly in Overleaf. Upload the repository or open `resume.tex` as the main file, then compile with the default LaTeX engine.

## Project highlights

- **orchex — Durable Workflow Engine:** workflow execution and orchestration infrastructure
- **lyo — Virtual Fitting Room:** asynchronous backend and real-time AI inference pipeline
- **ask-pg — Terminal PG Agent:** local-first, schema-aware natural-language interface for PostgreSQL

## Repository files

| File | Purpose |
| --- | --- |
| [`resume.tex`](./resume.tex) | Overleaf-ready resume source |
| [`CAREER_SOURCE.md`](./CAREER_SOURCE.md) | Detailed source material, work history, projects, claims, and links |
| [`RESUME_LINKS.md`](./RESUME_LINKS.md) | Organized inventory of supporting profiles, repositories, designs, schemas, and demos |
| [`RESUME_BRIEF.md`](./RESUME_BRIEF.md) | Target roles, positioning, and one-page layout constraints |

The Markdown files are working source material. The public-facing artifact is the rendered resume generated from `resume.tex`.

## Profile

- [Portfolio](https://nabhag.dev)
- [GitHub](https://github.com/Nabhag8848)
- [LinkedIn](https://www.linkedin.com/in/nabhagmotivaras/)
- [LeetCode](https://leetcode.com/u/NabhagMotivaras/)

## Scope

This repository is intentionally focused on the resume and its supporting source material. It does not include private job application data, recruiter conversations, or confidential employer information.

- Designed a browser-extension state layer that synchronized fitting requests and results across tabs, content scripts, workers, and side panels with optimistic updates.
   Architected an async garment-generation pipeline that processed provider webhooks, persisted results to S3, and published completion events through Pub/Sub
- Built a Pub/Sub backend SSE pipeline streaming fitting progress and results to the browser in ~10 seconds. 
