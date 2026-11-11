# ai-solopreneur: standing instructions for Claude

## Go-ahead
Just build and use your best judgment. Make any call that can be undone yourself
(code changes, tests, branches, pull requests), and at the end list the calls you
made so Bryan can check them.

Ask first before anything that can't be undone or reaches outside the repo:
deploying (Railway), touching live n8n workflows or credentials, or sending
anything to clients or third parties.

## Checks
- Tests: `node --test tests/*.test.mjs` (runs without installing dependencies).
- Full check: `npm run verify`.
- The project targets Node 24 (see .node-version).
