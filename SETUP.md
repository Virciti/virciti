# GitHub Profile Installation

This package is ready to use as the profile README for the GitHub account `Virciti`.

## Install

1. On GitHub, create a new **public** repository named exactly `Virciti`.
2. Keep the repository public and initialize it without a generated README.
3. Upload this package's `README.md` and the complete `assets` directory to the repository root.
4. Commit the files to the repository's default branch.
5. Visit `https://github.com/Virciti` and confirm that the profile README appears beneath the account header.

The final repository should look like this:

```text
Virciti/
├── README.md
└── assets/
    ├── hero-dark.svg
    ├── hero-light.svg
    ├── system-map-dark.svg
    └── system-map-light.svg
```

## Optional command-line installation

```bash
git clone https://github.com/Virciti/Virciti.git
cd Virciti
# Copy README.md and assets/ from this package into the repository.
git add README.md assets/
git commit -m "Create GitHub profile experience"
git push origin main
```

## Design behavior

- GitHub automatically selects the dark or light artwork using the visitor's color preference.
- The hero remains fully legible when animation is disabled.
- No external fonts, scripts, analytics, counters, or third-party badge services are used.
- The public copy intentionally avoids infrastructure details, model versions, deployment topology, customer names, and internal security information.

## Updating the closing line

Edit this line near the bottom of `README.md`:

```markdown
### Overly ambitious. ADHD-powered. Building Physical AI.
```

## Recommended profile bio

```text
Overly ambitious. ADHD-powered. Building Physical AI.
```
