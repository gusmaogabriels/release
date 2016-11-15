# IDAES Releases

[Release notes](release_notes.md)

Where the IDAES releases and integration tests live.

An IDAES release takes two forms:
* A set of tags from the dependent IDAES repos
  - models
  - DMF
* A Docker file for constructing a Docker container for running IDAES models.
  The Docker container contains the following major software packages, in addition to
  the IDAES repos mentioned above:
  - pyomo: Python linear optimization library
  - ipopt: Solver library

IDAES integration tests are part of the Docker container.
They can be run on cloud CI services like CircleCI or TravisCI, or
on local machines under Docker.

## Using a Release

### Downloading a release Docker container

### Checking out a development environment for a release from GitHub


