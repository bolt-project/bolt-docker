# Bolt Docker image

This repo contains a Dockerfile and example notebooks for trying [Bolt](http://neurofinder.codeneuro.org), including the Spark backend.

If you want to explore this environment interactively, we recommend using the live [notebook](http://try.bolt-project.org) service, hosted by [CodeNeuro](http://codeneuro.org) via [tmpnb](https://github.com/jupyter/tmpnb).

If you want to develop, we recommend setting up a Python environment with [Anaconda](https://store.continuum.io/cshop/anaconda/) and installing a local version of Bolt (see the [Bolt](http://bolt-project.org) documentation for more information).

## Running

To run the image on OS X follow these instructions:

- Download and install [boot2docker](https://github.com/boot2docker/osx-installer/releases/tag/v1.7.1)

- Launch the `boot2docker` application from your `Applications` folder

- Type `docker run -i -t -p 8888:8888 freemanlab/bolt`

- Point a web browser to `http://192.168.59.103:8888/`
