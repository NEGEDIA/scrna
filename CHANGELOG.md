# singleron-RD/scrna: Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.1.0 - [2024-05-28]

### Added
- Add subsample plots: saturation and median_gene.
- Change minimum cell UMI from 1000 to 500. [4ccb884](https://github.com/singleron-RD/scrna/commit/4ccb8843e5263dfdcf4be6051480ac065ff84a9c)
- Refactor the code to generate the HTML report.


## 1.2.0 - [2024-06-28]

### Changed
- Reduce the memory usage of the `subsample` module.
- Refactor cell-calling as a separate module; this way, changing the cell calling parameters does not require re-doing the time-consuming starsolo mapping and quantification step.

## 1.2.1 - [2024-07-04]

### Fixed
- Fix an issue where the pipeline do not work when `--protocol` is set to `new`.


## 1.2.2 - [2024-09-05]

### Added
- Add a new parameter `star_cpus`.