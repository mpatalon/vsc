# vsc
Microsoft Visual Studio Code Utilities.

## remote
___

Work with a sandboxed toolchain or container-based application inside (or mounted into) a container.

### container
___

Remote container configuration examples.

Documentation:
* [Developing inside a Container](https://code.visualstudio.com/docs/remote/containers),
* [Advanced Container Configuration](https://code.visualstudio.com/docs/remote/containers-advanced),
* [devcontainer.json reference](https://code.visualstudio.com/docs/remote/devcontainerjson-reference).

Usage:
* make sure that `Docker` engine is running,
* copy `.devcontainer` directory from specific example to your project root directory, e.g. `remote/container/gcc/.devcontainer`,
* open your project in Visual Studio Code and select one of the following from `Open a Remote Window` menu:
  * `Remote-Containers: Reopen in Container` or
  * `Remote-Containers: Clone Repository in Container Volume...`.

#### gcc
___

Latest version of gcc docker image.

Container details:
* project root directory under `/workspaces/{project-name}`,
* linux `developer` user home directory under `/home/developer`.