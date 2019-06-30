[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3238)


* ## to build the singualrity image file (Julia.sif)

```
./build.sh
```

* ## to run the built sif file

```
singularity run Julia.sif test.jl
# or 
./Julia.sif test.jl
```

* ## to test
```
singularity test Julia.sif
```

* ## to show help
```
singularity run-help Julia.sif
```
