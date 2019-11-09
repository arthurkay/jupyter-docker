# Jupyter Notebook (Dockerised)

## INTRODUCTION

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.

This is a jupyter notebook fork that has been containerised and packaged with machine learning modules and the tensorflow 2.0 framework.

## INSTALLATION

To run this container, one needs Docker installed.
Click [here](https://docs.docker.com/v17.09/engine/installation/)  for the official docker installation instructions

Once that is done, run:

```bash
docker run -d -p 8888:8888 -e dataStore=/data/storage/directory/ -t jupyter .
```

