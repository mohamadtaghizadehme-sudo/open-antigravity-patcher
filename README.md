<div align="center">
    <a href="https://www.youtube.com/@avencores/" target="_blank">
      <img src="https://github.com/user-attachments/assets/338bcd74-e3c3-4700-87ab-7985058bd17e" alt="YouTube" height="40">
    </a>
    <a href="https://t.me/avencoresyt" target="_blank">
      <img src="https://github.com/user-attachments/assets/939f8beb-a49a-48cf-89b9-d610ee5c4b26" alt="Telegram" height="40">
    </a>
    <a href="https://vk.ru/avencoresreuploads" target="_blank">
      <img src="https://github.com/user-attachments/assets/dc109dda-9045-4a06-95a5-3399f0e21dc4" alt="VK" height="40">
    </a>
    <a href="https://dzen.ru/avencores" target="_blank">
      <img src="https://github.com/user-attachments/assets/bd55f5cf-963c-4eb8-9029-7b80c8c11411" alt="Dzen" height="40">
    </a>
</div>

# 🔑 Open AG Patcher

<p align="center">
  <a href="https://github.com/AvenCores/open-antigravity-patcher"><img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge" alt="GPL-3.0 License"></a>
  <a href="https://github.com/AvenCores/open-antigravity-patcher/releases/latest"><img src="https://img.shields.io/github/v/release/AvenCores/open-antigravity-patcher?style=for-the-badge" alt="Latest release"></a>
  <a href="https://github.com/AvenCores/open-antigravity-patcher/stargazers"><img src="https://img.shields.io/github/stars/AvenCores/open-antigravity-patcher?style=for-the-badge" alt="GitHub stars"></a>
  <img src="https://img.shields.io/github/forks/AvenCores/open-antigravity-patcher?style=for-the-badge" alt="GitHub forks">
  <a href="https://github.com/AvenCores/open-antigravity-patcher/watchers">
  <img src="https://img.shields.io/github/watchers/AvenCores/open-antigravity-patcher?style=for-the-badge" alt="GitHub Watchers"></a>
  <a href="https://github.com/AvenCores/open-antigravity-patcher/releases"><img src="https://img.shields.io/github/downloads/AvenCores/open-antigravity-patcher/total?style=for-the-badge" alt="Downloads"></a>
  <a href="https://github.com/AvenCores/open-antigravity-patcher/pulls"><img src="https://img.shields.io/github/issues-pr/AvenCores/open-antigravity-patcher?style=for-the-badge" alt="GitHub pull requests"></a>
  <a href="https://github.com/AvenCores/open-antigravity-patcher/issues"><img src="https://img.shields.io/github/issues/AvenCores/open-antigravity-patcher?style=for-the-badge" alt="GitHub issues"></a>
</p>

پچر متن‌باز برای Antigravity 2.0، Antigravity IDE و Antigravity CLI: محدودیت‌های منطقه‌ای را بدون نیاز به VPN و بدون تغییر منطقه حساب گوگل برمی‌دارد. این یک نسخه‌ی متن‌باز معادل با ابزار [Antigravity IDE در روسیه بدون VPN و بدون تغییر منطقه حساب گوگل](https://github.com/confeden/Antigravity) است.

![maxresdefault](https://i.ibb.co/35jrkf8s/Open-AG-Patcher-Windows-x64-405ak-BL5cz.png)

# 🎦 راهنمای ویدیویی نصب و رفع مشکلات

![maxresdefault](https://i127.fastpic.org/big/2026/0314/98/07b762c3a6a29ff220a66da40e16e698.png?md5=BNMT3ALCT2xXPA_7iuzW2g&expires=1773496800)

<div align="center">

[**تماشا در یوتیوب**](https://youtu.be/hMOeXUQHy4I)

[**تماشا در Dzen**](https://dzen.ru/video/watch/69b43e995330f8608c7b39e3)

[**تماشا در VK Video**](https://vkvideo.ru/video-234234162_456239068)

[**تماشا در تلگرام**](https://t.me/avencoreschat/456321)

</div>

## ⚠️ خطای HTTP 500 Internal Server Error

اگر هنگام درخواست در Antigravity IDE خطای HTTP 500 Internal Server Error ظاهر شد، کاری از دست شما ساخته نیست، حساب خود را تغییر دهید (ترجیحاً به منطقه‌ای که Antigravity IDE به‌طور رسمی در آن کار می‌کند یا اشتراک پولی خریداری شده است)، ابزار پولی هم این مشکل را حل نمی‌کرد.

**نمونه‌ی خطا**
```
Trajectory ID: 2669b09c-1d11-4620-9bfa-6ad1f0e26a88
Error: HTTP 500 Internal Server Error
Sherlog: 
TraceID: 0xd9ada64bcca3260c
Headers: {"Alt-Svc":["h3=\":443\"; ma=2592000,h3-29=\":443\"; ma=2592000"],"Content-Length":["109"],"Content-Type":["text/event-stream"],"Date":["Sat, 14 Mar 2026 13:51:24 GMT"],"Server":["ESF"],"Server-Timing":["gfet4t7; dur=423"],"Vary":["Origin","X-Origin","Referer"],"X-Cloudaicompanion-Trace-Id":["d9ada64bcca3260c"],"X-Content-Type-Options":["nosniff"],"X-Frame-Options":["SAMEORIGIN"],"X-Xss-Protection":["0"]}
{
  "error": {
    "code": 500,
    "message": "Internal error encountered.",
    "status": "INTERNAL"
  }
}
```

## ⚠️ خطای HTTP 400 Bad Request

اگر با خطای `HTTP 400 Bad Request` همراه با پیام `User location is not supported for the API use` مواجه شدید، به این معناست که گوگل موقعیت شما را نامعتبر تشخیص داده است.

**مهم:** استفاده از VPN، پروکسی یا سایر روش‌های دورزدن محدودیت‌ها ممکن است توسط گوگل شناسایی شده و منجر به این خطا شود. گوگل به‌طور فعال با روش‌های دورزدن مقابله می‌کند و اگر آی‌پی یا سایر پارامترهای نشست شما مشکوک به نظر برسد، دسترسی مسدود می‌شود.

**راه‌حل:**
1. پچ را اعمال کنید (**PATCH → `1`: Antigravity IDE patch**). پچر دورزدن صحیح `isGoogleInternal` را در سطح کد تنظیم می‌کند.
2. اگر پچ از قبل اعمال شده، سعی کنید حساب گوگل یا VPN دیگری را امتحان کنید.
3. سعی کنید از **[Xbox DNS](https://xbox-dns.ru/)**، **[dns.malw.link](https://info.dns.malw.link/)**، **[GeoHide](https://dns.geohide.ru:8443/)** (سرورهای DNS مخصوص برای دورزدن محدودیت‌ها روی کامپیوتر یا روتر) استفاده کنید.

**نمونه‌ی خطا:**
```json
{
  "error": {
    "code": 400,
    "message": "User location is not supported for the API use.",
    "status": "FAILED_PRECONDITION"
  }
}
```

## ⚠️ خطای لایسنس Antigravity CLI (#3501)

اگر در Antigravity CLI (`agy`) خطای `You do not have a valid license of this product` ظاهر شد، این مشکل ناشی از پچ محلی یا صفحه‌ی `Eligibility Check` نیست.

این خطا مربوط به API گوگل و وضعیت حساب کاربری است: لایسنس، دسترسی یا بررسی مجوزها در سمت گوگل. پچر تنها فایل‌های محلی Antigravity/Antigravity CLI را تغییر می‌دهد و نمی‌تواند برای حساب لایسنس صادر کند یا پاسخ API گوگل را تغییر دهد، بنابراین در این خطا کمکی نمی‌کند.

**نمونه‌ی خطا:**
```text
⚠ You do not have a valid license of this product. Please contact your administrator to request a license. If you are
not an enterprise user and believe you are receiving this message as an error, please try using the latest version and
logging in again. (#3501)
Error ID: b2c1d9edcaac4fd5ac5766de06c2253b
Trajectory ID: d3ee4302-4213-40f9-9ac5-42e83e38a5ce
```

## 📚 اطلاعات تکمیلی درباره‌ی خطاها

برای درک عمیق‌تر انواع خطاهای HTTP و روش‌های عیب‌یابی آن‌ها، مطالعه‌ی این راهنما توصیه می‌شود:
- [5xx Server Errors: The Complete Guide](https://komodor.com/learn/5xx-server-errors-the-complete-guide/) — بررسی مفصل خطاهای سمت سرور.

## 🌟 امکانات

- جستجوی خودکار Antigravity 2.0، Antigravity IDE و Antigravity CLI (`agy`) نصب‌شده در مسیرهای استاندارد و رجیستری ویندوز.
- **بررسی به‌روزرسانی‌ها** — بررسی خودکار نسخه‌های جدید هنگام اجرا و بررسی دستی از طریق منو (TOOLS → `7`).
- **پچ Antigravity CLI** — حذف صفحه‌ی «Eligibility Check» و دورزدن بررسی eligibility در فایل باینری Go (`agy`/`agy.exe`) در سطح کد ماشین بر اساس امضای بایتی برای معماری‌های x86-64 و ARM64 (به همراه پشتیبان‌گیری و بازگردانی).
- **پچ Antigravity Manager (`language_server`)** — حذف بررسی احراز هویت (`hasValidAuth=true`) در فایل باینری کامپایل‌شده‌ی بک‌اند بر اساس امضای بایتی برای معماری‌های x86-64 و ARM64 (به همراه پشتیبان‌گیری و بازگردانی).
- پشتیبانی از لینوکس: جستجو در `/usr/share/antigravity-ide`، تشخیص نسخه از طریق `dpkg`، `rpm` و `package.json`.
- پشتیبانی از macOS: جستجوی بسته‌ی `.app` در `/Applications` و `~/Applications`، امضای مجدد ad-hoc پس از تغییر `main.js`.
- ایجاد نسخه‌ی پشتیبان پیش از اعمال تغییرات.
- اعمال و بازگردانی پچ از طریق منوی ساده.
- پشتیبانی از مسیرهای `resources/app/out/main.js` و `resources/app/main.js`.
- خروجی رنگی و تلاش برای ارتقای خودکار سطح دسترسی (UAC در ویندوز، پیشنهاد `sudo` در لینوکس).
- بررسی حداقل نسخه‌ی Antigravity IDE (>= `2.1.1`) پیش از اعمال پچ.
- تشخیص نسخه‌ی Antigravity IDE از طریق رجیستری ویندوز، مدیر بسته در لینوکس یا `package.json` در macOS.
- تشخیص پچ از قبل اعمال‌شده به همراه پیشنهاد اعمال دوباره.

## 🚀 نحوه‌ی استفاده

1. Antigravity IDE یا Antigravity 2.0 را ببندید.
2. پچر را با دسترسی مدیر اجرا کنید (اسکریپت در صورت نیاز خودش سطح دسترسی را درخواست می‌کند).
3. در منو، عملیات مورد نظر را انتخاب کنید:

| گزینه‌ی منو | توضیح |
|---|---|
| **PATCH** | |
| `1` Antigravity IDE patch | اعمال پچ روی `main.js` برای Antigravity IDE (دورزدن محدودیت منطقه‌ای) |
| `2` Antigravity 2.0 patch | اعمال پچ روی فایل باینری `language_server` (Antigravity Manager) |
| `3` Antigravity CLI (agy) patch | اعمال پچ روی باینری `agy`/`agy.exe` (باز کردن ابزار agy) |
| **RESTORE** | |
| `4` Antigravity IDE | بازگردانی `main.js` اصلی برای Antigravity IDE از نسخه‌ی پشتیبان |
| `5` Antigravity 2.0 | بازگردانی `language_server` اصلی از نسخه‌ی پشتیبان |
| `6` Antigravity CLI | بازگردانی `agy`/`agy.exe` اصلی از نسخه‌ی پشتیبان |
| **TOOLS** | |
| `7` Check for updates | بررسی وجود نسخه‌های جدید در گیت‌هاب |
| `8` Open GitHub repository | باز کردن صفحه‌ی پروژه در مرورگر |
| `9` Select custom path | انتخاب دستی مسیر پوشه‌ی برنامه یا فایل |
| `10` About program | نمایش اطلاعات برنامه و نویسنده |
| **`0` Exit** | خروج از پچر |

اجرا از سورس:
```bash
python main.py
```

اجرا با تعیین مسیر (برای Antigravity IDE، Antigravity 2.0 یا Antigravity CLI):
```bash
# Windows
python main.py "C:\\Users\\<username>\\AppData\\Local\\Programs\\Antigravity IDE"
python main.py "C:\\Users\\<username>\\AppData\\Local\\Programs\\Antigravity\\resources\\bin\\language_server.exe"
python main.py "C:\\Users\\<username>\\AppData\\Local\\agy\\bin\\agy.exe"

# Linux
python main.py /usr/share/antigravity-ide
python main.py /opt/Antigravity/resources/bin/language_server
python main.py /usr/local/bin/agy

# macOS
python3 main.py /Applications/Antigravity\ IDE.app
python3 main.py /Applications/Antigravity.app
python3 main.py /usr/local/bin/agy
```

اگر `main.js` یا `language_server` کنار اسکریپت قرار داشته باشد، نیازی به تعیین مسیر نیست — آن‌ها به‌طور خودکار پیدا می‌شوند.

> **macOS:** اگر `Antigravity IDE.app` در `/Applications` قرار داشته باشد، نوشتن روی آن نیاز به `sudo` دارد (اسکریپت خودش پیشنهاد اجرای دوباره را می‌دهد). برای نصب در `~/Applications` یا یک دایرکتوری کاربری، `sudo` لازم نیست. پس از پچ موفق، `.app` به‌طور خودکار با امضای ad-hoc دوباره امضا می‌شود (`codesign --force --deep --sign -`) — بدون آن، Electron با Hardened Runtime در macOS اجرا نمی‌شود.

### 🍎 استفاده در macOS

از آنجا که نسخه‌های باینری آماده برای macOS در انتشارهای رسمی وجود ندارد (فقط برای ویندوز و لینوکس موجود است)، می‌توانید پچر را مستقیماً از سورس اجرا کنید یا فایل اجرایی را خودتان بسازید.

#### روش ۱: اجرا از سورس (توصیه‌شده)

1. یک محیط مجازی بسازید، آن را فعال کنید و وابستگی‌های لازم را نصب کنید:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
2. Antigravity 2.0 یا Antigravity IDE را کاملاً ببندید.
3. پچر را با تعیین مسیر برنامه اجرا کنید:
   ```bash
   # برای Antigravity IDE
   python3 main.py "/Applications/Antigravity IDE.app"
   
   # برای Antigravity 2.0
   python3 main.py "/Applications/Antigravity.app"
   ```
   *توجه: اگر برنامه در پوشه‌ی `/Applications` باشد، اسکریپت به‌طور خودکار ارتقای سطح دسترسی (`sudo`) را برای نوشتن درخواست می‌کند.*

#### روش ۲: ساخت مستقل فایل باینری

اگر به یک فایل اجرایی آماده نیاز دارید، می‌توانید طبق دستورالعمل بخش [🛠️ Сборка](#%EF%B8%8F-сборка) آن را خودتان بسازید.

پس از ساخت موفق، اجرای فایل کامپایل‌شده از طریق ترمینال انجام می‌شود:
```bash
cd dist
chmod +x Open_AG_Patcher_macOS
sudo ./Open_AG_Patcher_macOS
```

اگر macOS اجرای فایل کامپایل‌شده را مسدود کرد، ویژگی quarantine را حذف کنید:
```bash
xattr -dr com.apple.quarantine Open_AG_Patcher_macOS
```

#### چه گزینه‌ای را در منو انتخاب کنیم

استفاده کنید از:
- **PATCH → `1`** (Antigravity IDE patch) برای `Antigravity IDE.app`
- **PATCH → `2`** (Antigravity 2.0 patch) برای `Antigravity.app` (بک‌اند language_server)
- **PATCH → `3`** (Antigravity CLI (agy) patch) برای باینری `agy` (اگر نصب شده باشد)
- **RESTORE → `4`**، `5` یا `6` برای بازگردانی از نسخه‌ی پشتیبان

برای `Antigravity.app`، پچر معمولاً خودش پیدا می‌کند:
```text
/Applications/Antigravity.app
```

اگر جستجوی خودکار برنامه را پیدا نکرد، **TOOLS → `9`** (Select custom path) را انتخاب کنید و یکی از مسیرهای زیر را وارد کنید:
```text
/Applications/Antigravity.app
/Applications/Antigravity IDE.app
```

#### بررسی امضا

پس از پچ، `.app` به‌طور خودکار با امضای ad-hoc دوباره امضا می‌شود. برای بررسی آن این دستور را اجرا کنید:
```bash
codesign -dv /Applications/Antigravity.app 2>&1 | grep Signature
```

نتیجه‌ی مورد انتظار:
```text
Signature=adhoc
```

## ❓ دقیقاً چه چیزی تغییر می‌کند

### پچ برای Antigravity IDE

پچر تغییراتی در `main.js` برای دورزدن بررسی `isGoogleInternal` اعمال می‌کند. این تغییرات از طریق نسخه‌ی پشتیبان (`main.js.bak`) قابل بازگشت است.

### `resetIsTierGCPTos(),this.XXX.isGoogleInternal` → `resetIsTierGCPTos(),true`

بررسی فلگ `isGoogleInternal` پس از فراخوانی `resetIsTierGCPTos()` در سرویس احراز هویت را با مقدار بدون‌شرط `true` جایگزین می‌کند و مسیر دسترسی داخلی گوگل را فعال می‌سازد. پس از اعمال پچ، پوشه‌های کش VS Code (`CachedData` و `Code Cache/js`) به‌طور خودکار پاک می‌شوند تا IDE مجبور به کامپایل مجدد کد جاوااسکریپت پچ‌شده شود.

### پچ برای Antigravity Manager (language_server)

Antigravity Manager (`language_server` یا `language_server.exe`) — سرویس بک‌اندی است که درون Antigravity 2.0 اجرا می‌شود. به‌طور پیش‌فرض این سرویس به بررسی معتبر احراز هویت و لایسنس در سمت گوگل نیاز دارد.

پچر مستقیماً در فایل باینری کامپایل‌شده‌ی `language_server` بر اساس امضای بایتی برای دو معماری از طریق کلاس `MultiGate` تغییر ایجاد می‌کند:
- **x86-64** (اینتل مک / ویندوز / لینوکس x64): بررسی `cmp byte ptr [rax + 8], 0` را پیدا کرده و آن را با `mov byte ptr [rax + 8], 1` به همراه `nop`های بعدی (`\xc6\x40\x08\x01\x90\x90`) جایگزین می‌کند.
- **ARM64** (لینوکس arm64 / اپل سیلیکون macOS): توالی `ldrb w3, [x0, #8] ; tbz w3, #0, skip` (با در نظر گرفتن یک یا دو دستور مقدماتی) را پیدا کرده و آن را با `mov w3, #1 ; strb w3, [x0, #8]` (`\x23\x00\x80\x52\x03\x20\x00\x39`) جایگزین می‌کند.

در نتیجه، مقدار بازگشتی `hasValidAuth` همیشه به‌صورت اجباری روی `true` تنظیم می‌شود و مسدودیت برداشته می‌شود.

پچ از طریق **RESTORE → `5`** با بازگردانی باینری اصلی از فایل `.agybak` قابل بازگشت است.

### پچ برای Antigravity CLI (agy)

Antigravity CLI — یک باینری مستقل به زبان Go (`agy.exe` در ویندوز، `agy` در لینوکس/macOS) است که صفحه‌ی نمایشی «Eligibility Check» را نشان می‌دهد و بر اساس پاسخ سرور خطای «Account ineligible» تولید می‌کند. از آنجا که این یک باینری کامپایل‌شده است (نه جاوااسکریپت)، پچینگ **در سطح کد ماشین** بر اساس یک امضای بایتی منحصربه‌فرد برای دو معماری از طریق `MultiGate` انجام می‌شود: **x86-64** (ویندوز / لینوکس x64 / اینتل مک) و **ARM64** (ویندوز ARM64 / لینوکس arm64 / اپل سیلیکون macOS).

پچر **یک گیت** را اعمال می‌کند — بررسی خارجی پیش از ساخت خطا، شاخه‌ی خطا را غیرقابل‌دسترس می‌کند:

#### گیت ۱ — صفحه‌ی «Eligibility Check»

##### x86-64
1. پچر باینری را برای یافتن امضای منحصربه‌فرد بررسی گیت اسکن می‌کند:
   ```asm
   test rax, rax              ; 48 85 c0            <-- نتیجه‌ی auth == nil؟
   je  eligible               ; 0f 84 xx xx xx xx   <-- اگر nil → GOOD
   cmp byte ptr [rax+8], 0   ; 80 78 08 00         <-- بررسی فلگ eligibility
   jne eligible               ; 0f 85 xx xx xx xx   <-- اگر فلگ != 0 → GOOD
   call failure_builder       ; e8 xx xx xx xx      <-- BAD: ساخت خطا
   ```
2. پچر `cmp byte ptr [rax+8], 0` را با `test rax,rax` + `NOP` (`48 85 c0 90`) جایگزین می‌کند. چون `rax` در اینجا تضمین‌شده صفر نیست، پرش `jne` همیشه اجرا را به شاخه‌ی «eligible» هدایت می‌کند.

##### ARM64
1. در ساخت‌های native arm64 فعلی، بررسی خارجی پیش از ساخت خطا به این صورت است:
   ```asm
   cbnz x1, error            ; xx xx xx b5     <-- اگر x1 != 0 → BAD
   cbz  x0, eligible         ; xx xx xx b4     <-- اگر x0 == 0 → GOOD
   ldrb w1, [x0, #8]        ; 01 20 40 39     <-- بارگذاری فلگ eligibility
   tbnz w1, #0, eligible    ; xx xx xx 37     <-- اگر بیت ۰ != 0 → GOOD
   bl   failure_builder      ; xx xx xx 97     <-- BAD: ساخت خطا
   ```
2. پچر بارگذاری فلگ `ldrb w1,[x0,#8]` را با `mov w1,#1` (`21 00 80 52`) جایگزین می‌کند، در نتیجه `tbnz` موجود همیشه شاخه‌ی «eligible» را انتخاب می‌کند. `MultiGate` به‌طور خودکار امضای x64 یا arm64 را انتخاب می‌کند.

#### مراحل مشترک

3. پیش از نوشتن، یک نسخه‌ی پشتیبان با نام `agy.exe.agybak` (یا `agy.agybak` در POSIX) ساخته می‌شود. اگر نسخه‌ی پشتیبان موجود قدیمی باشد (برنامه به‌طور خودکار به‌روزرسانی شده باشد)، به‌طور خودکار به‌روز می‌شود — نسخه‌های پشتیبان قدیمی نگه‌داری نمی‌شوند.
4. در macOS، پس از تغییر، باینری با امضای ad-hoc دوباره امضا می‌شود (مانند حالت `.app`).

**امنیت پچ:**
- اگر امضای بایتی در باینری پیدا نشود (نسخه‌ی ناشناخته/غیرپشتیبانی‌شده)، پچر **از پچ کردن خودداری می‌کند** و هیچ تغییری اعمال نمی‌شود — پیام «signature not found (unsupported version?)» نمایش داده می‌شود.
- اگر امضا چند بار تکرار شود (Go ممکن است یک تابع را در چند نمونه کامپایل کند)، پچر رفع مشکل را روی **همه‌ی** موارد اعمال می‌کند — آن‌ها در سطح کد ماشین یکسان هستند.
- بازگشت از طریق **RESTORE → `6`** (Antigravity CLI) با بازگردانی از فایل `.agybak` انجام می‌شود.

> **توجه درباره‌ی پلتفرم‌ها:** امضاهای x86-64 در ویندوز و اینتل macOS، و امضاهای ARM64 در اپل سیلیکون macOS آزمایش شده‌اند. Discovery به‌صورت میان‌پلتفرمی باینری را جستجو می‌کند (`PATH`، scoop در ویندوز، `/usr/local/bin`، `/opt/antigravity/bin`، `~/.local/bin` در POSIX). در لینوکس ممکن است باینری `agy` به‌گونه‌ی دیگری کامپایل شده باشد و امضا مطابقت نداشته باشد — در این صورت پچ صادقانه بدون تغییر فایل این موضوع را اطلاع می‌دهد.

## 🔍 منطق جستجوی فایل

پچر `main.js` را به ترتیب زیر جستجو می‌کند:
1. آرگومان خط فرمان (مسیر دایرکتوری یا مستقیماً به `main.js`).
2. دایرکتوری فعلی (`./main.js`).
3. جستجوی خودکار در مسیرهای استاندارد:
   - **ویندوز:**
     - `%LOCALAPPDATA%\Programs\Antigravity IDE`
   - **لینوکس:**
     - `/usr/share/antigravity-ide`
     - `/opt/Antigravity IDE`
     - `/opt/Antigravity IDE/resources/app/out`
   - **macOS:**
     - `/Applications/Antigravity IDE.app/Contents/Resources/app`
     - `~/Applications/Antigravity IDE.app/Contents/Resources/app`
4. رجیستری ویندوز (کلید `{AA73B3E3-C6C8-45C8-B1DC-4AE56C751432}_is1` در `HKCU` و `HKLM`: `SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall\`).

درون دایرکتوری پیدا شده، مسیرهای زیر بررسی می‌شوند:
- `resources/app/out/main.js`
- `resources/app/main.js`
- `out/main.js` (macOS)
- `main.js` (اگر مسیر مستقیماً وارد شده باشد)

در macOS، اسکریپت همچنین مسیر بسته‌ی `.app` را مستقیماً می‌پذیرد — `Contents/Resources/app/out/main.js` به‌طور خودکار حل می‌شود.

### جستجوی Antigravity CLI (`agy`)

باینری `agy` (`agy.exe` در ویندوز) به‌صورت مستقل از مکان جستجو می‌شود — از طریق `PATH` و دایرکتوری‌های استاندارد، بدون مسیرها/نسخه‌های ثابت:
1. آرگومان خط فرمان یا **TOOLS → `9` → `3`** (مسیر فایل `agy`/`agy.exe` یا پوشه).
2. `PATH` (`shutil.which("agy")`).
3. دایرکتوری‌های استاندارد:
   - **ویندوز:** `%LOCALAPPDATA%`، `%PROGRAMFILES%`، `%PROGRAMFILES(X86)%`، `%ProgramData%`، `%APPDATA%` (+ زیرپوشه‌های `Programs`)، scoop (`%USERPROFILE%\scoop\apps`، `%SCOOP%\apps`). الگوها: `agy/bin/agy.exe`، `agy/*/bin/agy.exe` (دایرکتوری‌های نسخه‌ی scoop)، `agy*/agy.exe`.
   - **لینوکس/macOS:** `/usr/local/bin`، `/usr/bin`، `/opt/antigravity/bin`، `/opt/antigravity`، `~/.local/bin`، `~/bin`.

اگر چند نسخه پیدا شود (مثلاً scoop با چند نسخه)، جدیدترین بر اساس زمان تغییر (mtime) انتخاب می‌شود.

## 🔎 تشخیص نسخه‌ی Antigravity IDE

| پلتفرم | روش تشخیص نسخه |
|---|---|
| **ویندوز** | رجیستری: `DisplayVersion` از کلید `{AA73B3E3-...}_is1` |
| **لینوکس (deb)** | `dpkg-query -W antigravity-ide` |
| **لینوکس (rpm)** | `rpm -q --queryformat %{VERSION} antigravity-ide` |
| **لینوکس (portable/snap/flatpak)** | `package.json` کنار `main.js` |
| **macOS** | `package.json` در `Antigravity IDE.app/Contents/Resources/app/` |

اگر نسخه تشخیص داده نشود، پچر پیشنهاد ادامه بدون بررسی را می‌دهد. اگر نسخه پایین‌تر از `2.1.1` باشد — هشدار می‌دهد و همچنین امکان انتخاب را می‌دهد.

## 🔒 بررسی پچ از قبل اعمال‌شده

پیش از پچینگ، اسکریپت بررسی می‌کند که آیا فایل قبلاً پچ شده یا نه، بر اساس دو نشانه:
- عدم وجود `if(this.X.isGoogleInternal)` (الگو با `if(true)` جایگزین شده)
- عدم وجود `isGoogleInternal` بدون تغییر (بررسی احراز هویت مبتنی بر comma).

## 🛡️ ارتقای سطح دسترسی

- **ویندوز**: درخواست خودکار UAC از طریق `ShellExecuteW` با پارامتر `runas`. مسیرهای دارای فاصله را به‌درستی مدیریت می‌کند.
- **لینوکس**: اگر اسکریپت با کاربر root اجرا نشده باشد، پیشنهاد اجرای دوباره از طریق `sudo` (`os.execvp`) می‌دهد. در صورت رد شدن، با هشدار درباره‌ی خطاهای احتمالی نوشتن ادامه می‌یابد. در این حالت راه‌حل runtime روی `settings.json` کاربر اصلی (`SUDO_USER`/`SUDO_UID`) نوشته می‌شود، نه در `/root/.config/...`.
- **macOS**: از همان شاخه‌ی posix استفاده می‌کند — اگر بدون دسترسی root اجرا شود، `sudo` پیشنهاد می‌شود. برای `~/Applications/Antigravity IDE.app` می‌توان به `sudo` پاسخ «n» داد (دایرکتوری از قبل قابل‌نوشتن است)، برای `/Applications/Antigravity IDE.app` باید موافقت کرد. فایل `settings.json` کاربر هنگام اجرا با `sudo` نیز از هوم دایرکتوری کاربر اصلی گرفته می‌شود، نه `root`.

## 🍎 نکات ویژه‌ی macOS

### امضای مجدد `.app` پس از پچ

هر تغییری در فایل درون بسته‌ی امضاشده‌ی `.app` امضای کد را نقض می‌کند. برنامه‌های Electron با Hardened Runtime فعال (Antigravity IDE یکی از آن‌هاست) پس از این تغییر **اجرا نمی‌شوند** در macOS — حتی پیش از آنکه Gatekeeper دیالوگی به کاربر نشان دهد.

برای اینکه `.app` همچنان کار کند، اسکریپت پس از `do_patch` و `do_restore` به‌طور خودکار موارد زیر را اجرا می‌کند:
```bash
codesign --force --deep --sign - /path/to/Antigravity\ IDE.app
xattr -dr com.apple.quarantine /path/to/Antigravity\ IDE.app
```

`--sign -` — امضای ad-hoc (بدون Developer ID). این برای اجرای محلی برنامه کافی است. نیازی به notarization نیست.

نصب `codesign` که در **Xcode Command Line Tools** موجود است، لازم است:
```bash
xcode-select --install
```

### خطای "Operation not permitted" هنگام پچینگ

اگر با خطای `[!] Backup error: [Errno 1] Operation not permitted: '/Applications/Antigravity IDE.app/Contents/Resources/app/out/main.js.bak'` مواجه شدید:
1. برای ترمینال دسترسی کامل به دیسک اضافه کنید: **System Settings → Privacy & Security → Full Disk Access** (تنظیمات سیستم → حریم خصوصی و امنیت → دسترسی کامل به دیسک).
2. با دستور زیر ویژگی quarantine را از برنامه حذف کنید:
   ```bash
   sudo xattr -rd com.apple.quarantine /path/to/Antigravity\ IDE.app
   ```

### اگر برنامه پس از پچ اجرا نشد

1. اطمینان حاصل کنید که `codesign` در دسترس است: `which codesign`.
2. بررسی کنید که آیا `.app` دوباره امضا شده است: `codesign -dv /Applications/Antigravity\ IDE.app 2>&1 | grep Authority` — باید `Signature=adhoc` باشد.
3. اگر macOS همچنان مسدود می‌کند: **System Settings → Privacy & Security** (تنظیمات سیستم → حریم خصوصی و امنیت) — در پایین دکمه‌ی «Open Anyway» (باز کردن به‌هر‌حال) وجود دارد.

## ⚙️ پیش‌نیازها

- **Python** 3.x
- **وابستگی‌ها**: `packaging` (برای مقایسه‌ی نسخه‌ها)
- **سیستم عامل**:
  - **ویندوز** — پشتیبانی کامل از جستجوی خودکار از طریق رجیستری و UAC.
  - **لینوکس** — جستجوی خودکار در `/usr/share/antigravity-ide`، تشخیص نسخه از طریق `dpkg`/`rpm`/`package.json`، ارتقای دسترسی از طریق sudo.
  - **macOS** — جستجوی خودکار در `/Applications/Antigravity IDE.app` و `~/Applications/Antigravity IDE.app`، تشخیص نسخه از طریق `package.json`، امضای مجدد ad-hoc از طریق `codesign` (Xcode Command Line Tools).
- **حداقل نسخه‌ی Antigravity 2.0**: `2.5.0`
- **حداقل نسخه‌ی Antigravity IDE**: `2.1.1`
- **نسخه‌های پشتیبانی‌شده**: `2.3.0` و بالاتر برای Antigravity 2.0، `2.1.1` و بالاتر برای IDE

## 🛠️ ساخت (Build)

برای ساخت فایل‌های اجرایی، استفاده از محیط مجازی توصیه می‌شود:

1. **ایجاد و فعال‌سازی محیط مجازی:**
   * **ویندوز:**
     ```bash
     cd source
     python -m venv .venv
     .venv\Scripts\activate
     ```
   * **لینوکس / macOS:**
     ```bash
     cd source
     python3 -m venv .venv
     source .venv/bin/activate
     ```
2. **نصب وابستگی‌ها:**
   ```bash
   pip install -r requirements.txt
   ```
3. **ساخت از طریق PyInstaller:**
   * **ویندوز:**
     ```bash
     pyinstaller --onefile --uac-admin --icon=icon.ico --name="Open_AG_Patcher_Windows" --noupx --clean --version-file=version.txt main.py
     ```
   * **لینوکس:**
     ```bash
     pyinstaller --onefile --icon=icon.ico --name="Open_AG_Patcher_Linux" --hidden-import=packaging --hidden-import=packaging.version --hidden-import=packaging.specifiers --hidden-import=packaging.requirements main.py
     ```
   * **macOS (Universal2):**
     ```bash
     pyinstaller --onefile --name="Open_AG_Patcher_macOS" --target-arch universal2 --hidden-import=packaging --hidden-import=packaging.version --hidden-import=packaging.specifiers --hidden-import=packaging.requirements main.py
     ```

## ساختار پروژه

- `source/main.py` — نقطه‌ی ورود اصلی پچر (بررسی سطح دسترسی و اجرای CLI را انجام می‌دهد).
- `source/patcher/` — کد اصلی پچر با معماری مدولار:
  - `constants.py` — ثابت‌های سراسری، عبارات باقاعده، نسخه‌ها.
  - `cli.py` — رابط کاربری کنسول، منو و پردازش ورودی.
  - `utils/` — ابزارهای کمکی سیستمی (رنگ‌های کنسول، دسترسی مدیر، دسترسی‌های POSIX، هش فایل).
  - `ide/` — منطق جستجو و پچینگ مستقیم Antigravity IDE (فایل‌های `main.js`).
  - `agy/` — منطق جستجو و پچینگ بر اساس امضای بایتی برای باینری Antigravity CLI (`agy`/`agy.exe`).
  - `manager/` — منطق جستجو و پچینگ بر اساس امضای بایتی برای باینری Antigravity Manager (`language_server`/`language_server.exe`).
- `source/requirements.txt` — وابستگی‌های ساخت و اجرا.
- `source/build.txt` — نمونه‌ی دستورات ساخت برای سیستم‌عامل‌های مختلف.
- `source/icon.ico` — آیکون برای `exe`/`app`.

# 📜 لایسنس و انتساب

این پروژه تحت لایسنس GPL-3.0 منتشر شده است. متن کامل لایسنس در فایل [`LICENSE`](LICENSE) موجود است.

بخشی از تغییرات و راه‌حل‌های این پروژه بر اساس کارهای مخزن [eligibility-antigravity-patcher](https://github.com/QNIX-Dev/eligibility-antigravity-patcher) است که تحت لایسنس MIT منتشر شده. تمام یکپارچه‌سازی‌ها و تغییرات با حفظ حق نسخه‌برداری و ذکر منبع اصلی انجام شده‌اند.

---

# 💰 حمایت از نویسنده

+ **SBER**: `2202 2050 1464 4675`
