# nvidia-settings
Contains configuration for Nvidia external GPU configuration for Intel NUC on a Manjaro Linux system

copy the modprobe.d directory into /etc

copy the xorg.conf.d directory into /etc/X11

Tested on 5.11.0-1-MANJARO with NVIDIA Driver 460.39

Works with Pytorch CUDA 11.2 support


# Graphics:  
           
           Device-1: Intel Iris Plus Graphics 655 driver: i915 v: kernel

           Device-2: NVIDIA TU102 [GeForce RTX 2080 Ti Rev. A] driver: nvidia v: 460.39
           
           Display: x11 server: X.Org 1.20.10 driver: loaded: modesetting,nvidia unloaded: intel,nouveau resolution:
           
           1: 3840x2160~60Hz 2: 3840x2160~60Hz
           
           OpenGL: renderer: GeForce RTX 2080 Ti/PCIe/SSE2 v: 4.6.0 NVIDIA 460.39 
