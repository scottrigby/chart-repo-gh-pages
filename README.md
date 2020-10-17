# Example chart repo on GitHub pages

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Repos

- stable: <https://scottrigby.github.io/chart-repo-gh-pages/stable>
- incubator: <https://scottrigby.github.io/chart-repo-gh-pages/incubator>

## Purpose

The purpose of this project is to demonstrate hosting a Helm chart repo entirely on GitHub pages, using GitHub actions.
There are edge cases where this is preferable.

To host a chart repo index on GitHub pages with packages in GitHub releases, instead use <https://github.com/helm/chart-releaser-action>.
This is often the better choice, since you can then get download stats using the GitHub API.

## License

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
[Apache 2.0 License](https://github.com/scottrigby/chart-repo-gh-pages/blob/main/LICENSE).
