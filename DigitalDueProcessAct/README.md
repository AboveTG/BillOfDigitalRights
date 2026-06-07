Digital Due Process Act — folder overview

This folder contains materials for the Minnesota Digital Due Process Act (a first "Act" in a staged rollout of the broader "American Bill of Digital Rights").

Purpose
- Present a concise, committee-ready packet for Minnesota policymakers.
- Maintain a clear separation between working drafts and packet-ready materials.

Structure (implemented below)
- 00_README_START_HERE/: Guidance for using the packet
- 01_ONE_PAGE_SUMMARY/: One-page handouts for quick distribution
- 02_LEGISLATIVE_BRIEF/: In-depth brief and talking points
- 03_PROBLEM_AND_EVIDENCE/: Problem statement, case examples, evidence
- 04_DRAFT_LEGISLATION/: Draft bill and section-by-section explanation
- 05_CONSTITUTIONAL_SUPPORT/: Constitutional/legal analysis resources
- 06_FISCAL_AND_IMPLEMENTATION/: Fiscal notes and agency guidance
- 07_STAKEHOLDER_ANALYSIS/: Stakeholder maps and messaging
- 08_FAQ_AND_REBUTTALS/: FAQs and common oppositions
- 09_REAL_WORLD_EXAMPLES/: Case studies and scenarios
- 10_LEGISLATIVE_OUTREACH/: Email templates, meeting scripts, testimony
- 11_APPENDICES/: Glossary, references, citations

Notes
- Existing markdown files (e.g., `LegislativeBrief.md`, `LegislativeProblemStatement.md`, `MinnesotaDigitalDueProcessAct.md`) have been copied into the packet subfolders.
- Keep working drafts in a `drafts/` subfolder if you want to preserve iterative changes.
- Final copies: authoritative files have been added to `final/`.
- Drafts: place working or incremental files in `drafts/`.


Next steps you can ask me to do now:
- Move any additional authoritative files into `final/` (I can do this).
- Create a versioning scheme and `CHANGELOG.md` (I can generate one).
- Produce committee-ready packet PDFs and a separate print-ready one-pager.

Lead-by-example architecture
- Purpose: this Act serves as the canonical template for future Acts that will compose the American Bill of Digital Rights. Use the templates in `templates/` to create consistent, defensible, and committee-ready packets.

How to create a new Act using this packet (recommended quick workflow):
1. Copy `templates/ACT_TEMPLATE.md` to `YourState_YourAct_Packet/04_DRAFT_LEGISLATION/` and replace front-matter metadata.
2. Draft the problem statement from `templates/PROBLEM_TEMPLATE.md` into `03_PROBLEM_AND_EVIDENCE/`.
3. Complete the legislative brief using `templates/BRIEF_TEMPLATE.md` in `02_LEGISLATIVE_BRIEF/`.
4. Place the authoritative bill text (use `templates/BILL_TEMPLATE.md`) in `04_DRAFT_LEGISLATION/` and add a short section-by-section note.
5. Populate `06_FISCAL_AND_IMPLEMENTATION/` with an `IMPLEMENTATION_CHECKLIST.md` (see `templates/IMPLEMENTATION_CHECKLIST.md`) and agency recordkeeping guidance (`templates/RECORDKEEPING_POLICY.md`).
6. Move finalized files into `final/` and regenerate PDFs for distribution.

Templates and guidance are in `templates/` (below). Use them as starting points and adapt jurisdiction-specific language where necessary. If you want, I can scaffold a new Act packet automatically from these templates.
