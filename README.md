# DSAI Projects

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/NTU-DSAI/DSAI-Projects/master.svg)](https://results.pre-commit.ci/latest/github/NTU-DSAI/DSAI-Projects/master)

- [DSAI Projects](#dsai-projects)
  - [Foreword](#foreword)
  - [Contributing](#contributing)
    - [Installation instructions](#installation-instructions)
    - [Repository Structure](#repository-structure)
    - [Pull Requests](#pull-requests)
    - [Branch Naming](#branch-naming)
    - [Commit Message](#commit-message)

## Foreword

Welcome to the DSAI Projects Repository! This is a repository maintained by current and former students of NTU DSAI aiming to make it easier for future students to get ideas for their projects.

_**Note**_: All the projects listed in this repository is the sole work of the students involved in creating and managing said projects. The maintainers of this repository take no ownership of the listed projects.

_**Disclaimer**_: The maintainers of this repository do not condone plagarism. Any action taken unto you by the school for any plagarism is not our liability.

## Contributing

This repository is actively seeking projects from students. Please read this document carefully before contributing.

### Installation instructions

Ensure that you have [pre-commit](https://pre-commit.com) installed on your machine.

```bash
pip install pre-commit
```

After cloning the repository, install the pre-commit hook.

```bash
pre-commit install
```

### Repository Structure

All subdirectories and files of this repository should be written as such:

```text
/<Course Code>_<Course Name>/<Calendar Year Undertaken>/README.md
```

An example is given below:

```text
/CZ3005_Artificial Intelligence/2020/README.md
```

### Pull Requests

Please submit the links to your project by forking the repository and adding your changes in as few commits as possible. Please follow the structure in the sample directory. **Pull requests that do not follow these instructions will not be accepted.**

### Branch Naming

All contribution branches are to be named as such:

- **Contribution**: `contribution-<yourname>`

- **Bug**: `bug-yourname-<nature of bug>`, eg. `bug-bhargav-broken-links`

### Commit Message

If you are creating a Pull Request that fixes an Issue, include the issue number in the commit message as such:

```text
[#3] Fixed infinite loop
```
