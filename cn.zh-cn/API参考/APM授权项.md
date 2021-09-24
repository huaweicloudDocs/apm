# APM授权项<a name="apm_04_0023"></a>

此功能目前仅对华北、华东、华南区域开放。

>![](public_sys-resources/icon-note.gif) **说明：** 
>“√”表示支持，“x”表示暂不支持。

**表 1**  API授权项列表

<a name="table1864042012710"></a>
<table><thead align="left"><tr id="row9640182017711"><th class="cellrowborder" valign="top" width="12.378762123787618%" id="mcps1.2.6.1.1"><p id="p1217184416710"><a name="p1217184416710"></a><a name="p1217184416710"></a>权限</p>
</th>
<th class="cellrowborder" valign="top" width="32.556744325567436%" id="mcps1.2.6.1.2"><p id="p4982103684413"><a name="p4982103684413"></a><a name="p4982103684413"></a>对应API接口</p>
</th>
<th class="cellrowborder" valign="top" width="33.006699330066986%" id="mcps1.2.6.1.3"><p id="p2171344272"><a name="p2171344272"></a><a name="p2171344272"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="11.468853114688528%" id="mcps1.2.6.1.4"><p id="p382349102520"><a name="p382349102520"></a><a name="p382349102520"></a>IAM项目(Project)</p>
</th>
<th class="cellrowborder" valign="top" width="10.58894110588941%" id="mcps1.2.6.1.5"><p id="p18821749152512"><a name="p18821749152512"></a><a name="p18821749152512"></a>企业项目(Enterprise Project)</p>
</th>
</tr>
</thead>
<tbody><tr id="row106401620675"><td class="cellrowborder" valign="top" width="12.378762123787618%" headers="mcps1.2.6.1.1 "><p id="p9171134415718"><a name="p9171134415718"></a><a name="p9171134415718"></a>查询应用列表</p>
</td>
<td class="cellrowborder" valign="top" width="32.556744325567436%" headers="mcps1.2.6.1.2 "><p id="p12171164418717"><a name="p12171164418717"></a><a name="p12171164418717"></a>GET /v1/{project_id}/atps/monitorgroups</p>
</td>
<td class="cellrowborder" valign="top" width="33.006699330066986%" headers="mcps1.2.6.1.3 "><p id="p1817194420719"><a name="p1817194420719"></a><a name="p1817194420719"></a>apm:inventory:get</p>
</td>
<td class="cellrowborder" valign="top" width="11.468853114688528%" headers="mcps1.2.6.1.4 "><p id="p15781412194516"><a name="p15781412194516"></a><a name="p15781412194516"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="10.58894110588941%" headers="mcps1.2.6.1.5 "><p id="p1694462510507"><a name="p1694462510507"></a><a name="p1694462510507"></a>√</p>
</td>
</tr>
<tr id="row12640122016713"><td class="cellrowborder" valign="top" width="12.378762123787618%" headers="mcps1.2.6.1.1 "><p id="p918710449710"><a name="p918710449710"></a><a name="p918710449710"></a>查询服务列表</p>
</td>
<td class="cellrowborder" valign="top" width="32.556744325567436%" headers="mcps1.2.6.1.2 "><p id="p161872441671"><a name="p161872441671"></a><a name="p161872441671"></a>GET /v1/{project_id}/ats/applications</p>
</td>
<td class="cellrowborder" valign="top" width="33.006699330066986%" headers="mcps1.2.6.1.3 "><p id="p1818734415710"><a name="p1818734415710"></a><a name="p1818734415710"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="11.468853114688528%" headers="mcps1.2.6.1.4 "><p id="p3151131710452"><a name="p3151131710452"></a><a name="p3151131710452"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="10.58894110588941%" headers="mcps1.2.6.1.5 "><p id="p294442545013"><a name="p294442545013"></a><a name="p294442545013"></a>√</p>
</td>
</tr>
<tr id="row116401220173"><td class="cellrowborder" valign="top" width="12.378762123787618%" headers="mcps1.2.6.1.1 "><p id="p18187344173"><a name="p18187344173"></a><a name="p18187344173"></a>查询服务实例列表</p>
</td>
<td class="cellrowborder" valign="top" width="32.556744325567436%" headers="mcps1.2.6.1.2 "><p id="p618719446712"><a name="p618719446712"></a><a name="p618719446712"></a>GET /v1/{project_id}/ats/applications/{application}/instances</p>
</td>
<td class="cellrowborder" valign="top" width="33.006699330066986%" headers="mcps1.2.6.1.3 "><p id="p3187154410716"><a name="p3187154410716"></a><a name="p3187154410716"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="11.468853114688528%" headers="mcps1.2.6.1.4 "><p id="p1598852011455"><a name="p1598852011455"></a><a name="p1598852011455"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="10.58894110588941%" headers="mcps1.2.6.1.5 "><p id="p1694472514507"><a name="p1694472514507"></a><a name="p1694472514507"></a>√</p>
</td>
</tr>
<tr id="row10640122017713"><td class="cellrowborder" valign="top" width="12.378762123787618%" headers="mcps1.2.6.1.1 "><p id="p3202154412714"><a name="p3202154412714"></a><a name="p3202154412714"></a>查询服务事务列表</p>
</td>
<td class="cellrowborder" valign="top" width="32.556744325567436%" headers="mcps1.2.6.1.2 "><p id="p13202174412710"><a name="p13202174412710"></a><a name="p13202174412710"></a>GET /v1/{project_id}/ats/applications/{application}/transactions</p>
</td>
<td class="cellrowborder" valign="top" width="33.006699330066986%" headers="mcps1.2.6.1.3 "><p id="p3202184412712"><a name="p3202184412712"></a><a name="p3202184412712"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="11.468853114688528%" headers="mcps1.2.6.1.4 "><p id="p1598822015453"><a name="p1598822015453"></a><a name="p1598822015453"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="10.58894110588941%" headers="mcps1.2.6.1.5 "><p id="p11944192510502"><a name="p11944192510502"></a><a name="p11944192510502"></a>√</p>
</td>
</tr>
<tr id="row1364016202710"><td class="cellrowborder" valign="top" width="12.378762123787618%" headers="mcps1.2.6.1.1 "><p id="p22025449718"><a name="p22025449718"></a><a name="p22025449718"></a>查询调用链</p>
</td>
<td class="cellrowborder" valign="top" width="32.556744325567436%" headers="mcps1.2.6.1.2 "><p id="p142025441170"><a name="p142025441170"></a><a name="p142025441170"></a>GET /v1/{project_id}/ats/traces</p>
</td>
<td class="cellrowborder" valign="top" width="33.006699330066986%" headers="mcps1.2.6.1.3 "><p id="p11202544176"><a name="p11202544176"></a><a name="p11202544176"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="11.468853114688528%" headers="mcps1.2.6.1.4 "><p id="p108401827114514"><a name="p108401827114514"></a><a name="p108401827114514"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="10.58894110588941%" headers="mcps1.2.6.1.5 "><p id="p1394432595019"><a name="p1394432595019"></a><a name="p1394432595019"></a>√</p>
</td>
</tr>
<tr id="row78719438467"><td class="cellrowborder" valign="top" width="12.378762123787618%" headers="mcps1.2.6.1.1 "><p id="p16993154916464"><a name="p16993154916464"></a><a name="p16993154916464"></a>查询调用链详情</p>
</td>
<td class="cellrowborder" valign="top" width="32.556744325567436%" headers="mcps1.2.6.1.2 "><p id="p1993164974615"><a name="p1993164974615"></a><a name="p1993164974615"></a>GET /v1/{project_id}/ats/spans</p>
</td>
<td class="cellrowborder" valign="top" width="33.006699330066986%" headers="mcps1.2.6.1.3 "><p id="p99938495463"><a name="p99938495463"></a><a name="p99938495463"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="11.468853114688528%" headers="mcps1.2.6.1.4 "><p id="p884032764511"><a name="p884032764511"></a><a name="p884032764511"></a>√</p>
</td>
<td class="cellrowborder" valign="top" width="10.58894110588941%" headers="mcps1.2.6.1.5 "><p id="p2944102514509"><a name="p2944102514509"></a><a name="p2944102514509"></a>√</p>
</td>
</tr>
</tbody>
</table>

