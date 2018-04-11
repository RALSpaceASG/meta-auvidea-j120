# meta-auvidea-j120

A yocto layer for the Auvidea J120 carrier board for the NVIDIA Jetson TX1/TX2 [(link)][j120].

It is based off the kernel and patches from Auvidea [(link)][firmware]. As these
themselves are based on the Linux kernel, they and this work are covered by the
GNU GPL v2.0 by the 'derivative work' clause. See the LICENSE file for details.

## linux-tegra recipe

The linux-tegra recipe applies patches for the carrier board device tree. The
patches were derived from the kernel r28.1_v1.5 sources from Auvidea [(link)][sources].

[j120]: https://auvidea.com/j120/
[firmware]: https://auvidea.com/firmware/
[sources]: https://auvidea.com/download/firmware/TX2/v1.5/ChangesTX2J140_Kernel_r28.1_v1.5.tar.gz
