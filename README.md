# College Student Productivity Platform — PM Case Study

A personal Product Management case study I built while learning PM, and while applying for PM internships.

It follows one problem — college students missing deadlines — all the way from a real survey through to a problem statement, an MVP, a PRD, UX flow, an agile delivery plan, metrics, and a roadmap.

> **Honesty note:** This is a student project, not a real company or a launched product. Nothing here is a real user metric, real revenue, or a real experiment result. Wherever I go beyond what the research actually shows, I've labeled it as a hypothesis or an assumption instead of presenting it as fact.

---

## Why I made this

I wanted to practice the full PM workflow — not just "come up with a feature idea," but actually start from real user research, question my own assumptions, and only then move toward a product decision. So this project runs in phases, and each phase builds on the one before it.

---

## Project phases

| Phase | File | What it covers |
|---|---|---|
| Raw data | `Reasearch_Data_PM_.xlsx` | The original Google Form survey responses (25 college students), unedited. |
| Phase 1 — Research Analysis | `College_Productivity_Platform_Research_Analysis.xlsx` | Turns the raw survey into a proper analysis: quantitative breakdowns, qualitative theme coding, pain points, and key insights — all calculated with formulas, not typed-in numbers. |
| Phase 2 — Problem Definition & Product Strategy | `Phase2_Problem_Definition_Product_Strategy.docx` | Reviews the research, picks the strongest problem (not just the one I originally assumed), defines the target user, a persona, user needs, a user journey, competitive analysis, vision, and a small MVP scope. |
| Phase 3 — Feature Prioritization & PRD | `Phase3_Feature_Prioritization_PRD.pages` | Brainstorms features, prioritizes them (evidence + impact + effort, not a made-up RICE score), locks in the final MVP, and writes the PRD with goals/non-goals, functional requirements, and user stories. |
| Phase 4 — UX, User Flow & Figma Design Spec | `Phase4_UX_Figma_Design_Spec.pages` | The UX direction, information architecture, core user flow, and a screen-by-screen plan meant to be built out in Figma. |
| Phase 5 — Agile Execution, Backlog & Sprint Plan | `Phase5_Agile_Execution_Backlog_SprintPlan.pages` | A lightweight Scrum-style plan: epics/stories/tasks, story points, and 4 sprints to actually build the MVP. |
| Phase 6 — Product Metrics & Experimentation | `Phase6_Product_Metrics_Experimentation.pages` | How I'd know if this was actually working: a North Star metric, supporting/guardrail metrics, a funnel, and 4 planned experiments. |
| Phase 7 — Product Roadmap & Release Strategy | `Phase7_Product_Roadmap.pages` | A staged roadmap (validation → MVP → v1 improvements), with clear gates for what needs to be proven before adding more. |
| Phase 8 — Final Product Case Study | `Phase8_Final_Product_Case_Study.pages` | Everything above pulled into one portfolio-ready document, plus risks, research limitations, what I'd do next, and a 60-second interview summary. |

**Suggested reading order:** Phase 1 → 2 → 3 → 4 → 5 → 6 → 7 → 8. Phase 8 is the shortest way to see the whole project if you're short on time.

---

## A quick look at the research

From the 25-response survey (small sample — see limitations below):

- **56%** of students forget or miss an important task "Sometimes," "Often," or "Very Often."
- **76%** already use 2 or more tools/platforms to track deadlines — so the problem isn't "no tools," it's "no tool that pulls it together."
- **WhatsApp** is the single most-used tool for tracking deadlines (60% of mentions) — even though it's a chat app, not a task manager.
- Three themes tied as the biggest pain points, each mentioned by 32% of students: **information scattered across platforms, manual tracking, and weak/inconsistent reminders.**

## The problem I chose to solve

> College students juggling multiple ongoing responsibilities (assignments, exams, forms, project work, and internship/placement applications) struggle to reliably track and get reminded about their deadlines, because the relevant information is spread across separate channels (WhatsApp, email, the college portal, calendars) and current reminders are missing or require manual setup — which leads to missed deadlines, lost opportunities, and last-minute stress.

**Target user (hypothesis, not proven):** later-year (3rd–4th year) engineering/CS students juggling coursework with internship/placement applications. I'm calling this a hypothesis on purpose — 68% of the survey respondents were 4th-years, so this segment could just be over-represented in the sample rather than genuinely more affected.

## The MVP

Kept deliberately small — just enough to test the core idea:

1. Add a deadline (title, date, category)
2. See upcoming deadlines in one simple list
3. Get a basic reminder before a deadline
4. Mark a task as complete
5. Simple categories (assignment, exam, form/application, project, placement)

**Not in the MVP:** automatic WhatsApp/email parsing, AI features, social features, gamification, advanced analytics. These are noted as *possible future ideas*, not commitments.

## How I'd measure success

**North Star Metric:** Deadline Adherence Rate — the percentage of tracked deadlines completed before their due date. Full details, supporting metrics, guardrails, and planned experiments are in Phase 6.

## Research limitations (worth knowing before judging any of this too harshly)

- Small sample — only 25 responses.
- Skewed toward 4th-year students (68% of the sample), so year-based conclusions are hypotheses, not proof.
- Mostly CS/engineering branches — other courses are barely represented.
- Self-reported data — no interviews or usage data to cross-check it.
- 44% of open-ended answers were vague enough to be coded as "Other/Unclear."

## About this repo

This is a learning project, built to practice end-to-end PM thinking for internship applications — not a pitch for a real company. Feedback is very welcome, especially on anywhere the research doesn't actually support the conclusion I drew from it.
