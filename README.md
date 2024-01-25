# Pull Request Dashboard

This project aims to provide a clear and concise dashboard for open Pull Requests on GitHub. It is designed as a single HTML page for straightforward, local, and secure use. The page is also available on GitHub Pages.

## Usage

1. Generate a standard GitHub Personal Access Token with read access to the `repo` scope across all organizations you wish to monitor.
2. Open `pr-radiator.html` or visit [sampsakuronen.github.io/terrific-status-updater/pr-radiator.html](https://sampsakuronen.github.io/terrific-status-updater/pr-radiator.html) and follow the user interface instructions.

## Contributing

To contribute, fork the repository and submit a pull request. As a token of appreciation, your name will be added to this README. You can also raise issues. However, please note that time is only allocated to this project if GitHub makes a breaking change to the API.

### Technical Guidelines

- The project is contained in a single file.
- The only requests made are to the GitHub PR API.
- There is no build process: no preprocessors or fancy build tools are used.
- The project has no dependencies.
- The project runs on a modern browser, so you can assume modern browser functionalities are available.

## Contributors

- Sampsa Kuronen
