subdir-ccflags-y +=	-I$(srctree)/include/melis/kernel/drivers \
			-I$(srctree)/include/melis/misc \
			-I$(srctree)/include/melis/module \
			-I$(srctree)/include/melis/kernel \
			-I$(srctree)/include/melis/libs/libc \
			-I$(obj)/ \
			-I$(srctree)/ekernel/core/rt-thread/include \
			-I$(srctree)/ekernel/core/rt-thread/libdl \
			-I$(srctree)/ekernel/drivers/include \
			-I$(srctree)/ekernel/drivers/include/drv \
			-I$(srctree)/ekernel/components/aw/multi_console \
			-DEPDK_DEBUG_LEVEL=EPDK_DEBUG_LEVEL_LOG_ALL -Wall -Wstrict-prototypes

obj-y += ymodem.o
obj-y += cmd_ry_sy.o

