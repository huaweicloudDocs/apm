# ApacheHttpClient<a name="apm_07_0040"></a>

**表 1**  ApacheHttpClient连接池监控指标

<a name="table123816350211"></a>
<table><thead align="left"><tr id="row7381035182117"><th class="cellrowborder" valign="top" width="22.93%" id="mcps1.2.6.1.1"><p id="p12479112916258"><a name="p12479112916258"></a><a name="p12479112916258"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="14.93%" id="mcps1.2.6.1.2"><p id="p1948014299256"><a name="p1948014299256"></a><a name="p1948014299256"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="13.87%" id="mcps1.2.6.1.3"><p id="p1348014297254"><a name="p1348014297254"></a><a name="p1348014297254"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="11.959999999999999%" id="mcps1.2.6.1.4"><p id="p848082912257"><a name="p848082912257"></a><a name="p848082912257"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="36.309999999999995%" id="mcps1.2.6.1.5"><p id="p64806293253"><a name="p64806293253"></a><a name="p64806293253"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row439163532113"><td class="cellrowborder" rowspan="5" valign="top" width="22.93%" headers="mcps1.2.6.1.1 "><p id="p93973522119"><a name="p93973522119"></a><a name="p93973522119"></a></p>
<p id="p93983542111"><a name="p93983542111"></a><a name="p93983542111"></a></p>
<p id="p11395357212"><a name="p11395357212"></a><a name="p11395357212"></a>connectionPool</p>
<p id="p43913515217"><a name="p43913515217"></a><a name="p43913515217"></a></p>
<p id="p939133517214"><a name="p939133517214"></a><a name="p939133517214"></a></p>
</td>
<td class="cellrowborder" valign="top" width="14.93%" headers="mcps1.2.6.1.2 "><p id="p19391352214"><a name="p19391352214"></a><a name="p19391352214"></a>poolId</p>
</td>
<td class="cellrowborder" valign="top" width="13.87%" headers="mcps1.2.6.1.3 "><p id="p739103572114"><a name="p739103572114"></a><a name="p739103572114"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="11.959999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.309999999999995%" headers="mcps1.2.6.1.5 "><p id="p3395356212"><a name="p3395356212"></a><a name="p3395356212"></a>连接池id</p>
</td>
</tr>
<tr id="row439133517214"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p43918355215"><a name="p43918355215"></a><a name="p43918355215"></a>available</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p439193512217"><a name="p439193512217"></a><a name="p439193512217"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p439173510219"><a name="p439173510219"></a><a name="p439173510219"></a>空闲连接数</p>
</td>
</tr>
<tr id="row639123518217"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p153913522114"><a name="p153913522114"></a><a name="p153913522114"></a>leased</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p153973518219"><a name="p153973518219"></a><a name="p153973518219"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p143913516219"><a name="p143913516219"></a><a name="p143913516219"></a>占用连接数</p>
</td>
</tr>
<tr id="row739133522119"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p139635132117"><a name="p139635132117"></a><a name="p139635132117"></a>max</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7172124393012"><a name="p7172124393012"></a><a name="p7172124393012"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p19391535122115"><a name="p19391535122115"></a><a name="p19391535122115"></a>最大连接数</p>
</td>
</tr>
<tr id="row139535162116"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1639235182115"><a name="p1639235182115"></a><a name="p1639235182115"></a>pending</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9172184363017"><a name="p9172184363017"></a><a name="p9172184363017"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p83911358211"><a name="p83911358211"></a><a name="p83911358211"></a>正在连接数</p>
</td>
</tr>
<tr id="row1781517416277"><td class="cellrowborder" rowspan="6" valign="top" width="22.93%" headers="mcps1.2.6.1.1 "><p id="p1981314182715"><a name="p1981314182715"></a><a name="p1981314182715"></a></p>
<p id="p7355104416270"><a name="p7355104416270"></a><a name="p7355104416270"></a></p>
<p id="p19355114414271"><a name="p19355114414271"></a><a name="p19355114414271"></a></p>
<p id="p115631746102710"><a name="p115631746102710"></a><a name="p115631746102710"></a>connectionPoolRoute</p>
<p id="p656434612272"><a name="p656434612272"></a><a name="p656434612272"></a></p>
<p id="p656484652719"><a name="p656484652719"></a><a name="p656484652719"></a></p>
</td>
<td class="cellrowborder" valign="top" width="14.93%" headers="mcps1.2.6.1.2 "><p id="p181319412276"><a name="p181319412276"></a><a name="p181319412276"></a>poolId</p>
</td>
<td class="cellrowborder" valign="top" width="13.87%" headers="mcps1.2.6.1.3 "><p id="p581384113279"><a name="p581384113279"></a><a name="p581384113279"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="11.959999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.309999999999995%" headers="mcps1.2.6.1.5 "><p id="p3813204122714"><a name="p3813204122714"></a><a name="p3813204122714"></a>连接池id</p>
</td>
</tr>
<tr id="row12359154419273"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p73554445276"><a name="p73554445276"></a><a name="p73554445276"></a>route</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p18355344182713"><a name="p18355344182713"></a><a name="p18355344182713"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1355164472713"><a name="p1355164472713"></a><a name="p1355164472713"></a>路由信息</p>
</td>
</tr>
<tr id="row3358164462718"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p5355444152717"><a name="p5355444152717"></a><a name="p5355444152717"></a>available</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p17402164553010"><a name="p17402164553010"></a><a name="p17402164553010"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p196227012344"><a name="p196227012344"></a><a name="p196227012344"></a>空闲连接数</p>
</td>
</tr>
<tr id="row457174632719"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1171832182814"><a name="p1171832182814"></a><a name="p1171832182814"></a>leased</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9402124511309"><a name="p9402124511309"></a><a name="p9402124511309"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p15622403342"><a name="p15622403342"></a><a name="p15622403342"></a>占用连接数</p>
</td>
</tr>
<tr id="row357124611276"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1271432132815"><a name="p1271432132815"></a><a name="p1271432132815"></a>max</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p144025456304"><a name="p144025456304"></a><a name="p144025456304"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p56221901343"><a name="p56221901343"></a><a name="p56221901343"></a>最大连接数</p>
</td>
</tr>
<tr id="row75701146162713"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p9716328283"><a name="p9716328283"></a><a name="p9716328283"></a>pending</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1940213452305"><a name="p1940213452305"></a><a name="p1940213452305"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1062290183417"><a name="p1062290183417"></a><a name="p1062290183417"></a>正在连接数</p>
</td>
</tr>
</tbody>
</table>

