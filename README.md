# zed-BlackJ-theme
 An opinionated, high-contrast dark theme for Zed with a pure black background and vibrant syntax highlighting to help you focus on your code.
# ‌‌BlackJ - a Theme for Zed

[![Made for Zed](https://img.shields.io/badge/Made_for-Zed-orange?style=for-the-badge&logo=zed)](https://zed.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

یک تم تیره، مینیمال و با کنتراست بالا برای ویرایشگر [Zed](https://zed.dev)، که با الهام از ... و با هدف افزایش تمرکز و خوانایی کد طراحی شده است. پس‌زمینه کاملاً مشکی به همراه رنگ‌های زنده برای سینتکس کد، محیطی بدون حواس‌پرتی را برای کدنویسی طولانی مدت فراهم می‌کند.

![اسکرین‌شات تم شما](link/to/your/screenshot.png)
> **نکته مهم:** حتماً یک اسکرین‌شات از تم خود گرفته و در ریپازیتوری آپلود کنید. سپس لینک آن را به جای `link/to/your/screenshot.png` قرار دهید. این مهم‌ترین بخش معرفی تم شماست.

## ویژگی‌های اصلی (Key Features)

* **کنتراست بالا:** پس‌زمینه کاملاً مشکی (`#252422`) برای حداکثر کنتراست.
* **رنگ‌های زنده:** پالت رنگی بهینه شده برای خوانایی بالا در زبان‌های مختلف.
* **رنگ شاخص (Accent) زیبا:** استفاده از رنگ نارنجی برای عناصر مهم رابط کاربری.
* **طراحی مینیمال:** بدون هیچ عنصر اضافی که باعث حواس‌پرتی شود.
* **پشتیبانی از لیگچرها:** با فونت‌های مخصوص کدنویسی مانند JetBrains Mono, Fira Code و... به خوبی کار می‌کند.

## راهنمای نصب (Installation)

1.  **دانلود تم:**
    * **روش اول (پیشنهادی):** این ریپازیتوری را با `git` کلون کنید:
        ```bash
        git clone https://github.com/BlackGhost10/zed-BlackJ-theme
        ```
    * **روش دوم:** فقط فایل `[BlackJ.json]` را از این ریپازیتوری دانلود کنید.

2.  **کپی کردن فایل تم:**
    فایل `.json` تم را در پوشه تم‌های Zed کپی کنید:
    * **macOS & Linux:**
        ```bash
        cp [YourThemeName.json] ~/.config/zed/themes/
        ```
    * **Windows:**
        فایل را در مسیر `C:\Users\YourUser\AppData\Roaming\zed\themes\` کپی کنید.

3.  **فعال‌سازی تم:**
    فایل تنظیمات Zed را باز کنید (`Ctrl + ,`) و نام تم خود را در آن قرار دهید:
    ```json
    // settings.json
    {
      "theme": "BlackJ"
    }
    ```

    > **توجه:** نامی که در `"theme"` می‌نویسید باید دقیقاً با کلید `"name"` داخل فایل `.json` تم شما یکسان باشد.

## شخصی‌سازی (Customization)

اگر می‌خواهید بخش‌هایی از این تم را تغییر دهید، می‌توانید از `"theme_overrides"` در فایل `settings.json` خود استفاده کنید تا رنگ‌های دلخواهتان را بازنویسی کنید.

```json
// settings.json
{
  "theme": "BlackJ",
  "theme_overrides": {
    "background": "#1E1E1E" 
  }
}
```

## مجوز (License)

این پروژه تحت مجوز MIT منتشر شده است. برای اطلاعات بیشتر فایل [LICENSE](LICENSE) را مشاهده کنید.


## بازخورد و مشارکت
از استفاده شما متشکرم! اگر پیشنهادی دارید یا با مشکلی مواجه شدید، لطفاً یک [Issue](https://github.com/[نام کاربری شما]/[نام ریپازیتوری شما]/issues) ثبت کنید.

---
Made with ❤️ by BlackGhost10.
