# React App Example

This folder simulates a basic React app setup for testing the `node-ci.yml` workflow.

✅ You can copy this into a new repo and add the following workflow:

```yaml
name: Node CI (Example Use)

on: [push]

jobs:
  use-node-ci:
    uses: your-org/automation-workflows/.github/workflows/node-ci.yml@main
