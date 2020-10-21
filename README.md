# vsc
Microsoft Visual Studio Code Utilities

## remote

### container

Remote container configuration examples.

Usage:
* make sure that `Docker` engine is running,
* copy `.devcontainer` directory from specific example to your project root directory, e.g. `remote/container/gcc/.devcontainer`,
* In Visual Studio Code run `Remote-Containers: Reopen in Container` or `Remote-Containers: Clone Repository in Container Volume...`.

#### gcc

Latest version of gcc docker image.

Container details:
* project root directory under `/workspaces/{project-name}`,
* linux `developer` user home directory under `/home/developer`.