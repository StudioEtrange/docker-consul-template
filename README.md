# docker-consul-template

## Note on this fork

* This fork store versiond of Dockerfile in splitted folders, so its easier to manage different docker image version of consul-template

## To build and publish

```
VERSION=0.21.0
git clone https://github.com/StudioEtrange/docker-consul-template

cd docker-consul-template/ver/${VERSION}
docker build . -t studioetrange/docker-consul-template:${VERSION}
docker push studioetrange/docker-consul-template:${VERSION}
```
## Usage
For instructions how to use consul-template, see the consule-template documentation: 
https://github.com/hashicorp/consul-template

You can also have a look at the examples: https://github.com/avthart/docker-consul-template/blob/master/examples/examples.md
