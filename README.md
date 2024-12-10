# moto-z-griffin
=Build for ubports==
Motorola Moto Z (griffin/sheridan-p3b)

INFO:

deviceinfo_dtb="qcom/msm8996-sheridan-p3b.dtb"  
msm8996-sheridan-p3b.dtb - DTB created during kernel comilaton:  
...  
Building modules, stage 2.  
  MODPOST 0 modules  
  DTC     arch/arm64/boot/dts/qcom/msm8996-griffin-p3b.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-sheridan-p1b.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-sheridan-p3b.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996pro-griffin-p3b.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-sheridan-p2c.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996pro-sheridan-p3b.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996pro-sheridan-p3a.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-princeton-p1.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-wabash-p1.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996pro-griffin-p3a.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-griffin-p1b.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996pro-wabash-p1.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-sheridan-p3a.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-griffin-p2c.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-griffin-p3a.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-griffin-p2a.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-princeton-p2.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-sheridan-p1a.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996pro-griffin-p2a.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996pro-sheridan-p2c.dtb  
  DTC     arch/arm64/boot/dts/qcom/msm8996-griffin-p1a.dtb  
  GZIP    arch/arm64/boot/Image.gz  
  CAT     arch/arm64/boot/Image.gz-dtb  
...  
  
  
  
boot.img-dtb - extracted from stock boot  
boot.img-dtb: data  
binwalk boot.img-dtb   
  
DECIMAL       HEXADECIMAL     DESCRIPTION  
--------------------------------------------------------------------------------  
0             0x0             Qualcomm device tree container, version: 3, DTB entries: 24  
4096          0x1000          device tree image (dtb)  
316044        0x4D28C         Unix path: /dev/block/bootdevice/by-name/utags  
316200        0x4D328         Unix path: /dev/block/bootdevice/by-name/hw  
352256        0x56000         device tree image (dtb)  
664432        0xA2370         Unix path: /dev/block/bootdevice/by-name/utags  
664588        0xA240C         Unix path: /dev/block/bootdevice/by-name/hw  
700416        0xAB000         device tree image (dtb)  
1025804       0xFA70C         Unix path: /dev/block/bootdevice/by-name/utags  
1025960       0xFA7A8         Unix path: /dev/block/bootdevice/by-name/hw  
1060864       0x103000        device tree image (dtb)  
1386364       0x15277C        Unix path: /dev/block/bootdevice/by-name/utags  
1386520       0x152818        Unix path: /dev/block/bootdevice/by-name/hw  
1421312       0x15B000        device tree image (dtb)  
1746732       0x1AA72C        Unix path: /dev/block/bootdevice/by-name/utags  
1746888       0x1AA7C8        Unix path: /dev/block/bootdevice/by-name/hw  
1781760       0x1B3000        device tree image (dtb)  
2107244       0x20276C        Unix path: /dev/block/bootdevice/by-name/utags  
2107400       0x202808        Unix path: /dev/block/bootdevice/by-name/hw  
2142208       0x20B000        device tree image (dtb)  
2467692       0x25A76C        Unix path: /dev/block/bootdevice/by-name/utags  
2467848       0x25A808        Unix path: /dev/block/bootdevice/by-name/hw  
2502656       0x263000        device tree image (dtb)  
2828140       0x2B276C        Unix path: /dev/block/bootdevice/by-name/utags  
2828296       0x2B2808        Unix path: /dev/block/bootdevice/by-name/hw  
2863104       0x2BB000        device tree image (dtb)  
3194560       0x30BEC0        Unix path: /dev/block/bootdevice/by-name/utags  
3194716       0x30BF5C        Unix path: /dev/block/bootdevice/by-name/hw  
3231744       0x315000        device tree image (dtb)  
3563312       0x365F30        Unix path: /dev/block/bootdevice/by-name/utags  
3563468       0x365FCC        Unix path: /dev/block/bootdevice/by-name/hw  
3600384       0x36F000        device tree image (dtb)  
3931872       0x3BFEE0        Unix path: /dev/block/bootdevice/by-name/utags  
3932028       0x3BFF7C        Unix path: /dev/block/bootdevice/by-name/hw  
3969024       0x3C9000        device tree image (dtb)  
4300576       0x419F20        Unix path: /dev/block/bootdevice/by-name/utags  
4300732       0x419FBC        Unix path: /dev/block/bootdevice/by-name/hw  
4337664       0x423000        device tree image (dtb)  
4669216       0x473F20        Unix path: /dev/block/bootdevice/by-name/utags  
4669372       0x473FBC        Unix path: /dev/block/bootdevice/by-name/hw  
4706304       0x47D000        device tree image (dtb)  
5037856       0x4CDF20        Unix path: /dev/block/bootdevice/by-name/utags  
5038012       0x4CDFBC        Unix path: /dev/block/bootdevice/by-name/hw  
5074944       0x4D7000        device tree image (dtb)  
5404992       0x527940        Unix path: /dev/block/bootdevice/by-name/utags  
5405148       0x5279DC        Unix path: /dev/block/bootdevice/by-name/hw  
5439488       0x530000        device tree image (dtb)  
5760400       0x57E590        Unix path: /dev/block/bootdevice/by-name/utags  
5760556       0x57E62C        Unix path: /dev/block/bootdevice/by-name/hw  
5795840       0x587000        device tree image (dtb)  
6116824       0x5D55D8        Unix path: /dev/block/bootdevice/by-name/utags  
6116980       0x5D5674        Unix path: /dev/block/bootdevice/by-name/hw  
6152192       0x5DE000        device tree image (dtb)  
6473176       0x62C5D8        Unix path: /dev/block/bootdevice/by-name/utags  
6473332       0x62C674        Unix path: /dev/block/bootdevice/by-name/hw  
6508544       0x635000        device tree image (dtb)  
6829528       0x6835D8        Unix path: /dev/block/bootdevice/by-name/utags  
6829684       0x683674        Unix path: /dev/block/bootdevice/by-name/hw  
6864896       0x68C000        device tree image (dtb)  
7191876       0x6DBD44        Unix path: /dev/block/bootdevice/by-name/utags  
7192032       0x6DBDE0        Unix path: /dev/block/bootdevice/by-name/hw  
7229440       0x6E5000        device tree image (dtb)  
7556492       0x734D8C        Unix path: /dev/block/bootdevice/by-name/utags  
7556648       0x734E28        Unix path: /dev/block/bootdevice/by-name/hw  
7593984       0x73E000        device tree image (dtb)  
7921036       0x78DD8C        Unix path: /dev/block/bootdevice/by-name/utags  
7921192       0x78DE28        Unix path: /dev/block/bootdevice/by-name/hw  
7958528       0x797000        device tree image (dtb)  
8285580       0x7E6D8C        Unix path: /dev/block/bootdevice/by-name/utags  
8285736       0x7E6E28        Unix path: /dev/block/bootdevice/by-name/hw  
8323072       0x7F0000        device tree image (dtb)  
8648680       0x83F7E8        Unix path: /dev/block/bootdevice/by-name/utags  
8648836       0x83F884        Unix path: /dev/block/bootdevice/by-name/hw  
  
  
  
BUILD:  
./build.sh -b workdir  
  
