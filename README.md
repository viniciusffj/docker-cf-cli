# docker-cf-cli

Docker image with the [cloud foundry CLI](https://github.com/cloudfoundry/cli) installed.

Docker hub: https://hub.docker.com/r/viniciusffj/docker-cf-cli/

# Usage

First, is necessary to run a container based on this image:
```
docker run -i -t viniciusffj/docker-cf-cli /bin/bash
```

Then the command is available as `cf`, for example:
```
$ cf --version
cf version 6.18.0+b22884b-2016-05-10
```
