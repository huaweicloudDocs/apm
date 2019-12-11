# 安装PHP探针<a name="apm_02_0049"></a>

## 前提条件<a name="section147361624505"></a>

-   已完成ICAgent安装。
-   满足APM支持的[Linux操作系统](https://support.huaweicloud.com/productdesc-apm/apm_06_0007.html)。
-   满足APM支持的[PHP类型](https://support.huaweicloud.com/productdesc-apm/apm_06_0007.html)。

## 安装PHP探针<a name="section927121015450"></a>

1.  在左侧导航栏中选择“采集管理 \>探针安装”。
2.  选择探针类型为“PHP”。
3.  （可选）[安装ICAgent](安装ICAgent（Linux）.md)。如果您已安装ICAgent，请跳过此步骤。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >PHP探针仅支持Linux系统下ICAgent的安装方式。  

4.  参考[表 参数说明](#zh-cn_topic_0114121306_tc77c337fd6654f05885648b51c3f016d)输入应用名称、服务名称和采样率。

    **表 1**  参数说明

    <a name="zh-cn_topic_0114121306_tc77c337fd6654f05885648b51c3f016d"></a>
    <table><thead align="left"><tr id="zh-cn_topic_0114121306_ra6391e2ab5214123a1a44a87d60c5582"><th class="cellrowborder" valign="top" width="32%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0114121306_a88d7723164014827b084ca9ca3e80d61"><a name="zh-cn_topic_0114121306_a88d7723164014827b084ca9ca3e80d61"></a><a name="zh-cn_topic_0114121306_a88d7723164014827b084ca9ca3e80d61"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="68%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0114121306_aa07b3ae9a51048e481bad857743eba40"><a name="zh-cn_topic_0114121306_aa07b3ae9a51048e481bad857743eba40"></a><a name="zh-cn_topic_0114121306_aa07b3ae9a51048e481bad857743eba40"></a>取值说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="zh-cn_topic_0114121306_rdb6ae5c75a894098be04e07c8a93f6b1"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0114121306_a096690794f8c43359fe3c5b52472ca36"><a name="zh-cn_topic_0114121306_a096690794f8c43359fe3c5b52472ca36"></a><a name="zh-cn_topic_0114121306_a096690794f8c43359fe3c5b52472ca36"></a>应用名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p795763316326"><a name="p795763316326"></a><a name="p795763316326"></a>只能由小写字母、数字、中划线（-）、下划线（_）组成，且以小写字母或下划线（_）开头，长度限制为1~64位字符。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0114121306_r534299532600473290fc80b6a6731248"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0114121306_ada94f89825624eb7913aa6e47b63ade4"><a name="zh-cn_topic_0114121306_ada94f89825624eb7913aa6e47b63ade4"></a><a name="zh-cn_topic_0114121306_ada94f89825624eb7913aa6e47b63ade4"></a>服务名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="zh-cn_topic_0114121306_a4f72c2450a744180abe14d40a7b0edb5"><a name="zh-cn_topic_0114121306_a4f72c2450a744180abe14d40a7b0edb5"></a><a name="zh-cn_topic_0114121306_a4f72c2450a744180abe14d40a7b0edb5"></a>组成该应用的微服务名称。</p>
    <p id="p3408611583"><a name="p3408611583"></a><a name="p3408611583"></a>只能由小写字母、数字、中划线（-）、下划线（_）组成，且以小写字母或下划线（_）开头，长度限制为1~64位字符。</p>
    </td>
    </tr>
    <tr id="zh-cn_topic_0114121306_r1deb74cb647d4e29943d5d571fb765f7"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="zh-cn_topic_0114121306_aa1c772fc824b49d6b68fb662c5246b87"><a name="zh-cn_topic_0114121306_aa1c772fc824b49d6b68fb662c5246b87"></a><a name="zh-cn_topic_0114121306_aa1c772fc824b49d6b68fb662c5246b87"></a>采样率</p>
    </td>
    <td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p8731526133215"><a name="p8731526133215"></a><a name="p8731526133215"></a>0~1之间的数字。</p>
    </td>
    </tr>
    <tr id="row458014311332"><td class="cellrowborder" valign="top" width="32%" headers="mcps1.2.3.1.1 "><p id="p758143111335"><a name="p758143111335"></a><a name="p758143111335"></a>版本号</p>
    </td>
    <td class="cellrowborder" valign="top" width="68%" headers="mcps1.2.3.1.2 "><p id="p11918175413018"><a name="p11918175413018"></a><a name="p11918175413018"></a>版本号由后台获取，无需用户输入。</p>
    </td>
    </tr>
    </tbody>
    </table>

    ![](figures/PHP探针.png)

5.  使用远程登录工具以root用户登录待安装PHP探针的服务器，执行复制的PHP探针安装命令。
6.  重启PHP应用，5分钟后，PHP应用的性能数据就会呈现在应用性能管理服务界面上。

    当PHP应用服务出现HTTP请求接入，说明您已经成功监控到PHP应用的性能数据。


