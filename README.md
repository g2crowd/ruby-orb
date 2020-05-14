ruby-orb
========

CircleCi orb for common ruby tasks. This orb is published to `g2crowd/ruby`.

Setup
-----

1. Install the [CircleCi CLI](https://circleci.com/docs/2.0/orb-author-cli/#install-the-cli-for-the-first-time)
    ```bash
    brew install circleci   
    ```
1. Configure the CLI:
    ```bash
    circleci setup
    ```

Usage
-----

Many of the command line tools necessary to work with this project are sub-commands of `circleci orb`. Run
```bash
circleci orb --help
```

We will also use the `circleci config` command to build from source:
```bash
circleci config pack src > orb.yml
circleci orb validate orb.yml
```
