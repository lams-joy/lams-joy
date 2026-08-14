# GitHub Profile README setup

This folder is designed to become your GitHub profile repository.

## 1. Repository name

Create a **public** repository whose name is exactly your GitHub username.

For example:

```text
jlamka/jlamka
```

Then place `README.md` and `.github/workflows/snake.yml` in that repository.

## 2. Important username check

The README currently uses `jlamka` in the dynamic GitHub widgets.

If your actual GitHub username is different, replace every occurrence of:

```text
jlamka
```

with your actual username.

## 3. Contribution animation

The workflow generates:

- `snake.svg` for light mode
- `snake-dark.svg` for dark mode

It publishes them to an `output` branch automatically.

The workflow runs daily and can also be started manually from:

**GitHub → Actions → Generate Contribution Snake → Run workflow**

## 4. Optional upgrades

You can later add:

- a custom profile illustration
- a 3D contribution graph
- GitHub trophies
- pinned project cards
- a custom portfolio link
- a LinkedIn badge
- a downloadable CV badge

The README is intentionally kept professional enough for recruiters while still having personality.
