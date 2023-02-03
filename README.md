# actions
Github Action workflow files for Kubernetes deployments

# Usage example:
Add to your <your_repository>/.github/workflows/build.yml:

```
jobs:
  build:
    uses: mini-ci-cd/actions/.github/workflows/build.yml@master
    secrets: inherit
    with:
      sha: ${{ github.sha }}
```
