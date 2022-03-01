OUTNAME_RELEASE = trtexec
OUTNAME_DEBUG   = trtexec_debug
EXTRA_DIRECTORIES = ../common
#EXTRA_DIRECTORIES += /home/alexander/opencv_build/opencv/include/
SAMPLE_DIR_NAME = $(shell basename $(dir $(abspath $(firstword $(MAKEFILE_LIST)))))
MAKEFILE ?= ../Makefile.config
include $(MAKEFILE)
