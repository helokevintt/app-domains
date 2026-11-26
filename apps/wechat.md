# 微信 / WeChat 官方域名

核实日期：2026-11-26
来源：https://yfamilys.com/rule/WeChat.list（全文同步，同步日期 2026-11-26）

本文件的域名清单按 Gui 2026-11-26 的要求全文同步自 yfamilys WeChat.list，不再是逐条核实的官方域名清单。`apps/wechat.list` 即该文件原文（仅加了文件头注释），含 12 条域名规则与 9 条 IP-CIDR 规则。

## 清单里的域名

qlogo.cn、qpic.cn（图片 CDN，与 QQ 共用）、servicewechat.com（小程序框架）、tenpay.com（财付通）、wechat.com（国际版官网）、wechatlegal.net（品牌维权平台）、wechatpay.com（微信支付全球站）、weixin.com、weixin.qq.com（国内官网）、weixinbridge.com（对外跳转桥接）、weixinsxy.com、wxapp.tc.qq.com（小程序文件传输）。

另有 9 条 IP-CIDR 规则（腾讯云 IP 段），见 `.list` 文件原文。

## 注意

- 这份同步版比之前核实版少了几个域名：wx.qq.com（网页版登录入口）、wechatpay.cn、wechatpay.com.hk、wxpayglobal.com、tenpayglobal.com、tenpaygo.com（TenPayGo）、wechatos.net、weixin110.qq.com（安全中心单主机）。如果代理分流要覆盖这些，需要另行补回。
- 微信官方不通过邮件索要密码或验证码，客服在 App 内和 help.wechat.com。

## 之前核实的官方主域名（供对照）

wechat.com、weixin.qq.com、wx.qq.com、weixin.com；微信支付由财付通支付科技有限公司运营，主域名 tenpay.com、wechatpay.com、wechatpay.cn；图片 CDN 为 qlogo.cn、qpic.cn。完整核实版清单见本文件同步前的历史版本。
