# DubboProvider<a name="apm_07_0039"></a>

**表 1**  Dubbo服务端监控指标

<a name="table4233357151117"></a>
<table><thead align="left"><tr id="row162345575114"><th class="cellrowborder" valign="top" width="12%" id="mcps1.2.6.1.1"><p id="p62681320151215"><a name="p62681320151215"></a><a name="p62681320151215"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="22.830000000000002%" id="mcps1.2.6.1.2"><p id="p526862011218"><a name="p526862011218"></a><a name="p526862011218"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="16.580000000000002%" id="mcps1.2.6.1.3"><p id="p6268162014122"><a name="p6268162014122"></a><a name="p6268162014122"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="11.899999999999999%" id="mcps1.2.6.1.4"><p id="p10268152010126"><a name="p10268152010126"></a><a name="p10268152010126"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="36.69%" id="mcps1.2.6.1.5"><p id="p11268122010127"><a name="p11268122010127"></a><a name="p11268122010127"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row423405713110"><td class="cellrowborder" rowspan="19" valign="top" width="12%" headers="mcps1.2.6.1.1 "><p id="p1234165717118"><a name="p1234165717118"></a><a name="p1234165717118"></a></p>
<p id="p0234125719113"><a name="p0234125719113"></a><a name="p0234125719113"></a></p>
<p id="p42343573112"><a name="p42343573112"></a><a name="p42343573112"></a></p>
<p id="p142341657101120"><a name="p142341657101120"></a><a name="p142341657101120"></a></p>
<p id="p14234205791112"><a name="p14234205791112"></a><a name="p14234205791112"></a></p>
<p id="p063719198010"><a name="p063719198010"></a><a name="p063719198010"></a></p>
<p id="p97951423207"><a name="p97951423207"></a><a name="p97951423207"></a></p>
<p id="p578252514016"><a name="p578252514016"></a><a name="p578252514016"></a></p>
<p id="p978314251608"><a name="p978314251608"></a><a name="p978314251608"></a></p>
<p id="p12836132710011"><a name="p12836132710011"></a><a name="p12836132710011"></a></p>
<p id="p383717278015"><a name="p383717278015"></a><a name="p383717278015"></a>invocation</p>
<p id="p783762718019"><a name="p783762718019"></a><a name="p783762718019"></a></p>
<p id="p28376273015"><a name="p28376273015"></a><a name="p28376273015"></a></p>
<p id="p6415103016010"><a name="p6415103016010"></a><a name="p6415103016010"></a></p>
<p id="p041523013015"><a name="p041523013015"></a><a name="p041523013015"></a></p>
<p id="p114166301003"><a name="p114166301003"></a><a name="p114166301003"></a></p>
<p id="p1141617301009"><a name="p1141617301009"></a><a name="p1141617301009"></a></p>
<p id="p174176301909"><a name="p174176301909"></a><a name="p174176301909"></a></p>
<p id="p194170301207"><a name="p194170301207"></a><a name="p194170301207"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.830000000000002%" headers="mcps1.2.6.1.2 "><p id="p142348574118"><a name="p142348574118"></a><a name="p142348574118"></a>serviceUniqueName</p>
</td>
<td class="cellrowborder" valign="top" width="16.580000000000002%" headers="mcps1.2.6.1.3 "><p id="p16234557191116"><a name="p16234557191116"></a><a name="p16234557191116"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="11.899999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.69%" headers="mcps1.2.6.1.5 "><p id="p13234135712119"><a name="p13234135712119"></a><a name="p13234135712119"></a>服务唯一标识（group+interface+version）</p>
</td>
</tr>
<tr id="row19234557141119"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p12234557101120"><a name="p12234557101120"></a><a name="p12234557101120"></a>method</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p13234155761114"><a name="p13234155761114"></a><a name="p13234155761114"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p192342572119"><a name="p192342572119"></a><a name="p192342572119"></a>方法</p>
</td>
</tr>
<tr id="row02341857191110"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p182342570119"><a name="p182342570119"></a><a name="p182342570119"></a>source</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p112340578111"><a name="p112340578111"></a><a name="p112340578111"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p923465761112"><a name="p923465761112"></a><a name="p923465761112"></a>调用源</p>
</td>
</tr>
<tr id="row1023485701118"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1523455761118"><a name="p1523455761118"></a><a name="p1523455761118"></a>lastError</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1223419573112"><a name="p1223419573112"></a><a name="p1223419573112"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p723465714110"><a name="p723465714110"></a><a name="p723465714110"></a>错误信息</p>
</td>
</tr>
<tr id="row13234125751113"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4234145714111"><a name="p4234145714111"></a><a name="p4234145714111"></a>slowTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1323455731116"><a name="p1323455731116"></a><a name="p1323455731116"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p9234257101120"><a name="p9234257101120"></a><a name="p9234257101120"></a>最慢调用traceId</p>
</td>
</tr>
<tr id="row116367191905"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p76374191301"><a name="p76374191301"></a><a name="p76374191301"></a>errorTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1863717191013"><a name="p1863717191013"></a><a name="p1863717191013"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p136371019807"><a name="p136371019807"></a><a name="p136371019807"></a>错误traceId</p>
</td>
</tr>
<tr id="row179819238016"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p5795162314015"><a name="p5795162314015"></a><a name="p5795162314015"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p77951223508"><a name="p77951223508"></a><a name="p77951223508"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p107958231400"><a name="p107958231400"></a><a name="p107958231400"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row13788925306"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p278220251406"><a name="p278220251406"></a><a name="p278220251406"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p19783182516012"><a name="p19783182516012"></a><a name="p19783182516012"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p67832025203"><a name="p67832025203"></a><a name="p67832025203"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row18787172518015"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p2078310251404"><a name="p2078310251404"></a><a name="p2078310251404"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p147834252011"><a name="p147834252011"></a><a name="p147834252011"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1578362510013"><a name="p1578362510013"></a><a name="p1578362510013"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row7847627703"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1783618271019"><a name="p1783618271019"></a><a name="p1783618271019"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p98366271704"><a name="p98366271704"></a><a name="p98366271704"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p58370271907"><a name="p58370271907"></a><a name="p58370271907"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row7846627000"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p2959195419011"><a name="p2959195419011"></a><a name="p2959195419011"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p158371627503"><a name="p158371627503"></a><a name="p158371627503"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p28376279012"><a name="p28376279012"></a><a name="p28376279012"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row584614271209"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p3521155816011"><a name="p3521155816011"></a><a name="p3521155816011"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p168372278016"><a name="p168372278016"></a><a name="p168372278016"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p128371427907"><a name="p128371427907"></a><a name="p128371427907"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row108451327804"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p5837102714016"><a name="p5837102714016"></a><a name="p5837102714016"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p138381427501"><a name="p138381427501"></a><a name="p138381427501"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p58381227601"><a name="p58381227601"></a><a name="p58381227601"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row44364309011"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p541563014014"><a name="p541563014014"></a><a name="p541563014014"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p154151130808"><a name="p154151130808"></a><a name="p154151130808"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p841573014014"><a name="p841573014014"></a><a name="p841573014014"></a>调用次数</p>
</td>
</tr>
<tr id="row443603017016"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p14151530803"><a name="p14151530803"></a><a name="p14151530803"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1941503014015"><a name="p1941503014015"></a><a name="p1941503014015"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p34161930002"><a name="p34161930002"></a><a name="p34161930002"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1541623014012"><a name="p1541623014012"></a><a name="p1541623014012"></a>总响应时间</p>
</td>
</tr>
<tr id="row144352306017"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1441617309017"><a name="p1441617309017"></a><a name="p1441617309017"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p64161630205"><a name="p64161630205"></a><a name="p64161630205"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p141616301808"><a name="p141616301808"></a><a name="p141616301808"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p9416133017019"><a name="p9416133017019"></a><a name="p9416133017019"></a>最大响应时间</p>
</td>
</tr>
<tr id="row10435123017012"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4416163018014"><a name="p4416163018014"></a><a name="p4416163018014"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p74164303018"><a name="p74164303018"></a><a name="p74164303018"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p041619302019"><a name="p041619302019"></a><a name="p041619302019"></a>错误数</p>
</td>
</tr>
<tr id="row164351830808"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p54176300010"><a name="p54176300010"></a><a name="p54176300010"></a>runningCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1341716301604"><a name="p1341716301604"></a><a name="p1341716301604"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p74171330207"><a name="p74171330207"></a><a name="p74171330207"></a>当前正在处理的请求个数</p>
</td>
</tr>
<tr id="row943418305011"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4417830808"><a name="p4417830808"></a><a name="p4417830808"></a>concurrentMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p14170308013"><a name="p14170308013"></a><a name="p14170308013"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1417143018012"><a name="p1417143018012"></a><a name="p1417143018012"></a>最大并发数</p>
</td>
</tr>
<tr id="row10434130402"><td class="cellrowborder" rowspan="14" valign="top" width="12%" headers="mcps1.2.6.1.1 "><p id="p17417113014019"><a name="p17417113014019"></a><a name="p17417113014019"></a></p>
<p id="p194187301704"><a name="p194187301704"></a><a name="p194187301704"></a></p>
<p id="p19555171014210"><a name="p19555171014210"></a><a name="p19555171014210"></a></p>
<p id="p1671131214210"><a name="p1671131214210"></a><a name="p1671131214210"></a></p>
<p id="p97121112624"><a name="p97121112624"></a><a name="p97121112624"></a></p>
<p id="p7889914121"><a name="p7889914121"></a><a name="p7889914121"></a></p>
<p id="p168895141623"><a name="p168895141623"></a><a name="p168895141623"></a></p>
<p id="p38891914023"><a name="p38891914023"></a><a name="p38891914023"></a>cluster</p>
<p id="p178901714829"><a name="p178901714829"></a><a name="p178901714829"></a></p>
<p id="p785813161422"><a name="p785813161422"></a><a name="p785813161422"></a></p>
<p id="p178591216022"><a name="p178591216022"></a><a name="p178591216022"></a></p>
<p id="p2859151618218"><a name="p2859151618218"></a><a name="p2859151618218"></a></p>
<p id="p98607166218"><a name="p98607166218"></a><a name="p98607166218"></a></p>
<p id="p176557161735"><a name="p176557161735"></a><a name="p176557161735"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.830000000000002%" headers="mcps1.2.6.1.2 "><p id="p1041713301308"><a name="p1041713301308"></a><a name="p1041713301308"></a>cluster</p>
</td>
<td class="cellrowborder" valign="top" width="16.580000000000002%" headers="mcps1.2.6.1.3 "><p id="p241723017010"><a name="p241723017010"></a><a name="p241723017010"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="11.899999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.69%" headers="mcps1.2.6.1.5 "><p id="p441816301104"><a name="p441816301104"></a><a name="p441816301104"></a>主机</p>
</td>
</tr>
<tr id="row243410301606"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p641803010012"><a name="p641803010012"></a><a name="p641803010012"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p6628104810911"><a name="p6628104810911"></a><a name="p6628104810911"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p24185305015"><a name="p24185305015"></a><a name="p24185305015"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row165571910029"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1155571010219"><a name="p1155571010219"></a><a name="p1155571010219"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1662818481697"><a name="p1662818481697"></a><a name="p1662818481697"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p755691016212"><a name="p755691016212"></a><a name="p755691016212"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row9717101210213"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4711512623"><a name="p4711512623"></a><a name="p4711512623"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16287483915"><a name="p16287483915"></a><a name="p16287483915"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p147121412826"><a name="p147121412826"></a><a name="p147121412826"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row1571614121724"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p187123122029"><a name="p187123122029"></a><a name="p187123122029"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16629194812915"><a name="p16629194812915"></a><a name="p16629194812915"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p11712512625"><a name="p11712512625"></a><a name="p11712512625"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row1389661410214"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1889191411210"><a name="p1889191411210"></a><a name="p1889191411210"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p762918486916"><a name="p762918486916"></a><a name="p762918486916"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p088919141215"><a name="p088919141215"></a><a name="p088919141215"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row1089619141122"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p18941540823"><a name="p18941540823"></a><a name="p18941540823"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1162904812911"><a name="p1162904812911"></a><a name="p1162904812911"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p688913141024"><a name="p688913141024"></a><a name="p688913141024"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row118961714828"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p158891714924"><a name="p158891714924"></a><a name="p158891714924"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1562910482916"><a name="p1562910482916"></a><a name="p1562910482916"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1689014141217"><a name="p1689014141217"></a><a name="p1689014141217"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row148951914929"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1389061412215"><a name="p1389061412215"></a><a name="p1389061412215"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p12613004101"><a name="p12613004101"></a><a name="p12613004101"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p93027151421"><a name="p93027151421"></a><a name="p93027151421"></a>调用次数</p>
</td>
</tr>
<tr id="row14867181611215"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1858161617217"><a name="p1858161617217"></a><a name="p1858161617217"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p196139019105"><a name="p196139019105"></a><a name="p196139019105"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p12858101610214"><a name="p12858101610214"></a><a name="p12858101610214"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p9858191619216"><a name="p9858191619216"></a><a name="p9858191619216"></a>总响应时间</p>
</td>
</tr>
<tr id="row15866916222"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p14859131615211"><a name="p14859131615211"></a><a name="p14859131615211"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1961380161013"><a name="p1961380161013"></a><a name="p1961380161013"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p68591816220"><a name="p68591816220"></a><a name="p68591816220"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p13859171615220"><a name="p13859171615220"></a><a name="p13859171615220"></a>最大响应时间</p>
</td>
</tr>
<tr id="row586615166215"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p19859616420"><a name="p19859616420"></a><a name="p19859616420"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1361317071017"><a name="p1361317071017"></a><a name="p1361317071017"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1860171615218"><a name="p1860171615218"></a><a name="p1860171615218"></a>错误数</p>
</td>
</tr>
<tr id="row19866151618219"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p486017161429"><a name="p486017161429"></a><a name="p486017161429"></a>runningCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p06138016105"><a name="p06138016105"></a><a name="p06138016105"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p886011164218"><a name="p886011164218"></a><a name="p886011164218"></a>当前正在处理的请求个数</p>
</td>
</tr>
<tr id="row46581416638"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p66551116533"><a name="p66551116533"></a><a name="p66551116533"></a>concurrentMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p661315021017"><a name="p661315021017"></a><a name="p661315021017"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p065518165311"><a name="p065518165311"></a><a name="p065518165311"></a>最大并发数</p>
</td>
</tr>
<tr id="row1894417195313"><td class="cellrowborder" rowspan="3" valign="top" width="12%" headers="mcps1.2.6.1.1 "><p id="p10941719837"><a name="p10941719837"></a><a name="p10941719837"></a></p>
<p id="p139423193316"><a name="p139423193316"></a><a name="p139423193316"></a>resultCode</p>
<p id="p84262213314"><a name="p84262213314"></a><a name="p84262213314"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.830000000000002%" headers="mcps1.2.6.1.2 "><p id="p199412191332"><a name="p199412191332"></a><a name="p199412191332"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="16.580000000000002%" headers="mcps1.2.6.1.3 "><p id="p209415191837"><a name="p209415191837"></a><a name="p209415191837"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="11.899999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.69%" headers="mcps1.2.6.1.5 "><p id="p109427191434"><a name="p109427191434"></a><a name="p109427191434"></a>返回码</p>
</td>
</tr>
<tr id="row294415191431"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1994216191437"><a name="p1994216191437"></a><a name="p1994216191437"></a>count</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p189421119938"><a name="p189421119938"></a><a name="p189421119938"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p15942161911311"><a name="p15942161911311"></a><a name="p15942161911311"></a>调用次数</p>
</td>
</tr>
<tr id="row174722211313"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p11430229310"><a name="p11430229310"></a><a name="p11430229310"></a>lastMethod</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p24318229317"><a name="p24318229317"></a><a name="p24318229317"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p0432022835"><a name="p0432022835"></a><a name="p0432022835"></a>最近调用方法</p>
</td>
</tr>
<tr id="row9471229319"><td class="cellrowborder" rowspan="16" valign="top" width="12%" headers="mcps1.2.6.1.1 "><p id="p943162210318"><a name="p943162210318"></a><a name="p943162210318"></a></p>
<p id="p204352213315"><a name="p204352213315"></a><a name="p204352213315"></a></p>
<p id="p144417221737"><a name="p144417221737"></a><a name="p144417221737"></a></p>
<p id="p485418241316"><a name="p485418241316"></a><a name="p485418241316"></a></p>
<p id="p685510241634"><a name="p685510241634"></a><a name="p685510241634"></a></p>
<p id="p14855192417310"><a name="p14855192417310"></a><a name="p14855192417310"></a></p>
<p id="p168561224537"><a name="p168561224537"></a><a name="p168561224537"></a></p>
<p id="p1785612413318"><a name="p1785612413318"></a><a name="p1785612413318"></a>total</p>
<p id="p48561324638"><a name="p48561324638"></a><a name="p48561324638"></a></p>
<p id="p38575248312"><a name="p38575248312"></a><a name="p38575248312"></a></p>
<p id="p108575241135"><a name="p108575241135"></a><a name="p108575241135"></a></p>
<p id="p133745116419"><a name="p133745116419"></a><a name="p133745116419"></a></p>
<p id="p8447105812417"><a name="p8447105812417"></a><a name="p8447105812417"></a></p>
<p id="p17317415517"><a name="p17317415517"></a><a name="p17317415517"></a></p>
<p id="p183181210520"><a name="p183181210520"></a><a name="p183181210520"></a></p>
<p id="p27721221657"><a name="p27721221657"></a><a name="p27721221657"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.830000000000002%" headers="mcps1.2.6.1.2 "><p id="p194317228316"><a name="p194317228316"></a><a name="p194317228316"></a>lastError</p>
</td>
<td class="cellrowborder" valign="top" width="16.580000000000002%" headers="mcps1.2.6.1.3 "><p id="p04310221436"><a name="p04310221436"></a><a name="p04310221436"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="11.899999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.69%" headers="mcps1.2.6.1.5 "><p id="p143162219313"><a name="p143162219313"></a><a name="p143162219313"></a>错误信息</p>
</td>
</tr>
<tr id="row84716221235"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p94362213318"><a name="p94362213318"></a><a name="p94362213318"></a>slowTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p6437221733"><a name="p6437221733"></a><a name="p6437221733"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p18442224310"><a name="p18442224310"></a><a name="p18442224310"></a>最慢调用traceId</p>
</td>
</tr>
<tr id="row84715221839"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p44492213317"><a name="p44492213317"></a><a name="p44492213317"></a>errorTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p12449221037"><a name="p12449221037"></a><a name="p12449221037"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p04415221532"><a name="p04415221532"></a><a name="p04415221532"></a>错误traceId</p>
</td>
</tr>
<tr id="row586592418313"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p9979847746"><a name="p9979847746"></a><a name="p9979847746"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1874024351012"><a name="p1874024351012"></a><a name="p1874024351012"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p178557241137"><a name="p178557241137"></a><a name="p178557241137"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row1786516241335"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p189805471745"><a name="p189805471745"></a><a name="p189805471745"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p17740184317101"><a name="p17740184317101"></a><a name="p17740184317101"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p148559243317"><a name="p148559243317"></a><a name="p148559243317"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row18659247320"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p149801347948"><a name="p149801347948"></a><a name="p149801347948"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p4741154315105"><a name="p4741154315105"></a><a name="p4741154315105"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p78551124435"><a name="p78551124435"></a><a name="p78551124435"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row1286414241339"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1398013471746"><a name="p1398013471746"></a><a name="p1398013471746"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p147411043191010"><a name="p147411043191010"></a><a name="p147411043191010"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1085616247315"><a name="p1085616247315"></a><a name="p1085616247315"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row18864024038"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p13980174716420"><a name="p13980174716420"></a><a name="p13980174716420"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p167411243111011"><a name="p167411243111011"></a><a name="p167411243111011"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1985618242314"><a name="p1985618242314"></a><a name="p1985618242314"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row886420241838"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p398064718414"><a name="p398064718414"></a><a name="p398064718414"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p10741104317108"><a name="p10741104317108"></a><a name="p10741104317108"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p19857424033"><a name="p19857424033"></a><a name="p19857424033"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row986422418318"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p189804471541"><a name="p189804471541"></a><a name="p189804471541"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p9741164315107"><a name="p9741164315107"></a><a name="p9741164315107"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p168576241932"><a name="p168576241932"></a><a name="p168576241932"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row1086419241239"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p49803471244"><a name="p49803471244"></a><a name="p49803471244"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p124771651101018"><a name="p124771651101018"></a><a name="p124771651101018"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p138581424336"><a name="p138581424336"></a><a name="p138581424336"></a>调用次数</p>
</td>
</tr>
<tr id="row133745116420"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p23371551640"><a name="p23371551640"></a><a name="p23371551640"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p34781651191019"><a name="p34781651191019"></a><a name="p34781651191019"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p033775111418"><a name="p033775111418"></a><a name="p033775111418"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p2033715511147"><a name="p2033715511147"></a><a name="p2033715511147"></a>总响应时间</p>
</td>
</tr>
<tr id="row3450135813412"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p94471586415"><a name="p94471586415"></a><a name="p94471586415"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p6478145111101"><a name="p6478145111101"></a><a name="p6478145111101"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p8447115812411"><a name="p8447115812411"></a><a name="p8447115812411"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1044817582416"><a name="p1044817582416"></a><a name="p1044817582416"></a>最大响应时间</p>
</td>
</tr>
<tr id="row203234120513"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p19317711657"><a name="p19317711657"></a><a name="p19317711657"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1847885141013"><a name="p1847885141013"></a><a name="p1847885141013"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p3318319517"><a name="p3318319517"></a><a name="p3318319517"></a>错误数</p>
</td>
</tr>
<tr id="row0322181857"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p43181311951"><a name="p43181311951"></a><a name="p43181311951"></a>runningCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1747811514108"><a name="p1747811514108"></a><a name="p1747811514108"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p17318161158"><a name="p17318161158"></a><a name="p17318161158"></a>当前正在处理的请求个数</p>
</td>
</tr>
<tr id="row157756217516"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p137721921650"><a name="p137721921650"></a><a name="p137721921650"></a>concurrentMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p4478185131017"><a name="p4478185131017"></a><a name="p4478185131017"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p107721211954"><a name="p107721211954"></a><a name="p107721211954"></a>最大并发数</p>
</td>
</tr>
<tr id="row1777552113517"><td class="cellrowborder" rowspan="8" valign="top" width="12%" headers="mcps1.2.6.1.1 "><p id="p157726218513"><a name="p157726218513"></a><a name="p157726218513"></a></p>
<p id="p145739461518"><a name="p145739461518"></a><a name="p145739461518"></a></p>
<p id="p20116114818513"><a name="p20116114818513"></a><a name="p20116114818513"></a></p>
<p id="p206771502514"><a name="p206771502514"></a><a name="p206771502514"></a></p>
<p id="p1667715505510"><a name="p1667715505510"></a><a name="p1667715505510"></a>threadPool</p>
<p id="p1167812502054"><a name="p1167812502054"></a><a name="p1167812502054"></a></p>
<p id="p264620544513"><a name="p264620544513"></a><a name="p264620544513"></a></p>
<p id="p126480543519"><a name="p126480543519"></a><a name="p126480543519"></a></p>
</td>
<td class="cellrowborder" valign="top" width="22.830000000000002%" headers="mcps1.2.6.1.2 "><p id="p18772172113515"><a name="p18772172113515"></a><a name="p18772172113515"></a>poolId</p>
</td>
<td class="cellrowborder" valign="top" width="16.580000000000002%" headers="mcps1.2.6.1.3 "><p id="p157723212511"><a name="p157723212511"></a><a name="p157723212511"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="11.899999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.69%" headers="mcps1.2.6.1.5 "><p id="p220631141818"><a name="p220631141818"></a><a name="p220631141818"></a>线程池唯一标识（主机名+端口）</p>
</td>
</tr>
<tr id="row65761468514"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p257414614517"><a name="p257414614517"></a><a name="p257414614517"></a>poolType</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p18574846457"><a name="p18574846457"></a><a name="p18574846457"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p95741546551"><a name="p95741546551"></a><a name="p95741546551"></a>dubbo自定义线程池类型（fixed、cached、limited等）</p>
</td>
</tr>
<tr id="row141194481555"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p111177485516"><a name="p111177485516"></a><a name="p111177485516"></a>activeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p5117144812511"><a name="p5117144812511"></a><a name="p5117144812511"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1211720481354"><a name="p1211720481354"></a><a name="p1211720481354"></a>当前激活个数</p>
</td>
</tr>
<tr id="row46831502520"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1267755016515"><a name="p1267755016515"></a><a name="p1267755016515"></a>corePoolSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16776506515"><a name="p16776506515"></a><a name="p16776506515"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p8677115010519"><a name="p8677115010519"></a><a name="p8677115010519"></a>核心线程数</p>
</td>
</tr>
<tr id="row1568265019512"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p106771050357"><a name="p106771050357"></a><a name="p106771050357"></a>maximumPoolSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1067765010520"><a name="p1067765010520"></a><a name="p1067765010520"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p136777504517"><a name="p136777504517"></a><a name="p136777504517"></a>最大核心线程数</p>
</td>
</tr>
<tr id="row2068245012515"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1267845016520"><a name="p1267845016520"></a><a name="p1267845016520"></a>poolSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p167835015519"><a name="p167835015519"></a><a name="p167835015519"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p8678125015518"><a name="p8678125015518"></a><a name="p8678125015518"></a>线程池大小</p>
</td>
</tr>
<tr id="row136605541953"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p136472541154"><a name="p136472541154"></a><a name="p136472541154"></a>queueSize</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p126474541651"><a name="p126474541651"></a><a name="p126474541651"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1564716545510"><a name="p1564716545510"></a><a name="p1564716545510"></a>等待队列大小</p>
</td>
</tr>
<tr id="row4660254755"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p964815418518"><a name="p964815418518"></a><a name="p964815418518"></a>taskCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p14648155413511"><a name="p14648155413511"></a><a name="p14648155413511"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p664813541651"><a name="p664813541651"></a><a name="p664813541651"></a>任务数</p>
</td>
</tr>
<tr id="row6660135418517"><td class="cellrowborder" valign="top" width="12%" headers="mcps1.2.6.1.1 "><p id="p66491541758"><a name="p66491541758"></a><a name="p66491541758"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="22.830000000000002%" headers="mcps1.2.6.1.2 "><p id="p26497547516"><a name="p26497547516"></a><a name="p26497547516"></a>version</p>
</td>
<td class="cellrowborder" valign="top" width="16.580000000000002%" headers="mcps1.2.6.1.3 "><p id="p46491854857"><a name="p46491854857"></a><a name="p46491854857"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="11.899999999999999%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="36.69%" headers="mcps1.2.6.1.5 "><p id="p186501654954"><a name="p186501654954"></a><a name="p186501654954"></a>客户端版本</p>
</td>
</tr>
</tbody>
</table>

