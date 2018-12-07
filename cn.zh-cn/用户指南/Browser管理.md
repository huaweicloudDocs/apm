# Browser管理<a name="apm_02_0027"></a>

Browser管理即创建浏览器应用。

## 新建浏览器应用<a name="section1896116102227"></a>

1.  登录[应用性能管理](https://console.huaweicloud.com/apm/)。
2.  在左侧导航栏中选择“Browser”，展开选项卡，单击“管理”。
3.  创建浏览器应用。单击“添加”，按提示输入应用名称后点击“生成”，系统将生成专属您应用的埋点命令行。

    ![](figures/zh-cn_image_0128868296.png)

4.  单击“完成拷贝”，完成应用创建并自动拷贝命令行到剪贴板。

    >![](public_sys-resources/icon-notice.gif) **注意：**   
    >若您的页面涉及跨域访问，您需要在跨域目标服务器上配置以下自定义Header：Access-Control-Allow-Methods: POST,OPTIONS,GET,PUTAccess-Control-Allow-Headers: X-Application-Id,Content-Type,X-EP-App-Id,X-App-Id,Pinpoint-TxType,Pinpoint-SrcResId,Pinpoint-TraceID,Pinpoint-pSpanID,Pinpoint-SpanID,X-Device-Id,X-Forwarded-For,X-Real-IpAccess-Control-Expose-Headers: Date,X-Dest-Resource-Id,Pinpoint-TxType,Pinpoint-SrcResId,X-App-Id,Pinpoint-CallChain,Zipkin-TraceID,Pinpoint-MonitorG,Timing-Allow-Origin  


## 嵌入命令行<a name="section12998155554416"></a>

1.  在应用创建完成后，埋点命令行就已存在于剪贴板中。若您不慎丢失命令行，可在列表右侧的动作列单击![](figures/zh-cn_image_0128868299.png)。

    ![](figures/zh-cn_image_0128868302.png)

2.  在“查看埋点命令行”弹框中单击“完成拷贝”重新获取埋点命令行。

    ![](figures/zh-cn_image_0128868305.png)

3.  将命令行粘贴在您想要监控的页面的HTML文件中**<head\>**代码块的**第一行**，然后重启应用即可。

    >![](public_sys-resources/icon-notice.gif) **注意：**   
    >如果相比全站的监控数据您更关心单页面的监控数据，您可以为单页面创建一个应用并嵌入它的专属命令行，这样通过该应用即可查看单页面的监控数据。  


## 更多浏览器管理界面操作<a name="section16744158919"></a>

在浏览器管理中，您还可以执行如下表操作。

**表 1**  相关操作

<a name="table15831736105910"></a>
<table><thead align="left"><tr id="row14583153620596"><th class="cellrowborder" valign="top" width="20%" id="mcps1.2.3.1.1"><p id="p10583203610596"><a name="p10583203610596"></a><a name="p10583203610596"></a>操作</p>
</th>
<th class="cellrowborder" valign="top" width="80%" id="mcps1.2.3.1.2"><p id="p35838364598"><a name="p35838364598"></a><a name="p35838364598"></a>说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1058316369591"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.3.1.1 "><p id="p3583036195916"><a name="p3583036195916"></a><a name="p3583036195916"></a>全选或者取消全选</p>
</td>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.2.3.1.2 "><p id="p258317365591"><a name="p258317365591"></a><a name="p258317365591"></a>可通过<a name="image536513147519"></a><a name="image536513147519"></a><span><img id="image536513147519" src="figures/zh-cn_image_0128868308.png"></span>全选浏览器应用管理表中行，通过<a name="image1251516262073"></a><a name="image1251516262073"></a><span><img id="image1251516262073" src="figures/zh-cn_image_0128868311.png" width="20.9475" height="20.045627"></span>可取消全选。</p>
</td>
</tr>
<tr id="row019992094812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.3.1.1 "><p id="p205831436115916"><a name="p205831436115916"></a><a name="p205831436115916"></a>跳转到拓扑界面</p>
</td>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.2.3.1.2 "><p id="p1167075833016"><a name="p1167075833016"></a><a name="p1167075833016"></a>单击列表右侧的动作列单击<a name="image194232024181112"></a><a name="image194232024181112"></a><span><img id="image194232024181112" src="figures/zh-cn_image_0128868314.png"></span>按钮，可跳转到Browser拓扑界面详细查看调用过程。</p>
</td>
</tr>
<tr id="row185831236125917"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.3.1.1 "><p id="p1358333615919"><a name="p1358333615919"></a><a name="p1358333615919"></a>跳转到浏览器汇总界面</p>
</td>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.2.3.1.2 "><p id="p2317132418122"><a name="p2317132418122"></a><a name="p2317132418122"></a>单击列表右侧的动作列单击<a name="image1762782117139"></a><a name="image1762782117139"></a><span><img id="image1762782117139" src="figures/zh-cn_image_0128868317.png"></span>按钮，可跳转到浏览器汇总界面，查看用户体验详情。</p>
</td>
</tr>
</tbody>
</table>

