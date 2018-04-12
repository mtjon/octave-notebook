# Jupyter Notebook Octave Stack
Jupyter Notebook server with enabled Octave kernel.  
Based off of Jupyter's [jupyter/minimal-notebook][minimal-notebook], [Octave's ubuntu distribution][octave-ubuntu] and [calysto/octave_kernel][octave_kernel]

## Basic Use
```
docker run -it --rm -p 8888:8888 mtjon/octave-notebook
```

[minimal-notebook]: https://github.com/jupyter/docker-stacks/tree/master/minimal-notebook
[octave-ubuntu]: http://wiki.octave.org/Octave_for_Debian_systems
[octave_kernel]: https://github.com/Calysto/octave_kernel
