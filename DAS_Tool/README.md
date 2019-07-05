[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3238)


* ## to build the singualrity image file (DAS_Tool.sif)

```
./build.sh
```

* ## to run the built sif file

```
singularity run DAS_Tool.sif DAS_Tool -i methodA.scaffolds2bin,...,methodN.scaffolds2bin -l methodA,...,methodN -c contigs.fa -o myOutput 
# or 
./DAS_Tool.sif DAS_Tool -i methodA.scaffolds2bin,...,methodN.scaffolds2bin -l methodA,...,methodN -c contigs.fa -o myOutput
```

* ## to test
```
singularity test DAS_Tool.sif
```

* ## to show help
```
singularity run-help DAS_Tool.sif
```
