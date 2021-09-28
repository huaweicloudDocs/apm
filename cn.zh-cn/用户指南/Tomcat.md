# Tomcat<a name="apm_07_0047"></a>

**表 1**  Tomcat监控指标

<a name="table1598571516180"></a>
<table><thead align="left"><tr id="row18985111510187"><th class="cellrowborder" valign="top" width="12.67%" id="mcps1.2.6.1.1"><p id="p115791839191817"><a name="p115791839191817"></a><a name="p115791839191817"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="23.200000000000003%" id="mcps1.2.6.1.2"><p id="p14580133913187"><a name="p14580133913187"></a><a name="p14580133913187"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="13.059999999999999%" id="mcps1.2.6.1.3"><p id="p19580439181810"><a name="p19580439181810"></a><a name="p19580439181810"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="11.3%" id="mcps1.2.6.1.4"><p id="p1358014393183"><a name="p1358014393183"></a><a name="p1358014393183"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="39.77%" id="mcps1.2.6.1.5"><p id="p14580183910186"><a name="p14580183910186"></a><a name="p14580183910186"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row2985181531814"><td class="cellrowborder" valign="top" width="12.67%" headers="mcps1.2.6.1.1 "><p id="p498541517188"><a name="p498541517188"></a><a name="p498541517188"></a>tomcatInfo</p>
</td>
<td class="cellrowborder" valign="top" width="23.200000000000003%" headers="mcps1.2.6.1.2 "><p id="p7985615151820"><a name="p7985615151820"></a><a name="p7985615151820"></a>tomcatVersion</p>
</td>
<td class="cellrowborder" valign="top" width="13.059999999999999%" headers="mcps1.2.6.1.3 "><p id="p149869158181"><a name="p149869158181"></a><a name="p149869158181"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="11.3%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="39.77%" headers="mcps1.2.6.1.5 "><p id="p598631510181"><a name="p598631510181"></a><a name="p598631510181"></a>tomcat版本</p>
</td>
</tr>
<tr id="row2986161518189"><td class="cellrowborder" rowspan="8" valign="top" width="12.67%" headers="mcps1.2.6.1.1 "><p id="p99861315171815"><a name="p99861315171815"></a><a name="p99861315171815"></a></p>
<p id="p17986515171813"><a name="p17986515171813"></a><a name="p17986515171813"></a></p>
<p id="p59865153189"><a name="p59865153189"></a><a name="p59865153189"></a></p>
<p id="p59861159188"><a name="p59861159188"></a><a name="p59861159188"></a></p>
<p id="p6986415121817"><a name="p6986415121817"></a><a name="p6986415121817"></a>tomcat</p>
<p id="p59861115151810"><a name="p59861115151810"></a><a name="p59861115151810"></a></p>
<p id="p1480714910215"><a name="p1480714910215"></a><a name="p1480714910215"></a></p>
<p id="p180818492219"><a name="p180818492219"></a><a name="p180818492219"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.200000000000003%" headers="mcps1.2.6.1.2 "><p id="p39864153182"><a name="p39864153182"></a><a name="p39864153182"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="13.059999999999999%" headers="mcps1.2.6.1.3 "><p id="p898613154180"><a name="p898613154180"></a><a name="p898613154180"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="11.3%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="39.77%" headers="mcps1.2.6.1.5 "><p id="p1098601515184"><a name="p1098601515184"></a><a name="p1098601515184"></a>端口名称</p>
</td>
</tr>
<tr id="row0986131531817"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p898641561818"><a name="p898641561818"></a><a name="p898641561818"></a>currentThreadCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p198661591810"><a name="p198661591810"></a><a name="p198661591810"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p149866159187"><a name="p149866159187"></a><a name="p149866159187"></a>当前线程数</p>
</td>
</tr>
<tr id="row39861115131816"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p15986191510185"><a name="p15986191510185"></a><a name="p15986191510185"></a>currentThreadsBusy</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p129861515131812"><a name="p129861515131812"></a><a name="p129861515131812"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1198691591817"><a name="p1198691591817"></a><a name="p1198691591817"></a>采集时间点的繁忙线程数</p>
</td>
</tr>
<tr id="row398681517186"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p29861215121811"><a name="p29861215121811"></a><a name="p29861215121811"></a>currentThreadsBusyMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1794714212239"><a name="p1794714212239"></a><a name="p1794714212239"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1198611514185"><a name="p1198611514185"></a><a name="p1198611514185"></a>采集周期内的最大繁忙线程数</p>
</td>
</tr>
<tr id="row998613151181"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p149868153187"><a name="p149868153187"></a><a name="p149868153187"></a>maxThreads</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1594854216234"><a name="p1594854216234"></a><a name="p1594854216234"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p198617158182"><a name="p198617158182"></a><a name="p198617158182"></a>最大线程数容量</p>
</td>
</tr>
<tr id="row398621519181"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p169869159186"><a name="p169869159186"></a><a name="p169869159186"></a>maxConnections</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p10411446231"><a name="p10411446231"></a><a name="p10411446231"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p10433512142715"><a name="p10433512142715"></a><a name="p10433512142715"></a>最大连接数容量</p>
</td>
</tr>
<tr id="row11815104962118"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p12807104910216"><a name="p12807104910216"></a><a name="p12807104910216"></a>connectionCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p104119449231"><a name="p104119449231"></a><a name="p104119449231"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p0986121501816"><a name="p0986121501816"></a><a name="p0986121501816"></a>采集时间点的连接数</p>
</td>
</tr>
<tr id="row9815154918217"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p78081549152120"><a name="p78081549152120"></a><a name="p78081549152120"></a>connectionCountMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1580824914217"><a name="p1580824914217"></a><a name="p1580824914217"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p0809849172112"><a name="p0809849172112"></a><a name="p0809849172112"></a>采集周期内最大连接数</p>
</td>
</tr>
</tbody>
</table>

