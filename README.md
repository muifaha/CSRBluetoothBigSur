# CSRBluetoothBigSur
Kext for cheap USB Dongle CSR Bluetooth v5.0 in MacOS Big Sur

Today I bought very cheap CSR Bluetooth 5.0 USB Dongle for less than 2$ (IDR 17,000,-). When I plug it into Ryzentosh, the usb bluethooth device is read on USB and in Hackintool but it doesn't read as Bluethoot device. After googling I found a kext USB CSR Injection Driver https://www.insanelymac.com/forum/topic/307181-csrapplebluetoothkext-usb-csr-injection-driver/?ct=1624345620 but it doesn't work in BigSur.

So I created a new one that can run on BigSur. This kext is just Info.plist which adjusts *vendor id* and *product id* of USB Donggle. if your CSR Bluetooth USB Dongle still doesn't work maybe you can adjust the *vendor id* and *product id* in this kext.

Tested on MacOS Big Sur 11.4

