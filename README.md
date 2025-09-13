# PS4 Baikal 5.4.213 Kernel with MT7668 WiFi/BT Fix (with DNS issue fix) & VPN support
The modified kernel based on [whitehax0r's source ](https://ps4linux.com/downloads/#Kernel_54213_LTS) includes:-
1. Fix and support for MT7668 WiFi/Bluetooth chipset with fix for DNS issues on PS4s with MT7668 chipset, as explained [here](https://ps4linux.com/dns-issues-mt7668-ps4-linux-fix/)
2. VPN support (Wireguard, OpenVPN), as explained [here](https://ps4linux.com/ps4-linux-vpn-wireguard-openvpn/)

# NEW!!!
3. registers_AMD_GPU_GLADIUS_ps4_pro.txt by saya applied for better GPU Performance "Haven Benchmark Score: 870" See: [saya's benchmark video](https://www.youtube.com/watch?v=9Q1WwvZUEQc&t) for comparison.
4. 480-2160@60-edids supported

This project is actually a continuation of the [MT7668 kernel modules for PS4](https://github.com/noob404yt/mt7668-wifi-bt).

## How to compile PS4 Baikal kernel with MT7668 WiFi & Bluetooth support
Since the source has everything pre-packed, you can directly compile the kernel and use it to boot your PS4 Linux distro. Check the article on [compiling PS4 Linux kernel from source](https://ps4linux.com/compile-ps4-linux-kernel-tutorial/). You can also [add additional drivers](https://ps4linux.com/add-drivers-ps4-linux-kernel/).

## Thanks to
1. novice4321 (Sponsored the driver port to PS4)
2. Reo Au In (Helped in testing and has helped sponsor projects from the beginning)
3. eioltesr1 (Sponsored DNS fix and VPN support)
4. Khadas's Repo
5. Fire Stick drivers
6. Many others
