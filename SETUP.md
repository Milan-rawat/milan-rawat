# Setup Guide

## Required repository

Your GitHub profile repository must be:

```text
milan-rawat/milan-rawat
```

The repository must be public.

## Folder structure

```text
README.md
.github/
└── workflows/
    ├── snake.yml
    └── profile-3d.yml
```

Do not place workflow files inside `.git`.

## Installation

1. Copy all files from this package into the repository root.
2. Commit and push the files.
3. Open the repository on GitHub.
4. Go to **Settings → Actions → General**.
5. Under **Workflow permissions**, select **Read and write permissions**.
6. Save the setting.
7. Open **Actions**.
8. Run **Generate contribution snake** manually.
9. Run **Generate 3D contribution calendar** manually.
10. Refresh the profile after both workflows complete.

The 3D contribution calendar workflow commits generated files to the main repository.
The snake workflow publishes generated files to an `output` branch.

## Optional checks

- Confirm the default branch is named `main` or `master`.
- Enable private contribution visibility from GitHub profile settings when desired.
- Hard-refresh the profile with `Ctrl + F5` after the first workflow run.
