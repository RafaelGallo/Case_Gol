# Gol_ML documentation!

## Description

Case vaga Gol

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `gsutil rsync` to recursively sync files in `data/` up to `gs://datalab1/data/`.
* `make sync_data_down` will use `gsutil rsync` to recursively sync files in `gs://datalab1/data/` to `data/`.


