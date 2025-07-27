I need a rock-solid CI/CD pipeline for our finance tracker. Here's what I want to happen:

For every pull request:
- Run the full test suite (unit, integration, E2E)
- Check TypeScript compilation 
- Verify code formatting with Prettier
- Run ESLint for code quality issues
- Build the production bundle successfully
- Run security audits on dependencies
- Check for any breaking changes

For main branch merges:
- Everything from PR checks
- Deploy to a staging environment automatically
- Run smoke tests against staging
- Send a Slack notification about deployment status

For tagged releases:
- Deploy to production with zero downtime
- Run post-deployment health checks
- Update monitoring dashboards

Make this bulletproof - I never want broken code to reach production.