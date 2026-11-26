# Monzo 官方域名

核实日期：2026-11-26
来源：Monzo 官网 FAQ、Monzo 官网页面、DNS 记录（subdomainfinder / Shodan）

Monzo 没有公布过完整域名清单，以下是能核实的。

## 官网与主站

| 域名 | 用途 |
| --- | --- |
| monzo.com | 官网主站，登录链接也只用这个开头 |
| monzo.co.uk | 跳转到 monzo.com |
| monzo.me | 收款链接，格式为 monzo.me/姓名 |
| monzo.plus | 曾用于 Plus 相关页面，现跳转到官网 |

## 邮件域名

官网 FAQ “Emails from Monzo”：Monzo 发来的邮件只会来自以下域名。

| 域名 | 用途 |
| --- | --- |
| @monzo.com | 官方邮件 |
| @email.monzo.com | 官方邮件 |
| @business.monzo.com | 商业账户邮件 |
| @research.monzo.com | 调研邮件 |
| @customercontent.monzo.com | 代客户发邮件时使用 |
| monzomail.com | 2023 年 4 月之前用于发客户邮件，**现已停用**。官网原话：“This is a domain that we used prior to April 2023 to send emails to customers. We no longer send emails from this domain.” |
| monzoemail.com | 旧的营销邮件域名，官网现行 FAQ 已不再列出 |
| monzo.intercom-mail.com | 旧的 Intercom 客服邮件域名 |

## 其他官方域名

| 域名 | 用途 |
| --- | --- |
| monzo-alt.net | 2023 年 10 月起用于支持客户应用。官网原话：“This is a domain that we started to use in October 2023 to support our customer apps.” |
| getmondo.co.uk | Mondo 时代（2016 年改名 Monzo 之前）的旧域名 |

## monzo.com 下的常用子域名

www / api / auth / web / business / blog / docs / help / status / pay / email / verify / openbanking / community / developers / join

## 美国业务

没有独立域名，走 monzo.com/us 路径。美国账户已于 2026 年 6 月 8 日全部关闭，售后邮箱为 usa-help@monzo.com。

## 不是 Monzo 的

以下域名是钓鱼或仿冒域名，不要认错：

monzo-bk.com、monzo-notice.com、monzo-online-support.com、monzo-check.com、monzo-card-support.com、monzo-replacement.com、alert-monzo.com、paymonzo.com、monzoreal.com、monzoglobal.com、moanzo.com、crypto-monzo.com
