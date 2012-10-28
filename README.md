# Embedded Tomcat

Simple example showing customizing makefiles with autoconf,
and also a basic standalone tomcat web app. 

## Get started

    $ ./configure PKGNAME=whatever
    $ make run

Now open your browser to http://localhost:8080. There are 
`all jar uberjar clean run` targets available.

## To rebuild the configure script
To rebuild the configure script after modifiying configure.ac, run:

    $ autoconf configure.ac > configure

10/27/2012
AMB
