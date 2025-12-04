---
id: 1
title: Physical AI Robotics Textbook Constitution
stage: constitution
date: 2025-12-04
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: master
user: User
command: /sp.constitution
labels: [constitution, project-setup, documentation]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
- ./.specify/memory/constitution.md
tests:
- none
---

## Prompt

```text
Write a project constitution for the project:

“Physical AI & Humanoid Robotics Textbook”.

Follow the Spec-Kit Plus conventions: produce a `memory/constitution.md` style constitution that defines immutable, global standards for all future content, code, and artifacts.

Your output must:

- Use the template structure of Spec-Kit Plus constitution (global project rules, principles, constraints, governance).
- Define at least 6 core principles (Articles) that will guide all features (chapters, labs, code examples, documentation).
- Clearly specify for each principle: name and detailed description.
- Include additional sections for constraints/standards (for code quality, documentation, reproducibility, modularity).
- Include a section describing the development workflow / collaboration rules.
- Include a governance section (how to amend constitution, versioning, ratification date, etc.).
- Reference the fact this is an AI-driven, educational textbook + robotics project (not a typical software library).
- Use precise, non-vague, enforceable rules (e.g. “All notebooks must include tests or validation cells”, “All chapters must include learning objectives, worked examples, exercises”, etc.).
- The constitution should guide not only code but also pedagogical content, documentation style, lab reproducibility, clarity, accessibility.

Do *not* include feature-specific specs (which will come later); only global rules that apply across the entire project.

Output the constitution markdown directly — with headings, clear principle statements, version info, placeholders filled (use today’s date as ratification date).
```

## Response snapshot

The project constitution for "Physical AI & Humanoid Robotics Textbook" has been created at `./.specify/memory/constitution.md`. It defines immutable, global standards for all future content, code, and artifacts, adhering to Spec-Kit Plus conventions. The constitution includes 6 core principles (Pedagogical Clarity, Code Reproducibility, Practical Application & Robotics Relevance, Test-Driven Learning, Documentation & Accessibility, Modularity & Extensibility), additional constraints and standards for Code Quality, Documentation Style, Reproducibility, Modularity, and sections for Development Workflow & Collaboration, and Governance. The initial version is 1.0.0, ratified and last amended on 2025-12-04.

## Outcome

- ✅ Impact: Project constitution defined.
- 🧪 Tests: none
- 📁 Files: ./.specify/memory/constitution.md created/modified.
- 🔁 Next prompts: None
- 🧠 Reflection: Successfully generated and wrote the project constitution.

## Evaluation notes (flywheel)

- Failure modes observed: `create-phr.sh` script not found, requiring manual PHR generation.
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): Verify existence and path of `create-phr.sh` or ensure agent has direct file writing capabilities for PHRs.
