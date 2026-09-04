# What changed when retargeting this site from NeurIPS 2026 to NAACL 2027

Applied on 2026-09-04, aligned with the submitted proposal
(`assets/real-health-naacl2027-proposal.pdf`).

## Files changed
- `_config.yml` — title, description, keywords, `url`, blog name, contact note.
- `_pages/home.md` — new title, hero, welcome text (clinical-NLP framing, three
  clusters with agent safety promoted to cluster 2, multilinguality cross-cutting),
  new "How we differ from neighbouring venues" section, NAACL dates table,
  archival status, ARR statement, hybrid participation section, shared-task blurb.
- `_pages/call_for_paper.md` — full rewrite: topics, ACL paper lengths, archival
  status, OpenReview-no-ARR declaration, ethics section, D&I section, NAACL dates.
- `_pages/schedule.md` — 7.5-hour program matching the proposal, plus a
  "Hybrid and virtual-only participation" section (required by the ACL call).
- `_pages/shared_task.md` — 2027 timeline, multilingual and multi-turn agentic
  subtracks, ethics and risk-management section, artifacts section.
- `_pages/speakers.md` — intro rewritten to 9 confirmed speakers.
- `_pages/organization.md` — intro paragraph, workshop roles in bios, PC note.
- `_pages/contact.md`, `_pages/accepted_papers.md` — year and dates.
- `_news/announcement_1.md`, `_news/announcement_2.md` — rewritten.
- `README.md` — rewritten, including a note on the repository name.

## Things you must decide before publishing

1. **Repository name / URL.** `_config.yml` sets
   `url: https://real-health-workshop.github.io`, matching the proposal. That
   resolves only if the repo is `real-health-workshop.github.io` under a user or
   org of that name. Otherwise revert the `url` line and change the URL in the PDF.

2. **Three speakers are commented out.** James Zou, Lei Xing, and Yanmin Gong
   appeared on the old site but are not among the 9 confirmed speakers in the
   proposal. They are wrapped in HTML comments in `_pages/home.md` and
   `_pages/speakers.md`, not deleted. If they are genuinely confirmed, remove the
   comment wrappers and update the count in the proposal.

3. **Program committee.** The site says members "have confirmed". The proposal
   marks all 38 with a dagger meaning the same thing. Verify before the CFP goes out.

4. **Dewan Fahim Noor** appears in the site PC list but not in the proposal PC
   list. Reconcile the two.

5. **Nothing is live until October 2, 2026.** Every page carries a provisional
   status note. Remove those notes only after notification.
