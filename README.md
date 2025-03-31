# Amex Challenge

## Project Configuration

### Build & Development
- Added TypeScript strict mode configuration
- Added ESLint with recommended configs:
  ```json
  {
    "extends": [
      "eslint:recommended",
      "plugin:@typescript-eslint/recommended",
      "plugin:react/recommended",
      "plugin:react-hooks/recommended"
    ]
  }

- Added Prettier for code formatting
- Added Jest and React Testing Library for unit tests

- In FUTURE...Add build optimizations:
- Code splitting
- Tree shaking
- Minification
- Source maps for production debugging

### CI/CD Pipeline
- GitHub Actions workflow for:
- Running tests
- Type checking
- Linting
- Building
- Docker image creation
- Deployment to staging/production

## Monitoring & Logging
- Add error boundary components
- Integrated application monitoring (e.g. New Relic)
- Add structured logging with Winston
- Add performance monitoring with web vitals

## Security
- Add security headers:
    - CSP
    - HSTS
    - X-Frame-Options
    - etc.
- Add input sanitization
- Add rate limiting
- Add CSRF protection
- Regular dependency updates with Dependabot

## Development Experience
- Add Husky for git hooks:
- pre-commit: lint, format
- pre-push: test, type-check
- *ADDED* commitlint for consistent commit messages
- Add documentation generation with TypeDoc
- Add component documentation with Storybook

## Docker Support
- *ADDED* Multi-stage build Dockerfile
- *ADDED* Docker Compose for local development
- Optimized node_modules caching
- *ADDED* Environment Configuration
- Add env var validation
- Add separate configs for dev/staging/prod

## Performance
- Add Lighthouse CI
- Add bundle size monitoring
- Add code coverage requirements
- Add performance budgets

## Next Steps
- Implement API rate limiting
- Add E2E tests with Cypress
- Set up automated security scanning
- Add automated accessibility testing
