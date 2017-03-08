<p>
    <strong><span style="font-size: 19px;line-height: 173%;font-family: 微软雅黑, sans-serif;background: white">TypeSdk</span></strong><strong><span style="font-size: 19px;line-height: 173%;font-family: 微软雅黑, sans-serif;background: white">是一个手机游戏渠道SDK开源接入框架，解决手机游戏发布需要耗费大量人力和时间接入不同渠道SDK的问题， 并解决发行过程中大量隐藏的问题，实现一次接入多渠道上线。 TypeSDK支持Unity3D、cocos2项目开发的手机游戏，支持发布Android和IOS游戏渠道包。 游戏开发者可安上线需求自行部署和管理线上环境和编译环境， 运营数据不通过第三方转发，直接与渠道签约和收款，无需担心游戏代码外泄、运营数据外流、被第三方扣量扣款等风险。</span></strong>
</p>
<hr/>
<p>
    <strong style="color: rgb(84, 141, 212); font-size: 18px;"><span style="font-family: 微软雅黑, sans-serif; background: white;">接入TYPESDK后，复杂的渠道接口处理以及兼容性问题就转由TYPESDK来处理了，而开发者只需要接入TYPESDK所提供的接口，就可以一次接入，多渠道上线。此时的架构如图所示</span></strong><br/>
</p>
<p style="margin-top:5px;margin-right:0;margin-bottom:5px;margin-left: 0">
    <span style="font-family: Arial, sans-serif; font-size: 18px;">&nbsp;</span>
</p>
<p style="text-align:center">
    <img src="http://120.132.11.160:30003/123.png" title="demo.jpg" alt="demo.jpg" width="607" height="392"/>
</p>
<p style="margin-top:5px;margin-right:0;margin-bottom:5px;margin-left: 0">
    <span style="font-family: Arial, sans-serif"></span>
</p>
<hr/>
<p>
    <strong style="color: rgb(84, 141, 212);"><span style="font-size: 19px; line-height: 173%; font-family: 黑体;">TypeSdkServer</span></strong><strong style="color: rgb(84, 141, 212);"><span style="font-size: 19px; line-height: 173%; font-family: 黑体;">是TypeSdk统一渠道接入框架的服务端，主要包含：</span></strong><br/>
</p>
<h2 style="margin: 5px 0 16px 48px;text-indent: 40px">
    <span style="color: rgb(84, 141, 212);"><strong><span style="color: rgb(84, 141, 212); font-size: 19px; line-height: 173%; font-family: 黑体;">1</span></strong><strong><span style="color: rgb(84, 141, 212); font-size: 19px; line-height: 173%; font-family: 黑体;">、渠道用户验证</span></strong></span>
</h2>
<h2 style="margin: 5px 0 16px 48px;text-indent: 40px">
    <span style="color: rgb(84, 141, 212);"><strong><span style="color: rgb(84, 141, 212); font-size: 19px; line-height: 173%; font-family: 黑体;">2</span></strong><strong><span style="color: rgb(84, 141, 212); font-size: 19px; line-height: 173%; font-family: 黑体;">、处理支付回调</span></strong></span>
</h2>
<h2 style="margin: 5px 0 16px 48px;text-indent: 40px">
    <span style="color: rgb(84, 141, 212);"><strong><span style="color: rgb(84, 141, 212); font-size: 19px; line-height: 173%; font-family: 黑体;">3</span></strong><strong><span style="color: rgb(84, 141, 212); font-size: 19px; line-height: 173%; font-family: 黑体;">、商品信息校验</span></strong></span><span style="font-family: Arial, sans-serif"></span>
</h2>
<p>
    <a></a>
</p>
<hr/>
<p>
    <span style="color: rgb(255, 0, 0); font-family: 黑体; font-size: 19px; background-color: white;">特别注意：</span><br/>
</p>
<h3 style="margin: 16px 0;background: white">
    <span style="color: rgb(255, 0, 0);"><span style="color: rgb(255, 0, 0); font-size: 19px; font-family: Arial, sans-serif;">1</span><span style="color: rgb(255, 0, 0); font-size: 19px;">、</span><span style="color: rgb(255, 0, 0); font-size: 19px; font-family: 黑体;">TypeSdkServer负担着整个游戏的登入和支付，请务必考虑冗余</span></span>
</h3>
<h3 style="margin: 16px 0;background: white">
    <span style="color: rgb(255, 0, 0);"><span style="color: rgb(255, 0, 0); font-size: 19px; font-family: Arial, sans-serif;">2</span><span style="color: rgb(255, 0, 0); font-size: 19px;">、</span><span style="color: rgb(255, 0, 0); font-size: 19px; font-family: 黑体;">少数用户会伪造订单进行攻击，务必使用商品校验接口，确保安全</span></span>
</h3>
<p>
    <span style="color: rgb(255, 0, 0);"><span style="color: rgb(255, 0, 0); font-size: 19px; font-family: 黑体;"></span></span>
</p>
<h3 style="white-space: normal; margin: 16px 0px; background: white;">
    <span style="color: rgb(255, 0, 0);"><span style="font-size: 19px; font-family: Arial, sans-serif;">3</span><span style="font-size: 19px;">、<span style="font-family:黑体">安装脚本目前支持Centos_7.x_x86_64</span></span></span>
</h3>
<hr/>
<p>
    <span style="font-family: 黑体;">联系QQ：1771930259</span><br/>
</p>
<p style="margin: 0 0 16px">
    <span style="font-family: 黑体">官方网站：</span><a href="http://www.typesdk.com/"><span style="font-family:黑体;color:black">http://www.typesdk.com</span></a>
</p>
<p style="margin: 0 0 16px">
    <span style="font-family: 黑体">支持渠道列表：</span><a href="http://www.typesdk.com/"><span style="font-family:黑体;color:black">支持列表</span></a>
</p>
<p style="margin: 0 0 16px">
    <span style="font-family: 黑体">TypeSdkServer服务器部署文档：</span><a href="http://www.typesdk.com/docs/typesdk_install/typesdk_server/"><span style="font-family:黑体;color:black">服务器部署文档</span></a>
</p>
<p style="margin: 0 0 16px">
    <span style="font-family: 黑体">游戏服务器接入文档：</span><a href="http://www.typesdk.com/docs/%E6%9C%8D%E5%8A%A1%E7%AB%AF/"><span style="font-family:黑体;color:black">游戏服务器接入文档</span></a>
</p>
<p style="margin: 0 0 16px">
    <span style="font-family: 黑体">DEMO演示地址：</span><a href="http://demo.typesdk.com:56789/"><span style="font-family:黑体;color:black">演示地址</span></a><span style="font-family: Calibri, sans-serif">&nbsp;</span><span style="font-family: 黑体">（用户名和密码：demo@typesdk.com/123.com）</span>
</p>
<p style="margin: 5px 0 16px">
    <span style="font-family: 黑体">安装完成后请检查TCP:80;40000;3306;6379是否都已经开通</span>
</p>
<p style="margin: 5px 0px 16px;">
    <span style="font-family:黑体">通过访问：http://ip:40000/1001/301/Login能返回json就说明部署成功</span>
</p>