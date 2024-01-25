# Pull Request dashboard

The purpose of this project is to provide a readable and concise dashboard to open Pull Requests on GitHub. It is built to be a single HTML page for simple, local (secure) use. The page is also hosted on GitHub Pages.

## Usage

1. Create a classic GitHub Personal Access token with read rights to `repo` scope in all organizations you wish to track
2. Open `pr-radiator.html` and use the UI

## Contributing

Fork the repository and submit a pull request. As a reward you get your name on this readme. Issues can also be raised although I only spend time on this project if GitHub changes the API in a breaking way.

### Technical guidelines

- Single file
- Doesn't do requests besides GitHub PR API
- No build: no preprocessors, fancy
- No dependencies
- Runs on a modern browser (so you can assume modern browser functionalities)

## Contributors

- Sampsa Kuronen
