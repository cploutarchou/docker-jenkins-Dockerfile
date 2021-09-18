## Pipeline Status :  [![pipeline status](https://cygit.eu/public-projects/docker-jenkins-Dockerfile/badges/master/pipeline.svg)](https://cygit.eu/public-projects/docker-jenkins-Dockerfile/-/commits/master)

# Jenkins with Docker Build support

_________________________

A Jenkins container supporting docker build using host's docker.

# Usage

____________________

````bash 
# To start Jenkins docker container, run the following command.
./start.sh
````

# Viewing Logs

_______________

```bash
# Tail logs
docker logs -f --tail 0 jenkins
```

# References
___________
* [Jenkins User Documentation](https://www.jenkins.io/doc/)
