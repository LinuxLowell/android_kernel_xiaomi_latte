# Makefile for Intel display driver based on ADF framework
ccflags-y := -Idrivers/staging/ -Iinclude/adf -Iinclude/uapi/adf -Idrivers/video/adf/intel/include -Werror

obj-$(CONFIG_ADF_INTEL) += intel_adf_drv.o \
	intel_plane.o \
	intel_pipe.o \
	intel_dc_power.o \
	intel_dc_memory.o \
	intel_dc_config.o \
	intel_color_manager.o

obj-$(CONFIG_ADF_INTEL) += common/
obj-$(CONFIG_ADF_INTEL_VLV)	+= vlv/
