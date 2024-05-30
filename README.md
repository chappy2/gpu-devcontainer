# GPU Devcontainer for Python Jupyter Notebook Development

Welcome to the GPU Devcontainer for Python Jupyter Notebook development! This setup allows you to utilize GPU-accelerated Docker containers for enhanced performance during your Python development and data science tasks. 

## Prerequisites

### GPU Support

To run GPU-accelerated Docker containers, ensure you have the necessary setup on your operating system:
- **Windows**: Follow the instructions to enable GPU support in [Docker Desktop](https://docs.docker.com/desktop/gpu/).
- **Linux**: 
  - **NVIDIA GPUs**: Set up the NVIDIA container toolkit as described in the [NVIDIA documentation](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/index.html).
  - **AMD GPUs**: Install the AMD drivers for Linux from the [AMD support page](https://www.amd.com/en/support/linux-drivers).

### Development Environment

Utilize [Visual Studio Code (VS Code)](https://code.visualstudio.com/) with the [Remote Container VS Code Extension](https://code.visualstudio.com/docs/remote/remote-overview) to create a GPU-accelerated development environment:
- **Python 3 Docker Devcontainer**: A pre-configured development container with Python 3.
- **Jupyter Notebook VS Code Extension**: [Install from the marketplace](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) to enable Jupyter Notebook support within VS Code.
- **Python VS Code Extension**: [Install from the marketplace](https://marketplace.visualstudio.com/items?itemName=ms-python.python) for Python development support.
- **Pylance VS Code Extension**: [Install from the marketplace](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) for enhanced Python language features.

### Pre-installed Libraries
To avoid lengthy installation times, certain libraries are pre-installed within the image:
- **torch**: [PyTorch](https://pytorch.org/get-started/locally/) is included to ensure rapid startup and usage.

## Compatibility
This setup has been tested on Ubuntu with an `NVIDIA GeForce RTX 3080` GPU. Ensure your system meets the requirements for GPU acceleration.

## Getting Started
1. Clone this repository to your local machine.
2. Open the project in VS Code.
3. Ensure the Remote - Containers extension is installed and running.
4. Open the devcontainer using the "Remote-Containers: Open Folder in Container" command.
5. Start developing with GPU acceleration enabled!

## Example
An example Jupyter Notebook is provided to test the setup. Run the [Example Notebook](./index.ipynb) to verify that everything is configured correctly.

Enjoy a powerful and efficient development experience with your new GPU-accelerated devcontainer!

