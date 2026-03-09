# GitHub Readme Stats — Quick Setup for Your Repo

This README shows how to embed dynamic GitHub stats (cards, top languages, Wakatime, gists, and pins) into your repository README using the github-readme-stats service.

## Quick Start

Add an image to your README that points to the stats API. Replace `USERNAME` with your GitHub username.

Example - simple stats card:

```md
![GitHub stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true)
```

Example - stats card with theme and icons:

```md
[![My GitHub stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=dark)](https://github.com/USERNAME)
```

Top languages card:

```md
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact)
```

Wakatime summary (if configured):

```md
![Wakatime](https://github-readme-stats.vercel.app/api/wakatime?username=USERNAME)
```

Pin a repo (example):

```md
![Pinned repo](https://github-readme-stats.vercel.app/api/pin/?username=USERNAME&repo=REPO_NAME)
```

## Query Parameters

- `username` (required): GitHub username.
- `repo` (for pin): repository name.
- `show_icons`: `true`/`false` to show icons.
- `theme`: use built-in theme names (e.g., `dark`, `radical`, `tokyonight`) or custom theme object name.
- `hide`: comma-separated items to hide (e.g., `stars,prs`).
- `count_private`: `true` to include private contributions (if token/configured).
- `include_all_commits`: `true` to count all commits.
- `locale`: set language locale (e.g., `en`, `fr`).
- `layout`: for `top-langs`, uses `compact` or default.

You can combine parameters, for example: `?username=USERNAME&show_icons=true&theme=dark&count_private=true`.

## Available Themes

This project provides multiple built-in themes. See the `themes` directory in this repository for the full list and examples.

## Using in a Profile README

Place one or more of the image links above into your profile repository README (the repository with the same name as your GitHub username). The images will render dynamically on GitHub.

## Troubleshooting

- If images do not render, ensure the URL is correct and the service (vercel) is accessible from your environment.
- For private stats (private repos/WakaTime), confirm tokens/authorization are set up according to the project's docs.

## Contributing

This repository contains the implementation and themes. To contribute themes or fixes, fork the repo, make changes, and open a pull request.

## License

See the repository LICENSE for details.

---

If you'd like, I can customize this README for your specific username/repo (replace `USERNAME` and add any cards you prefer). Tell me your GitHub username and which cards you'd like included.