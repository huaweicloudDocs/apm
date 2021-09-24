# 为JAVA应用手工安装Agent<a name="apm_07_0004"></a>

## 前提条件<a name="section8132103817447"></a>

-   确保接入APM的机器与APM服务网络连通。

    <a name="table152221920142815"></a>
    <table><thead align="left"><tr id="row222242032818"><th class="cellrowborder" valign="top" width="25.580000000000002%" id="mcps1.1.3.1.1"><p id="p1222214202282"><a name="p1222214202282"></a><a name="p1222214202282"></a>区域</p>
    </th>
    <th class="cellrowborder" valign="top" width="74.42%" id="mcps1.1.3.1.2"><p id="p142221520152820"><a name="p142221520152820"></a><a name="p142221520152820"></a>联通测试</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row17222102010285"><td class="cellrowborder" valign="top" width="25.580000000000002%" headers="mcps1.1.3.1.1 "><p id="p1622212010280"><a name="p1622212010280"></a><a name="p1622212010280"></a>北京四</p>
    </td>
    <td class="cellrowborder" valign="top" width="74.42%" headers="mcps1.1.3.1.2 "><p id="p11237544122816"><a name="p11237544122816"></a><a name="p11237544122816"></a>telnet 100.125.12.108 41333</p>
    <p id="p13237184492820"><a name="p13237184492820"></a><a name="p13237184492820"></a>telnet 100.125.12.108 41335</p>
    </td>
    </tr>
    <tr id="row1863305019417"><td class="cellrowborder" valign="top" width="25.580000000000002%" headers="mcps1.1.3.1.1 "><p id="p1361814591520"><a name="p1361814591520"></a><a name="p1361814591520"></a>上海一</p>
    </td>
    <td class="cellrowborder" valign="top" width="74.42%" headers="mcps1.1.3.1.2 "><p id="p7650628136"><a name="p7650628136"></a><a name="p7650628136"></a>telnet 100.125.4.27 41333</p>
    <p id="p1618105918210"><a name="p1618105918210"></a><a name="p1618105918210"></a>telnet 100.125.4.27 41335</p>
    </td>
    </tr>
    <tr id="row132421832159"><td class="cellrowborder" valign="top" width="25.580000000000002%" headers="mcps1.1.3.1.1 "><p id="p424417311514"><a name="p424417311514"></a><a name="p424417311514"></a>广州</p>
    </td>
    <td class="cellrowborder" valign="top" width="74.42%" headers="mcps1.1.3.1.2 "><p id="p888695541610"><a name="p888695541610"></a><a name="p888695541610"></a>telnet 100.125.143.102 41333</p>
    <p id="p18886555111617"><a name="p18886555111617"></a><a name="p18886555111617"></a>telnet 100.125.143.102 41335</p>
    </td>
    </tr>
    <tr id="row186309233175"><td class="cellrowborder" valign="top" width="25.580000000000002%" headers="mcps1.1.3.1.1 "><p id="p063113235172"><a name="p063113235172"></a><a name="p063113235172"></a>新加坡</p>
    </td>
    <td class="cellrowborder" valign="top" width="74.42%" headers="mcps1.1.3.1.2 "><p id="p1563242351711"><a name="p1563242351711"></a><a name="p1563242351711"></a>telnet 100.125.4.25 41333</p>
    <p id="p1394484610176"><a name="p1394484610176"></a><a name="p1394484610176"></a>telnet 100.125.4.25 41335</p>
    </td>
    </tr>
    </tbody>
    </table>

-   选择“系统管理 \> 访问密钥”进入访问密钥页面，查看获取接入javaagent所需的AK/SK。

    ![](figures/zh-cn_image_0000001193796915.png)


## 操作步骤<a name="section2010313462448"></a>

1.  下载javaagent，参考[表1](Agent下载地址和接入地址master-address配置.md#table152221920142815)下载apm-javaagent-x.x.x.zip，并将javaagent下载到需要接入APM机器的任意目录。

    示例命令：

    **curl  -O https://xxx/apm-javaagent-x.x.x.tar**


1.  执行tar命令解压javaagent。

    示例命令：

    **tar -xvf apm-javaagent-x.x.x.tar**


1.  修改javaagent中的apm.config配置文件。master.address配置请参见[表2](Agent下载地址和接入地址master-address配置.md#table1193774063913)，将AK/SK写入配置文件中，如下图所示。

    ![](figures/20210506-185007(eSpace).png)


1.  修改java进程启动脚本。

    在服务启动脚本的java命令之后，配置apm-javaagent.jar包所在路径，并指定java进程的应用名。

    添加-javaagent参数示例：

    java  **-javaagent:/xxx/apm-javaagent/apm-javaagent.jar=appName=\{appName\}**

    当企业应用很多的情况下，也支持更为复杂一些的配置，添加-javaagent参数的复杂模式如：

    java  **-javaagent:/xxx/apm-javaagent/apm-javaagent.jar=appName=myApp,env=myEnv,envTag=myTag,business=myBusiness,subBusiness=mySub**

    >![](public_sys-resources/icon-note.gif) **说明：** 
    >上述参数属于APM内置的CMDB信息，具体详情见[CMDB结构树](CMDB结构树.md)章节。

2.  重启应用。

