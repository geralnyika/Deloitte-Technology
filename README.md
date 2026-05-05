
This repository contains Deliverables and solutions from the Deloitte Australia Technology consulting simulation on Forage.

## Task 1: Telemetry Data Unification

**The problem:** Daikibo Industrials' factory needed analysis, however, unified analysis was not possible because the factory telemetry from Daikibo Industrials was coming in two different JSON formats.

**What I built:** A Python data pipeline that imports both formats, converts timestamps to UTC, and produces a standardized schema that can be used for further analysis. incorporates automated unit testing to verify the accuracy of the output.

**Files:**
- `main.py` - Conversion functions and unit tests
- `data-1.json` - Input format 1 (flat structure)
- `data-2.json` - Input format 2 (nested structure)
- `data-result.json` - Target unified output format

**Results:** All 3 unit tests passed successfully.

## Task 2: Development Proposal

Drafted a formal development proposal for a real-time manufacturing status dashboard for Daikibo Industrials, covering project scope, man-hour estimates, project timeline, and post-launch support planning.

**Files:**
- `Geraldine Nyika  —  Software Development Proposal.pdf` - Full proposal document

## Technologies Used
- Python 3
- JSON
