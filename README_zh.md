[English](./READMD.md) | [中文](./README_zh.md) 

# Awesome Quick Start
此存储库旨在收集、整理热门项目，并尽可能地做到开箱即用，降低上手难度，使得更多人可以无痛的体验最新的技术。

## 快速启动
### 先决条件

如无特殊说明，默认均为Docker环境 

推荐使用`Win+WSL+Docker`环境，只需要安装Docker和GPU驱动即可。

- 所有快速启动依赖Docker
  - [Get-docker](https://docs.docker.com/get-docker/)
- GPU驱动
  - 部分程序需要GPU，容器指定GPU后，在容器内执行`nvidia-smi`可查看GPU是否可用。
    - [Gpu-support](https://docs.docker.com/compose/gpu-support/)

### 可用列表

- [ &#10004; ] [stable-diffusion-webui](./stable-diffusion-webui/README.md) 
- [ - ] Grounded-Segment-Anything
- [ - ] ChatGLM-6B
- [ - ] text-generation-webui
