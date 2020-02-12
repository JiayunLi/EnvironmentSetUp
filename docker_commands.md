## Build Docker image
`-t`: tag
`./`: folder that contains the docker file. 
```
docker image build --build-arg USER_ID=$(id -u ${USER}) --build-arg GROUP_ID=$(id -g ${USER}) -t nvcr.io/uclacid/cid/nvidia-pytorch04-tf18-py35-jiayun:v1 ./
```
