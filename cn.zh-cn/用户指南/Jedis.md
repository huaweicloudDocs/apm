# Jedis<a name="apm_07_0044"></a>

**表 1**  Jedis连接池监控指标

<a name="table74819143516"></a>
<table><thead align="left"><tr id="row1552019173518"><th class="cellrowborder" valign="top" width="16%" id="mcps1.2.6.1.1"><p id="p13874530193511"><a name="p13874530193511"></a><a name="p13874530193511"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="23.39%" id="mcps1.2.6.1.2"><p id="p15874130183516"><a name="p15874130183516"></a><a name="p15874130183516"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="12.32%" id="mcps1.2.6.1.3"><p id="p387453093513"><a name="p387453093513"></a><a name="p387453093513"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="13.03%" id="mcps1.2.6.1.4"><p id="p11874230143513"><a name="p11874230143513"></a><a name="p11874230143513"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="35.260000000000005%" id="mcps1.2.6.1.5"><p id="p198748303356"><a name="p198748303356"></a><a name="p198748303356"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row1851119173513"><td class="cellrowborder" rowspan="14" valign="top" width="16%" headers="mcps1.2.6.1.1 "><p id="p165161983519"><a name="p165161983519"></a><a name="p165161983519"></a></p>
<p id="p135141911355"><a name="p135141911355"></a><a name="p135141911355"></a></p>
<p id="p12513196355"><a name="p12513196355"></a><a name="p12513196355"></a></p>
<p id="p95101915356"><a name="p95101915356"></a><a name="p95101915356"></a></p>
<p id="p2051619153517"><a name="p2051619153517"></a><a name="p2051619153517"></a></p>
<p id="p25151915359"><a name="p25151915359"></a><a name="p25151915359"></a></p>
<p id="p115319123512"><a name="p115319123512"></a><a name="p115319123512"></a></p>
<p id="p101531549153515"><a name="p101531549153515"></a><a name="p101531549153515"></a>jedisPool</p>
<p id="p315314912352"><a name="p315314912352"></a><a name="p315314912352"></a></p>
<p id="p1615304963516"><a name="p1615304963516"></a><a name="p1615304963516"></a></p>
<p id="p1715384913355"><a name="p1715384913355"></a><a name="p1715384913355"></a></p>
<p id="p3153164918356"><a name="p3153164918356"></a><a name="p3153164918356"></a></p>
<p id="p415404923510"><a name="p415404923510"></a><a name="p415404923510"></a></p>
<p id="p4154649173515"><a name="p4154649173515"></a><a name="p4154649173515"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.39%" headers="mcps1.2.6.1.2 "><p id="p3581919359"><a name="p3581919359"></a><a name="p3581919359"></a>pool</p>
</td>
<td class="cellrowborder" valign="top" width="12.32%" headers="mcps1.2.6.1.3 "><p id="p105171983517"><a name="p105171983517"></a><a name="p105171983517"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.260000000000005%" headers="mcps1.2.6.1.5 "><p id="p05121933517"><a name="p05121933517"></a><a name="p05121933517"></a>连接池唯一标识（主机名+端口）</p>
</td>
</tr>
<tr id="row175151918358"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1511910353"><a name="p1511910353"></a><a name="p1511910353"></a>maxTotal</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1659190352"><a name="p1659190352"></a><a name="p1659190352"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p175201912353"><a name="p175201912353"></a><a name="p175201912353"></a>最大连接数</p>
</td>
</tr>
<tr id="row1251019193511"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p65151915353"><a name="p65151915353"></a><a name="p65151915353"></a>maxIdle</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7541912358"><a name="p7541912358"></a><a name="p7541912358"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p451619113515"><a name="p451619113515"></a><a name="p451619113515"></a>最大空闲数</p>
</td>
</tr>
<tr id="row105171983510"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1501912358"><a name="p1501912358"></a><a name="p1501912358"></a>minIdle</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p121464844211"><a name="p121464844211"></a><a name="p121464844211"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p195151918352"><a name="p195151918352"></a><a name="p195151918352"></a>最小空闲数</p>
</td>
</tr>
<tr id="row12511191356"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p145121963515"><a name="p145121963515"></a><a name="p145121963515"></a>numActive</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p171414481427"><a name="p171414481427"></a><a name="p171414481427"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p14591943519"><a name="p14591943519"></a><a name="p14591943519"></a>当前激活个数</p>
</td>
</tr>
<tr id="row75151923518"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1553194355"><a name="p1553194355"></a><a name="p1553194355"></a>numIdle</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9263105013426"><a name="p9263105013426"></a><a name="p9263105013426"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p251119163512"><a name="p251119163512"></a><a name="p251119163512"></a>当前空闲个数</p>
</td>
</tr>
<tr id="row115171933515"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p153191356"><a name="p153191356"></a><a name="p153191356"></a>numWaiters</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p192635504426"><a name="p192635504426"></a><a name="p192635504426"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p351319113518"><a name="p351319113518"></a><a name="p351319113518"></a>等待个数</p>
</td>
</tr>
<tr id="row815784918359"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p121571649153515"><a name="p121571649153515"></a><a name="p121571649153515"></a>createdCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p142630507428"><a name="p142630507428"></a><a name="p142630507428"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1215734916352"><a name="p1215734916352"></a><a name="p1215734916352"></a>创建个数</p>
</td>
</tr>
<tr id="row7157124911356"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p5156749133518"><a name="p5156749133518"></a><a name="p5156749133518"></a>destroyedCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p626315074217"><a name="p626315074217"></a><a name="p626315074217"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p16156149203519"><a name="p16156149203519"></a><a name="p16156149203519"></a>销毁个数</p>
</td>
</tr>
<tr id="row3157449113516"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p8156164943514"><a name="p8156164943514"></a><a name="p8156164943514"></a>borrowedCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1211445494217"><a name="p1211445494217"></a><a name="p1211445494217"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1215634917358"><a name="p1215634917358"></a><a name="p1215634917358"></a>borrow个数</p>
</td>
</tr>
<tr id="row20157134923514"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4156164923518"><a name="p4156164923518"></a><a name="p4156164923518"></a>maxWaitMillis</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7115135416429"><a name="p7115135416429"></a><a name="p7115135416429"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p41566495352"><a name="p41566495352"></a><a name="p41566495352"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p2156249173514"><a name="p2156249173514"></a><a name="p2156249173514"></a>最大等待时间</p>
</td>
</tr>
<tr id="row615715492359"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p171568499357"><a name="p171568499357"></a><a name="p171568499357"></a>maxBorrowWaitTimeMillis</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p311565444216"><a name="p311565444216"></a><a name="p311565444216"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p7156134912350"><a name="p7156134912350"></a><a name="p7156134912350"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p11562049103512"><a name="p11562049103512"></a><a name="p11562049103512"></a>borrow最大等待时间</p>
</td>
</tr>
<tr id="row1315744916355"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1515614920355"><a name="p1515614920355"></a><a name="p1515614920355"></a>meanActiveTimeMillis</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p688035614429"><a name="p688035614429"></a><a name="p688035614429"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p11156124915358"><a name="p11156124915358"></a><a name="p11156124915358"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p8156154983519"><a name="p8156154983519"></a><a name="p8156154983519"></a>平均激活时间</p>
</td>
</tr>
<tr id="row71579494359"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1915613493359"><a name="p1915613493359"></a><a name="p1915613493359"></a>meanBorrowWaitTimeMillis</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p5880105664218"><a name="p5880105664218"></a><a name="p5880105664218"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p7156649193515"><a name="p7156649193515"></a><a name="p7156649193515"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p315654913356"><a name="p315654913356"></a><a name="p315654913356"></a>平均borrow等待时间</p>
</td>
</tr>
<tr id="row1698145043510"><td class="cellrowborder" rowspan="3" valign="top" width="16%" headers="mcps1.2.6.1.1 "><p id="p196944500357"><a name="p196944500357"></a><a name="p196944500357"></a></p>
<p id="p19695750153518"><a name="p19695750153518"></a><a name="p19695750153518"></a>clientInfo</p>
<p id="p11695165073517"><a name="p11695165073517"></a><a name="p11695165073517"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.39%" headers="mcps1.2.6.1.2 "><p id="p4697185011354"><a name="p4697185011354"></a><a name="p4697185011354"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="12.32%" headers="mcps1.2.6.1.3 "><p id="p26972050143515"><a name="p26972050143515"></a><a name="p26972050143515"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.260000000000005%" headers="mcps1.2.6.1.5 "><p id="p1269714504356"><a name="p1269714504356"></a><a name="p1269714504356"></a>客户端版本</p>
</td>
</tr>
<tr id="row17698145093520"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p46971250183513"><a name="p46971250183513"></a><a name="p46971250183513"></a>mode</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p8697195020355"><a name="p8697195020355"></a><a name="p8697195020355"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p46973504350"><a name="p46973504350"></a><a name="p46973504350"></a>redis运行模式（standalone、cluster）</p>
</td>
</tr>
<tr id="row669895012357"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p13697155019359"><a name="p13697155019359"></a><a name="p13697155019359"></a>nodes</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p2697115043515"><a name="p2697115043515"></a><a name="p2697115043515"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1697750113514"><a name="p1697750113514"></a><a name="p1697750113514"></a>redis节点（只统计主节点）</p>
</td>
</tr>
<tr id="row156983505356"><td class="cellrowborder" rowspan="3" valign="top" width="16%" headers="mcps1.2.6.1.1 "><p id="p15695165015351"><a name="p15695165015351"></a><a name="p15695165015351"></a></p>
<p id="p1469565093519"><a name="p1469565093519"></a><a name="p1469565093519"></a>switch</p>
<p id="p1169575033517"><a name="p1169575033517"></a><a name="p1169575033517"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.39%" headers="mcps1.2.6.1.2 "><p id="p669785010354"><a name="p669785010354"></a><a name="p669785010354"></a>from</p>
</td>
<td class="cellrowborder" valign="top" width="12.32%" headers="mcps1.2.6.1.3 "><p id="p6697135043510"><a name="p6697135043510"></a><a name="p6697135043510"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.260000000000005%" headers="mcps1.2.6.1.5 "><p id="p11697205093519"><a name="p11697205093519"></a><a name="p11697205093519"></a>原主机</p>
</td>
</tr>
<tr id="row7698125015359"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p10697450203510"><a name="p10697450203510"></a><a name="p10697450203510"></a>to</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p969735063513"><a name="p969735063513"></a><a name="p969735063513"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p146971050133512"><a name="p146971050133512"></a><a name="p146971050133512"></a>目标主机</p>
</td>
</tr>
<tr id="row86983501358"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1769713502356"><a name="p1769713502356"></a><a name="p1769713502356"></a>switchTimes</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9697350143514"><a name="p9697350143514"></a><a name="p9697350143514"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p869785017352"><a name="p869785017352"></a><a name="p869785017352"></a>切换次数</p>
</td>
</tr>
</tbody>
</table>

