# Frontend Pull Request Template

**Ticket / Issue**
- Closes: # (issue number) / Fixes: # / Related: #

## Summary
- One-sentence summary of the change.
- High-level rationale — why this change is needed.

## Key changes
- Bullet list of the most important changes (components created/updated, hooks, services, styles, assets, pages, build config, package updates).

## Type of change (check all that apply)
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation
- [ ] Refactor
- [ ] Tests
- [ ] CI/CD
- [ ] Chore (deps, tooling)
- [ ] Release
- [ ] Other — describe: ______

## Breaking changes
- [ ] Yes — describe breaking change(s) and migration plan
- [ ] No

## UI / Design
- Is this change visible to users? (Yes/No)
- Design links (Figma/Sketch):
- Visual changelog (short description of UX change):

## Accessibility
- [ ] Keyboard navigation verified

## Browser / Device Support
- Supported browsers and versions tested locally (e.g., Chrome, Firefox, Safari, Edge)
- Responsive breakpoints checked (mobile/tablet/desktop)

## Dependencies
- [ ] None
- [ ] New package(s) added — list packages and reasons
- [ ] Packages updated — list packages and reasons

## Testing performed
**Type:**
- [ ] Automated (unit / integration / e2e) — list affected test suites and commands to run (e.g., `yarn test`, `npm run test:unit`)
- [ ] Manual — describe scenarios and verification steps (include pages, actions, expected results)
- [ ] Storybook / component previews added — link or story names

**Details:**
Describe how the changes were tested (commands, scenarios, or attach screenshots if manual).

## How to run locally (exact commands)
- Clone/checkout:
  - `git checkout -b <branch-name>`
- Setup:
  - e.g., `cp .env.example .env` and set environment variables
  - `yarn install` or `npm install`
- Run:
  - `yarn start` / `npm start`
  - `yarn test` / `npm test`
  - `yarn build` / `npm run build`
  - `yarn storybook` (if applicable)

## Security considerations
- Any new secrets, token scope changes, or user data exposure
- Third-party scripts or tracking added — review required

## Checklist (self-review)
- [ ] I have reviewed my PR
- [ ] I removed unnecessary logs and commented-out code
- [ ] I ran the test suite locally and all tests pass
- [ ] I added/updated tests for my changes
- [ ] I updated documentation where needed (README, components README)
- [ ] I considered security implications

## Notes for the reviewer
- Anything the reviewer should focus on, tricky areas, or files to ignore
- Suggested reviewers or teams: @team/frontend, @team-design

## Screenshots / Recordings (required for UI changes)
- Attach screenshots, recordings, or GIFs demonstrating UI/behavior

## Other notes
