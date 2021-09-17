# carvel-release-scripts

## Overview

carvel-release-scripts contains scripting assets related to distributing carvel's binaries to the various distribution channels. i.e. Homebrew, carvel.dev install.sh script etc.

Adding a new product requires adding a github action workflow file:

```bash
./hack/generate-gh-action-workflows.sh tool-name-goes-here
```

for e.g.

```bash
./hack/generate-gh-action-workflows.sh imgpkg
```

## Contributing

The carvel-release-scripts project team welcomes contributions from the community. Before you start working with carvel-release-scripts, please
read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be
signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on
as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).