# ds-capstone documentation!

## Description

CS 163 Data Science Senior Project

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `gsutil rsync` to recursively sync files in `data/` up to `gs://smoke-forecast/data/`.
* `make sync_data_down` will use `gsutil rsync` to recursively sync files in `gs://smoke-forecast/data/` to `data/`.


