# DueSoon
A small personal assignment planner for GUI Design & Web Optimization.

Author: Hazar Umut Bitnel. Prepared as catch-up work on 27 October 2026 with Codex assistance.

## Versions
- `/v1/`: preserved first build. Add assignments, mark completion and delete items.
- `/`: redesigned version. Earliest-deadline sorting, due-status labels, next-seven-days view, course filter, search, edit and undo for the most recent deletion.

## Run
Serve this folder using any static server, or publish its contents to GitHub Pages / Netlify. No build command or dependencies are needed. Use an HTTP localhost server or HTTPS hosting for browser APIs.

## Storage and limitations
Each version stores data only in the current browser, using a separate localStorage key. There is no account, cloud sync, import from Teams, exact deadline time or reminder system. Clearing browser data can erase assignments. Dates follow the device's local calendar; a task becomes overdue on the next day. The optional sample dataset is fictional.

## Design process
The first build was inspected against Nielsen's usability heuristics. The redesign responds to recovery, deadline interpretation and feedback issues. Desk research informed the provisional context. No user interviews or usability study with participants were conducted; the redesign is not user-validated.

## Checks
Both scripts passed JavaScript syntax checks. Browser checks covered adding, editing, deletion/undo, completion/reopening, search, course filtering, next-seven-days filtering and reload persistence. The first version's insertion ordering and immediate deletion were inspected directly. These are functional checks, not evidence of improved student outcomes.

## References
- https://www.nngroup.com/articles/ten-usability-heuristics/
- https://lsc.cornell.edu/managing-time/
- https://support.microsoft.com/en-us/education/assignments/schedule-work-to-assign-later
