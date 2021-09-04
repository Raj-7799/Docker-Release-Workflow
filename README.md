## Docker Release Workflow Demo

### Purpose : The repository is created as to illustrate a seamless release workflow for Docker Images on DockerHub. This also provides support for highlighting the default repository. 

## Documentation
- The `release.json` file holds the configuration for the version as well as the supported platform. This is used as metadata for building the image as well.
- The `latest` tag is used to indicate the default image. For each new release the previous config needs to be set as `false` to avoud multiple `default` image push to the docker registry.
- In the demo a image for BrowserStackLocal binary is being created and is being pushed. Although, this framework is extensible to any dockerfile as well as platform. (The versioned folders and platforms are just meant as a guide to kickstart.)


### Demo ReadME : 
![Docker CI / CD](https://github.com/Raj-7799/docker_test/workflows/Docker%20CI%20/%20CD/badge.svg)

### Supported versions

- [7.6-ubuntu](https://github.com/Raj-7799/docker_test/tree/master/7.6/ubuntu)
- [8.0-ubuntu](https://github.com/Raj-7799/docker_test/tree/master/8.0/ubuntu)
