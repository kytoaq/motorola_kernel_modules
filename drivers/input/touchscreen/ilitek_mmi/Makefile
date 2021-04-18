
#
# Makefile for the ipio touchscreen drivers.
#

# Each configuration option enables a list of files.
ifeq ($(filter m y, $(CONFIG_TOUCHSCREEN_ILI9881H)),)
	obj-y += ilitek_mmi.o
endif

ilitek_mmi-objs += \
	platform.o \
	userspace.o

ilitek_mmi-objs += \
	core/config.o \
	core/finger_report.o \
	core/firmware.o \
	core/flash.o \
	core/i2c.o \
	core/spi.o \
	core/mp_test.o \
	core/protocol.o \
	core/parser.o \
	core/gesture.o
