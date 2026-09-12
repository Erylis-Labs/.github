# Contributing

## Development workflow

1. Create a branch from the default branch.
2. Make focused and atomic changes.
3. Run the relevant tests and quality checks locally.
4. Open a pull request.
5. Ensure all CI checks pass before merging.

## Branch naming

Recommended conventions:

- `feat/<description>`
- `fix/<description>`
- `refactor/<description>`
- `docs/<description>`
- `chore/<description>`

Examples:

```text
feat/add-oidc-authentication
fix/terraform-provider-version
chore/update-dependencies
```

## Commits

Use clear and concise commit messages.

Conventional Commits are recommended (not enforced):

```text
feat: add OIDC authentication
fix: correct Terraform backend configuration
docs: update deployment instructions
chore: update dependencies
```

## Pull requests

Pull requests should:

- contain a focused set of changes;
- explain the purpose of the change;
- pass all automated checks;
- contain no secrets or sensitive information.

## Security

Do not report security vulnerabilities through public issues.

See [SECURITY.md](SECURITY.md) for reporting instructions.
