
<p align="center">
	<a href="https://www.yuandalao.com/#/index"><img src="https://vkceyugu.cdn.bspapp.com/VKCEYUGU-fe88ac54-ee24-4fe0-a14c-fdf4e0a87f4d/ec66a3f7-2c9b-4c4d-baa9-7dbcdba111a9.png" width="400"></a>
</p>
<p align="center">
	<strong>猿大佬助力技术同胞换现</strong>
</p>
<p align="center">
	
   [猿大佬观网](https://www.yuandalao.com)
   
   [技术换现后台](https://www.yuandalao.com/merchant)
<p>
	<a target="_blank" href='https://github.com/zhangyd-c/JustAuth'>
		<img src="https://img.shields.io/github/stars/2792273/programmer-makemoney?style=social" alt="github star"></img>
	</a>
	<a target="_blank" href="https://gitee.com/hongyanli_admin/programmer-makemoney/blob/master/LICENSE">
		<img src="https://img.shields.io/apm/l/vim-mode.svg?color=yellow">
	</a>
	<a target="_blank" href="https://www.oracle.com/technetwork/java/javase/downloads/index.html" rel="nofollow">
		<img src="https://img.shields.io/badge/JDK-1.8+-green.svg">
	</a>
</p>	
	
</p>
-------------------------------------------------------------------------------
  

## 什么是 猿大佬？
<a href="https://www.yuandalao.com" target="_blank">猿大佬（YuanDaLao)</a>是国内一家专注技术资源整合、垂直于软件技术服务领域的新型平台。平台聚集世界各地的优秀程序员，他们在各自的技术领域都有一定的建树，在线为中小微企业提供专业的技术服务。平台采用大数据，对技术和企业进行智能化匹配。秉承着

最好的人做最好的事的原则。猿大佬平台不仅为雇主提供解决方案服务，还帮助广大IT从业人员实现真正意义上的**技术变现**，我们励志成为技术和企业的桥梁，让企业和技术人实现价值的最大化！



## 有哪些优势？
  1、海量用户流量：与tb、aliyun紧密合作。
  
  2、门槛低：个人开发者即可入驻使用。
  
  3、0抽成：无任何抽成，开发者赚多少，收入即为多少。
  
## 有哪些项目？
 平台内包含商城、社区团购、OA、ERP、Saas、官网（门户店）、餐饮外卖、社交通讯、游戏、财务、只能工具、视频授课等多种系统，其中包括微信小程序、h5、pc、安卓、ios等多端载体！
 
## 联系我们
 <p align="center">
<p>猿大佬1群 已满</p>
<p>猿大佬2群 已满</p>
<p>猿大佬3群 已满</p>
<p>猿大佬4群 已满</p>
<p>猿大佬5群 已满</p>
<p>猿大佬6群 已满</p>
<p>猿大佬7群 <a target="_blank" href="https://qm.qq.com/cgi-bin/qm/qr?k=ZAbazRyv3ggNdNAJdZl5Wnw46X5nKm2B&jump_from=webapi"><img border="0" src="//pub.idqqimg.com/wpa/images/group.png" alt="猿大佬7群" title="猿大佬7群"></a>
</p>
-
## 快速开始

- 引入依赖
```xml
<dependency>
    <groupId>me.zhyd.oauth</groupId>
    <artifactId>JustAuth</artifactId>
    <version>1.16.0</version>
</dependency>
```
- 调用api
```java
// 创建授权request
AuthRequest authRequest = new AuthGiteeRequest(AuthConfig.builder()
        .clientId("clientId")
        .clientSecret("clientSecret")
        .redirectUri("redirectUri")
        .build());
// 生成授权页面
authRequest.authorize("state");
// 授权登录后会返回code（auth_code（仅限支付宝））、state，1.8.0版本后，可以用AuthCallback类作为回调接口的参数
// 注：JustAuth默认保存state的时效为3分钟，3分钟内未使用则会自动清除过期的state
authRequest.login(callback);
```

如下**任选一种** HTTP 工具 依赖，_项目内如果已有，请忽略。另外需要特别注意，如果项目中已经引入了低版本的依赖，请先排除低版本以后来，引入高版本或者最新版本的依赖_

- hutool-http

  ```xml
  <dependency>
      <groupId>cn.hutool</groupId>
      <artifactId>hutool-http</artifactId>
      <version>5.2.5</version>
  </dependency>
  ```

- httpclient

  ```xml
  <dependency>
  	<groupId>org.apache.httpcomponents</groupId>
    	<artifactId>httpclient</artifactId>
    	<version>4.5.12</version>
  </dependency>
  ```

- okhttp

  ```xml
  <dependency>
    <groupId>com.squareup.okhttp3</groupId>
    <artifactId>okhttp</artifactId>
    <version>4.4.1</version>
  </dependency>
  ```

## 赞助和支持

感谢以下赞助商的支持：

<a href="https://www.duohui.cn?utm_source=justauth" target="_blank"><img src="https://docs.duohui.cn/brand_source/img/std.svg" alt="多会 - 专业活动管理系统" style="height: 54px;" height="54px" /></a>

## JustAuth 的用户
有很多公司、组织和个人把 JustAuth 用于学习、研究、生产环境和商业产品中，包括（但不限于）：
[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-VfJQ8V4W-1618212829882)(docs/users/4ca0177c.png)]


怎么没有我？[登记](https://gitee.com/yadong.zhang/JustAuth/issues/IZ2T7)

## 开源推荐
- `JAP` 开源的登录认证中间件: [https://gitee.com/fujieid/jap](https://gitee.com/fujieid/jap)
- `spring-boot-demo` 深度学习并实战 spring boot 的项目: [https://github.com/xkcoding/spring-boot-demo](https://github.com/xkcoding/spring-boot-demo)
- `mica` SpringBoot 微服务高效开发工具集: [https://github.com/lets-mica/mica](https://github.com/lets-mica/mica)
- `pig` 微服务认证授权脚手架(架构师必备): [https://gitee.com/log4j/pig](https://gitee.com/log4j/pig)
- `SpringBlade` 完整的线上解决方案（企业开发必备）: [https://gitee.com/smallc/SpringBlade](https://gitee.com/smallc/SpringBlade)
- `MaxKey` 马克思的钥匙，寓意是最大钥匙,是用户单点登录认证系统（Sigle Sign On System）,OAuth 2.0/OpenID Connect、SAML 2.0、JWT、CAS等标准化的开放协议，使用JustAuth集成OAuth第三方认证。: [https://shimingxy.github.io/MaxKey/](https://shimingxy.github.io/MaxKey/)
- `YurunOAuthLogin` PHP 第三方登录授权 SDK：[YurunOAuthLogin](https://gitee.com/yurunsoft/YurunOAuthLogin)

## 鸣谢
- 感谢 JetBrains 提供的免费开源 License：
<img src="https://images.gitee.com/uploads/images/2020/0406/220236_f5275c90_5531506.png" alt="图片引用自lets-mica" style="float:left;">

## 其他
- [CONTRIBUTORS](https://justauth.wiki/contributors.html)
- [CHANGELOGS](https://justauth.wiki/update.html)
- [PLAN](https://gitee.com/yadong.zhang/JustAuth/issues/IUGRK)

## 贡献者列表

[![contributors](https://img-blog.csdnimg.cn/img_convert/6217831420d7a6235be13cd681e0f30c.gif)](https://whnb.wang)

## Stars 趋势

### Gitee

[![Stargazers over time](https://img-blog.csdnimg.cn/img_convert/34f636eb8824600de3fedc1d7c65e582.gif)](https://whnb.wang/yadong.zhang/JustAuth?e=604800)

### Github

[[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-YrwTSS3G-1618212829908)(https://starchart.cc/justauth/JustAuth.svg)]](https://starchart.cc/justauth/JustAuth)

### ProductHunt

<a href="https://www.producthunt.com/posts/justauth?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-justauth" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=196886&theme=dark" alt="JustAuth - Login, so easy! | Product Hunt Embed" style="width: 250px; height: 54px;" width="250px" height="54px" /></a>
