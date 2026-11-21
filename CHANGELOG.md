# Changelog

All notable changes to this project will be documented in this file. See [commit-and-tag-version](https://github.com/absolute-version/commit-and-tag-version) for commit guidelines.

## [2.0.0](https://github.com/tonylea/helm-chart-bookshelf/compare/v1.0.1...v2.0.0) (2026-11-21)

### ⚠ BREAKING CHANGES

* persistence.data is now a list of named mounts, each at
  /data/<name>, with at least one required.

### Features

* mount each data volume at /data/<name> ([3de7058](https://github.com/tonylea/helm-chart-bookshelf/commit/3de705889f7c986024891d8e3b580d59a6919b84))

### Documentation

* show the chart's download count ([db9f810](https://github.com/tonylea/helm-chart-bookshelf/commit/db9f810163339830bf5a8cc2a18a4c747f9be068))

## [1.0.1](https://github.com/tonylea/helm-chart-bookshelf/compare/v1.0.0...v1.0.1) (2026-11-21)

### Bug Fixes

* leave resource requests to whoever deploys the chart ([a9ed8dc](https://github.com/tonylea/helm-chart-bookshelf/commit/a9ed8dce4caaa84e33e661555e3e27e30e2fc34a))

### Documentation

* keep only the comments that record a decision ([b07d932](https://github.com/tonylea/helm-chart-bookshelf/commit/b07d932c054c2bf09b66ac6a528f6a170c79efd8))
* keep the README to the fixed settings and what the chart needs ([9859b0a](https://github.com/tonylea/helm-chart-bookshelf/commit/9859b0ae01f7cb6e0f398f23aaedec8eb1eb67ce))
* link Bookshelf's own repo rather than the Servarr wiki ([319f780](https://github.com/tonylea/helm-chart-bookshelf/commit/319f7805dd65a5770da75c8152d7da6542238e93))

## 1.0.0 (2026-11-21)

### Features

* deploy Bookshelf on Postgres, with a fixed API key, a required login and claims for /config and /data ([7c59a9a](https://github.com/tonylea/helm-chart-bookshelf/commit/7c59a9af51dac104740e80e3fa3833e635802f53))

### Documentation

* describe the chart, its values and how to contribute ([90ef551](https://github.com/tonylea/helm-chart-bookshelf/commit/90ef551a5e13689cb57f35752f4ee90e7ddba569))
