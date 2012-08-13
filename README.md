# libtwitc - C Support Library for Twitter
###Copyright (C) 2012  Orazio Briante orazio.briante@hotmail.it

####Other developers: Patryk Rzucidlo ptkdev@gmail.com

## Prerequisites:

* gcc, g++, or cc
* pkg-config
* autotools

* libcurl
* libxml-2.0
* oauth

## How to Generate Makefile:

	$ ./autogen.sh
  or

	$ sh autogen.sh


## Compile - Makefile:
    
	$ ./configure
	$ make

and if necessary:
	$ su
	# make install

 
## To enable Debug option on Compiling process:
 	
	$ ./configure --enable-debug
 	
    
## Unistalling - Makefile (if necessary)
	$ su
	# make uninstall

## To clean directory
 
 run "make clean" from the test source tree.

## Test Files:

* test: Simple example that show how to use the library 
