## Ciao 👋🏻
I'm a Linux kernel and systems engineer: BPF, networking, resource control, and the occasional embedded hack.  
Previously at Meta, Microsoft, Red Hat and Canonical. Linux user since 2003, Debian/Fedora + KDE Plasma.

Some things I've worked on:
* systemd-oomd and RPM copy-on-write at Meta
* page_pool skb recycling in the network stack
* optimized string routines for RISC-V

I contribute upstream whenever I can:
* **Kernel & low level:** [Linux](https://github.com/torvalds/linux/commits?author=teknoraver), [u-root](https://github.com/u-root/u-root/commits?author=teknoraver), [BusyBox](https://git.busybox.net/busybox/log/?qt=grep&q=Matteo+Croce)
* **Userspace:** [systemd](https://github.com/systemd/systemd/commits?author=teknoraver), [RPM](https://github.com/rpm-software-management/rpm/commits?author=teknoraver), [Snap](https://github.com/snapcore/snapd/commits?author=teknoraver), [SANE](https://gitlab.com/sane-project/backends/-/commits/master?author=Matteo%20Croce)
* **Networking:** [Open vSwitch](https://github.com/openvswitch/ovs/commits?author=teknoraver), [iproute2](https://github.com/shemminger/iproute2/commits?author=teknoraver), [OpenWrt](https://github.com/openwrt/openwrt/commits?author=teknoraver)

…plus lots of small fixes here and there 🙂

Despite my efforts to contribute to science, my most recognized works are April fools:
* https://sourceware.org/pipermail/libc-alpha/2016-April/069898.html
* https://lists.gnu.org/archive/html/qemu-devel/2019-04/msg00075.html
* https://lkml.org/lkml/2019/4/1/335
* https://inbox.dpdk.org/stable/20200401131044.7259-1-mcroce@redhat.com/

or silly sound generating scripts, e.g. `perl -e 'for($t=0;;$t++){print chr($t*($t>>8|$t>>13)&255)}' |aplay` (replace `|` with `&` for an alternate version)
