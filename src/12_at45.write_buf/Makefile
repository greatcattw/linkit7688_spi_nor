#PATH=$PATH:/home/ai7688/1208/AI7688H_OpenWRT_Build_FW_Setting_Tool_V1.0/openwrt/staging_dir/toolchain-mipsel_24kec+dsp_gcc-4.8-linaro_uClibc-0.9.33.2/bin
#export CROSS_COMPILE="mipsel-openwrt-linux-uclibc-"
#export ARCH=mips


cfilename=at45.write_buf
CC=mipsel-openwrt-linux-uclibc-gcc

all:$(cfilename)

$(cfilename):$(cfilename).o
	$(CC) -o $(cfilename).out $^

.PHONY:clean

clean:
	rm $(cfilename).out *.o *.~
