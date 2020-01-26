THISDIR=$(dir $(realpath $(firstword $(MAKEFILE_LIST))))
all:
	kotlinc $(THISDIR)hello_world.kt -include-runtime -d $(THISDIR)hello_world.jar
