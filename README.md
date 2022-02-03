# Requirements
Next to Docker, install the NVIDIA Container Toolkit: https://github.com/NVIDIA/nvidia-docker.


# Usage Prebuilt Images

````shell
docker run --gpus all hedrich9000/cuda-opencv-pytorch:tagname
````
For example: 
* CUDA 11.3.1
* Pytorch 1.10.2
* OpenCV 4.5.2

````shell
docker run --gpus all hedrich9000/cuda-opencv-pytorch:cuda11.3-cv4.5-pytorch1.10.2
````



# Dockerhub

https://hub.docker.com/repository/docker/hedrich9000/cuda-opencv-pytorch

## Available Images
* cuda11.3.1-cv4.5.2-pytorch1.10.0
* cuda11.3.1-cv4.5.2-pytorch1.10.2
