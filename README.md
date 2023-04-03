# CI-Common Action

![Build Status](https://github.com/panubo/ci-common-action/actions/workflows/main.yml/badge.svg)

This action installs Panubo's ci-common tools and scripts.

## Usage

```
jobs:
  ci-common:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: panubo/ci-common-action@v1
```
