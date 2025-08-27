# Python Package Example

This demonstrates a Python project that uses the reusable Python CI workflow.

You can use it like this:

```yaml
name: Python CI (Example Use)

on: [push]

jobs:
  use-python-ci:
    uses: your-org/automation-workflows/.github/workflows/python-ci.yml@main
