# Kali Linux 2.0
Kali Linux 2.0 i386 (32-bit) and amd64 (64-bit) images for QEMU. Images are 25GiB images in QCOW2 format on which a Kali Linux 2.0 system has been installed. The "light" version is a variant of the normal version in which less packages are installed and uses the XFCE desktop environment instead of the default GNOME 3 environment to be able to have a smaller install footprint.

## Downloads
32-bit: https://drive.google.com/open?id=1Jjv9Hhk2Vgs6iu9osXZUl_4XkWKHYwYn

64-bit: https://drive.google.com/open?id=1juzw7je82MxCMoKyktDvX-XzaOTIVP6f

32-bit-light: https://drive.google.com/open?id=1y0hP1fMC6GYlMsetkko9tYs_Zy_PuHWd

64-bit-light: https://drive.google.com/open?id=112gDupqRM_nAFprnq-FvQaEqOGqGPzwO

Un-compress the .7z files to retrieve the .qcow2 images

## Install Info
The other installation options are the following:
- Keyboard:       US
- Locale:         en_US
- Timezone:       Pacific
- Mirror:         N/A
- Hostname:       kali
- Root password:  toor

Run the images with the following where `kali-image` is the image you are using
- 32-bit: `qemu-system-i386 -hda kali-image.qcow2`
- 64-bit: `qemu-system-x86_64 -hda kali-image.qcow2`

### What is the difference between the normal and "light" images?
- The normal ISO provides the full Kali 2.0 setup using GNOME 3, which now requires 768MB of memory. The light ISO provides a Kali 2.0 setup using XFCE, and a smaller selection of tools
