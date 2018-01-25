![AOSCP](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQw2CdARcSM7EoolY4HYqHPG8mw8yFL8xH4-MrxV1NnptPMLWFIa0e_t306Yw)
# 7.1.2 Iris X8 L

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | MT6592 1.4GHz 32bit
GPU     | Mali-450MP4
Memory  | 2GB RAM - LPDR3
Shipped Android Version | 4.4.2
Update Android Version | 5.1
Kernel  | 3.10.72
Storage | 16GB
DPI     | 320
Display | 5" 1280 x 720 px




# Command To Build :-

repo init -u git://github.com/Manish4586/aoscp_manifest.git -b nougat-mr2

repo sync

git clone https://github.com/Manish4586/Iris-X8-L-Device_3.10.72.git -b aosp device/Lava/IrisX8

git clone https://github.com/Manish4586/Iris-X8-L-Vendor_3.10.72.git vendor/Lava/IrisX8

source build/envsetup.sh

IrisX8

![Lava Iris X8](http://www.lavamobiles.com/lavastorecms/material/product/lava-smartphone-iris-x8-375x700-04022015.jpg)
