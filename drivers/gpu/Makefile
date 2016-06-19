ccflags-y := -Ofast -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -ffast-math -fsingle-precision-constant -marm -mcpu=cortex-a9 -mtune=cortex-a15 -mfpu=neon -funsafe-math-optimizations -ftree-vectorize -mvectorize-with-neon-quad

obj-y			+= drm/ vga/ stub/ ion/
obj-$(CONFIG_MSM_KGSL)	+= msm/
