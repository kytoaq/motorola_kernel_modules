#
# Makefile for the Novatek touchscreen driver
#

# Built everything has module
ifneq ($(filter m y,$(CONFIG_TOUCHSCREEN_NOVATEK_CHIPSET)),)
	obj-y += nova_mmi.o
endif

nova_mmi-objs += nt36xxx.o
nova_mmi-objs += nt36xxx_ext_proc.o
nova_mmi-objs += nt36xxx_fw_update.o
nova_mmi-objs += nt36xxx_mp_ctrlram.o
