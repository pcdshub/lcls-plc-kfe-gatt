IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.1
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := plc-kfe-gatt
PROJECT_PATH := ../../plc-kfe-gatt/plc-kfe-gatt.tsproj
PLC := plc_kfe_gatt

PYTMC_OPTS := 
PREFIX := PLC:KFE:GATT

include $(IOC_TOP)/iocBoot/templates/Makefile.base
