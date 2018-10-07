# Tpay 个人微信支付宝收款零手工全自动回调系统
Tpay是微信和支付宝的个人免签全自动回调支付系统 资金直达 个人账户 开源免费 不用预先保存二维码 金额自定义 无需映射 无需vps服务器 手机和web端都支持 响应及时 回调自定 稳定不改原app

### Tpay：全自动，零人工，24小时自动发卡等操作
### Tpay：全自动，零人工，24小时自动发卡等操作   重要的事说几遍？
### Tpay：全自动，零人工，24小时自动发卡等操作
### ------------------------------------我是排版华丽分割线-----------------------------------------------
### Tpay：测试地址
 - 本项目已经部署到线下，可以点此在线测试：http://www.paohuituan.com/pay
 
### Tpay：现有其它项目缺点
 - 1、大部分需要商家微信或支付宝才能实现全自动回调收款
 - 2、很多其它方案实现需要您事先提供很多张定额的二维码截图
 - 3、大部分其它方案是要收取价格很高的扣费率
 - 4、更有甚者很多其它方案，其实只是收款的通知系统而已，还需要手动确认我的天...完全不能实现24小时全自动支付结算等处理
 - 5、有的其它方案金额不能固定，他们的实现方案需要价格有1分钱或几分钱的波动才能实现
 - 6、这个是通病，很多其它方案很麻烦，各种依赖，文件超多，甚至还用到ehcache或redis等缓存框架，还得vps服务器，个人收款用得了这样？
 - 7、其它方案很多采用的是状态栏消息拦截方式，其实这些方案很不稳定

### Tpay：我的特点
 - 1、个人微信或支付宝都可接入本项目
 - 2、不用事先截图保存很多图片，图片都是软件即时生成的最新二维码
 - 3、本系统开源免费给大家使用
 - 4、本系统能实现24小时全自动结算处理等操作，完全的零手工，常用场景为：自动充值、自动续费、自动发卡、自动XXX等业务
 - 5、支付的金额完全可自定义，而且金额没有一分钱的波动
 - 6、本系统简单到吐血，后台7个左右的php文件超小文件，前端就一个界面。但却是用的前后端分享开发的，前端只暴露两个API（一个取，一个问）
 - 7、本系统采用底层HOOK技术，可以做到免root的HOOK方式，超稳定的实现24小时全自动支付结算功能
 - 8、本系统超级简洁，后台只需要配置一个文件，前端只需在一个界面配置即可，一个12元支持php的虚拟空间即可，和vps等说拜拜吧!
 - 9、本系统虽然简洁，但五脏俱全，有加密系统、日志记录系统、充值系统、留言系统、防攻击系统等更多功能

### Tpay：适用场景
 - 1、只要不违法的都可以！例如：
 - 2、自动充值，自动续费、自动发卡
 - 3、收费展示、收费下载、收费通知系统
 

### Tpay：项目展示
 - 1、APP就一个界面（简单，就一个简单配置界面）
 
 ![](http://std.superlist.yaodenglu.com/tpay_page.png)
 
 - 2、后端也只需要配置一个文件（注释超多）
 
 ![](http://std.superlist.yaodenglu.com/php_page.png)
 
 
### Tpay：使用流程
 - 1、安装Xposed框架，不想root的安装virtualxposed也可以。
 - 2、用户下载源码编译安装到手机，不会的可以在这里下载已经编译好的源码：http://www.paohuituan.com/pay
 - 3、后台中有一个文件是配置文件，把配置文件中的值设置来和手机一样
 - 4、在xposed中打勾并重启手机后，先后启动微信和支付宝即可。

### Tpay：技术交流
 - QQ技术群：524901982（群共享有相关的详细资料）
 - 项目测试：http://wwww.paohuituan.com/pay
 
 
### Tpay：感谢捐赠

 ![](http://std.superlist.yaodenglu.com/wechat_pay.png?m=s) 


 ![](http://std.superlist.yaodenglu.com/alipay_pay.png?m=s)
 
 
 
 