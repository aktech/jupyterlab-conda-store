# conda-store JupyterLab extension

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/conda-incubator/jupyterlab-conda-store/build.yml?label=Build%20Workflow&logo=GitHub&style=for-the-badge)

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/conda-incubator/jupyterlab-conda-store/build_and_deploy_release.yml?label=Deploy%20Workflow&logo=GitHub&style=for-the-badge)

A JupyterLab extension that provides a user-friendly graphical interface for building and managing environments using an instance of [conda-store](https://github.com/conda-incubator/conda-store).

## Requirements

- `JupyterLab >= 3.0`

## Install

To install the extension, execute:

```bash
pip install jupyterlab-conda-store
```

## Uninstall

To remove the extension, execute:

```bash
pip uninstall jupyterlab-conda-store
```

## Release

To create a new package and release:

1. Bump the version as indicated in `pyproject.toml` and `package.json`

2. Create a new release, and then ensure the release tag is the same as the bumped version tag.

## Code of Conduct

To guarantee a welcoming and friendly community, we require all community members to follow our [Code of Conduct](https://github.com/conda-incubator/governance/blob/main/CODE_OF_CONDUCT.md).

## License

jupyterlab-conda-store is developed under the [BSD 3-Clause License](./LICENSE).
