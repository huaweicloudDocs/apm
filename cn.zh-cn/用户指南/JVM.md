# JVM<a name="apm_07_0033"></a>

**表 1**  JVM相关的基础监控指标

<a name="table173769321116"></a>
<table><thead align="left"><tr id="row123769321417"><th class="cellrowborder" valign="top" width="10.05%" id="mcps1.2.6.1.1"><p id="p53762322111"><a name="p53762322111"></a><a name="p53762322111"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="24.93%" id="mcps1.2.6.1.2"><p id="p20377333836"><a name="p20377333836"></a><a name="p20377333836"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="12.13%" id="mcps1.2.6.1.3"><p id="p43766321511"><a name="p43766321511"></a><a name="p43766321511"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="10.549999999999999%" id="mcps1.2.6.1.4"><p id="p16376113219112"><a name="p16376113219112"></a><a name="p16376113219112"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="42.34%" id="mcps1.2.6.1.5"><p id="p1337616321311"><a name="p1337616321311"></a><a name="p1337616321311"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row23776321114"><td class="cellrowborder" rowspan="3" valign="top" width="10.05%" headers="mcps1.2.6.1.1 "><p id="p11377832116"><a name="p11377832116"></a><a name="p11377832116"></a></p>
<p id="p1937714321417"><a name="p1937714321417"></a><a name="p1937714321417"></a>classLoading</p>
<p id="p8377103215112"><a name="p8377103215112"></a><a name="p8377103215112"></a></p>
</td>
<td class="cellrowborder" valign="top" width="24.93%" headers="mcps1.2.6.1.2 "><p id="p16377103212114"><a name="p16377103212114"></a><a name="p16377103212114"></a>loadedClassCount</p>
</td>
<td class="cellrowborder" valign="top" width="12.13%" headers="mcps1.2.6.1.3 "><p id="p15377432811"><a name="p15377432811"></a><a name="p15377432811"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" width="10.549999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="42.34%" headers="mcps1.2.6.1.5 "><p id="p14377123212114"><a name="p14377123212114"></a><a name="p14377123212114"></a><span>采集周期内加载的类的个数</span></p>
</td>
</tr>
<tr id="row1137714325119"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p13778321110"><a name="p13778321110"></a><a name="p13778321110"></a>totalLoadedClassCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p837712321610"><a name="p837712321610"></a><a name="p837712321610"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p13377153211112"><a name="p13377153211112"></a><a name="p13377153211112"></a><span>总共加载的类的个数</span></p>
</td>
</tr>
<tr id="row143771432814"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p33771932814"><a name="p33771932814"></a><a name="p33771932814"></a>unloadedClassCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p73777323111"><a name="p73777323111"></a><a name="p73777323111"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1237717327115"><a name="p1237717327115"></a><a name="p1237717327115"></a><span>采集周期内卸载的类的个数</span></p>
</td>
</tr>
<tr id="row53775329112"><td class="cellrowborder" rowspan="2" valign="top" width="10.05%" headers="mcps1.2.6.1.1 "><p id="p1637718325114"><a name="p1637718325114"></a><a name="p1637718325114"></a>compile</p>
<p id="p61761036111010"><a name="p61761036111010"></a><a name="p61761036111010"></a></p>
</td>
<td class="cellrowborder" valign="top" width="24.93%" headers="mcps1.2.6.1.2 "><p id="p837711323116"><a name="p837711323116"></a><a name="p837711323116"></a>compilationTime</p>
</td>
<td class="cellrowborder" valign="top" width="12.13%" headers="mcps1.2.6.1.3 "><p id="p03776329113"><a name="p03776329113"></a><a name="p03776329113"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" width="10.549999999999999%" headers="mcps1.2.6.1.4 "><p id="p13772321618"><a name="p13772321618"></a><a name="p13772321618"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" width="42.34%" headers="mcps1.2.6.1.5 "><p id="p183776321011"><a name="p183776321011"></a><a name="p183776321011"></a><span>采集周期内</span><span>的编译时间</span></p>
</td>
</tr>
<tr id="row3549203181017"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p135504310107"><a name="p135504310107"></a><a name="p135504310107"></a>totalCompilationTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1955013113103"><a name="p1955013113103"></a><a name="p1955013113103"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p0550133121016"><a name="p0550133121016"></a><a name="p0550133121016"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p75501431161014"><a name="p75501431161014"></a><a name="p75501431161014"></a><span>总编译时间</span></p>
</td>
</tr>
<tr id="row1037719321719"><td class="cellrowborder" rowspan="6" valign="top" width="10.05%" headers="mcps1.2.6.1.1 "><p id="p1759725618104"><a name="p1759725618104"></a><a name="p1759725618104"></a></p>
<p id="p74681658111013"><a name="p74681658111013"></a><a name="p74681658111013"></a></p>
<p id="p55321209115"><a name="p55321209115"></a><a name="p55321209115"></a></p>
<p id="p1917720364100"><a name="p1917720364100"></a><a name="p1917720364100"></a>cpu</p>
<p id="p17654174121112"><a name="p17654174121112"></a><a name="p17654174121112"></a></p>
</td>
<td class="cellrowborder" valign="top" width="24.93%" headers="mcps1.2.6.1.2 "><p id="p113774321913"><a name="p113774321913"></a><a name="p113774321913"></a>cpuRatio</p>
</td>
<td class="cellrowborder" valign="top" width="12.13%" headers="mcps1.2.6.1.3 "><p id="p83772324118"><a name="p83772324118"></a><a name="p83772324118"></a>DOUBLE</p>
</td>
<td class="cellrowborder" valign="top" width="10.549999999999999%" headers="mcps1.2.6.1.4 "><p id="p23778321015"><a name="p23778321015"></a><a name="p23778321015"></a>%</p>
</td>
<td class="cellrowborder" valign="top" width="42.34%" headers="mcps1.2.6.1.5 "><p id="p173771932216"><a name="p173771932216"></a><a name="p173771932216"></a><span>cpu利用率</span></p>
</td>
</tr>
<tr id="row0597125612109"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p059745614102"><a name="p059745614102"></a><a name="p059745614102"></a>cpuRatioMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p859785631019"><a name="p859785631019"></a><a name="p859785631019"></a>DOUBLE</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p3597156161013"><a name="p3597156161013"></a><a name="p3597156161013"></a>%</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p259711565103"><a name="p259711565103"></a><a name="p259711565103"></a>采集<span>周期内最大的cpu利用率</span></p>
</td>
</tr>
<tr id="row1546895815101"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p10468105817105"><a name="p10468105817105"></a><a name="p10468105817105"></a>cpuTimeInterval</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9468165891017"><a name="p9468165891017"></a><a name="p9468165891017"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p1946810583101"><a name="p1946810583101"></a><a name="p1946810583101"></a>ns</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1446835816106"><a name="p1446835816106"></a><a name="p1446835816106"></a><span>采集间隔内cpu使用的时间</span></p>
</td>
</tr>
<tr id="row1253215051119"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p6532307113"><a name="p6532307113"></a><a name="p6532307113"></a>processorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p253260141116"><a name="p253260141116"></a><a name="p253260141116"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p55325013119"><a name="p55325013119"></a><a name="p55325013119"></a><span>处理器个数</span></p>
</td>
</tr>
<tr id="row27561271117"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p675612281117"><a name="p675612281117"></a><a name="p675612281117"></a>systemTimeInterval</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p675610251114"><a name="p675610251114"></a><a name="p675610251114"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p2689203616160"><a name="p2689203616160"></a><a name="p2689203616160"></a>ns</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p175613261113"><a name="p175613261113"></a><a name="p175613261113"></a>采集周期</p>
</td>
</tr>
<tr id="row165412441115"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p16654124181119"><a name="p16654124181119"></a><a name="p16654124181119"></a>totalCpuTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16654174111115"><a name="p16654174111115"></a><a name="p16654174111115"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p129683719166"><a name="p129683719166"></a><a name="p129683719166"></a>ns</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p06541441118"><a name="p06541441118"></a><a name="p06541441118"></a><span>cpu使用总时间</span></p>
</td>
</tr>
<tr id="row1945314691111"><td class="cellrowborder" rowspan="5" valign="top" width="10.05%" headers="mcps1.2.6.1.1 "><p id="p1330811811117"><a name="p1330811811117"></a><a name="p1330811811117"></a></p>
<p id="p12264143111911"><a name="p12264143111911"></a><a name="p12264143111911"></a></p>
<p id="p10453865116"><a name="p10453865116"></a><a name="p10453865116"></a>memory</p>
<p id="p01688471199"><a name="p01688471199"></a><a name="p01688471199"></a></p>
</td>
<td class="cellrowborder" valign="top" width="24.93%" headers="mcps1.2.6.1.2 "><p id="p204534661119"><a name="p204534661119"></a><a name="p204534661119"></a>directMemoryUsage</p>
</td>
<td class="cellrowborder" valign="top" width="12.13%" headers="mcps1.2.6.1.3 "><p id="p9453116171112"><a name="p9453116171112"></a><a name="p9453116171112"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" width="10.549999999999999%" headers="mcps1.2.6.1.4 "><p id="p545313617114"><a name="p545313617114"></a><a name="p545313617114"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" width="42.34%" headers="mcps1.2.6.1.5 "><p id="p845315620111"><a name="p845315620111"></a><a name="p845315620111"></a>直接内存使用大小</p>
</td>
</tr>
<tr id="row33081813112"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p163084817111"><a name="p163084817111"></a><a name="p163084817111"></a>directMemoryCapacity</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p173089881115"><a name="p173089881115"></a><a name="p173089881115"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p203086814110"><a name="p203086814110"></a><a name="p203086814110"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p0466113813287"><a name="p0466113813287"></a><a name="p0466113813287"></a>总直接内存容量</p>
</td>
</tr>
<tr id="row15264164312193"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4264164331916"><a name="p4264164331916"></a><a name="p4264164331916"></a>heapMemoryUsage</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p2026454381910"><a name="p2026454381910"></a><a name="p2026454381910"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p52640434194"><a name="p52640434194"></a><a name="p52640434194"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1117619917221"><a name="p1117619917221"></a><a name="p1117619917221"></a><span>堆内存使用的大小</span></p>
</td>
</tr>
<tr id="row18224174521916"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1224104514191"><a name="p1224104514191"></a><a name="p1224104514191"></a>nonHeapMemoryUsage</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1622412459198"><a name="p1622412459198"></a><a name="p1622412459198"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p0224184515194"><a name="p0224184515194"></a><a name="p0224184515194"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p182241745151914"><a name="p182241745151914"></a><a name="p182241745151914"></a><span>非堆内存的使用大小</span></p>
</td>
</tr>
<tr id="row161677478194"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p171686472195"><a name="p171686472195"></a><a name="p171686472195"></a>objectPendingFinalizationCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1416810472199"><a name="p1416810472199"></a><a name="p1416810472199"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1816854711912"><a name="p1816854711912"></a><a name="p1816854711912"></a><span>采集时间点正在回收对象的个数</span></p>
</td>
</tr>
<tr id="row128855742313"><td class="cellrowborder" rowspan="5" valign="top" width="10.05%" headers="mcps1.2.6.1.1 "><p id="p828965720237"><a name="p828965720237"></a><a name="p828965720237"></a></p>
<p id="p117101159102315"><a name="p117101159102315"></a><a name="p117101159102315"></a></p>
<p id="p374115172412"><a name="p374115172412"></a><a name="p374115172412"></a>memoryPool</p>
<p id="p1615415241"><a name="p1615415241"></a><a name="p1615415241"></a></p>
<p id="p99721351244"><a name="p99721351244"></a><a name="p99721351244"></a></p>
</td>
<td class="cellrowborder" valign="top" width="24.93%" headers="mcps1.2.6.1.2 "><p id="p02891557182316"><a name="p02891557182316"></a><a name="p02891557182316"></a>name</p>
</td>
<td class="cellrowborder" valign="top" width="12.13%" headers="mcps1.2.6.1.3 "><p id="p19289155722313"><a name="p19289155722313"></a><a name="p19289155722313"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="10.549999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="42.34%" headers="mcps1.2.6.1.5 "><p id="p4289057112318"><a name="p4289057112318"></a><a name="p4289057112318"></a><span>内存池名称</span></p>
</td>
</tr>
<tr id="row1171019595234"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p187101259112311"><a name="p187101259112311"></a><a name="p187101259112311"></a>init</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1771065911230"><a name="p1771065911230"></a><a name="p1771065911230"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p971015591237"><a name="p971015591237"></a><a name="p971015591237"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p11710195918232"><a name="p11710195918232"></a><a name="p11710195918232"></a><span>初始化内存大小</span></p>
</td>
</tr>
<tr id="row174117116248"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p874119142416"><a name="p874119142416"></a><a name="p874119142416"></a>max</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p6741111172415"><a name="p6741111172415"></a><a name="p6741111172415"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p174113112410"><a name="p174113112410"></a><a name="p174113112410"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p5741121112416"><a name="p5741121112416"></a><a name="p5741121112416"></a><span>最大内存大小</span></p>
</td>
</tr>
<tr id="row16611412414"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p561345244"><a name="p561345244"></a><a name="p561345244"></a>used</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1767432410"><a name="p1767432410"></a><a name="p1767432410"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p161417245"><a name="p161417245"></a><a name="p161417245"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p2068413246"><a name="p2068413246"></a><a name="p2068413246"></a><span>已经被使用的内存大小</span></p>
</td>
</tr>
<tr id="row497220516240"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p097255152415"><a name="p097255152415"></a><a name="p097255152415"></a>committed</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p19728512248"><a name="p19728512248"></a><a name="p19728512248"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p2097213502411"><a name="p2097213502411"></a><a name="p2097213502411"></a><span>Byte</span></p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p149721755246"><a name="p149721755246"></a><a name="p149721755246"></a><span>当前可使用的内存大小</span></p>
</td>
</tr>
<tr id="row1965224017247"><td class="cellrowborder" rowspan="8" valign="top" width="10.05%" headers="mcps1.2.6.1.1 "><p id="p16652124092412"><a name="p16652124092412"></a><a name="p16652124092412"></a></p>
<p id="p18108930192819"><a name="p18108930192819"></a><a name="p18108930192819"></a></p>
<p id="p1053763918287"><a name="p1053763918287"></a><a name="p1053763918287"></a></p>
<p id="p28411370287"><a name="p28411370287"></a><a name="p28411370287"></a></p>
<p id="p10919364282"><a name="p10919364282"></a><a name="p10919364282"></a>thread</p>
<p id="p17185234102811"><a name="p17185234102811"></a><a name="p17185234102811"></a></p>
<p id="p1926513272819"><a name="p1926513272819"></a><a name="p1926513272819"></a></p>
<p id="p912449122912"><a name="p912449122912"></a><a name="p912449122912"></a></p>
</td>
<td class="cellrowborder" valign="top" width="24.93%" headers="mcps1.2.6.1.2 "><p id="p14652144052419"><a name="p14652144052419"></a><a name="p14652144052419"></a>currentThreadCpuTime</p>
</td>
<td class="cellrowborder" valign="top" width="12.13%" headers="mcps1.2.6.1.3 "><p id="p86527403241"><a name="p86527403241"></a><a name="p86527403241"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" width="10.549999999999999%" headers="mcps1.2.6.1.4 "><p id="p1465217403247"><a name="p1465217403247"></a><a name="p1465217403247"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" width="42.34%" headers="mcps1.2.6.1.5 "><p id="p365215408247"><a name="p365215408247"></a><a name="p365215408247"></a><span>当前线程的cpu时间</span></p>
</td>
</tr>
<tr id="row1810813092816"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p181087308285"><a name="p181087308285"></a><a name="p181087308285"></a>currentThreadUserTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1410819308285"><a name="p1410819308285"></a><a name="p1410819308285"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p31084304284"><a name="p31084304284"></a><a name="p31084304284"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p17108163012812"><a name="p17108163012812"></a><a name="p17108163012812"></a><span>当前线程的用户时间</span></p>
</td>
</tr>
<tr id="row153783917281"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p653715392286"><a name="p653715392286"></a><a name="p653715392286"></a>daemonThreadCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p8537439182818"><a name="p8537439182818"></a><a name="p8537439182818"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1753723914287"><a name="p1753723914287"></a><a name="p1753723914287"></a><span>守护线程数</span></p>
</td>
</tr>
<tr id="row168411237142811"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1284173762814"><a name="p1284173762814"></a><a name="p1284173762814"></a>deadlockedThreadsCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p17841163719280"><a name="p17841163719280"></a><a name="p17841163719280"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p13841163722817"><a name="p13841163722817"></a><a name="p13841163722817"></a><span>死锁线程数</span></p>
</td>
</tr>
<tr id="row59193652814"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p10953615285"><a name="p10953615285"></a><a name="p10953615285"></a>monitorDeadlockedThreads</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p179123612281"><a name="p179123612281"></a><a name="p179123612281"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p3332566282"><a name="p3332566282"></a><a name="p3332566282"></a>监视器死锁线程数</p>
</td>
</tr>
<tr id="row2185103417286"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p618513415284"><a name="p618513415284"></a><a name="p618513415284"></a>peakThreadCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p151854342281"><a name="p151854342281"></a><a name="p151854342281"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p718523442810"><a name="p718523442810"></a><a name="p718523442810"></a><span>峰值线程数</span></p>
</td>
</tr>
<tr id="row13265232102818"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p152651432202816"><a name="p152651432202816"></a><a name="p152651432202816"></a>threadCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p626553218289"><a name="p626553218289"></a><a name="p626553218289"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p7265432102813"><a name="p7265432102813"></a><a name="p7265432102813"></a><span>当前线程数</span></p>
</td>
</tr>
<tr id="row13124139162916"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p151246914297"><a name="p151246914297"></a><a name="p151246914297"></a>totalStartedThreadCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1812449182917"><a name="p1812449182917"></a><a name="p1812449182917"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1124179192918"><a name="p1124179192918"></a><a name="p1124179192918"></a><span>总共启动的线程数</span></p>
</td>
</tr>
</tbody>
</table>

