# Changelog

All notable changes to the AeroSPC simulator. Newest at top.

## v1.0 — 2026-10-02
- Initial release.
- 10-round shift drawn at random from a bank of 22 aerospace scenarios (X̄-R, p-, c-charts), with guaranteed variety and a stable/faulty mix.
- Three-stage round flow: stop/continue decision → root-cause diagnosis (retry until correct) → verification re-run.
- Points-based scoring: 10 pts per stop/continue call, 10 pts per diagnosis minus 4 pts per wrong attempt; every missed decision lowers the score.
- Live tracking: score %, correct decisions, missed decisions, quality cost, scrap (kg), uptime %, downtime %.
- Five competence levels (Lead Quality Engineer ≥90, Quality Engineer II 80–90, Quality Engineer I 70–80, Quality Engineer Intern 60–70, Scrap Collector <60).
- PNG certificate (client-side) awarded at Quality Engineer I (70%) and above, showing name, score, and competence level.

<!-- Template for new entries:
## v1.1 — YYYY-MM-DD
- Changed: ...
- Added: ...
- Fixed: ...
-->
