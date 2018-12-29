# APP管理<a name="apm_02_0031"></a>

APP管理即创建移动APP应用。

>![](public_sys-resources/icon-note.gif) **说明：**   
>1.  Mobile探针需要的手机权限：  
>    权限1：android.permission.INTERNET  
>    权限2：android.permission.ACCESS\_NETWORK\_STATE  
>2.  执行埋点命令行的环境必须安装Java1.8及以上版本，并设置了正确的JAVA\_HOME环境变量。  

## 新建移动APP应用<a name="section091961131017"></a>

1.  登录[应用性能管理](https://console.huaweicloud.com/apm/)。
2.  在左侧导航栏中选择“Mobile”，展开选项卡，单击“APP管理”。
3.  单击“下载埋点工具包”下载埋点工具，并解压埋点工具包到本地。

    Windows：

    ![](figures/Windows系统.jpg)

    Linux：

    ![](figures/Linux系统.jpg)

4.  创建APP。单击“添加”，按提示输入应用名称后点击“生成”，系统将生成专属您应用的埋点命令行。

    黑色背景框中会生成Windows和Linux的命令行。

    ![](figures/创建APP.png)

5.  单击“完成拷贝”，完成应用创建并自动拷贝命令行到剪贴板。
6.  将拷贝的命令行粘贴到记事本文档，将其中的\{APK\_PATH\}替换为您的实际apk地址。

    Windows：

    1.  进入apk\_instrumenter文件夹。
    2.  在当前文件夹打开命令行：

        ![](figures/打开命令行.png)

    3.  把生成的Windows命令行中的 “\{APK\_PATH\}” 替换为需要埋点的apk全路径。

        ![](figures/apk全路径.png)


    Linux:

    1.  进入apk\_instrumenter文件夹
    2.  把生成的Linux命令行中的 “\{APK\_PATH\}” 替换为需要埋点的apk全路径，例：

        ![](figures/apk全路径Linux.png)


7.  根据您运行埋点的操作系统拷贝对应执行命令行运行命令。

    Windows

    1.  在刚才打开的cmd中执行替换好的命令行

        ![](figures/Windows命令行.png)

    2.  埋点完成后会弹出一个文件夹，文件夹中包含了原始apk和埋点后的apk，名称如

        ![](figures/埋点后的apk.png)


    Linux:

    在apk\_instrumenter目录下执行埋点命令行，执行完毕后生成的apk会显示在命令行中：

    ![](figures/Linux生成的apk.png)

8.  将APK签名即可发布安装。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >**埋点完成后是不带签名的，需要用户自己对生成后的apk进行签名**。  


## 埋点命令行<a name="section4222102941910"></a>

1.  在应用创建完成后，埋点命令行就已存在于剪贴板中。若您不慎丢失命令行，或需要埋点升级的app，可在列表右侧的动作列单击![](figures/icon-找回2.png)按钮。

    ![](figures/APP管理.png)

2.  在“查看埋点命令行”弹框中单击“完成拷贝”重新获取埋点命令行。

    ![](figures/查看埋点命令行2.png)

3.  重新执行埋点过程生成新的APK文件即可。

## 更多APP管理界面操作<a name="section16744158919"></a>

在APP管理中，您还可以执行如下表操作。

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
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.2.3.1.2 "><p id="p258317365591"><a name="p258317365591"></a><a name="p258317365591"></a>可通过<a name="image119715991820"></a><a name="image119715991820"></a><span><img id="image119715991820" src="figures/icon-全选2.png" width="27.93" height="23.425157000000002"></span>全选APP管理表中行，通过<a name="image19871195411259"></a><a name="image19871195411259"></a><span><img id="image19871195411259" src="figures/icon-取消全选2.png" width="21.28" height="20.354719"></span>可取消全选。</p>
</td>
</tr>
<tr id="row019992094812"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.3.1.1 "><p id="p205831436115916"><a name="p205831436115916"></a><a name="p205831436115916"></a>跳转到拓扑界面</p>
</td>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.2.3.1.2 "><p id="p1167075833016"><a name="p1167075833016"></a><a name="p1167075833016"></a>单击列表右侧的动作列单击<a name="image21257486273"></a><a name="image21257486273"></a><span><img id="image21257486273" src="figures/icon-跳转到拓扑界面2.png"></span>按钮，可跳转到Mobile拓扑界面详细查看调用过程。</p>
</td>
</tr>
<tr id="row185831236125917"><td class="cellrowborder" valign="top" width="20%" headers="mcps1.2.3.1.1 "><p id="p1358333615919"><a name="p1358333615919"></a><a name="p1358333615919"></a>跳转到APP汇总界面</p>
</td>
<td class="cellrowborder" valign="top" width="80%" headers="mcps1.2.3.1.2 "><p id="p2317132418122"><a name="p2317132418122"></a><a name="p2317132418122"></a>单击列表右侧的动作列单击<a name="image341494142810"></a><a name="image341494142810"></a><span><img id="image341494142810" src="figures/icon-跳转到APP界面.png"></span>按钮，可跳转到APP汇总界面，查看用户体验详情。</p>
</td>
</tr>
</tbody>
</table>

