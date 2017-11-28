# singularity-docker-centos7-firefox57
firefox57 singularity container on CentOS-7

```
Running without installation:
singularity run shub://truatpasteurdotfr/singularity-docker-centos7-firefox57
Building:
singularity build firefox57 Singularity
Download and rename:
singularity pull --name "firefox57" shub://truatpasteurdotfr/singularity-docker-centos7-firefox57
Running with a separate $HOME and access to /run as a new instance "--no-remote --new-instance"
mkdir -p  ~/singularity.d/home/firefox57 
singularity run -B /run -H  ~/singularity.d/home/firefox57 ./firefox57 --no-remote --new-instance
```
