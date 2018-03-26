## 1. Linux系统

1. [Linux 中直接 I/O 机制的介绍](https://www.ibm.com/developerworks/cn/linux/l-cn-directio/): 介绍Linux direct IO。
2. [Linux 中的零拷贝技术，第 1 部分](https://www.ibm.com/developerworks/cn/linux/l-cn-zerocopy1/index.html): 什么是zero copy，为什么需要zero copy，zero copy技术分类。
3. [Linux 中的零拷贝技术，第 2 部分](https://www.ibm.com/developerworks/cn/linux/l-cn-zerocopy2/index.html): zero copy技术实现。
4. [How To Check If A Linux System Is Physical Or Virtual Machine](https://www.ostechnix.com/check-linux-system-physical-virtual-machine/):判断是物理机还是虚拟机的各种方法。
5. [Generating a img from tarball the dev loop devices](https://unix.stackexchange.com/questions/187326/generating-a-img-from-tarball-the-dev-loop-devices): 挂载raw为loop设备。
6. [what is the internal interface and port for openvswitch](https://ask.openstack.org/en/question/4276/what-is-the-internal-interface-and-port-for-on-openvswitch/): 为什么ovs桥需要一个与之名字一样的internal port，为什么不能把IP配在物理网卡上。
7. [Major and Minor Numbers](http://www.linux-tutorial.info/modules.php?name=MContent&pageid=94): 介绍Linux主设备号和次设备号。

## 2. Ceph

1. [大话Ceph--CRUSH那点事儿](http://www.xuxiaopang.com/2016/11/08/easy-ceph-CRUSH/): 通俗介绍CRUSH算法原理。
2. [Ceph and krbd discard](http://www.sebastien-han.fr/blog/2015/01/26/ceph-and-krbd-discard/): 介绍Ceph的discard特性。

## 3. OpenStack

1. [9 tips to properly configure your OpenStack Instance](https://redhatstackblog.redhat.com/2017/01/18/9-tips-to-properly-configure-your-openstack-instance/)：OpenStack的9个配置建议。
2. [The Dos and Don'ts for Ceph for OpenStack](https://www.hastexo.com/resources/hints-and-kinks/dos-donts-ceph-openstack/)：关于OpenStack使用Ceph的一些优化配置。
3. [More recommendations for Ceph and OpenStack](https://www.hastexo.com/resources/hints-and-kinks/more-recommendations-ceph-openstack/)：关于OpenStack使用Ceph的更多优化配置。
4. [Importing an existing Ceph RBD image into Glance](https://www.hastexo.com/resources/hints-and-kinks/importing-rbd-into-glance/)：把RBD image导入到Glance的方法。
5. [Virtual Private Cloud: Creating Custom Images](https://blog.selectel.com/virtual-private-cloud-creating-custom-images/): 使用DIB制作OpenStack镜像。
