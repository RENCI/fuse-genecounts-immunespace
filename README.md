# fuse-server-gc-immunespace
`Usage:  docker run --rm -d --env GENE_ARGS="-group2 -a 'session|<my-key>'" fuse-server-gc-immunespace`

This repo contains the source code to create a docker container for the following purpose:
* Given a user-defined group name created in Immunespace and an API key, get gene counts.

The latest working container can be retrieved from `txscience/fuse-server-gc-immunespace`.

## build container
`docker build  -t fuse-server-gc-immunespace .`

## run test
`test/test.sh`
