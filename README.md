# GPU Devcontainer for Python Jupyter Notebook Development

It is now possible to start GPU accelerated Docker containers:
- [Windows with Docker Desktop](https://docs.docker.com/desktop/gpu/)
- [Linux](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/index.html)


Combined with [VS Code](https://code.visualstudio.com/) and the [Remote Container VS Code Extension](https://code.visualstudio.com/docs/remote/remote-overview) you can have gpu accelerated devcontainer:
- Python 3 Docker Devcontainer
- Added [Jupyter Notebook VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- Added [Python VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- Added [Pylance VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
- Installed [torch](https://pytorch.org/get-started/locally/). It is to slow to install it every time after the start. So its faster to add it within the image already.


Tested with Ubuntu and `NVIDIA GeForce RTX 3080`.

Test it yourself and run [Example Notebook](./index.ipynb)!

