# Plugin agent workspace navigation QA

Supporting Web QA for the upstream plugin navigation fix. These artifacts contain only synthetic test projects and idle mock-provider agents in an isolated daemon. They do not contain production conversations or credentials.

- `after.png`: native archived agent tab and callout alongside the preserved Explorer search.
- `after.webm`: browser test recording, including repeated opens and native Unarchive.
- `e2e-after.log`: raw Playwright output from the passing run.
- `before.webm` and `e2e-before.log`: the same test with the original navigation bridge; the archived workspace tab never becomes visible.

This is Chromium Web evidence on Linux. It is not a macOS Desktop verification or real-provider transcript resumption test.
