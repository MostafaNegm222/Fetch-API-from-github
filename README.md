# Fetch GitHub Repos

## 1. Description

A small web app that fetches and displays the public repositories of any GitHub username, using the GitHub REST API. It shows each repository's name, star count and a link to it.

## 2. Technologies and Versions

- HTML5, CSS3, vanilla JavaScript (no build step)
- GitHub REST API (`GET https://api.github.com/users/{username}/repos`)

## 3. Requirements and Dependencies

- A modern web browser with JavaScript enabled
- An internet connection
- No packages to install

## 4. Installation and Run Steps

```bash
git clone https://github.com/MostafaNegm222/Fetch-API-from-github.git
cd Fetch-API-from-github
```

Open `index.html` in a web browser.

## 5. Environment Variables

None required. (The GitHub API rate limit applies; a personal access token would raise it, but none is needed.)

## 6. Usage and Main Features

1. Enter a GitHub username in the input field.
2. Click the "Fetch Data" button.
3. The app lists the user's repositories with their names, star counts and links.
- The entered username must exist on GitHub.

## 7. Screenshots / Demo

- Live demo: https://mostafanegm222.github.io/Fetch-API-from-github/

## 8. Running Tests

No automated tests in this repo.
