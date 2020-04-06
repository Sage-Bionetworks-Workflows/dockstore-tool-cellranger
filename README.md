# dockstore-tool-cellranger

![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/sagebionetworks/dockstore-tool-cellranger)

Dockerized cellranger and CWL tool definition for Dockstore.

This Docker image is not provided or supported by 10x Genomics.

## Contributing

New features should be opened on branches from `develop` and merged there with a code review.

CWL definitions should go in [/cwl](cwl/).

## Tests

Tests can be run with the [cwltest tool](https://github.com/common-workflow-language/cwltest/), using this command:

```shell
cwltest --test tests/test-descriptions.yml --tool cwl-runner
```

## Releasing

TODO: Use semantic versioning, possibly tied to the version of the software the container is wrapping?
