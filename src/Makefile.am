ACLOCAL_AMFLAGS = -I m4

SUBDIRS = \
	shared \
	libudev \
	udev

# Helper programs
SUBDIRS += \
	accelerometer \
	ata_id \
	cdrom_id \
	collect \
	mtd_probe \
	scsi_id \
	v4l_id

if ENABLE_GUDEV
SUBDIRS += \
	gudev
endif
