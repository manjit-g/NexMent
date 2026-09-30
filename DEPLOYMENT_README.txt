Clean deployment package
=========================
This package excludes:
- .env and environment secrets
- .git history
- node_modules
- .next build output
- private payment/preference uploads

Before deployment:
1. Install dependencies with npm install.
2. Configure production environment variables in your hosting provider.
3. Configure the production database and run required Prisma migrations/generation.
4. Do not commit secrets to GitHub.
