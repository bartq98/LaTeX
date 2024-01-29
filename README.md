<h1 align="center">Latex working environment with Visual Studio Code</h1>

<p align="center">Make your Latex document locally efficient way!</p>

<!-- This reposiory allows you to use 

#### List of useful articles etc.:
- https://github.com/dspinellis/latex-advice
- https://tex.stackexchange.com/questions/36423/random-unwanted-space-between-paragraphs -->

### 0. Prerequarities

This tutorial is intended to be run/executed on as many operating systems as possible.
As whole environment is wrapped in Docker and uses Visual Studio Code you problably don't need install anything additional.

Requirements:
- Docker (tested on 24.0.7)
- Visual Studio Code (tested on 1.85.2)
  - exstension: ms-vscode-remote.remote-containers

### 1. Usage

#### 1.1 How to run this repository

1. Go to folder where you've downloaded this repository
2. Run `code .` to open it
3. Press `ctrl+shift+p` or press `F1` and choose `Dev Containers: Open Workspace in Container`
4. Now you can use separated Latex environment for your purposes.
