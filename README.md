# pcoip-client-container
Pcoip Cleint Container for Linux

#Step 1 install singularity from here

https://docs.sylabs.io/guides/3.0/user-guide/installation.html

https://github.com/sylabs/singularity/releases

#Step 2 Build the .sif file

```
git clone https://github.com/spikyness/pcoip-client-container.git
cd pcoip-client-container
sudo singularity build pcoip-client.sif pcoip-client.def
singularity run pcoip-client.sif
```