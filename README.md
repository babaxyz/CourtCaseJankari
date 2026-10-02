# CourtCaseJankari — Complete Static Website

A complete multi-page HTML/CSS/JavaScript website package inspired by the user's existing CourtCaseJankari design and packaged like a multi-page static project.

## Pages
- `index.html` — Homepage
- `tools.html` — Searchable all-tools directory
- `tools/calculators.html` — Date difference, simple interest, age, GST
- `tools/limitation-helper.html` — Calendar arithmetic helper with legal caveat
- `tools/drafts.html` — 8 editable starter templates
- `tools/checklist.html` — Create/check/export a document checklist
- `tools/case-diary.html` — Local case diary, JSON import/export
- `tools/fee-tracker.html` — Local fee/expense tracker
- `tools/text-pad.html` — Hindi/English text pad, copy/download
- `tools/document-tools.html` — Text-to-file utility
- `resources.html` — Official legal resource links
- `about.html`, `contact.html`, `privacy.html`, `terms.html`

## GitHub Pages
1. Extract the ZIP.
2. Upload the **contents** of `CourtCaseJankari` to the repository root (do not upload only the ZIP).
3. Confirm `index.html`, `css/`, `js/`, `tools/` are at the repository root.
4. GitHub → Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

## Notes
- Static website; no backend, database, login or API key.
- Case diary and fee records use browser localStorage. This is not encrypted and does not sync between devices.
- Before publishing, replace `[YOUR OFFICIAL EMAIL]` in `contact.html` and `privacy.html`.
- Legal templates are starter formats. Verify current law, facts, jurisdiction, limitation and court rules before use.
- The limitation helper performs calendar arithmetic only; it does not calculate legal limitation.
- External legal-resource links require internet access.
