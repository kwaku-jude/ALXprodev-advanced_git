# ALXprodev Advanced Git

This repository demonstrates advanced Git workflows using GitFlow.

## Project Structure

- `login-page/` - Login feature implementation
- `signup-page/` - Signup feature implementation

## Features

### Version 1.0.0
- Login page scaffolding
- Signup page with data requirements (email, firstName, lastName, profilePic)

## Git Workflow

This project uses GitFlow for branch management:
- `main` - Production releases
- `develop` - Integration branch
- `feature/*` - Feature development
- `release/*` - Release preparation

## Git Hooks

- **Pre-commit**: Ensures all directories have README files
- **Post-merge**: Logs merges into main branch
