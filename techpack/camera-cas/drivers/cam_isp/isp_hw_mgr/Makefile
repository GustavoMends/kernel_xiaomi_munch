# SPDX-License-Identifier: GPL-2.0-only

ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_req_mgr
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_utils
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_core
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_smmu
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_cdm
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_isp/isp_hw_mgr/include
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_isp/isp_hw_mgr/hw_utils/include
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_isp/isp_hw_mgr/hw_utils/irq_controller
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_isp/isp_hw_mgr/isp_hw/include
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_smmu/
ccflags-y += -I$(srctree)/techpack/camera-cas/drivers/cam_cpas/include
ccflags-y += -I$(src)

obj-$(CONFIG_SPECTRA_CAMERA) += hw_utils/ isp_hw/
obj-$(CONFIG_SPECTRA_CAMERA) += cam_isp_hw_mgr.o cam_ife_hw_mgr.o
