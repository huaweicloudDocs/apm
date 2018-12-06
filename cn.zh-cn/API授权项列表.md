# API授权项列表<a name="apm_04_0021"></a>

此功能目前仅对华北、华东、华南区域开放。

**表 1**  API授权项列表

<a name="table1864042012710"></a>
<table><thead align="left"><tr id="row9640182017711"><th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.1"><p id="p617114417716"><a name="p617114417716"></a><a name="p617114417716"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="24.67%" id="mcps1.2.5.1.2"><p id="p1217184416710"><a name="p1217184416710"></a><a name="p1217184416710"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="25.330000000000002%" id="mcps1.2.5.1.3"><p id="p2171344272"><a name="p2171344272"></a><a name="p2171344272"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="25%" id="mcps1.2.5.1.4"><p id="p121711944272"><a name="p121711944272"></a><a name="p121711944272"></a>授权作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row106401620675"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p12171164418717"><a name="p12171164418717"></a><a name="p12171164418717"></a>GET /v1/{projectId}/atps/monitorgroups</p>
</td>
<td class="cellrowborder" valign="top" width="24.67%" headers="mcps1.2.5.1.2 "><p id="p9171134415718"><a name="p9171134415718"></a><a name="p9171134415718"></a>查询应用列表</p>
</td>
<td class="cellrowborder" valign="top" width="25.330000000000002%" headers="mcps1.2.5.1.3 "><p id="p1817194420719"><a name="p1817194420719"></a><a name="p1817194420719"></a>apm:inventory:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.4 "><a name="ul10187044177"></a><a name="ul10187044177"></a><ul id="ul10187044177"><li>支持：项目(Project)</li></ul>
<a name="ul15187184412711"></a><a name="ul15187184412711"></a><ul id="ul15187184412711"><li>不支持：企业项目(Enterprise Project)</li></ul>
</td>
</tr>
<tr id="row12640122016713"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p161872441671"><a name="p161872441671"></a><a name="p161872441671"></a>GET /v1/{projectId}/ats/applications</p>
</td>
<td class="cellrowborder" valign="top" width="24.67%" headers="mcps1.2.5.1.2 "><p id="p918710449710"><a name="p918710449710"></a><a name="p918710449710"></a>查询服务列表</p>
</td>
<td class="cellrowborder" valign="top" width="25.330000000000002%" headers="mcps1.2.5.1.3 "><p id="p1818734415710"><a name="p1818734415710"></a><a name="p1818734415710"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.4 "><a name="ul11187444872"></a><a name="ul11187444872"></a><ul id="ul11187444872"><li>支持：项目(Project)</li></ul>
<a name="ul7187944171"></a><a name="ul7187944171"></a><ul id="ul7187944171"><li>不支持：企业项目(Enterprise Project)</li></ul>
</td>
</tr>
<tr id="row116401220173"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p618719446712"><a name="p618719446712"></a><a name="p618719446712"></a>GET /v1/{projectId}/ats/applications/{application}/instances</p>
</td>
<td class="cellrowborder" valign="top" width="24.67%" headers="mcps1.2.5.1.2 "><p id="p18187344173"><a name="p18187344173"></a><a name="p18187344173"></a>查询服务实例列表</p>
</td>
<td class="cellrowborder" valign="top" width="25.330000000000002%" headers="mcps1.2.5.1.3 "><p id="p3187154410716"><a name="p3187154410716"></a><a name="p3187154410716"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.4 "><a name="ul81874441679"></a><a name="ul81874441679"></a><ul id="ul81874441679"><li>支持：项目(Project)</li></ul>
<a name="ul11871441071"></a><a name="ul11871441071"></a><ul id="ul11871441071"><li>不支持：企业项目(Enterprise Project)</li></ul>
</td>
</tr>
<tr id="row10640122017713"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p13202174412710"><a name="p13202174412710"></a><a name="p13202174412710"></a>GET /v1/{projectId}/ats/applications/{application}/transactions</p>
</td>
<td class="cellrowborder" valign="top" width="24.67%" headers="mcps1.2.5.1.2 "><p id="p3202154412714"><a name="p3202154412714"></a><a name="p3202154412714"></a>查询服务事务列表</p>
</td>
<td class="cellrowborder" valign="top" width="25.330000000000002%" headers="mcps1.2.5.1.3 "><p id="p3202184412712"><a name="p3202184412712"></a><a name="p3202184412712"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.4 "><a name="ul1120213447712"></a><a name="ul1120213447712"></a><ul id="ul1120213447712"><li>支持：项目(Project)</li></ul>
<a name="ul1720244420718"></a><a name="ul1720244420718"></a><ul id="ul1720244420718"><li>不支持：企业项目(Enterprise Project)</li></ul>
</td>
</tr>
<tr id="row1364016202710"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p142025441170"><a name="p142025441170"></a><a name="p142025441170"></a>GET /v1/{projectId}/ats/traces</p>
</td>
<td class="cellrowborder" valign="top" width="24.67%" headers="mcps1.2.5.1.2 "><p id="p22025449718"><a name="p22025449718"></a><a name="p22025449718"></a>查询调用链</p>
</td>
<td class="cellrowborder" valign="top" width="25.330000000000002%" headers="mcps1.2.5.1.3 "><p id="p11202544176"><a name="p11202544176"></a><a name="p11202544176"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.4 "><a name="ul102021444878"></a><a name="ul102021444878"></a><ul id="ul102021444878"><li>支持：项目(Project)</li></ul>
<a name="ul821884410719"></a><a name="ul821884410719"></a><ul id="ul821884410719"><li>不支持：企业项目(Enterprise Project)</li></ul>
</td>
</tr>
<tr id="row78719438467"><td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.1 "><p id="p1993164974615"><a name="p1993164974615"></a><a name="p1993164974615"></a>GET /v1/{projectId}/ats/spans</p>
</td>
<td class="cellrowborder" valign="top" width="24.67%" headers="mcps1.2.5.1.2 "><p id="p16993154916464"><a name="p16993154916464"></a><a name="p16993154916464"></a>查询调用链详情</p>
</td>
<td class="cellrowborder" valign="top" width="25.330000000000002%" headers="mcps1.2.5.1.3 "><p id="p99938495463"><a name="p99938495463"></a><a name="p99938495463"></a>apm:ats:get</p>
</td>
<td class="cellrowborder" valign="top" width="25%" headers="mcps1.2.5.1.4 "><a name="ul1199311494462"></a><a name="ul1199311494462"></a><ul id="ul1199311494462"><li>支持：项目(Project)</li></ul>
<a name="ul399319499464"></a><a name="ul399319499464"></a><ul id="ul399319499464"><li>不支持：企业项目(Enterprise Project)</li></ul>
</td>
</tr>
</tbody>
</table>

