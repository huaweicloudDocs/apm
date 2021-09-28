# Lettuce<a name="apm_07_0045"></a>

**表 1**  Lettuce基本信息监控指标

<a name="table1067418487369"></a>
<table><thead align="left"><tr id="row15674184833612"><th class="cellrowborder" valign="top" width="15.47%" id="mcps1.2.6.1.1"><p id="p156741248123613"><a name="p156741248123613"></a><a name="p156741248123613"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="22.720000000000002%" id="mcps1.2.6.1.2"><p id="p1767564811369"><a name="p1767564811369"></a><a name="p1767564811369"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="14.32%" id="mcps1.2.6.1.3"><p id="p19675348173616"><a name="p19675348173616"></a><a name="p19675348173616"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="12.44%" id="mcps1.2.6.1.4"><p id="p1167510488366"><a name="p1167510488366"></a><a name="p1167510488366"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="35.05%" id="mcps1.2.6.1.5"><p id="p1967584893620"><a name="p1967584893620"></a><a name="p1967584893620"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row5675194814368"><td class="cellrowborder" rowspan="3" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p1067534813366"><a name="p1067534813366"></a><a name="p1067534813366"></a></p>
<p id="p16676154843616"><a name="p16676154843616"></a><a name="p16676154843616"></a>clientInfo</p>
<p id="p176778486366"><a name="p176778486366"></a><a name="p176778486366"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.720000000000002%" headers="mcps1.2.6.1.2 "><p id="p2675124833618"><a name="p2675124833618"></a><a name="p2675124833618"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="14.32%" headers="mcps1.2.6.1.3 "><p id="p5676144813369"><a name="p5676144813369"></a><a name="p5676144813369"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="12.44%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.05%" headers="mcps1.2.6.1.5 "><p id="p267612485361"><a name="p267612485361"></a><a name="p267612485361"></a>客户端版本</p>
</td>
</tr>
<tr id="row6676248193615"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p467674810365"><a name="p467674810365"></a><a name="p467674810365"></a>mode</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p367674813611"><a name="p367674813611"></a><a name="p367674813611"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1267610489366"><a name="p1267610489366"></a><a name="p1267610489366"></a>redis运行模式（standalone、cluster）</p>
</td>
</tr>
<tr id="row7676048173612"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1467717486368"><a name="p1467717486368"></a><a name="p1467717486368"></a>nodes</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1767715480365"><a name="p1767715480365"></a><a name="p1767715480365"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p06775484361"><a name="p06775484361"></a><a name="p06775484361"></a>redis节点（只统计主节点）</p>
</td>
</tr>
<tr id="row166777481366"><td class="cellrowborder" rowspan="3" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p9677164833616"><a name="p9677164833616"></a><a name="p9677164833616"></a></p>
<p id="p1667874843615"><a name="p1667874843615"></a><a name="p1667874843615"></a>switch</p>
<p id="p96799485365"><a name="p96799485365"></a><a name="p96799485365"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.720000000000002%" headers="mcps1.2.6.1.2 "><p id="p467754814365"><a name="p467754814365"></a><a name="p467754814365"></a>from</p>
</td>
<td class="cellrowborder" valign="top" width="14.32%" headers="mcps1.2.6.1.3 "><p id="p46771148133614"><a name="p46771148133614"></a><a name="p46771148133614"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="12.44%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.05%" headers="mcps1.2.6.1.5 "><p id="p126784481364"><a name="p126784481364"></a><a name="p126784481364"></a>原主机</p>
</td>
</tr>
<tr id="row13678748133611"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p13678194816364"><a name="p13678194816364"></a><a name="p13678194816364"></a>to</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16678154816367"><a name="p16678154816367"></a><a name="p16678154816367"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p16787483363"><a name="p16787483363"></a><a name="p16787483363"></a>目标主机</p>
</td>
</tr>
<tr id="row3679144893615"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p56795484369"><a name="p56795484369"></a><a name="p56795484369"></a>switchTimes</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1767944823616"><a name="p1767944823616"></a><a name="p1767944823616"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p4679144817366"><a name="p4679144817366"></a><a name="p4679144817366"></a>切换次数</p>
</td>
</tr>
</tbody>
</table>

