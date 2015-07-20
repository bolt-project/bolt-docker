# Bolt Docker image

This repo contains a Dockerfile and example notebooks for trying Bolt [Neurofinder](http://neurofinder.codeneuro.org), including the Spark backend.

If you want to explore this environment interactively, we recommend using the [notebook](http://notebooks.codeneuro.org) service hosted by CodeNeuro.

If you want to develop locally, we recommend setting up a Python environment with [Anaconda](https://store.continuum.io/cshop/anaconda/) (see the [Bolt](http://bolt-project.org) documentation for more information).

## Running

To run this image, if you are new to Docker, follow these instructions to get set up on (on OS X):

- Download and install [boot2docker](https://github.com/boot2docker/osx-installer/releases/tag/v1.7.1)

- Launch the `boot2docker` application from your `Applications` folder

- Type `docker run -i -t -p 8888:8888 freemanlab/bolt`

- Point a web browser to `http://192.168.59.103:8888/`