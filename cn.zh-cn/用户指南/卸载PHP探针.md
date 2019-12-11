# 卸载PHP探针<a name="apm_02_0050"></a>

服务器上的PHP探针被卸载后，会影响该服务器的运维能力，导致拓扑、调用链等功能不可用，请谨慎操作！

1.  以**root**用户登录需卸载PHP探针的服务器。
2.  执行命令卸载PHP探针。
    -   卸载RPM包（RHEL/CentOS 6+, Fedra 20+）安装的PHP探针，执行如下命令。

        **rpm -e phpprob**

    -   卸载DEB包（Debian Jessie+，Ubuntu 14.04+）安装的PHP探针，执行如下命令。

        **dpkg -P phpprob**



