# pcoip-client-container
Pcoip Cleint Container for Linux

#Step 1 install apptainer and apptainer-suid from epel

https://apptainer.org/getting-started/

#Step 2 Build the .sif file

```
git clone https://github.com/spikyness/pcoip-client-container.git
cd pcoip-client-container
sudo apptainer build pcoip-client.sif pcoip-client.def
apptainer run pcoip-client.sif
```