# Rserve-Cooperative

### A repository for Rserve binaries compiled for cooperative mode.

Windows: Rserve_1.8-7.zip, Rserve_1.8-8.zip

MacOSX : Rserve_1.8-15_Mac_arm64.tgz

Linux  : Rserve_1.8-7.tar.gz, Rserve_1.8-8.tar.gz, Rserve_1.8-15_Linux_x86_64.tar.gz

Linux AARCH : Rserve_1.8-15_Linux_aarch64.tar.gz

#### Installation from Github (1) or local installation (2) on Windows, MacOSX and Linux from the R command line (please adapt the file path!):

#### Windows:

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-8.zip", repos = NULL)

2. install.packages("C:/xxx/Rserve_1.8-8.zip", repos=NULL)

#### MacOSX:

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-8.tgz", repos = NULL)

2. install.packages("/Users/xxx/Rserve_1.8-8.tgz", repos=NULL)

#### MacOSX ARM:

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-15_Mac_arm64.tgz", repos = NULL)

2. install.packages("/Users/xxx/Rserve_1.8-15_Mac_arm64.tgz", repos=NULL)

#### Linux (Compiled with Ubuntu 20.10):

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-15_Linux_x86_64.tar.gz", repos = NULL)

2. install.packages("/home/xxx/Rserve_1.8-15_Linux_x86_64.tar.gz", repos=NULL)

#### Linux AARCH:

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-15_Linux_aarch64.tar.gz", repos = NULL)

2. install.packages("/home/xxx/Rserve_1.8-15_Linux_aarch64.tar.gz", repos=NULL)

#### Cooperative Mode

In cooperative mode only one connection at a time is allowed and all subsequent connections share the same namespace (default on Windows)!

#### Rserve sources from:

https://github.com/s-u/Rserve

#### Rserve can be build with cooperative mode enabled (from an archive or unpacked) with the shell command:

From an archive:

sudo PKG_CPPFLAGS=-DCOOPERATIVE R CMD INSTALL --build Rserve_1.8-15.tar.gz

Unpacked folder:

sudo PKG_CPPFLAGS=-DCOOPERATIVE R CMD INSTALL --build Rserve




