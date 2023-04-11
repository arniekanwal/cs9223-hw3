# _CSGY 9223 Cloud Computing HW3_

## Steps for building a docker image

From directory containing docker file: `docker build --tag <workdir_name> .` <br />
To view images, run: `docker images` <br />
`docker run -d -p 5000:5000 <workdir_name>` <br />

To see running containers, use: <br />
`docker ps` <br />

To stop containers: <br />
`docker stop <container-name>` <br />

To remove all unused resources: <br />
`docker container prune` <br /> 




