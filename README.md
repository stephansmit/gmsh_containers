# Singularity container for gmsh

Singularity container with [Gmsh](http://gmsh.info/) and [CoolProp](http://www.coolprop.org/)
## Build Container
~~~
sudo singularity build gmsh_containers.sif Singularity
~~~

## Pull Image
~~~
singularity pull shub://stephansmit/gmsh_containers
~~~

### Run Image
~~~
singularity run gmsh_containers test.geo
~~~

Hosted on Singularity Hub:

[![h://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3419)
