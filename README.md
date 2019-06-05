# shibboleth-sp
Use YAML2RPM to build a set of RPMS for shibboleth with fastcgi support

Pre-requisites
 - `rocks-devel rpm` from the Rocks repository (https://github.com/rocksclusters/core), installed
 - `yaml2rpm rpm` from the RCIC-UCI-Pubic Repository (https://github.com/RCIC-UCI-Public/yaml2rpm)
 
 Quickstart:
 ```bash
 make download
 cd yamlspecs
 make bootstrap 
 make 
 make unbootstrap
 ```
   
 RPMS will be placed in RPMS/x86_64
