#
#   Defines
#
BASEDIR		:=	../

#CFLAGS		:=	-DDEBUG -O2 -Wall -DSTD_B25
CFLAGS		:=	-DDEBUG -O2 -Wall

#INCLUDES	:= -I./ $(shell pkg-config --cflags libarib25)
INCLUDES	:= -I./

#LIBS		:= -lpthread $(shell pkg-config --libs libarib25)
LIBS		:= -lpthread

USERDEFS	:= \

SUBDIRS		:= \

#
#   Target object
#
TARGET_NAME	:=	recfsusb2i

#
#   Target type
#     (EXEC/SHARED/STATIC/OBJECT)
#
TARGET_TYPE	:=	EXEC

#
#   Compile sources
#
SRCS	:= \
	main.c utils.c message.c osdepend.c usbdevfile.c usbops.c it9175.c it9175_usb.c tsthread.c


#
#   Configurations
#
include $(BASEDIR)/Config.mak
