# Verification performed on 17 November 2026

## Course and archive check

Checked the lab-sheet headings and starter manifests against the source repository's tasks. The ten included labs belong to AI1220 Software, Web & Mobile Engineering. Lab 2's sheet was read directly from the LMS. Lab 7 is cancelled per the user's explicit clarification. The AI2210 notebooks in the separately uploaded `Lab7.zip` were not used.

## Observed results

| Lab | Check | Result |
| --- | --- | --- |
| 1 | `PYTHONPATH=src python3 -m unittest discover -s tests` | 1 test passed |
| 2 | Required template headings and placeholder review | Required sections populated; no product-name/TODO/TBD placeholders detected |
| 3 | Required template headings and placeholder review | Stakeholders, requirements, stories, traceability and validation sections populated; no TODO/TBD placeholders detected |
| 4 | `create_song` valid/invalid calls, trimming, 80/81-character limits, rejected-request state and ID preservation | Passed |
| 5 | File inventory | Five editable DOT sources and matching SVG/PDF export filenames present; no fresh visual rendering review performed |
| 6 | `python3 -m unittest discover -s tests` | 5 tests ran: 3 passed and the 2 expected AC2 tests failed; this lab diagnoses the supplied faulty code, which was left unchanged |
| 8 | FastAPI TestClient: initial list, valid add, invalid fields, unchanged list after refusal, vote, nonexistent ID, page serving | Passed |
| 9 | Supplied `npm test` | 6 tests passed |
| 10 | Supplied `.venv/bin/python -m pytest` | 8 tests passed; 1 dependency deprecation warning |
| 11 | Supplied `npm test` after repairing the five components | 8 tests passed |

For Lab 10, the initial run was blocked by the test host's SOCKS proxy dependency. Installing `socksio` into that local virtual environment allowed the unchanged public tests to run. The submitted project manifest and lockfile were not changed for this host-only dependency.

## Limits

No fresh interactive browser/keyboard verification of the local apps was possible during this session because the connected browser returned an authentication error. No live LM Studio or IFM run was performed, no TA demonstration was performed, and the command-line Git push could not authenticate. The ten lab archives were subsequently uploaded through the signed-in GitHub website, in separate ordered commits. Prior reports inside the source labs are historical imported records, not current-session evidence.
