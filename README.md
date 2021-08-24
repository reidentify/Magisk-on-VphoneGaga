# Magisk on VphoneGaga

## English

Set up a proper minial Magisk on VphoneGaga virtual machine without patching boot image

VphoneGaga 32bit and 64bit now supported!

Good news for anyone who want to run Magisk on VMOS: Vphone have proper system and can run Magisk properly thanks to [emulator.sh](https://github.com/topjohnwu/Magisk/blob/master/scripts/emulator.sh) script by **topjohnwu**. 

  1. Download `vmostool_magisk.zip`
  2. Import to VphoneGaga. You can find it at `/sdcard/Documents`, extract to any folder. For example here `/sdcard/Documents/vmostool_magisk`.
  3. Open Terminal app, grant superuser first by `su` command then run `sh <extracted_folder>/vphonegaga.sh`.
  
  For example run:
```
su
sh /sdcard/Documents/vmostool_magisk/vphonegaga
```
  4. Reboot the virtual machine.

     If you want to load Magisk then run this command:
```
su
magisk_root enable
```


Also reboot to make it work...

Only install Magisk Manager v8.0.0
Newer Magisk doesn't work

## Tiếng Việt

Thiết lập môi trường Magisk thích hợp trên máy ảo VphoneGaga mà không cần vá hình ảnh khởi động

Cách cài Magisk này hỗ trợ VphoneGaga 32bit và 64bit!

Tin vui cho những ai muốn chạy Magisk trên VMOS: Vphone có hệ thống phù hợp và có thể chạy Magisk đúng cách nhờ [emulator.sh](https://github.com/topjohnwu/Magisk/blob/master/scripts/emulator.sh  ) script của **topjohnwu**.

   1. Tải xuống `vmostool_magisk.zip`
   2. Nhập vào VphoneGaga.  Bạn có thể tìm thấy nó tại `/sdcard/Documents`, giải nén vào bất kỳ thư mục nào.  Ví dụ ở đây `/sdcard/Documents/vmostool_magisk`.
   3. Mở ứng dụng Terminal, cấp superuser trước bằng lệnh `su` sau đó chạy `sh <extracted_folder>/vphonegaga.sh`.
  
   Ví dụ chạy:

```
su
sh /sdcard/Documents/vmostool_magisk/vphonegaga
```
   4. Khởi động lại máy ảo.

      Nếu bạn muốn cài đặt Magisk thì hãy chạy lệnh này:
```
su
magisk_root enable
```


 Cũng khởi động lại để làm cho nó hoạt động ...

 Chỉ cài đặt Magisk Manager v8.0.0
 Magisk mới hơn không hoạt động

## Download

Download link: https://link1s.com/MagiskVphoneGaGa
VPhoneGaGa link: https://link1s.com/VphoneGaga
