# Solution for Issue #4: [BOUNTY $150] AGENT: Claude Code sub-agent that reviews a PR and posts a structured comment

## 💰 Bounty: $150 — powered by [Opire](https://opire.dev)

## Description
Create a Claude Code agent that takes a PR diff as input, analyzes it,
and returns a structured Markdown review comment.

## Acceptance Criteria
- [ ] Works via CLI: `claude-review --pr https://github.com/owner/repo/pull/123`
- [ ] OR via GitHub Action (include the workflow YAML)
- [ ] Structured Markdown output with:
  - Summary of changes (2–3 sentences)
  - Identified risks (list)
  - Improvement suggestions (list)
  - Confidence score: Low / Medium / High
- [ ] Tested on at least 2 real GitHub PRs (include outputs in the PR)
- [ ] README with setup and usage instructions

## How to Claim
1. Comment `/opire try` in this issue
2. Submit a PR with the agent + sample outputs
3. Payment is released automatically on merge ✅
