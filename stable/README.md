# Stable

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add chart-repo-gh-pages-stable https://scottrigby.github.io/chart-repo-gh-pages/stable
```

You can then run `helm search repo chart-repo-gh-pages-stable` to see the charts, or browse on CNCF [Artifact Hub](https://artifacthub.io/packages/search?page=1&repo=helm-stable).

## Purpose

This project demonstrates hosting a Helm chart repo entirely on GitHub pages, using GitHub actions.
There are edge cases where this is preferable.

To host a chart repo index on GitHub pages with packages in GitHub releases, instead use <https://github.com/helm/chart-releaser-action>.
This is usually the better choice, since you can then get download stats using the GitHub API.

## License

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
[Apache 2.0 License](https://github.com/scottrigby/chart-repo-gh-pages/blob/main/LICENSE).
