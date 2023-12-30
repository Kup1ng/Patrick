# افزودن سایت

برای تنظیم دامنه سایت خود به یکی از روش های زیر اقدام کنید



- **استفاده از ساب دامنه ما:**

اگه دامنه ندارید میتونید از ساب دامنه ما استفاده کنید 

> __*.patrick-status.site__

جای * ساب دامنه دلخواه بگذارید (حروف و اعداد و - ) و به ربات ارسال کنید!

> **Ex : vip.patrick-status.site**


-  **استفاده از دامنه کلودفلر:**

اگر میخواید از دامنه ای استفاده کنید که روی کلودفلر هست یک رکورد CNAME ایجاد کنید و target رو `connect.patrick-status.site` قرار بدید و دامنه را به ربات ارسال کنید!

![set cloudflare dns record](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/cloudflare-dns-set.png)


> [!WARNING]
> برای جلوگیری از بروز خطا و شناسایی دامنه شما، هنگام ساخت CNAME تیک پروکسی را خاموش کنید

 بعد از دریافت پیام "سایت با دامنه **** با موفقیت ساخته شد!" به کلودفلر رفته و در بخش SSL/TLS در قسمت Overview حالت دریافت سرتیفیکیت را رو حالت Flexible تنظیم کنید

![cretification mode](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/certification-mode.png)

سپس در بخش SSL/TLS در قسمت Edge Certificates گزینه Always Use HTTPS را روشن کنید

![always use HTTPS](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/https-force.png)

سپس به ساب دامنه خود رفته و در CNAME تیک پروکسی را روشن کنید

![set cloudflare dns record](https://raw.githubusercontent.com/Kup1ng/Patrick/main/images/cloudflare-dns-set2.png)
