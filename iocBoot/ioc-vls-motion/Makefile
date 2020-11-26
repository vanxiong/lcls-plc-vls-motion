IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.3.1

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := lcls-plc-vls-motion
PROJECT_PATH := ../../lcls-plc-vls-motion/lcls-plc-vls-motion.tsproj
PLC := vls_motion

PYTMC_OPTS := 
PREFIX := PLC:VLS:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base
