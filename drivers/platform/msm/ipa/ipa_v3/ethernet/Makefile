
obj-$(CONFIG_IPA_ETH) += ipa-eth.o

ipa-eth-y := \
	ipa_eth_bus.o \
	ipa_eth.o \
<<<<<<< HEAD
=======
	ipa_eth_debugfs.o \
>>>>>>> 701842278181eacacae61f735cbe8ff6394944f8
	ipa_eth_ep.o \
	ipa_eth_gsi.o \
	ipa_eth_net.o \
	ipa_eth_offload.o \
	ipa_eth_pci.o \
	ipa_eth_pm.o \
<<<<<<< HEAD
	ipa_eth_uc.o
=======
	ipa_eth_uc.o \
	ipa_eth_utils.o
>>>>>>> 701842278181eacacae61f735cbe8ff6394944f8

ifneq ($(wildcard $(srctree)/$(src)/aquantia/Makefile),)
obj-$(CONFIG_AQC_IPA) += aquantia/
endif
