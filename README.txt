HanHan Care V2.0 Release Candidate (FICTIONAL TEST ONLY)

1. Extract ZIP and open index.html, load 2213-foods.csv.
2. Use DEMO-only records. Release candidate has a distinct localStorage key: hanhan-v2-release-fixture-only-v1.
3. Test add/edit/delete, supplements totals, backup/restore, browser restart.
4. Run the existing 16 checks, then section 7's 9 release checks and export JSON.
5. For HTTPS, deploy ONLY to a separate test origin (e.g. test subdomain) with restricted access. Never overwrite V1.9.0 or public demo, and never input real health data.
6. A different URL path on the same origin does not isolate localStorage.
7. If anything fails: STOP, export the DEMO backup, keep the old ZIP, do not clear or overwrite any other version.
8. A passing fictional test does NOT approve real health data use.
