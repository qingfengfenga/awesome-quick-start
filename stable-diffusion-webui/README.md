# Quick start

```shell
git clone https://github.com/qingfengfenga/awesome-quick-start.git

cd ./awesome-quick-start/stable-diffusion-webui

docker-compose --profile auto-offline up
```

# Using a self created image

### Clone repository

```shell
git clone https://github.com/qingfengfenga/stable-diffusion-webui-docker.git

cd ./stable-diffusion-webui-docker
```

### Download data

```shell
docker-compose --profile download up --build
```

### Create images and initialize

> Due to the design of the framework itself, the previous download can only download most of the data. When the program starts, it also needs to download some of the data. Here, it starts once before packaging the data.

```shell
docker-compose --profile auto up --build
```

### Create and launch images with model data

```shell
docker-compose --profile auto-offline up --build
```

# Thanks

Special thanks to everyone behind these awesome projects, without them, none of this would have been possible:
- [AbdBarho/stable-diffusion-webui-docker](https://github.com/AbdBarho/stable-diffusion-webui-docker)
- [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
- [InvokeAI](https://github.com/invoke-ai/InvokeAI)
- [Sygil-webui](https://github.com/Sygil-Dev/sygil-webui)
- [CompVis/stable-diffusion](https://github.com/CompVis/stable-diffusion)
- and many many more.