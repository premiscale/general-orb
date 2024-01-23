# `general` orb for CircleCI

This orb is a collection of useful commands and jobs we can reuse in many repositories to simplify configs and reduce code duplication in [dynamically-continued](https://github.com/emmeowzing/dynamic-continuation-orb) pipelines.

## Development

This orb has been developed in _unpacked_ form. You may view its packed source with

```shell
yarn orb:pack  # creates a file 'orb.yml'
```

and further validate the resulting orb definition with

```shell
yarn orb:validate
```

When you're done with your testing, you may clean up the packed source with

```shell
yarn orb:clean
```

### `pre-commit`

This repository uses `pre-commit` to uphold certain code styling and standards. You may install the hooks listed in [`.pre-commit-config.yaml`](.pre-commit-config.yaml) with

```shell
yarn install:pre-commit-hooks
```