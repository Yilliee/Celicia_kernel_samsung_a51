# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_SOC_EXYNOS9610) += exynos/exynos9610.dtb

dtbo-$(CONFIG_DTBO_A51) += \
        samsung/exynos9611-a51_eur_open_01.dtbo \
        samsung/exynos9611-a51_eur_open_00.dtbo \
        samsung/exynos9611-a51_eur_open_03.dtbo \
        samsung/exynos9611-a51_eur_open_07.dtbo

dtbo-$(CONFIG_DTBO_M21) += \
        samsung/exynos9611-m21_swa_open_00.dtbo \
        samsung/exynos9611-m21_swa_open_06.dtbo

dtbo-$(CONFIG_DTBO_M31S) += \
        samsung/exynos9611-m31s_eur_open_00.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*

