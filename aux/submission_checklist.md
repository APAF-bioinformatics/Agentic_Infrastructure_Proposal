# HydraR ISC Grant Submission Checklist

Target Deadline: **May 1, 2026**

## [ ] Final Review and Polish
- [ ] Review `notes/temporary/isc-proposal.qmd` for tone and technical accuracy.
- [ ] Ensure all authors agree on the budget allocation in `notes/temporary/budget_estimate.md`.
- [ ] Verify that the "Expanding the scope" section (Interoperability & Benchmarks) aligns with APAF/Macquarie goals.

## [ ] Signatories and Commitment
- [ ] confirm availability of Ignatius Pang and Aidan Tay for the 12-month project duration.
- [ ] Obtain institutional sign-off if required (typically not for ISC, but good to check).

## [ ] GitHub Submission (Crucial)
The ISC process requires a Pull Request to the [R Consortium isc-proposal repository](https://github.com/RConsortium/isc-proposal).
- [ ] Fork `RConsortium/isc-proposal`.
- [ ] Add the `isc-proposal.qmd` and any supporting images into a new directory: `proposals/2026/HydraR`.
- [ ] Submit the Pull Request before May 1st.

## [ ] Technical Validation
- [ ] Run the new unit tests for `discover_package_skills()` (see `tests/testthat/test-skill_discovery.R`).
- [ ] Ensure `devtools::check()` remains at 0 errors/warnings/notes.

---
<!-- APAF Bioinformatics | notes/temporary/submission_checklist.md | Approved | 2026-04-16 -->
