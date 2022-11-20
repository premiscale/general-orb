# `general` orb for CircleCI

This orb is a collection of useful commands and jobs I like to reuse in many of my repositories to simplify their configs and reduce code duplication.

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
yarn orb:cleaup
```

### `pre-commit`

This repository uses `pre-commit` to uphold certain code styling and standards. You may install the hooks listed in [`.pre-commit-config.yaml`](.pre-commit-config.yaml) with

```shell
yarn install:pre-commit-hooks
```
