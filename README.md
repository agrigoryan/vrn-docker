# vrn-docker
Dockerfile for https://github.com/AaronJackson/vrn

Dependencies are loaded from aramg/vrn-dependencies

Requires nvidia-docker to run (https://github.com/NVIDIA/nvidia-docker)

Does not include VRN network model.

### How to run:

```shell
docker build -t vrn .
docker run -it --runtime=nvidia vrn

./download.sh
./run.sh
```