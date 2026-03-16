# Changelog

## [2026-03-16] avs-smartphrase.html v1.0
- Added AVS SmartPhrase Excel Generator to ClinForge
- Form-based entry with drag-to-reorder locations and section dividers
- Paste mode with auto-parsing of structured text
- Live preview mirroring Epic paste formatting
- ExcelJS in-browser .xlsx generation (no server)
- Epic-safe formatting: bold, italic, blue phones, gray section dividers, 2-column layout
- Reference tab with Epic paste workflow and build standards

## [2026-03-16] index.html
- Added AVS SmartPhrase Excel Generator card to Available Tools section

## [2026-03-16] nabla-setup.html v2.0
- Added Nabla Setup Tool to ClinForge
- Note Style Analyzer: paste de-identified notes, AI detects documentation patterns
- Build from Scratch: step-by-step questionnaire for General, HPI, PE, A&P, Results
- Section Troubleshooter: paste current instructions + describe problem, AI suggests fix
- Pattern Advisor: learns from saved output history
- BYOK (Bring Your Own Key): direct browser-to-Anthropic API via CORS
- Output history with localStorage persistence
- ClinForge design system integration

## [2026-03-16] index.html
- Added Nabla Setup Tool card to Available Tools section

## [2026-03-16] command-center.html v3.1
- Initial deployment
- Concurrent patient timers with pause/resume/switch
- Patient metadata: new-to-me, translator, complexity 1-5, scheduled vs actual time
- Split timers: visit duration + chart closure tracked separately
- Finish-time projection with green/yellow/red thresholds
- Non-patient time tracking (Inbox, Prior Auth, Referrals, Admin, Other)
- Weekly report with complexity breakdown, patient type breakdown, NPT breakdown
- localStorage exception: non-clinical persistence for timing data

## [2026-03-16] index.html
- Added Command Center card to Available Tools section

## [2026-03-16] cystatin-c.html v2.3
- Initial deployment
- CKD-EPI 2021 calculator (eGFRcr, eGFRcr-cys, eGFRcys)
- BSA adjustment for drug dosing
- Sources: KDIGO 2024, NKF-KDOQI 2025, VA/DoD 2025
