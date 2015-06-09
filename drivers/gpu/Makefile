ccflags-y := -Iinclude/uapi/drm -Iinclude/drm -Idrivers/gpu/msm -O3 -ffast-math -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -fsingle-precision-constant -mcpu=cortex-a15 -mtune=cortex-a15 -marm -mfpu=neon-vfpv4 -fgraphite -floop-parallelize-all -ftree-loop-linear -floop-interchange -floop-strip-mine -floop-block
obj-y			+= drm/ vga/
obj-$(CONFIG_TEGRA_HOST1X)	+= host1x/
obj-$(CONFIG_MSM_KGSL)	+= msm/
obj-y			+= gpu_sysfs/
