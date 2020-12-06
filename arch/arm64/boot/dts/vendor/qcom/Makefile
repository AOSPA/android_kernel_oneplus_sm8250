# SPDX-License-Identifier: GPL-2.0

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_KONA) += \
		instantnoodle-overlay-dvt.dtbo \
		instantnoodle-overlay-evt1.dtbo \
		instantnoodle-overlay-t0.dtbo \
		instantnoodlep-overlay-dvt.dtbo \
		instantnoodlep-overlay-evb.dtbo \
		instantnoodlep-overlay-evt1.dtbo \
		instantnoodlep-overlay-t0.dtbo \
		instantnoodlev-overlay-dvt.dtbo \
		instantnoodlev-overlay-evt1.dtbo \
		instantnoodlev-overlay-t0.dtbo \
		kebab-overlay.dtbo

instantnoodle-overlay-dvt.dtbo-base := kona-v2.1.dtb
instantnoodle-overlay-evt1.dtbo-base := kona-v2.1.dtb
instantnoodle-overlay-t0.dtbo-base := kona-v2.1.dtb

instantnoodlep-overlay-dvt.dtbo-base := kona-v2.1.dtb
instantnoodlep-overlay-evb.dtbo-base := kona-v2.1.dtb
instantnoodlep-overlay-evt1.dtbo-base := kona-v2.1.dtb
instantnoodlep-overlay-t0.dtbo-base := kona-v2.1.dtb

instantnoodlev-overlay-dvt.dtbo-base := kona-v2.1.dtb
instantnoodlev-overlay-evt1.dtbo-base := kona-v2.1.dtb
instantnoodlev-overlay-t0.dtbo-base := kona-v2.1.dtb

kebab-overlay.dtbo-base := kona-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
