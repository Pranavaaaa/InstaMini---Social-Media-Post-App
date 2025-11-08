# Contributing

Thanks for your interest in contributing to InstaMini!

Guidelines

- Fork the repository and create a branch for your change: `git checkout -b feat/my-change`
- Run and update tests (if any) and ensure lint rules pass (project uses basic ESLint in frontend).
- Keep PRs focused and small — one feature or bugfix per PR.
- Write clear commit messages and include a description in the PR.

Code style

- Follow the existing project style. The frontend uses modern React and functional components.
- Run `npm run lint` in the frontend to check linting rules (if configured).

Security & reporting

- Do not commit secrets (API keys, passwords). Use `.env` files and add them to `.gitignore`.
- To report security issues, please open an issue or contact the repository owner privately.
