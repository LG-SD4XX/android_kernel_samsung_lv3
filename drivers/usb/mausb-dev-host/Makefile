ccflags-y := -DDEBUG -DCONFIG_MAUSB_DEBUG

obj-m += mausb-core.o
mausb-core-y := mausb_common.o mausb_event.o

obj-m += mausb-device.o
mausb-device-y := stub_dev.o stub_main.o stub_rx.o stub_tx.o mausb_mgmt.o mausb_out.o mausb_in.o mausb_util.o

obj-m += mausb-host.o
mausb-host-y := vhci_sysfs.o vhci_tx.o vhci_rx.o vhci_hcd.o
