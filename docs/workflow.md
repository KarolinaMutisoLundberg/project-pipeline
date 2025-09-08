# Git Workflow Guidelines

## Branch naming
- **main** → always stable, production-ready code
- **dev** → integration branch, where features are merged
- **feature/** → for new features
  - example: `feature/login-page`
- **bugfix/** → for fixes
  - example: `bugfix/navbar-alignment`
- **hotfix/** → urgent fix on main
  - example: `hotfix/typo-homepage`

## Commit messages
Use short, descriptive messages in **imperative mood** ("add", "fix", "update").

Examples:
- `add login form component`
- `fix bug in session context`
- `update README with setup instructions`
- `remove unused imports`
- `refactor button styles`

## Pull requests
- Always open PRs into **dev**
- At least one code review before merge
- Squash commits when merging (keeps history clean)