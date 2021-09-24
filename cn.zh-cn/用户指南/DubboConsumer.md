# DubboConsumer<a name="apm_07_0043"></a>

**表 1**  Dubbo客户端监控指标

<a name="table202535316223"></a>
<table><thead align="left"><tr id="row1525316317221"><th class="cellrowborder" valign="top" width="15.47%" id="mcps1.2.6.1.1"><p id="p5319333132517"><a name="p5319333132517"></a><a name="p5319333132517"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="23.59%" id="mcps1.2.6.1.2"><p id="p831993392515"><a name="p831993392515"></a><a name="p831993392515"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="13.03%" id="mcps1.2.6.1.3"><p id="p1531983312250"><a name="p1531983312250"></a><a name="p1531983312250"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="9.78%" id="mcps1.2.6.1.4"><p id="p1631963311253"><a name="p1631963311253"></a><a name="p1631963311253"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="38.129999999999995%" id="mcps1.2.6.1.5"><p id="p1531953362514"><a name="p1531953362514"></a><a name="p1531953362514"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row625453152212"><td class="cellrowborder" rowspan="18" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p2254235223"><a name="p2254235223"></a><a name="p2254235223"></a></p>
<p id="p52541039227"><a name="p52541039227"></a><a name="p52541039227"></a></p>
<p id="p182541138221"><a name="p182541138221"></a><a name="p182541138221"></a></p>
<p id="p42541834225"><a name="p42541834225"></a><a name="p42541834225"></a></p>
<p id="p10254435229"><a name="p10254435229"></a><a name="p10254435229"></a></p>
<p id="p1412712521295"><a name="p1412712521295"></a><a name="p1412712521295"></a></p>
<p id="p14127105210919"><a name="p14127105210919"></a><a name="p14127105210919"></a></p>
<p id="p512895217918"><a name="p512895217918"></a><a name="p512895217918"></a></p>
<p id="p171295521914"><a name="p171295521914"></a><a name="p171295521914"></a></p>
<p id="p16129145216916"><a name="p16129145216916"></a><a name="p16129145216916"></a>invocation</p>
<p id="p13394255290"><a name="p13394255290"></a><a name="p13394255290"></a></p>
<p id="p11394105511910"><a name="p11394105511910"></a><a name="p11394105511910"></a></p>
<p id="p1439525510913"><a name="p1439525510913"></a><a name="p1439525510913"></a></p>
<p id="p11396255792"><a name="p11396255792"></a><a name="p11396255792"></a></p>
<p id="p153961655692"><a name="p153961655692"></a><a name="p153961655692"></a></p>
<p id="p3397455496"><a name="p3397455496"></a><a name="p3397455496"></a></p>
<p id="p739717551198"><a name="p739717551198"></a><a name="p739717551198"></a></p>
<p id="p173981455590"><a name="p173981455590"></a><a name="p173981455590"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.59%" headers="mcps1.2.6.1.2 "><p id="p725415332214"><a name="p725415332214"></a><a name="p725415332214"></a>serviceUniqueName</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.3 "><p id="p02548320228"><a name="p02548320228"></a><a name="p02548320228"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="9.78%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="38.129999999999995%" headers="mcps1.2.6.1.5 "><p id="p1254183112215"><a name="p1254183112215"></a><a name="p1254183112215"></a>服务唯一标识（group+interface+version）</p>
</td>
</tr>
<tr id="row13254837226"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p202545319228"><a name="p202545319228"></a><a name="p202545319228"></a>method</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p42541633226"><a name="p42541633226"></a><a name="p42541633226"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p925411311223"><a name="p925411311223"></a><a name="p925411311223"></a>方法</p>
</td>
</tr>
<tr id="row182541336229"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p22546320221"><a name="p22546320221"></a><a name="p22546320221"></a>lastError</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p142546382216"><a name="p142546382216"></a><a name="p142546382216"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p5254133182211"><a name="p5254133182211"></a><a name="p5254133182211"></a>错误信息</p>
</td>
</tr>
<tr id="row4254143102212"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p122544392211"><a name="p122544392211"></a><a name="p122544392211"></a>slowTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7254193192215"><a name="p7254193192215"></a><a name="p7254193192215"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p82542312227"><a name="p82542312227"></a><a name="p82542312227"></a>最慢调用traceId</p>
</td>
</tr>
<tr id="row4254183152218"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p625411332218"><a name="p625411332218"></a><a name="p625411332218"></a>errorTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p5254153132212"><a name="p5254153132212"></a><a name="p5254153132212"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p152542352210"><a name="p152542352210"></a><a name="p152542352210"></a>错误traceId</p>
</td>
</tr>
<tr id="row1414417521492"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1512712526918"><a name="p1512712526918"></a><a name="p1512712526918"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16249572232"><a name="p16249572232"></a><a name="p16249572232"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p9127155220918"><a name="p9127155220918"></a><a name="p9127155220918"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row1814495219913"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p10234101416142"><a name="p10234101416142"></a><a name="p10234101416142"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16625165712232"><a name="p16625165712232"></a><a name="p16625165712232"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p7128205212915"><a name="p7128205212915"></a><a name="p7128205212915"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row181431352796"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1423518142145"><a name="p1423518142145"></a><a name="p1423518142145"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p206252057112316"><a name="p206252057112316"></a><a name="p206252057112316"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p161284521597"><a name="p161284521597"></a><a name="p161284521597"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row1314311521399"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p5235614141413"><a name="p5235614141413"></a><a name="p5235614141413"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p362517574232"><a name="p362517574232"></a><a name="p362517574232"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p131296521091"><a name="p131296521091"></a><a name="p131296521091"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row51432522910"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1023581411410"><a name="p1023581411410"></a><a name="p1023581411410"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p17625105712238"><a name="p17625105712238"></a><a name="p17625105712238"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1713085219910"><a name="p1713085219910"></a><a name="p1713085219910"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row134069552099"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1023591415146"><a name="p1023591415146"></a><a name="p1023591415146"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1062575710239"><a name="p1062575710239"></a><a name="p1062575710239"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p193942551595"><a name="p193942551595"></a><a name="p193942551595"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row1240617551691"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p13235414121412"><a name="p13235414121412"></a><a name="p13235414121412"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p19625757112319"><a name="p19625757112319"></a><a name="p19625757112319"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1939515551790"><a name="p1939515551790"></a><a name="p1939515551790"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row1240655515910"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p11395655897"><a name="p11395655897"></a><a name="p11395655897"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9853161218240"><a name="p9853161218240"></a><a name="p9853161218240"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p83951355298"><a name="p83951355298"></a><a name="p83951355298"></a>调用次数</p>
</td>
</tr>
<tr id="row4406155511914"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p93963551917"><a name="p93963551917"></a><a name="p93963551917"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1885371242411"><a name="p1885371242411"></a><a name="p1885371242411"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p15396955890"><a name="p15396955890"></a><a name="p15396955890"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p639675512918"><a name="p639675512918"></a><a name="p639675512918"></a>总响应时间</p>
</td>
</tr>
<tr id="row184068554911"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p163961955691"><a name="p163961955691"></a><a name="p163961955691"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p20853121242414"><a name="p20853121242414"></a><a name="p20853121242414"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p33961555091"><a name="p33961555091"></a><a name="p33961555091"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p33979554918"><a name="p33979554918"></a><a name="p33979554918"></a>最大响应时间</p>
</td>
</tr>
<tr id="row18406955897"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p439711553913"><a name="p439711553913"></a><a name="p439711553913"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p28531912122417"><a name="p28531912122417"></a><a name="p28531912122417"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1839714556915"><a name="p1839714556915"></a><a name="p1839714556915"></a>错误数</p>
</td>
</tr>
<tr id="row74064556912"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1939713554911"><a name="p1939713554911"></a><a name="p1939713554911"></a>runningCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p158531124242"><a name="p158531124242"></a><a name="p158531124242"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p4398355296"><a name="p4398355296"></a><a name="p4398355296"></a>当前正在处理的请求个数</p>
</td>
</tr>
<tr id="row24061551799"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p63985557919"><a name="p63985557919"></a><a name="p63985557919"></a>concurrentMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1139815514919"><a name="p1139815514919"></a><a name="p1139815514919"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1039811558911"><a name="p1039811558911"></a><a name="p1039811558911"></a>最大并发数</p>
</td>
</tr>
<tr id="row640616555915"><td class="cellrowborder" rowspan="14" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p839815551696"><a name="p839815551696"></a><a name="p839815551696"></a></p>
<p id="p17399955891"><a name="p17399955891"></a><a name="p17399955891"></a></p>
<p id="p20731859999"><a name="p20731859999"></a><a name="p20731859999"></a></p>
<p id="p873285915914"><a name="p873285915914"></a><a name="p873285915914"></a></p>
<p id="p77332591798"><a name="p77332591798"></a><a name="p77332591798"></a></p>
<p id="p373411591790"><a name="p373411591790"></a><a name="p373411591790"></a></p>
<p id="p773545913920"><a name="p773545913920"></a><a name="p773545913920"></a></p>
<p id="p8735135916910"><a name="p8735135916910"></a><a name="p8735135916910"></a>cluster</p>
<p id="p17736859595"><a name="p17736859595"></a><a name="p17736859595"></a></p>
<p id="p97371059391"><a name="p97371059391"></a><a name="p97371059391"></a></p>
<p id="p147381159897"><a name="p147381159897"></a><a name="p147381159897"></a></p>
<p id="p8739105919919"><a name="p8739105919919"></a><a name="p8739105919919"></a></p>
<p id="p1974055912914"><a name="p1974055912914"></a><a name="p1974055912914"></a></p>
<p id="p167418594918"><a name="p167418594918"></a><a name="p167418594918"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.59%" headers="mcps1.2.6.1.2 "><p id="p1539945518917"><a name="p1539945518917"></a><a name="p1539945518917"></a>cluster</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.3 "><p id="p43994551091"><a name="p43994551091"></a><a name="p43994551091"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="9.78%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="38.129999999999995%" headers="mcps1.2.6.1.5 "><p id="p113997554914"><a name="p113997554914"></a><a name="p113997554914"></a>主机</p>
</td>
</tr>
<tr id="row1540605510913"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p19839546174"><a name="p19839546174"></a><a name="p19839546174"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p11331736172420"><a name="p11331736172420"></a><a name="p11331736172420"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1921140133116"><a name="p1921140133116"></a><a name="p1921140133116"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row077312592910"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p8839742171"><a name="p8839742171"></a><a name="p8839742171"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p13331836122412"><a name="p13331836122412"></a><a name="p13331836122412"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1192118017313"><a name="p1192118017313"></a><a name="p1192118017313"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row177345910913"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p118401415174"><a name="p118401415174"></a><a name="p118401415174"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p143423652418"><a name="p143423652418"></a><a name="p143423652418"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1892114012311"><a name="p1892114012311"></a><a name="p1892114012311"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row11772559196"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p38404410173"><a name="p38404410173"></a><a name="p38404410173"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9341536102420"><a name="p9341536102420"></a><a name="p9341536102420"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1392114019314"><a name="p1392114019314"></a><a name="p1392114019314"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row157729591097"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p98401947176"><a name="p98401947176"></a><a name="p98401947176"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1734173632415"><a name="p1734173632415"></a><a name="p1734173632415"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p149225011316"><a name="p149225011316"></a><a name="p149225011316"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row1277215591295"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p684015413175"><a name="p684015413175"></a><a name="p684015413175"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p534173613245"><a name="p534173613245"></a><a name="p534173613245"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p139221202313"><a name="p139221202313"></a><a name="p139221202313"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row27725593910"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1684020414174"><a name="p1684020414174"></a><a name="p1684020414174"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p18340368243"><a name="p18340368243"></a><a name="p18340368243"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1392270153119"><a name="p1392270153119"></a><a name="p1392270153119"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row1777265919917"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1373755913912"><a name="p1373755913912"></a><a name="p1373755913912"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p17856341192415"><a name="p17856341192415"></a><a name="p17856341192415"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1373710591295"><a name="p1373710591295"></a><a name="p1373710591295"></a>调用次数</p>
</td>
</tr>
<tr id="row14772165919910"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p773845915912"><a name="p773845915912"></a><a name="p773845915912"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9856541102416"><a name="p9856541102416"></a><a name="p9856541102416"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p8738185912914"><a name="p8738185912914"></a><a name="p8738185912914"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p673865910912"><a name="p673865910912"></a><a name="p673865910912"></a>总响应时间</p>
</td>
</tr>
<tr id="row1377215599913"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p973855918912"><a name="p973855918912"></a><a name="p973855918912"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p3856841182420"><a name="p3856841182420"></a><a name="p3856841182420"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p3739125911917"><a name="p3739125911917"></a><a name="p3739125911917"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1373911593916"><a name="p1373911593916"></a><a name="p1373911593916"></a>最大响应时间</p>
</td>
</tr>
<tr id="row477225918914"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p6739115914911"><a name="p6739115914911"></a><a name="p6739115914911"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p17856341192411"><a name="p17856341192411"></a><a name="p17856341192411"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p074018596914"><a name="p074018596914"></a><a name="p074018596914"></a>错误数</p>
</td>
</tr>
<tr id="row13772159893"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p174012591699"><a name="p174012591699"></a><a name="p174012591699"></a>runningCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p14857134122412"><a name="p14857134122412"></a><a name="p14857134122412"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1774185914916"><a name="p1774185914916"></a><a name="p1774185914916"></a>当前正在处理的请求个数</p>
</td>
</tr>
<tr id="row16771175918912"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p157416599910"><a name="p157416599910"></a><a name="p157416599910"></a>concurrentMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p147425592913"><a name="p147425592913"></a><a name="p147425592913"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p12742185917920"><a name="p12742185917920"></a><a name="p12742185917920"></a>最大并发数</p>
</td>
</tr>
<tr id="row47711459392"><td class="cellrowborder" rowspan="3" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p27427591097"><a name="p27427591097"></a><a name="p27427591097"></a></p>
<p id="p14743145913917"><a name="p14743145913917"></a><a name="p14743145913917"></a>resultCode</p>
<p id="p1574485913916"><a name="p1574485913916"></a><a name="p1574485913916"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.59%" headers="mcps1.2.6.1.2 "><p id="p177422591990"><a name="p177422591990"></a><a name="p177422591990"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.3 "><p id="p8743145918918"><a name="p8743145918918"></a><a name="p8743145918918"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="9.78%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="38.129999999999995%" headers="mcps1.2.6.1.5 "><p id="p15743559895"><a name="p15743559895"></a><a name="p15743559895"></a>返回码</p>
</td>
</tr>
<tr id="row1677111591193"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p974316591793"><a name="p974316591793"></a><a name="p974316591793"></a>count</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p18743145913915"><a name="p18743145913915"></a><a name="p18743145913915"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1474414596918"><a name="p1474414596918"></a><a name="p1474414596918"></a>调用次数</p>
</td>
</tr>
<tr id="row117715599913"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p137441059599"><a name="p137441059599"></a><a name="p137441059599"></a>lastMethod</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p13744135920913"><a name="p13744135920913"></a><a name="p13744135920913"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1274520594912"><a name="p1274520594912"></a><a name="p1274520594912"></a>最近调用方法</p>
</td>
</tr>
<tr id="row127718593915"><td class="cellrowborder" rowspan="16" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p57450591294"><a name="p57450591294"></a><a name="p57450591294"></a></p>
<p id="p117466592099"><a name="p117466592099"></a><a name="p117466592099"></a></p>
<p id="p13747859595"><a name="p13747859595"></a><a name="p13747859595"></a></p>
<p id="p16748859592"><a name="p16748859592"></a><a name="p16748859592"></a></p>
<p id="p1674914591591"><a name="p1674914591591"></a><a name="p1674914591591"></a></p>
<p id="p57211645131813"><a name="p57211645131813"></a><a name="p57211645131813"></a></p>
<p id="p107222045131817"><a name="p107222045131817"></a><a name="p107222045131817"></a></p>
<p id="p12722164511185"><a name="p12722164511185"></a><a name="p12722164511185"></a></p>
<p id="p3723104513185"><a name="p3723104513185"></a><a name="p3723104513185"></a>total</p>
<p id="p1372411454184"><a name="p1372411454184"></a><a name="p1372411454184"></a></p>
<p id="p1672454571817"><a name="p1672454571817"></a><a name="p1672454571817"></a></p>
<p id="p872513455188"><a name="p872513455188"></a><a name="p872513455188"></a></p>
<p id="p13143348131820"><a name="p13143348131820"></a><a name="p13143348131820"></a></p>
<p id="p31441348171818"><a name="p31441348171818"></a><a name="p31441348171818"></a></p>
<p id="p4145204816180"><a name="p4145204816180"></a><a name="p4145204816180"></a></p>
<p id="p101451548121817"><a name="p101451548121817"></a><a name="p101451548121817"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.59%" headers="mcps1.2.6.1.2 "><p id="p974513595919"><a name="p974513595919"></a><a name="p974513595919"></a>lastError</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.3 "><p id="p97451659494"><a name="p97451659494"></a><a name="p97451659494"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="9.78%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="38.129999999999995%" headers="mcps1.2.6.1.5 "><p id="p77467591692"><a name="p77467591692"></a><a name="p77467591692"></a>错误信息</p>
</td>
</tr>
<tr id="row477117591894"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p3746175919915"><a name="p3746175919915"></a><a name="p3746175919915"></a>slowTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7746759794"><a name="p7746759794"></a><a name="p7746759794"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p17472059098"><a name="p17472059098"></a><a name="p17472059098"></a>最慢调用traceId</p>
</td>
</tr>
<tr id="row15771259792"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p47471159193"><a name="p47471159193"></a><a name="p47471159193"></a>errorTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p174717595911"><a name="p174717595911"></a><a name="p174717595911"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p117489591597"><a name="p117489591597"></a><a name="p117489591597"></a>错误traceId</p>
</td>
</tr>
<tr id="row117712595918"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p31971253141917"><a name="p31971253141917"></a><a name="p31971253141917"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1960845182512"><a name="p1960845182512"></a><a name="p1960845182512"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1958173917324"><a name="p1958173917324"></a><a name="p1958173917324"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row1377016591799"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p91981853121917"><a name="p91981853121917"></a><a name="p91981853121917"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p14603458256"><a name="p14603458256"></a><a name="p14603458256"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p11958639113217"><a name="p11958639113217"></a><a name="p11958639113217"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row3738134516185"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p141981953191920"><a name="p141981953191920"></a><a name="p141981953191920"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p96014451250"><a name="p96014451250"></a><a name="p96014451250"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p18958113903220"><a name="p18958113903220"></a><a name="p18958113903220"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row13738245161813"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1919865315193"><a name="p1919865315193"></a><a name="p1919865315193"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1760184513250"><a name="p1760184513250"></a><a name="p1760184513250"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p169581639173213"><a name="p169581639173213"></a><a name="p169581639173213"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row177381145101819"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1319845318199"><a name="p1319845318199"></a><a name="p1319845318199"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16110454259"><a name="p16110454259"></a><a name="p16110454259"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p6958133914328"><a name="p6958133914328"></a><a name="p6958133914328"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row9737174561812"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p19198105316195"><a name="p19198105316195"></a><a name="p19198105316195"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p961104562511"><a name="p961104562511"></a><a name="p961104562511"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p20958739163219"><a name="p20958739163219"></a><a name="p20958739163219"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row3737545161819"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p8198145312198"><a name="p8198145312198"></a><a name="p8198145312198"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p116184582520"><a name="p116184582520"></a><a name="p116184582520"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1095913912325"><a name="p1095913912325"></a><a name="p1095913912325"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row14737164517183"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p87241945161817"><a name="p87241945161817"></a><a name="p87241945161817"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p518955132518"><a name="p518955132518"></a><a name="p518955132518"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p4725134531820"><a name="p4725134531820"></a><a name="p4725134531820"></a>调用次数</p>
</td>
</tr>
<tr id="row1273624518182"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p16725184518188"><a name="p16725184518188"></a><a name="p16725184518188"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p418975162515"><a name="p418975162515"></a><a name="p418975162515"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p8725114511182"><a name="p8725114511182"></a><a name="p8725114511182"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p6725114521817"><a name="p6725114521817"></a><a name="p6725114521817"></a>总响应时间</p>
</td>
</tr>
<tr id="row416144814188"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1014315487186"><a name="p1014315487186"></a><a name="p1014315487186"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p81891051122514"><a name="p81891051122514"></a><a name="p81891051122514"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p214414881813"><a name="p214414881813"></a><a name="p214414881813"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p114414814186"><a name="p114414814186"></a><a name="p114414814186"></a>最大响应时间</p>
</td>
</tr>
<tr id="row416164801819"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p6144134813185"><a name="p6144134813185"></a><a name="p6144134813185"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p14189251142519"><a name="p14189251142519"></a><a name="p14189251142519"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1214534818181"><a name="p1214534818181"></a><a name="p1214534818181"></a>错误数</p>
</td>
</tr>
<tr id="row4160134831816"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p151451348111812"><a name="p151451348111812"></a><a name="p151451348111812"></a>runningCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p161891516255"><a name="p161891516255"></a><a name="p161891516255"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p121452048171820"><a name="p121452048171820"></a><a name="p121452048171820"></a>当前正在处理的请求个数</p>
</td>
</tr>
<tr id="row816019488182"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p161451248191820"><a name="p161451248191820"></a><a name="p161451248191820"></a>concurrentMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p131469482187"><a name="p131469482187"></a><a name="p131469482187"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p314664813181"><a name="p314664813181"></a><a name="p314664813181"></a>最大并发数</p>
</td>
</tr>
<tr id="row116054811814"><td class="cellrowborder" rowspan="8" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p11461648201815"><a name="p11461648201815"></a><a name="p11461648201815"></a></p>
<p id="p61471487189"><a name="p61471487189"></a><a name="p61471487189"></a></p>
<p id="p10147134881813"><a name="p10147134881813"></a><a name="p10147134881813"></a></p>
<p id="p2374175020185"><a name="p2374175020185"></a><a name="p2374175020185"></a></p>
<p id="p113751850191817"><a name="p113751850191817"></a><a name="p113751850191817"></a>threadPool</p>
<p id="p63761850151819"><a name="p63761850151819"></a><a name="p63761850151819"></a></p>
<p id="p8376155091812"><a name="p8376155091812"></a><a name="p8376155091812"></a></p>
<p id="p13774507186"><a name="p13774507186"></a><a name="p13774507186"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.59%" headers="mcps1.2.6.1.2 "><p id="p11461148101816"><a name="p11461148101816"></a><a name="p11461148101816"></a>poolId</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.3 "><p id="p19146194811810"><a name="p19146194811810"></a><a name="p19146194811810"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="9.78%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="38.129999999999995%" headers="mcps1.2.6.1.5 "><p id="p214619481183"><a name="p214619481183"></a><a name="p214619481183"></a>线程池唯一标示（主机名+端口）</p>
</td>
</tr>
<tr id="row1159148171812"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1114714841814"><a name="p1114714841814"></a><a name="p1114714841814"></a>poolType</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1414714816185"><a name="p1414714816185"></a><a name="p1414714816185"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p19147114820189"><a name="p19147114820189"></a><a name="p19147114820189"></a>dubbo自定义线程池类型（fixed、cached、limited等）</p>
</td>
</tr>
<tr id="row121591048141817"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1514710489185"><a name="p1514710489185"></a><a name="p1514710489185"></a>activeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p185774299261"><a name="p185774299261"></a><a name="p185774299261"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p131481548171820"><a name="p131481548171820"></a><a name="p131481548171820"></a>当前激活个数</p>
</td>
</tr>
<tr id="row12384135015182"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p5374450151814"><a name="p5374450151814"></a><a name="p5374450151814"></a>corePoolSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p95771229142613"><a name="p95771229142613"></a><a name="p95771229142613"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p13375125091819"><a name="p13375125091819"></a><a name="p13375125091819"></a>核心线程数</p>
</td>
</tr>
<tr id="row4384125061818"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p9375145021812"><a name="p9375145021812"></a><a name="p9375145021812"></a>maximumPoolSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1357712962619"><a name="p1357712962619"></a><a name="p1357712962619"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p15375350141818"><a name="p15375350141818"></a><a name="p15375350141818"></a>最大核心线程数</p>
</td>
</tr>
<tr id="row1384150121814"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p8376950141813"><a name="p8376950141813"></a><a name="p8376950141813"></a>poolSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p637619501187"><a name="p637619501187"></a><a name="p637619501187"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1537605091810"><a name="p1537605091810"></a><a name="p1537605091810"></a>线程池大小</p>
</td>
</tr>
<tr id="row1638435061811"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p73766501185"><a name="p73766501185"></a><a name="p73766501185"></a>queueSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1637695019183"><a name="p1637695019183"></a><a name="p1637695019183"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p19377185010184"><a name="p19377185010184"></a><a name="p19377185010184"></a>等待队列大小</p>
</td>
</tr>
<tr id="row0384145081815"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p437715505181"><a name="p437715505181"></a><a name="p437715505181"></a>taskCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p637765031810"><a name="p637765031810"></a><a name="p637765031810"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1637715509187"><a name="p1637715509187"></a><a name="p1637715509187"></a>任务数</p>
</td>
</tr>
<tr id="row1384145031810"><td class="cellrowborder" valign="top" width="15.47%" headers="mcps1.2.6.1.1 "><p id="p737814501189"><a name="p737814501189"></a><a name="p737814501189"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="23.59%" headers="mcps1.2.6.1.2 "><p id="p193781850141812"><a name="p193781850141812"></a><a name="p193781850141812"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="13.03%" headers="mcps1.2.6.1.3 "><p id="p13378105016189"><a name="p13378105016189"></a><a name="p13378105016189"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="9.78%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="38.129999999999995%" headers="mcps1.2.6.1.5 "><p id="p1337816502189"><a name="p1337816502189"></a><a name="p1337816502189"></a>客户端版本</p>
</td>
</tr>
</tbody>
</table>

