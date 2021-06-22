# CSRBluetoothBigSur
Kext for cheap USB Dongle CSR Bluetooth v5.0 in MacOS Big Sur

Today I bought very cheap CSR Bluetooth 5.0 USB Dongle for less than 2$ (IDR 17,000,-). When I plug it into Ryzentosh, the usb bluethooth device is read on USB and in Hackintool but it doesn't read as Bluethoot device. After googling I found a kext USB CSR Injection Driver https://www.insanelymac.com/forum/topic/307181-csrapplebluetoothkext-usb-csr-injection-driver/?ct=1624345620 but it doesn't work in BigSur.

So I created a new one that can run on BigSur. This kext is just Info.plist which adjusts *vendor id* and *product id* of USB Dongle. if your CSR Bluetooth USB Dongle still doesn't work maybe you can adjust the *vendor id* and *product id* in this kext.

Tested on MacOS Big Sur 11.4 - USB 2.0

<img width="1015" alt="Screen Shot 2021-06-22 at 21 36 33" src="https://user-images.githubusercontent.com/35163902/122948643-44aa2d00-d3a5-11eb-9550-61350f55385f.png">

<img width="1015" alt="Screen Shot 2021-06-22 at 21 50 56" src="https://user-images.githubusercontent.com/35163902/122948580-352ae400-d3a5-11eb-85f1-8ab3f47c2e65.png">

