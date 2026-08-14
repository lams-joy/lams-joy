# Joy Lamka GitHub Profile Setup

## 1. Create the profile repository

Create a public repository named exactly your GitHub username.

The README currently assumes:

```text
jlamka
```

Replace `jlamka` if your username is different.

## 2. Add the files

```text
README.md
SETUP.md
assets/joy-banner.svg
.github/workflows/contribution-arcade.yml
.github/workflows/contribution-snake.yml
```

## 3. Enable GitHub Actions

Go to Repository → Settings → Actions → General and allow GitHub Actions.

Run **Generate contribution arcade** manually once. It publishes the generated Galaga-style contribution visualization to the `output-pacman` branch.

Run **Generate contribution snake** manually if you also want the snake animation available.

## 4. Why the arcade is only one section

The profile deliberately does NOT make everything game-themed. The arcade is a visual signature in the middle of the profile; the rest is a normal developer profile with projects, skills, telemetry and a personal growth story.

## 5. Custom banner

`assets/joy-banner.svg` is a custom original arcade-inspired banner made for this profile. It can be edited later without changing the README structure.
