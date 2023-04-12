[English](./READMD.md) | [中文](./README_zh.md) 

# Awesome Quick Start

This repository aims to collect and organize popular projects, and make it as easy to use out of the box as possible, reducing the difficulty of getting started and allowing more people to experience the latest technology painlessly.

## Quick Start

### Preconditions

Unless otherwise specified, the default is Docker environment

It is recommended to use the 'Win+WSL+Docker' environment, simply install the Docker and GPU driver.

- All Quick Start Dependent Dockers
    - [Get-docker]( https://docs.docker.com/get-docker/ )

- GPU drive
  - Some programs require a GPU. After specifying a GPU in the container, execute 'nvidia smi' inside the container to check if the GPU is available.
    - [Gpu-support]( https://docs.docker.com/compose/gpu-support/ )

### Available List

- [ &#10004; ] [stable-diffusion-webui](./stable-diffusion-webui/README.md) 
- [ - ] Grounded-Segment-Anything
- [ - ] ChatGLM-6B
- [ - ] text-generation-webui
