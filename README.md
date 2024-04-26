# Idefics 8B docker

Dockerization of the [Hugging Face Idefics 8B Space](https://huggingface.co/spaces/HuggingFaceM4/idefics-8b)

 * Model card: [HuggingFaceM4/idefics2-8b](https://huggingface.co/HuggingFaceM4/idefics2-8b)
 * Space: [HuggingFaceM4/idefics-8b](https://huggingface.co/spaces/HuggingFaceM4/idefics-8b)

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

### Download the image from the Docker Hub

You can download the image and run it

```bash
docker pull maximofn/idefics_8b:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```
