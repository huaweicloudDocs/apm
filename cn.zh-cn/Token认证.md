# Token认证<a name="apm_04_0004"></a>

## 应用场景<a name="zh-cn_topic_0024478020_section5608799912249"></a>

当您使用Token认证方式完成认证鉴权时，需要获取用户Token并在调用接口时增加“X-Auth-Token”到业务接口请求消息头中。

本节介绍如何调用接口完成Token认证。如何获取Token值，请参考“[获取用户Token](http://support.huaweicloud.com/api-iam/zh-cn_topic_0057845583.html)”。

## 调用接口步骤<a name="zh-cn_topic_0024478020_section3546598312249"></a>

1.  发送“POST https://_**IAM的Endpoint**_/v3/auth/tokens”，获取IAM的Endpoint及消息体中的区域名称，请参考[表1 IAM的Endpoint](#table611425921310)。

    **表 1**  IAM的Endpoint

    <a name="table611425921310"></a>
    <table><thead align="left"><tr id="row1011585971313"><th class="cellrowborder" valign="top" width="12.1%" id="mcps1.2.6.1.1"><p id="p153091771512"><a name="p153091771512"></a><a name="p153091771512"></a>服务名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.9%" id="mcps1.2.6.1.2"><p id="p1568524404210"><a name="p1568524404210"></a><a name="p1568524404210"></a>区域名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="19%" id="mcps1.2.6.1.3"><p id="p203063717153"><a name="p203063717153"></a><a name="p203063717153"></a>区域</p>
    </th>
    <th class="cellrowborder" valign="top" width="36%" id="mcps1.2.6.1.4"><p id="p4305157131510"><a name="p4305157131510"></a><a name="p4305157131510"></a>终端节点（Endpoint）</p>
    </th>
    <th class="cellrowborder" valign="top" width="15%" id="mcps1.2.6.1.5"><p id="p152828731515"><a name="p152828731515"></a><a name="p152828731515"></a>协议类型</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row811575991315"><td class="cellrowborder" rowspan="6" valign="top" width="12.1%" headers="mcps1.2.6.1.1 "><p id="p9251144117142"><a name="p9251144117142"></a><a name="p9251144117142"></a>IAM</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.9%" headers="mcps1.2.6.1.2 "><p id="p468524404210"><a name="p468524404210"></a><a name="p468524404210"></a>华北-北京一</p>
    </td>
    <td class="cellrowborder" valign="top" width="19%" headers="mcps1.2.6.1.3 "><p id="p725124121418"><a name="p725124121418"></a><a name="p725124121418"></a>cn-north-1</p>
    </td>
    <td class="cellrowborder" valign="top" width="36%" headers="mcps1.2.6.1.4 "><p id="p16251041181410"><a name="p16251041181410"></a><a name="p16251041181410"></a>iam.cn-north-1.myhuaweicloud.com</p>
    </td>
    <td class="cellrowborder" valign="top" width="15%" headers="mcps1.2.6.1.5 "><p id="p225124121414"><a name="p225124121414"></a><a name="p225124121414"></a>HTTPS</p>
    </td>
    </tr>
    <tr id="row73534483131"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p19355848171310"><a name="p19355848171310"></a><a name="p19355848171310"></a>华南-广州</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p5481173481516"><a name="p5481173481516"></a><a name="p5481173481516"></a>cn-south-1</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p848133451518"><a name="p848133451518"></a><a name="p848133451518"></a>iam.cn-south-1.myhuaweicloud.com</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p16481163418155"><a name="p16481163418155"></a><a name="p16481163418155"></a>HTTPS</p>
    </td>
    </tr>
    <tr id="row575175310138"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p107585310133"><a name="p107585310133"></a><a name="p107585310133"></a>华东-上海二</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p7291114911155"><a name="p7291114911155"></a><a name="p7291114911155"></a>cn-east-2</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p142916499155"><a name="p142916499155"></a><a name="p142916499155"></a>iam.cn-east-2.myhuaweicloud.com</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p13291194914157"><a name="p13291194914157"></a><a name="p13291194914157"></a>HTTPS</p>
    </td>
    </tr>
    <tr id="row138141254195912"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p1262410188119"><a name="p1262410188119"></a><a name="p1262410188119"></a>东北-大连</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p2062419181017"><a name="p2062419181017"></a><a name="p2062419181017"></a>cn-northeast-1</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p3624161815119"><a name="p3624161815119"></a><a name="p3624161815119"></a>iam.cn-northeast-1.myhuaweicloud.com</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1062417187118"><a name="p1062417187118"></a><a name="p1062417187118"></a>HTTPS</p>
    </td>
    </tr>
    <tr id="row1194272119012"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p16512124313620"><a name="p16512124313620"></a><a name="p16512124313620"></a>所有</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p18512174314366"><a name="p18512174314366"></a><a name="p18512174314366"></a>ALL</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p5512543123610"><a name="p5512543123610"></a><a name="p5512543123610"></a>iam.myhuaweicloud.com</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p1251214439362"><a name="p1251214439362"></a><a name="p1251214439362"></a>HTTPS</p>
    </td>
    </tr>
    <tr id="row134116281201"><td class="cellrowborder" valign="top" headers="mcps1.2.6.1.1 "><p id="p126654013379"><a name="p126654013379"></a><a name="p126654013379"></a>亚太-香港</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.2 "><p id="p066517033716"><a name="p066517033716"></a><a name="p066517033716"></a>ap-southeast-1</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.3 "><p id="p46654083714"><a name="p46654083714"></a><a name="p46654083714"></a>iam.ap-southeast-1.myhwclouds.com</p>
    </td>
    <td class="cellrowborder" valign="top" headers="mcps1.2.6.1.4 "><p id="p13665180183717"><a name="p13665180183717"></a><a name="p13665180183717"></a>HTTPS</p>
    </td>
    </tr>
    </tbody>
    </table>

    请求内容示例如下：

    ```
    {
      "auth": {
        "identity": {
          "methods": [
            "password"
          ],
          "password": {
            "user": {
              "name": "username",//username为用户名，请根据实际情况替换。
              "password": "password",//password为用户密码，请根据实际情况替换。
              "domain": {
                "name": "domainname"//domainname为域名，请根据实际情况替换。
              }
            }
          }
        },
        "scope": {
          "project": {
            "name": "cn-north-1" //cn-north-1为IAM区域，请根据实际情况替换。
    
          }
        }
      }
    }
    ```

2.  <a name="zh-cn_topic_0024478020_li2615608112249"></a>获取Token。请求响应成功后在响应消息头中包含的“X-Subject-Token”的值即为Token值。
3.  调用业务接口，在请求消息头中增加“X-Auth-Token”，“X-Auth-Token”的取值为[2](#zh-cn_topic_0024478020_li2615608112249)中获取的Token。

