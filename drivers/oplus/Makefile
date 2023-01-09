# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.
obj-$(CONFIG_OPLUS_FEATURE_DUMP_DEVICE_INFO) += system/dump_device_info/
obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) 	+= oplus_project.o
obj-y     += system/cmdline_parser/
obj-y     += system/acm/
obj-y     += system/project_info/
#ifdef OPLUS_FEATURE_MDMFEATURE
obj-$(CONFIG_OPLUS_FEATURE_MDMFEATURE)     += system/mdmfeature/
#endif /*OPLUS_FEATURE_MDMFEATURE*/

#ifdef VENDOR_EDIT
obj-$(CONFIG_OPLUS_FEATURE_MIDAS)    += system/oplus_midas/
#endif /* VENDOR_EDIT */

obj-$(CONFIG_OPLUS_FEATURE_SHUTDOWN_DETECT)    += system/shutdown_detect/

#ifdef OPLUS_FEATURE_HEALTHINFO
obj-y     +=  oplus_performance/healthinfo/main/
#endif /* OPLUS_FEATURE_HEALTHINFO */

obj-$(CONFIG_OPLUS_ION_BOOSTPOOL) += oplus_performance/ion_boost_pool/oplus_ion_boost_pool.o
obj-y += wakelock_profiler/
obj-y += oplus_performance/tpp/

obj-$(CONFIG_OPLUS_FEATURE_GAME_OPT) += game_opt/
#Add for NandSwap
obj-$(CONFIG_NANDSWAP)		+= oplus_performance/oplus_nandswap/


#ifdef CONFIG_OPLUS_FEATURE_FDLEAK_CHECK
obj-$(CONFIG_OPLUS_FEATURE_FDLEAK_CHECK)     += system/oplus_fdleak/
#endif /*CONFIG_OPLUS_FEATURE_FDLEAK_CHECK*/

#ifdef OPLUS_FEATURE_POWERINFO_STANDBY
obj-$(CONFIG_OPLUS_WAKELOCK_PROFILER) += wakelock_profiler/
#endif /* OPLUS_FEATURE_POWERINFO_STANDBY */

#ifdef OPLUS_FEATURE_TPD
obj-$(CONFIG_OPLUS_FEATURE_TPD)     +=  oplus_performance/tpd/
#endif

#ifdef OPLUS_FEATURE_IM
#ted.lin@optimization add for im module
obj-$(CONFIG_OPLUS_FEATURE_IM) += oplus_performance/im/
#endif /* OPLUS_FEATURE_IM */


#ifdef OPLUS_FEATURE_SAUPWK
#Add for theia saupwrkey
obj-$(CONFIG_OPLUS_FEATURE_SAUPWK)     += system/oplus_saupwk/
#endif /* OPLUS_FEATURE_SAUPWK */

obj-$(CONFIG_OPLUS_COMMON_SOFT)  +=  device_info/

#ifdef OPLUS_FEATURE_LOWMEM_DBG
#Add for dump mem when shrink
obj-$(CONFIG_OPLUS_FEATURE_LOWMEM_DBG)	+=  oplus_performance/lowmem_dbg/
#endif /* OPLUS_FEATURE_LOWMEM_DBG */

#ifdef OPLUS_FEATURE_MEMLEAK_DETECT
#Add for svelte logging
obj-$(CONFIG_SVELTE) +=  oplus_performance/memleak_detect/svelte/
#endif /* OPLUS_FEATURE_MEMLEAK_DETECT */

#ifdef OPLUS_FEATURE_IOMONITOR
obj-$(CONFIG_IOMONITOR)    +=  oplus_performance/iomonitor/
#endif /*OPLUS_FEATURE_IOMONITOR*/

