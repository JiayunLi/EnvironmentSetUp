## Build Docker image
`-t`: tag
`./`: folder that contains the docker file. 
```
docker image build --build-arg USER_ID=$(id -u ${USER}) --build-arg GROUP_ID=$(id -g ${USER}) -t nvcr.io/uclacid/cid/nvidia-pytorch04-tf18-py35-jiayun:v1 ./
```

## Config the Docker repository
For the username, enter '$oauthtoken' exactly as shown. It is a special authentication token for all users.
docker login nvcr.io
Username: $oauthtoken
Password: <Your Key>
