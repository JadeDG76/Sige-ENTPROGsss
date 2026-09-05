# Change Log 

## Setup - GitHub Actions Workflow
- **Date:** September 6, 2026
- **Description:** Added `.github/workflows/test-html.yml` to set up automated HTML validation using `html5validator`.
- **Outcome:** Automated test runner established for all incoming pull requests into `main`.

---

## Task 1 - Build the Site Together (Team Capstone)
- **Author:** Jade De Guzman
- **Date:** September 6, 2026
- **Section Assigned:** Added section content to `index.html`.
- **Notes & Mistakes Caught:** Verified sequential workflow, synced fork from `main`, and ensured HTML tags were cleanly closed before requesting review.

---

## Task 2 - Add Your Name (Happy Path)
- **Author:** Jade De Guzman
- **Date:** September 6, 2026
- **Changes:** Added `<li>Adriel Jade De Guzman</li>` to the Team Members list in `practice-page.html`.
- **PR Status:** Passed automated `Test HTML` check (✅) and merged cleanly into `main`.

---

## Task 3 - Break It on Purpose (Failure Path)
- **Author:** Jade De Guzman
- **Date:** September 6, 2026
- **Changes:** Intentionally broke HTML markup in `practice-page.html` to test CI workflow behavior.
- **Outcome:** The `Test HTML` runner flagged invalid syntax with a red ❌ as expected. Resolved by verifying failure diagnostics and closing/repairing the PR.

---

## Task 4 - Add Announcements Section (Happy Path)
- **Author:** Jade De Guzman
- **Date:** September 6, 2026
- **Branch:** `task-4-announcements`
- **Changes:** Added `<h2>Announcements</h2>` block with placeholder text `<p>Nothing new yet.</p>` to `practice-page.html`.
- **PR Status:** Passed automated `Test HTML` check (✅) and merged into `main`.

---

## Task 5 - Fix an Existing Failing PR (Stretch Goal)
- **Author:** Jade De Guzman
- **Date:** September 6, 2026
- **Branch:** `task-5-fix`
- **Initial State:** Submitted invalid HTML syntax (`<INVALIDTAG>`) to trigger a failing `Test HTML` workflow (❌).
- **In-Place Repair:** Pushed a corrective commit directly to `task-5-fix` without closing the pull request.
- **Final Outcome:** Re-run workflow turned green (✅); PR successfully merged into `main`.
