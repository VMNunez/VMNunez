# CLAUDE.md — VMNunez (GitHub profile README)

This repo is Víctor's **GitHub profile README** (`github.com/VMNunez/VMNunez`) — the page that shows
when a recruiter opens his GitHub profile. It is a **public, recruiter-facing artifact**, not a study
file: treat every line as something Víctor must be able to defend in an interview.

## Who maintains this and how

Claude is the one responsible for keeping this README **up to date and optimized** for Víctor's target:
a **junior / junior-mid Angular + Java (Spring Boot) developer role in Spain**, target Aug–Sept 2026,
mainly at large consultancies (NTT Data, Capgemini, Indra, Accenture and similar).

- **Claude edits the content directly** in this repo — Víctor does not want to be asked for context
  every session; this file + the source repo below is the context.
- **Víctor always makes the commit and push himself**, with the message Claude gives him. Never commit
  or push from here automatically — same rule as the main `learning` repo.
- This repo has **no other source of truth** — everything in it must trace back to real, verifiable
  facts (the source repo below, or something Víctor states directly). Never invent a stack, a metric,
  or a project detail.

## Source of truth — the `learning` repo

Nearly everything shown here is generated from
`C:\Users\Victor\Documents\main\dev\learning` (repo `dev-learning`). Read these before any update:

| File | What it gives you |
|---|---|
| `PROGRESS.md` | Every project, its status, and concepts learned — the project table's source |
| `projects/07-timetrack/PLANNING.md` (Section 0) | The **live** status of the flagship full-stack project — never say it's further along than this |
| `personal/job-search/internship-daw.md` | Ground truth for the Sagatech internship (dates, stack, the GitFlow story) — **outside the repo**, read directly |
| `notes/cv/cv-bullets.md` (if it exists) | Polished bullets from `portfolio-audit` — reuse the phrasing, don't rewrite from scratch |
| `notes/prompts/_shared-context.md` | Víctor's profile, English level, market context |

**A project is only added here as "shipped/done"** once it has passed `portfolio-audit` with a
✅ Ready verdict in the `learning` repo (see that repo's `notes/prompts/projects/portfolio/portfolio-audit.md`,
Phase 3). An in-progress project (like TimeTrack today) can be shown, but must be labelled honestly as
in progress — never implied finished.

## Voice and defensibility rules (same as the CV/LinkedIn standard)

- English (this is the public GitHub profile — recruiters at Spanish consultancies expect it in English
  here, unlike the CV which is in Spanish).
- No buzzwords ("passionate", "results-driven"), no filler adjectives.
- Every claim must be something Víctor can defend line-by-line in a technical interview.
- Prefer concrete evidence (stack used, a decision made, a real outcome) over generic claims.

## Known gaps — pending polish (as of 2026-07-09)

Flagged in review, not yet applied — pick these up on the next pass:

1. **No contact path.** No LinkedIn link, no location (e.g. Madrid/Barcelona), no way for an
   interested recruiter to reach out. This is the highest-priority gap — everything else in the README
   is wasted if there's no next step.
2. **"Currently building" framing risk.** The TimeTrack section is honest about it being in progress,
   but a recruiter skimming for ~20 seconds might read "unfinished" and move on before reaching the
   real substance (Spring Security, JWT, JPA already built). Reframe so the weight falls on what's
   already real, not on what's left.
3. **No visual proof.** The Angular projects table is text-only links. A screenshot or short GIF (start
   with the most complete one, HR Portal — guards, interceptors, role-based dashboard) would convert
   better than another link.
4. **English level not mentioned.** B2 / Cambridge FCE (in progress) is relevant for consultancies with
   international clients and costs nothing to state — add a short line.

## When to re-run a full pass

- Whenever a project passes `portfolio-audit` as ✅ Ready in the `learning` repo (per that repo's rule).
- Whenever Víctor asks directly ("optimize my profile", "update the portfolio README").
- Point Víctor to `notes/prompts/strategy/apply/profile-readme-prompt.md` in the `learning` repo if he
  wants a structured, repeatable way to trigger this from a fresh chat.
