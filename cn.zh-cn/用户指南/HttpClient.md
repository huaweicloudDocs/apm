# HttpClient<a name="apm_07_0041"></a>

**表 1**  HttpClient客户端调用监控指标

<a name="table16251144322111"></a>
<table><thead align="left"><tr id="row125264362114"><th class="cellrowborder" valign="top" width="15.73%" id="mcps1.2.6.1.1"><p id="p18403193013258"><a name="p18403193013258"></a><a name="p18403193013258"></a>指标集</p>
</th>
<th class="cellrowborder" valign="top" width="23.13%" id="mcps1.2.6.1.2"><p id="p134031730102516"><a name="p134031730102516"></a><a name="p134031730102516"></a>字段名称</p>
</th>
<th class="cellrowborder" valign="top" width="13.63%" id="mcps1.2.6.1.3"><p id="p340343016256"><a name="p340343016256"></a><a name="p340343016256"></a>字段类型</p>
</th>
<th class="cellrowborder" valign="top" width="12.11%" id="mcps1.2.6.1.4"><p id="p10403103062514"><a name="p10403103062514"></a><a name="p10403103062514"></a>字段单位</p>
</th>
<th class="cellrowborder" valign="top" width="35.4%" id="mcps1.2.6.1.5"><p id="p104031430142514"><a name="p104031430142514"></a><a name="p104031430142514"></a>字段说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row14252184332119"><td class="cellrowborder" rowspan="5" valign="top" width="15.73%" headers="mcps1.2.6.1.1 "><p id="p5252204382120"><a name="p5252204382120"></a><a name="p5252204382120"></a></p>
<p id="p125218434213"><a name="p125218434213"></a><a name="p125218434213"></a></p>
<p id="p1125216439214"><a name="p1125216439214"></a><a name="p1125216439214"></a>exception</p>
<p id="p925244316214"><a name="p925244316214"></a><a name="p925244316214"></a></p>
<p id="p14253204372117"><a name="p14253204372117"></a><a name="p14253204372117"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.13%" headers="mcps1.2.6.1.2 "><p id="p1225210433212"><a name="p1225210433212"></a><a name="p1225210433212"></a>exceptionType</p>
</td>
<td class="cellrowborder" valign="top" width="13.63%" headers="mcps1.2.6.1.3 "><p id="p1525294372118"><a name="p1525294372118"></a><a name="p1525294372118"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="12.11%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.4%" headers="mcps1.2.6.1.5 "><p id="p625219433214"><a name="p625219433214"></a><a name="p625219433214"></a>异常类型</p>
</td>
</tr>
<tr id="row7252343182116"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p172521343102115"><a name="p172521343102115"></a><a name="p172521343102115"></a>causeType</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p15252114322116"><a name="p15252114322116"></a><a name="p15252114322116"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p19252194313212"><a name="p19252194313212"></a><a name="p19252194313212"></a>发生异常的类</p>
</td>
</tr>
<tr id="row1252043152111"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p525234310212"><a name="p525234310212"></a><a name="p525234310212"></a>count</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p10252124322120"><a name="p10252124322120"></a><a name="p10252124322120"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1225264314212"><a name="p1225264314212"></a><a name="p1225264314212"></a>异常发生次数</p>
</td>
</tr>
<tr id="row425244312118"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1525214319218"><a name="p1525214319218"></a><a name="p1525214319218"></a>message</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p3252104311211"><a name="p3252104311211"></a><a name="p3252104311211"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1825274392119"><a name="p1825274392119"></a><a name="p1825274392119"></a>异常消息</p>
</td>
</tr>
<tr id="row125218433217"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1825334352120"><a name="p1825334352120"></a><a name="p1825334352120"></a>stackTrace</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p142531437215"><a name="p142531437215"></a><a name="p142531437215"></a>CLOB</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1625344362117"><a name="p1625344362117"></a><a name="p1625344362117"></a>异常堆栈信息</p>
</td>
</tr>
<tr id="row163711435104210"><td class="cellrowborder" rowspan="14" valign="top" width="15.73%" headers="mcps1.2.6.1.1 "><p id="p153681435134214"><a name="p153681435134214"></a><a name="p153681435134214"></a></p>
<p id="p1793853713420"><a name="p1793853713420"></a><a name="p1793853713420"></a></p>
<p id="p15939103718421"><a name="p15939103718421"></a><a name="p15939103718421"></a></p>
<p id="p1679193920420"><a name="p1679193920420"></a><a name="p1679193920420"></a></p>
<p id="p15791163934214"><a name="p15791163934214"></a><a name="p15791163934214"></a></p>
<p id="p1879273917424"><a name="p1879273917424"></a><a name="p1879273917424"></a></p>
<p id="p27921239174216"><a name="p27921239174216"></a><a name="p27921239174216"></a></p>
<p id="p512234264215"><a name="p512234264215"></a><a name="p512234264215"></a>hostInvocation</p>
<p id="p1612284294215"><a name="p1612284294215"></a><a name="p1612284294215"></a></p>
<p id="p14123042164213"><a name="p14123042164213"></a><a name="p14123042164213"></a></p>
<p id="p171233427426"><a name="p171233427426"></a><a name="p171233427426"></a></p>
<p id="p9124124294219"><a name="p9124124294219"></a><a name="p9124124294219"></a></p>
<p id="p1712444224216"><a name="p1712444224216"></a><a name="p1712444224216"></a></p>
<p id="p41259421422"><a name="p41259421422"></a><a name="p41259421422"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.13%" headers="mcps1.2.6.1.2 "><p id="p1936815353425"><a name="p1936815353425"></a><a name="p1936815353425"></a>envId</p>
</td>
<td class="cellrowborder" valign="top" width="13.63%" headers="mcps1.2.6.1.3 "><p id="p63692355426"><a name="p63692355426"></a><a name="p63692355426"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="12.11%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.4%" headers="mcps1.2.6.1.5 "><p id="p43691935194215"><a name="p43691935194215"></a><a name="p43691935194215"></a>被调用方的集群id</p>
</td>
</tr>
<tr id="row794217371429"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p093914375422"><a name="p093914375422"></a><a name="p093914375422"></a>hostUri</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p12939137184217"><a name="p12939137184217"></a><a name="p12939137184217"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1793903714421"><a name="p1793903714421"></a><a name="p1793903714421"></a>被调用的地址</p>
</td>
</tr>
<tr id="row194243734213"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p493993744218"><a name="p493993744218"></a><a name="p493993744218"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p129399375424"><a name="p129399375424"></a><a name="p129399375424"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p10939537144211"><a name="p10939537144211"></a><a name="p10939537144211"></a>错误次数</p>
</td>
</tr>
<tr id="row187981439104212"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1779110395423"><a name="p1779110395423"></a><a name="p1779110395423"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p12791133974220"><a name="p12791133974220"></a><a name="p12791133974220"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p3791113918424"><a name="p3791113918424"></a><a name="p3791113918424"></a>调用次数</p>
</td>
</tr>
<tr id="row17982392423"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p179112395425"><a name="p179112395425"></a><a name="p179112395425"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1479153918424"><a name="p1479153918424"></a><a name="p1479153918424"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p1779110395425"><a name="p1779110395425"></a><a name="p1779110395425"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1579110399429"><a name="p1579110399429"></a><a name="p1579110399429"></a>最大响应时间</p>
</td>
</tr>
<tr id="row1879883954213"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p47924397427"><a name="p47924397427"></a><a name="p47924397427"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p19792113915425"><a name="p19792113915425"></a><a name="p19792113915425"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p197921539154216"><a name="p197921539154216"></a><a name="p197921539154216"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p57923399424"><a name="p57923399424"></a><a name="p57923399424"></a>总响应时间</p>
</td>
</tr>
<tr id="row14798163994215"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1979211393425"><a name="p1979211393425"></a><a name="p1979211393425"></a>responseCloseCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p479243944216"><a name="p479243944216"></a><a name="p479243944216"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p77921399422"><a name="p77921399422"></a><a name="p77921399422"></a><span>响应关闭次数</span></p>
</td>
</tr>
<tr id="row8138642194210"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p012219427424"><a name="p012219427424"></a><a name="p012219427424"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p3108162711496"><a name="p3108162711496"></a><a name="p3108162711496"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p20122442114215"><a name="p20122442114215"></a><a name="p20122442114215"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row5138184217424"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p5122144274218"><a name="p5122144274218"></a><a name="p5122144274218"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p191087271494"><a name="p191087271494"></a><a name="p191087271494"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p171221942204214"><a name="p171221942204214"></a><a name="p171221942204214"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row141381142164210"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4123164212423"><a name="p4123164212423"></a><a name="p4123164212423"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p01091027114915"><a name="p01091027114915"></a><a name="p01091027114915"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1112364264217"><a name="p1112364264217"></a><a name="p1112364264217"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row1713713429425"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p10123104218422"><a name="p10123104218422"></a><a name="p10123104218422"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p17368182819498"><a name="p17368182819498"></a><a name="p17368182819498"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p171236426426"><a name="p171236426426"></a><a name="p171236426426"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row12137114211427"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p131246429424"><a name="p131246429424"></a><a name="p131246429424"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7368182814497"><a name="p7368182814497"></a><a name="p7368182814497"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p712417423422"><a name="p712417423422"></a><a name="p712417423422"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row61371842144219"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p3124154219422"><a name="p3124154219422"></a><a name="p3124154219422"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p6368122884918"><a name="p6368122884918"></a><a name="p6368122884918"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p412413427423"><a name="p412413427423"></a><a name="p412413427423"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row12137174210425"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p14125142154215"><a name="p14125142154215"></a><a name="p14125142154215"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p111251942104213"><a name="p111251942104213"></a><a name="p111251942104213"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p7125742144210"><a name="p7125742144210"></a><a name="p7125742144210"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row1613717429423"><td class="cellrowborder" rowspan="2" valign="top" width="15.73%" headers="mcps1.2.6.1.1 "><p id="p15125164218421"><a name="p15125164218421"></a><a name="p15125164218421"></a>info</p>
<p id="p199001845134211"><a name="p199001845134211"></a><a name="p199001845134211"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.13%" headers="mcps1.2.6.1.2 "><p id="p14125942194216"><a name="p14125942194216"></a><a name="p14125942194216"></a>httpClientVersion</p>
</td>
<td class="cellrowborder" valign="top" width="13.63%" headers="mcps1.2.6.1.3 "><p id="p12125134212424"><a name="p12125134212424"></a><a name="p12125134212424"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" width="12.11%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.4%" headers="mcps1.2.6.1.5 "><p id="p151256428422"><a name="p151256428422"></a><a name="p151256428422"></a>httpclient包的版本</p>
</td>
</tr>
<tr id="row8938645194220"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p190004510426"><a name="p190004510426"></a><a name="p190004510426"></a>httpCoreVersion</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p490074514216"><a name="p490074514216"></a><a name="p490074514216"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1690012455424"><a name="p1690012455424"></a><a name="p1690012455424"></a>httpCore包的版本</p>
</td>
</tr>
<tr id="row14938645114216"><td class="cellrowborder" rowspan="21" valign="top" width="15.73%" headers="mcps1.2.6.1.1 "><p id="p18900154584211"><a name="p18900154584211"></a><a name="p18900154584211"></a></p>
<p id="p9901144514211"><a name="p9901144514211"></a><a name="p9901144514211"></a></p>
<p id="p290217454421"><a name="p290217454421"></a><a name="p290217454421"></a></p>
<p id="p2090224520421"><a name="p2090224520421"></a><a name="p2090224520421"></a></p>
<p id="p1190314515428"><a name="p1190314515428"></a><a name="p1190314515428"></a></p>
<p id="p6903124594215"><a name="p6903124594215"></a><a name="p6903124594215"></a></p>
<p id="p990410450423"><a name="p990410450423"></a><a name="p990410450423"></a></p>
<p id="p2905204584215"><a name="p2905204584215"></a><a name="p2905204584215"></a></p>
<p id="p8905144514212"><a name="p8905144514212"></a><a name="p8905144514212"></a></p>
<p id="p11906174584218"><a name="p11906174584218"></a><a name="p11906174584218"></a></p>
<p id="p5906154511426"><a name="p5906154511426"></a><a name="p5906154511426"></a>invocation</p>
<p id="p4907124514429"><a name="p4907124514429"></a><a name="p4907124514429"></a></p>
<p id="p2908104544218"><a name="p2908104544218"></a><a name="p2908104544218"></a></p>
<p id="p119081945104213"><a name="p119081945104213"></a><a name="p119081945104213"></a></p>
<p id="p16909184519423"><a name="p16909184519423"></a><a name="p16909184519423"></a></p>
<p id="p10965113184610"><a name="p10965113184610"></a><a name="p10965113184610"></a></p>
<p id="p14966143184616"><a name="p14966143184616"></a><a name="p14966143184616"></a></p>
<p id="p996783144611"><a name="p996783144611"></a><a name="p996783144611"></a></p>
<p id="p05331565466"><a name="p05331565466"></a><a name="p05331565466"></a></p>
<p id="p1353315614467"><a name="p1353315614467"></a><a name="p1353315614467"></a></p>
<p id="p125346694618"><a name="p125346694618"></a><a name="p125346694618"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.13%" headers="mcps1.2.6.1.2 "><p id="p19018457421"><a name="p19018457421"></a><a name="p19018457421"></a>url</p>
</td>
<td class="cellrowborder" valign="top" width="13.63%" headers="mcps1.2.6.1.3 "><p id="p1901174544211"><a name="p1901174544211"></a><a name="p1901174544211"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="12.11%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.4%" headers="mcps1.2.6.1.5 "><p id="p20901174514215"><a name="p20901174514215"></a><a name="p20901174514215"></a>被调用接口的url</p>
</td>
</tr>
<tr id="row11938114584215"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p14901845184214"><a name="p14901845184214"></a><a name="p14901845184214"></a>method</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p11901154512421"><a name="p11901154512421"></a><a name="p11901154512421"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p59011345144216"><a name="p59011345144216"></a><a name="p59011345144216"></a>被调用接口的httpmethod</p>
</td>
</tr>
<tr id="row149381845174211"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p0902745134210"><a name="p0902745134210"></a><a name="p0902745134210"></a>client</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p590219454424"><a name="p590219454424"></a><a name="p590219454424"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p4902124517429"><a name="p4902124517429"></a><a name="p4902124517429"></a>客户端类型</p>
</td>
</tr>
<tr id="row1993754564211"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1690294510424"><a name="p1690294510424"></a><a name="p1690294510424"></a>concurrentMax</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1090234511427"><a name="p1090234511427"></a><a name="p1090234511427"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1390334519427"><a name="p1390334519427"></a><a name="p1390334519427"></a>最大并发</p>
</td>
</tr>
<tr id="row1193718452421"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p109039452428"><a name="p109039452428"></a><a name="p109039452428"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1490324517427"><a name="p1490324517427"></a><a name="p1490324517427"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p890344511421"><a name="p890344511421"></a><a name="p890344511421"></a>错误次数</p>
</td>
</tr>
<tr id="row19371545174212"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1090418454428"><a name="p1090418454428"></a><a name="p1090418454428"></a>errorTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p209041945124211"><a name="p209041945124211"></a><a name="p209041945124211"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p13904124511421"><a name="p13904124511421"></a><a name="p13904124511421"></a>采集周期内发生错误的调用链对应的traceid</p>
</td>
</tr>
<tr id="row5937114518423"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p19048453424"><a name="p19048453424"></a><a name="p19048453424"></a>slowTraceId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p159046452429"><a name="p159046452429"></a><a name="p159046452429"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p14904144515421"><a name="p14904144515421"></a><a name="p14904144515421"></a>采集周期内最慢的调用链对应的traceid</p>
</td>
</tr>
<tr id="row0936745184213"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p109054455425"><a name="p109054455425"></a><a name="p109054455425"></a>hostUri</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p10905204534215"><a name="p10905204534215"></a><a name="p10905204534215"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p953603519207"><a name="p953603519207"></a><a name="p953603519207"></a>调用地址</p>
</td>
</tr>
<tr id="row1593624514426"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p19905134544214"><a name="p19905134544214"></a><a name="p19905134544214"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1390515455427"><a name="p1390515455427"></a><a name="p1390515455427"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p15906045124216"><a name="p15906045124216"></a><a name="p15906045124216"></a>调用次数</p>
</td>
</tr>
<tr id="row8936144514210"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4906114514217"><a name="p4906114514217"></a><a name="p4906114514217"></a>lastError</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p10906645164219"><a name="p10906645164219"></a><a name="p10906645164219"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p10582115510203"><a name="p10582115510203"></a><a name="p10582115510203"></a>发生错误时产生的错误信息</p>
</td>
</tr>
<tr id="row5936145114218"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p4907104534219"><a name="p4907104534219"></a><a name="p4907104534219"></a>maxTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p0907184544218"><a name="p0907184544218"></a><a name="p0907184544218"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p12907445114210"><a name="p12907445114210"></a><a name="p12907445114210"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p390754564210"><a name="p390754564210"></a><a name="p390754564210"></a>最大响应时间</p>
</td>
</tr>
<tr id="row89359455422"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p14907164504211"><a name="p14907164504211"></a><a name="p14907164504211"></a>responseCloseCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p590794519425"><a name="p590794519425"></a><a name="p590794519425"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p164961832119"><a name="p164961832119"></a><a name="p164961832119"></a><span>响应关闭次数</span></p>
</td>
</tr>
<tr id="row89351045124214"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p0908045194216"><a name="p0908045194216"></a><a name="p0908045194216"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1790874516426"><a name="p1790874516426"></a><a name="p1790874516426"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p17908174564220"><a name="p17908174564220"></a><a name="p17908174564220"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p97142612118"><a name="p97142612118"></a><a name="p97142612118"></a>总响应时间</p>
</td>
</tr>
<tr id="row159350453422"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p15908154520428"><a name="p15908154520428"></a><a name="p15908154520428"></a>range1</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p18791735125014"><a name="p18791735125014"></a><a name="p18791735125014"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p82591233192115"><a name="p82591233192115"></a><a name="p82591233192115"></a>响应时间在0-10ms范围请求数</p>
</td>
</tr>
<tr id="row893484524211"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p12171133120463"><a name="p12171133120463"></a><a name="p12171133120463"></a>range2</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p107923515506"><a name="p107923515506"></a><a name="p107923515506"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p132596336217"><a name="p132596336217"></a><a name="p132596336217"></a>响应时间在10-100ms范围请求数</p>
</td>
</tr>
<tr id="row1997012314619"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p717153144617"><a name="p717153144617"></a><a name="p717153144617"></a>range3</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p177913512503"><a name="p177913512503"></a><a name="p177913512503"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p16259133202116"><a name="p16259133202116"></a><a name="p16259133202116"></a>响应时间在100-500ms范围请求数</p>
</td>
</tr>
<tr id="row19701324619"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1171631134615"><a name="p1171631134615"></a><a name="p1171631134615"></a>range4</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p16799357500"><a name="p16799357500"></a><a name="p16799357500"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p17259153312212"><a name="p17259153312212"></a><a name="p17259153312212"></a>响应时间在500-1000ms范围请求数</p>
</td>
</tr>
<tr id="row09707374613"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1417123118469"><a name="p1417123118469"></a><a name="p1417123118469"></a>range5</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p68011352506"><a name="p68011352506"></a><a name="p68011352506"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p7259103315217"><a name="p7259103315217"></a><a name="p7259103315217"></a>响应时间在1-10s范围请求数</p>
</td>
</tr>
<tr id="row85418619463"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1717123174614"><a name="p1717123174614"></a><a name="p1717123174614"></a>range6</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p158013355500"><a name="p158013355500"></a><a name="p158013355500"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p7259133392112"><a name="p7259133392112"></a><a name="p7259133392112"></a>响应时间在10s以上请求数</p>
</td>
</tr>
<tr id="row454116684614"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p617113115461"><a name="p617113115461"></a><a name="p617113115461"></a>ranges</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p08033514502"><a name="p08033514502"></a><a name="p08033514502"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p426063322115"><a name="p426063322115"></a><a name="p426063322115"></a>自定义响应时间区间</p>
</td>
</tr>
<tr id="row135411266467"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1653414618462"><a name="p1653414618462"></a><a name="p1653414618462"></a>envId</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p165341869461"><a name="p165341869461"></a><a name="p165341869461"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p155341367468"><a name="p155341367468"></a><a name="p155341367468"></a>集群id</p>
</td>
</tr>
<tr id="row135411466463"><td class="cellrowborder" rowspan="3" valign="top" width="15.73%" headers="mcps1.2.6.1.1 "><p id="p35341662460"><a name="p35341662460"></a><a name="p35341662460"></a></p>
<p id="p1853518611469"><a name="p1853518611469"></a><a name="p1853518611469"></a>not200Code</p>
<p id="p1653520694614"><a name="p1653520694614"></a><a name="p1653520694614"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.13%" headers="mcps1.2.6.1.2 "><p id="p1753456134610"><a name="p1753456134610"></a><a name="p1753456134610"></a>code</p>
</td>
<td class="cellrowborder" valign="top" width="13.63%" headers="mcps1.2.6.1.3 "><p id="p753410654615"><a name="p753410654615"></a><a name="p753410654615"></a>ENUM</p>
</td>
<td class="cellrowborder" valign="top" width="12.11%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.4%" headers="mcps1.2.6.1.5 "><p id="p653596104616"><a name="p653596104616"></a><a name="p653596104616"></a>非200的状态码</p>
</td>
</tr>
<tr id="row1454096174619"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p105351634614"><a name="p105351634614"></a><a name="p105351634614"></a>url</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7535268464"><a name="p7535268464"></a><a name="p7535268464"></a>STRING</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1253556114619"><a name="p1253556114619"></a><a name="p1253556114619"></a>产生对应状态码的url</p>
</td>
</tr>
<tr id="row25401160466"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p115351674615"><a name="p115351674615"></a><a name="p115351674615"></a>count</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1536160466"><a name="p1536160466"></a><a name="p1536160466"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1653611634613"><a name="p1653611634613"></a><a name="p1653611634613"></a>对应状态码的发生次数</p>
</td>
</tr>
<tr id="row2027312913469"><td class="cellrowborder" rowspan="4" valign="top" width="15.73%" headers="mcps1.2.6.1.1 "><p id="p192561296469"><a name="p192561296469"></a><a name="p192561296469"></a></p>
<p id="p162573912462"><a name="p162573912462"></a><a name="p162573912462"></a>total</p>
<p id="p72571597461"><a name="p72571597461"></a><a name="p72571597461"></a></p>
<p id="p162582093467"><a name="p162582093467"></a><a name="p162582093467"></a></p>
</td>
<td class="cellrowborder" valign="top" width="23.13%" headers="mcps1.2.6.1.2 "><p id="p725610954617"><a name="p725610954617"></a><a name="p725610954617"></a>errorCount</p>
</td>
<td class="cellrowborder" valign="top" width="13.63%" headers="mcps1.2.6.1.3 "><p id="p325618917466"><a name="p325618917466"></a><a name="p325618917466"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" width="12.11%" headers="mcps1.2.6.1.4 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" width="35.4%" headers="mcps1.2.6.1.5 "><p id="p1425739134614"><a name="p1425739134614"></a><a name="p1425739134614"></a>总的错误次数</p>
</td>
</tr>
<tr id="row1427311944619"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p42575974620"><a name="p42575974620"></a><a name="p42575974620"></a>invokeCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p6257189124619"><a name="p6257189124619"></a><a name="p6257189124619"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p102578919463"><a name="p102578919463"></a><a name="p102578919463"></a>总的调用次数</p>
</td>
</tr>
<tr id="row22733910464"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p725759154615"><a name="p725759154615"></a><a name="p725759154615"></a>responseCloseCount</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p20258149144618"><a name="p20258149144618"></a><a name="p20258149144618"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 ">&nbsp;&nbsp;</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p15258189144612"><a name="p15258189144612"></a><a name="p15258189144612"></a>总的关闭响应数</p>
</td>
</tr>
<tr id="row1627310910469"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p825869154617"><a name="p825869154617"></a><a name="p825869154617"></a>totalTime</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p1925859104619"><a name="p1925859104619"></a><a name="p1925859104619"></a>INT</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p1125879154618"><a name="p1125879154618"></a><a name="p1125879154618"></a>ms</p>
</td>
<td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p112580974616"><a name="p112580974616"></a><a name="p112580974616"></a>总响应时间</p>
</td>
</tr>
</tbody>
</table>

