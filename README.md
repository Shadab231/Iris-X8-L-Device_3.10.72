![Slim6](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSR4mJyK32tx50YWODnbgbFxcycG8DrdAH13Hnja1J-w6x-ZSN_aUSMuEmrRA)

# 6.0.1 Iris X8 L

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

Repo Source :

repo init -u git://github.com/SlimRoms/platform_manifest.git -b mm6.0

repo sync

git clone https://github.com/Manish4586/Iris-X8-L-Device_3.10.72.git -b slim-6 device/Lava/IrisX8

git clone https://github.com/Manish4586/Iris-X8-L-Vendor_3.10.72.git -b los-13 vendor/Lava/IrisX8

source build/envsetup.sh

cd device/Lava/IrisX8/patches

source apply.sh

breakfast IrisX8

mka -jx

![Lava Iris X8](http://www.lavamobiles.com/lavastorecms/material/product/lava-smartphone-iris-x8-375x700-04022015.jpg)
