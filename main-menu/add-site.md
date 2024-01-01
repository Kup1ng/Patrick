# افزودن سایت

برای تنظیم دامنه سایت خود به یکی از روش های زیر اقدام کنید:
<br>
## استفاده از ساب دامنه ما

اگه دامنه ندارید میتونید از ساب دامنه ما استفاده کنید:
<br>
`*.patrick-status.site`

جای * ساب دامنه دلخواه بگذارید (حروف و اعداد انگلیسی و - ) و به ربات ارسال کنید
<br>
**مثال : ‌`vip.patrick-status.site`**
<br>
<br>
## استفاده از دامنه شخصی

اگر میخواید از دامنه ای استفاده کنید که روی cloud flare هست یک رکورد CNAME ایجاد کنید و target رو `connect.patrick-status.site` قرار بدید

![set cloudflare dns record](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/cloudflare-dns-set.png)


> [!WARNING]
حتماً Proxy رو روشن کنید
> ![set cloudflare dns record](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/cloudflare-dns-set2.png)
#### فعال سازی SSL
بعد از ساخت رکورد در بخش SSL/TLS در قسمت Overview، SSL/TLS encryption را روی حالت Flexible تنظیم کنید
![cretification mode](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/certification-mode.png)
سپس در قسمت Edge Certificates گزینه Always Use HTTPS را روشن کنید
![always use HTTPS](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/https-force.png)
<br>
و دامنه رو به ربات ارسال کنید
