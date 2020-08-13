# changelog-playground

Sandbox for testing commit linting, changelog generation and versioning.

## Features
- Generating a new semver with `npm version` also generates and commits a changelog based on the configuration in package.json
- `commitlint` enforces JIRA style commit headers
- Githooks are managed by `husky`
