# Rserve-Cooperative

### A repository for Rserve binaries compiled for cooperative mode.

Windows: Rserve_1.8-7.zip, Rserve_1.8-8.zip

MacOSX : Rserve_1.8-7.tgz (R 4.0.x), Rserve_1.8-8.tgz (install for R >= 4.1)

Linux  : Rserve_1.8-7.tar.gz, Rserve_1.8-8.tar.gz

#### Installation from Github (1) or local installation (2) on Windows, MacOSX and Linux from the R command line (please adapt the file path!):

#### Windows:

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-8.zip", repos = NULL)

2. install.packages("C:/xxx/Rserve_1.8-8.zip", repos=NULL)

#### MacOSX:

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-8.tgz", repos = NULL)

2. install.packages("/Users/xxx/Rserve_1.8-8.tgz", repos=NULL)

#### MacOSX ARM:

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-10_arm.tgz", repos = NULL)

2. install.packages("/Users/xxx/Rserve_1.8-10_arm.tgz", repos=NULL)

#### Linux (Compiled with Ubuntu 20.10):

1. install.packages("https://raw.github.com/Bio7/Rserve-Cooperative/master/Rserve_1.8-8.tar.gz", repos = NULL)

2. install.packages("/home/xxx/Rserve_1.8-8.tar.gz", repos=NULL)

#### Cooperative Mode

In cooperative mode only one connection at a time is allowed and all subsequent connections share the same namespace (default on Windows)!

#### Rserve sources from:

https://github.com/s-u/Rserve
