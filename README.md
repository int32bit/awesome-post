## 1. Linux系统

1. [Linux 中直接 I/O 机制的介绍](https://www.ibm.com/developerworks/cn/linux/l-cn-directio/): 介绍Linux direct IO。
2. [Linux 中的零拷贝技术，第 1 部分](https://www.ibm.com/developerworks/cn/linux/l-cn-zerocopy1/index.html): 什么是zero copy，为什么需要zero copy，zero copy技术分类。
3. [Linux 中的零拷贝技术，第 2 部分](https://www.ibm.com/developerworks/cn/linux/l-cn-zerocopy2/index.html): zero copy技术实现。
4. [How To Check If A Linux System Is Physical Or Virtual Machine](https://www.ostechnix.com/check-linux-system-physical-virtual-machine/):判断是物理机还是虚拟机的各种方法。
5. [Generating a img from tarball the dev loop devices](https://unix.stackexchange.com/questions/187326/generating-a-img-from-tarball-the-dev-loop-devices): 挂载raw为loop设备。
6. [what is the internal interface and port for openvswitch](https://ask.openstack.org/en/question/4276/what-is-the-internal-interface-and-port-for-on-openvswitch/): 为什么ovs桥需要一个与之名字一样的internal port，为什么不能把IP配在物理网卡上。
7. [Major and Minor Numbers](http://www.linux-tutorial.info/modules.php?name=MContent&pageid=94): 介绍Linux主设备号和次设备号。
8. [lvm linear vs striped logical volumes](https://sysadmincasts.com/episodes/27-lvm-linear-vs-striped-logical-volumes)。
9. [Bonding VLAN Bridge](https://www.ovirt.org/documentation/how-to/networking/bonding-vlan-bridge/): 怎么手动配置linux bond以及vlan（不用vconfig）。
10. [How to configure linux virtual local area network vlan](http://www.gocit.vn/bai-viet/howto-configure-linux-virtual-local-area-network-vlan/):介绍手动配置vlan以及使用vconfig配置vlan。
11. [How to configure linux virtual local area network vlan](https://www.cyberciti.biz/tips/howto-configure-linux-virtual-local-area-network-vlan.html): Linux下创建vlan子接口的三种方法（network-scripts/vconfig/ip）。
12. [Linux VRF(Virtual Routing Forwarding)的原理和实现](https://blog.csdn.net/dog250/article/details/78069964)。
13. [Port mirroring with Linux bridges](http://backreference.org/2014/06/17/port-mirroring-with-linux-bridges/): 介绍Linux实现port mirror的方法。
14. [认识VXLAN](http://forum.huawei.com/enterprise/zh/forum.php?mod=viewthread&tid=334207): 介绍Vxlan、bridge domain以及集中网关、分布式网关。

## 2. Ceph

1. [大话Ceph--CRUSH那点事儿](http://www.xuxiaopang.com/2016/11/08/easy-ceph-CRUSH/): 通俗介绍CRUSH算法原理。
2. [Ceph and krbd discard](http://www.sebastien-han.fr/blog/2015/01/26/ceph-and-krbd-discard/): 介绍Ceph的discard特性。

## 3. OpenStack

1. [9 tips to properly configure your OpenStack Instance](https://redhatstackblog.redhat.com/2017/01/18/9-tips-to-properly-configure-your-openstack-instance/)：OpenStack的9个配置建议。
2. [The Dos and Don'ts for Ceph for OpenStack](https://www.hastexo.com/resources/hints-and-kinks/dos-donts-ceph-openstack/)：关于OpenStack使用Ceph的一些优化配置。
3. [More recommendations for Ceph and OpenStack](https://www.hastexo.com/resources/hints-and-kinks/more-recommendations-ceph-openstack/)：关于OpenStack使用Ceph的更多优化配置。
4. [Importing an existing Ceph RBD image into Glance](https://www.hastexo.com/resources/hints-and-kinks/importing-rbd-into-glance/)：把RBD image导入到Glance的方法。
5. [Virtual Private Cloud: Creating Custom Images](https://blog.selectel.com/virtual-private-cloud-creating-custom-images/): 使用DIB制作OpenStack镜像。
6. [openstack底层技术-虚拟网络设备(Bridge,VLAN)](https://opengers.github.io/openstack/openstack-base-virtual-network-devices-bridge-and-vlan/)
7. [openstack底层技术-虚拟网络设备(tun/tap,veth)](https://opengers.github.io/openstack/openstack-base-virtual-network-devices-tuntap-veth/)
8. [openstack底层技术-使用openvswitch](https://opengers.github.io/openstack/openstack-base-use-openvswitch/)
9. [openstack底层技术-openflow在OVS中的应用](https://opengers.github.io/openstack/openstack-base-openflow-in-openvswitch/)
10. [openstack底层技术-netfilter框架概述](https://opengers.github.io/openstack/openstack-base-netfilter-framework-overview/)
11. [Migrate Suse Linux from VMware ESXi to Nutanix AHV in minutes](http://vmwaremine.com/2015/09/14/migrate-suse-linux-from-vmware-esxi-to-nutanix-ahv-in-minutes/): Vmware虚拟机迁移到Nutanix AHV，同样适用OpenStack，需要手动添加virtio模块到initrd中，否则虚拟机起不来。
，
