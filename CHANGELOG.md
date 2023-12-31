# 1.0.0 (2023-12-04)


### Bug Fixes

* add CMD ([957df1d](https://github.com/devops-ia/prometheus-prefect-exporter/commit/957df1d852481b3d8d92d0ab6da8c1073473711c))
* add new label on deployments metrics ([9a40887](https://github.com/devops-ia/prometheus-prefect-exporter/commit/9a40887ac7ef13d23ea96f363dd90a8f98d5749a))
* add raise_for_status() attribute ([8d20939](https://github.com/devops-ia/prometheus-prefect-exporter/commit/8d2093983f0e502b64e9b2c714338a2fc6152640))
* added flow_run_name label ([a2f96b8](https://github.com/devops-ia/prometheus-prefect-exporter/commit/a2f96b8c602df97a7d0825407d2bbc7d4ad4aab0))
* change flow_runs to Enum metrics ([b77dd7d](https://github.com/devops-ia/prometheus-prefect-exporter/commit/b77dd7d8ea7934b29345f0aa353abaa2df7f7e76))
* change name labels ([1363e94](https://github.com/devops-ia/prometheus-prefect-exporter/commit/1363e946b44a17640dad2d423f519ed47a8cf666))
* clean code ([7a3d105](https://github.com/devops-ia/prometheus-prefect-exporter/commit/7a3d105235c9ba6020df8f111bc2cf88905a7ffa))
* clean values ([cb12113](https://github.com/devops-ia/prometheus-prefect-exporter/commit/cb121139b780f31f4b4414da6e8d597c7cf3d174))
* remove admin class ([b7427dd](https://github.com/devops-ia/prometheus-prefect-exporter/commit/b7427dd1f4d52f1267e8ba66f45605cb00b51db3))
* remove libraries and clean code ([20d9cc7](https://github.com/devops-ia/prometheus-prefect-exporter/commit/20d9cc73db1f1274c761e7c6b6218f60fbcbf6b8))
* rename labels ([f4184d0](https://github.com/devops-ia/prometheus-prefect-exporter/commit/f4184d0d3cf2fe0085d2f21be8dfeb5946963173))
* urllib3 CVE-2023-45803 CVE-2023-45084 ([dc76aa6](https://github.com/devops-ia/prometheus-prefect-exporter/commit/dc76aa6885cae9047ea4a5d7d6e05b6f11fe23ab))
* use Gauge instead Enum on flow runs ([f94abcc](https://github.com/devops-ia/prometheus-prefect-exporter/commit/f94abcce33de516138ed2902ecc5c0a0df035385))


### Features

* add CI/CD and repo basic files ([ec623f3](https://github.com/devops-ia/prometheus-prefect-exporter/commit/ec623f372d02c9881144ac9de6bb625dd25cccc3))
* add deployment name and flow name on flow runs metrics ([830b4d3](https://github.com/devops-ia/prometheus-prefect-exporter/commit/830b4d3c1fc00b4e7d4b765fd303664f804ebf51))
* add prefect_flow_runs_total_run_time metric ([1a8a118](https://github.com/devops-ia/prometheus-prefect-exporter/commit/1a8a1180b925da81dcbd0fab695883108a6a11ad))
* improve logging, errors and test registry ([186f8ce](https://github.com/devops-ia/prometheus-prefect-exporter/commit/186f8ce00ebc807b272dfde2b2efd3e57a92c48f))
* reduce functions and calls to API ([94968f7](https://github.com/devops-ia/prometheus-prefect-exporter/commit/94968f77d8edb449b59b37001f9e0ec4e48cdcb3))
* release stable version ([ee9816f](https://github.com/devops-ia/prometheus-prefect-exporter/commit/ee9816fbff50f387b5775789155715e6f2afdb8b))
* use REGISTRY to save metrics ([8bd1a5b](https://github.com/devops-ia/prometheus-prefect-exporter/commit/8bd1a5b2648787f0ac3bb7cf37e394f3c655a9b0))


### BREAKING CHANGES

* add repository files, documentation and clean code.

## [1.3.1](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.3.0...v1.3.1) (2023-11-28)


### Bug Fixes

* added flow_run_name label ([a2f96b8](https://github.com/devops-ia/prometheus-prefect-exporter/commit/a2f96b8c602df97a7d0825407d2bbc7d4ad4aab0))

# [1.3.0](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.2.4...v1.3.0) (2023-11-28)


### Features

* add prefect_flow_runs_total_run_time metric ([1a8a118](https://github.com/devops-ia/prometheus-prefect-exporter/commit/1a8a1180b925da81dcbd0fab695883108a6a11ad))

## [1.2.4](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.2.3...v1.2.4) (2023-10-19)


### Bug Fixes

* urllib3 CVE-2023-45803 CVE-2023-45084 ([dc76aa6](https://github.com/devops-ia/prometheus-prefect-exporter/commit/dc76aa6885cae9047ea4a5d7d6e05b6f11fe23ab))

## [1.2.3](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.2.2...v1.2.3) (2023-10-19)


### Bug Fixes

* clean values ([cb12113](https://github.com/devops-ia/prometheus-prefect-exporter/commit/cb121139b780f31f4b4414da6e8d597c7cf3d174))

## [1.2.2](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.2.1...v1.2.2) (2023-10-17)


### Bug Fixes

* clean code ([7a3d105](https://github.com/devops-ia/prometheus-prefect-exporter/commit/7a3d105235c9ba6020df8f111bc2cf88905a7ffa))

## [1.2.1](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.2.0...v1.2.1) (2023-10-16)


### Bug Fixes

* remove admin class ([b7427dd](https://github.com/devops-ia/prometheus-prefect-exporter/commit/b7427dd1f4d52f1267e8ba66f45605cb00b51db3))

# [1.2.0](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.1.3...v1.2.0) (2023-10-16)


### Features

* reduce functions and calls to API ([94968f7](https://github.com/devops-ia/prometheus-prefect-exporter/commit/94968f77d8edb449b59b37001f9e0ec4e48cdcb3))
* use REGISTRY to save metrics ([8bd1a5b](https://github.com/devops-ia/prometheus-prefect-exporter/commit/8bd1a5b2648787f0ac3bb7cf37e394f3c655a9b0))

## [1.1.3](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.1.2...v1.1.3) (2023-10-14)


### Bug Fixes

* use Gauge instead Enum on flow runs ([f94abcc](https://github.com/devops-ia/prometheus-prefect-exporter/commit/f94abcce33de516138ed2902ecc5c0a0df035385))

## [1.1.2](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.1.1...v1.1.2) (2023-10-11)


### Bug Fixes

* add new label on deployments metrics ([9a40887](https://github.com/devops-ia/prometheus-prefect-exporter/commit/9a40887ac7ef13d23ea96f363dd90a8f98d5749a))

## [1.1.1](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.1.0...v1.1.1) (2023-10-11)


### Bug Fixes

* change name labels ([1363e94](https://github.com/devops-ia/prometheus-prefect-exporter/commit/1363e946b44a17640dad2d423f519ed47a8cf666))

# [1.1.0](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v1.0.0...v1.1.0) (2023-10-11)


### Features

* add deployment name and flow name on flow runs metrics ([830b4d3](https://github.com/devops-ia/prometheus-prefect-exporter/commit/830b4d3c1fc00b4e7d4b765fd303664f804ebf51))

# [1.0.0](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.2.2...v1.0.0) (2023-10-11)


### Features

* release stable version ([ee9816f](https://github.com/devops-ia/prometheus-prefect-exporter/commit/ee9816fbff50f387b5775789155715e6f2afdb8b))


### BREAKING CHANGES

* add repository files, documentation and clean code.

## [0.2.2](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.2.1...v0.2.2) (2023-10-10)


### Bug Fixes

* add raise_for_status() attribute ([8d20939](https://github.com/devops-ia/prometheus-prefect-exporter/commit/8d2093983f0e502b64e9b2c714338a2fc6152640))

## [0.2.1](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.2.0...v0.2.1) (2023-10-10)


### Bug Fixes

* remove libraries and clean code ([20d9cc7](https://github.com/devops-ia/prometheus-prefect-exporter/commit/20d9cc73db1f1274c761e7c6b6218f60fbcbf6b8))

# [0.2.0](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.1.2...v0.2.0) (2023-10-09)


### Features

* improve logging, errors and test registry ([186f8ce](https://github.com/devops-ia/prometheus-prefect-exporter/commit/186f8ce00ebc807b272dfde2b2efd3e57a92c48f))

## [0.1.2](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.1.1...v0.1.2) (2023-09-21)


### Bug Fixes

* change flow_runs to Enum metrics ([b77dd7d](https://github.com/devops-ia/prometheus-prefect-exporter/commit/b77dd7d8ea7934b29345f0aa353abaa2df7f7e76))

## [0.1.1](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.1.0...v0.1.1) (2023-09-20)


### Bug Fixes

* rename labels ([f4184d0](https://github.com/devops-ia/prometheus-prefect-exporter/commit/f4184d0d3cf2fe0085d2f21be8dfeb5946963173))

# [0.1.0](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.0.1...v0.1.0) (2023-09-20)


### Bug Fixes

* add CMD ([957df1d](https://github.com/devops-ia/prometheus-prefect-exporter/commit/957df1d852481b3d8d92d0ab6da8c1073473711c))


### Features

* add CI/CD and repo basic files ([ec623f3](https://github.com/devops-ia/prometheus-prefect-exporter/commit/ec623f372d02c9881144ac9de6bb625dd25cccc3))

# [0.1.0](https://github.com/devops-ia/prometheus-prefect-exporter/compare/v0.0.1...v0.1.0) (2023-09-20)


### Features

* add CI/CD and repo basic files ([ec623f3](https://github.com/devops-ia/prometheus-prefect-exporter/commit/ec623f372d02c9881144ac9de6bb625dd25cccc3))
