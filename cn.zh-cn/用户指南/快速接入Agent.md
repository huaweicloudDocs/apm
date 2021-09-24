# 快速接入Agent<a name="ZH-CN_TOPIC_0000001120662690"></a>

## 前提条件<a name="section17813348121916"></a>

确保接入APM的机器与APM服务网络连通。

<a name="table152221920142815"></a>
<table><thead align="left"><tr id="row222242032818"><th class="cellrowborder" valign="top" width="29.09%" id="mcps1.1.3.1.1"><p id="p1222214202282"><a name="p1222214202282"></a><a name="p1222214202282"></a>区域</p>
</th>
<th class="cellrowborder" valign="top" width="70.91%" id="mcps1.1.3.1.2"><p id="p142221520152820"><a name="p142221520152820"></a><a name="p142221520152820"></a>联通测试</p>
</th>
</tr>
</thead>
<tbody><tr id="row17222102010285"><td class="cellrowborder" valign="top" width="29.09%" headers="mcps1.1.3.1.1 "><p id="p1622212010280"><a name="p1622212010280"></a><a name="p1622212010280"></a>北京四</p>
</td>
<td class="cellrowborder" valign="top" width="70.91%" headers="mcps1.1.3.1.2 "><p id="p11237544122816"><a name="p11237544122816"></a><a name="p11237544122816"></a>telnet 100.125.12.108 41333</p>
<p id="p13237184492820"><a name="p13237184492820"></a><a name="p13237184492820"></a>telnet 100.125.12.108 41335</p>
</td>
</tr>
<tr id="row166160599210"><td class="cellrowborder" valign="top" width="29.09%" headers="mcps1.1.3.1.1 "><p id="p1361814591520"><a name="p1361814591520"></a><a name="p1361814591520"></a>上海一</p>
</td>
<td class="cellrowborder" valign="top" width="70.91%" headers="mcps1.1.3.1.2 "><p id="p7650628136"><a name="p7650628136"></a><a name="p7650628136"></a>telnet 100.125.4.27 41333</p>
<p id="p1618105918210"><a name="p1618105918210"></a><a name="p1618105918210"></a>telnet 100.125.4.27 41335</p>
</td>
</tr>
<tr id="row16212310141814"><td class="cellrowborder" valign="top" width="29.09%" headers="mcps1.1.3.1.1 "><p id="p424417311514"><a name="p424417311514"></a><a name="p424417311514"></a>广州</p>
</td>
<td class="cellrowborder" valign="top" width="70.91%" headers="mcps1.1.3.1.2 "><p id="p888695541610"><a name="p888695541610"></a><a name="p888695541610"></a>telnet 100.125.143.102 41333</p>
<p id="p18886555111617"><a name="p18886555111617"></a><a name="p18886555111617"></a>telnet 100.125.143.102 41335</p>
</td>
</tr>
<tr id="row28645123181"><td class="cellrowborder" valign="top" width="29.09%" headers="mcps1.1.3.1.1 "><p id="p063113235172"><a name="p063113235172"></a><a name="p063113235172"></a>新加坡</p>
</td>
<td class="cellrowborder" valign="top" width="70.91%" headers="mcps1.1.3.1.2 "><p id="p1563242351711"><a name="p1563242351711"></a><a name="p1563242351711"></a>telnet 100.125.4.25 41333</p>
<p id="p1394484610176"><a name="p1394484610176"></a><a name="p1394484610176"></a>telnet 100.125.4.25 41335</p>
</td>
</tr>
</tbody>
</table>

## 操作步骤<a name="section1589121232011"></a>

1.  在左侧导航栏中选择“应用监控 \> 应用列表”。
2.  单击“接入应用”，进入接入应用页面。

    ![](figures/zh-cn_image_0000001147995832.png)

3.  单击安装命令后的![](figures/zh-cn_image_0000001121931180.png)复制安装命令，然后在需要接入APM机器的任意目录执行。

    ![](figures/zh-cn_image_0000001120832690.png)

4.  单击参数命令后的![](figures/zh-cn_image_0000001168691221.png)复制参数命令，将该参数添加到服务启动脚本的java命令。
5.  重启应用。

