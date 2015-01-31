# Makefile for QT-O1 application
#
# 2014/12/23 codeing by xb
#
#
#

CC = gcc

#CC =  /home/openwrt/trunk/staging_dir/toolchain-mips_34kc_gcc-4.8-linaro_uClibc-0.9.33.2/bin/mips-openwrt-linux-gcc

STRIP=/home/openwrt/trunk/staging_dir/toolchain-mips_34kc_gcc-4.8-linaro_uClibc-0.9.33.2/bin/mips-openwrt-linux-strip

LINUX_SRC=/home/openwrt/trunk/build_dir/target-mips_34kc_uClibc-0.9.33.2/linux-ar71xx_generic/linux-3.10.49/

INCLUDE = -I $(LINUX_SRC)/include/

TARGET_CLIENT=client.wifi
TARGET_SERVICE=service.wifi

all:

	$(CC) client.c -o $(TARGET_CLIENT)
	$(CC) service.c -o $(TARGET_SERVICE)
               
#	$(STRIP) $(TARGET1)	
clean:
	rm -f *.o

realclean:
	rm -f *.o
	rm -f *.wifi
 
