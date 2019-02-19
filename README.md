# EFI32_for_64bit
Script helps install 64bit OS on HW with EFI32bit like Mac Pro 1.1


**Compile file:**
```
cc -g -Wall efi64to32.c -o efi64to32.c
```
Download iso to folder where file has been compiled, change name to efi64to32.iso
```
cp original.iso efi64to32.iso
./efi64to32 efi64to32.iso
```
Burn CD/DVD and your done. USB probably want work, not tested 
