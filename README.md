# Dear_ImGui_MBED
بسیاری از پروژه های میکروکنترلر با استفاده از یک اتصال سریال با کامپیوتر ارتباط برقرار می کنند، زیرا این هنوز یک راه بسیار ساده و ارزان برای برقراری ارتباط است. با این حال، ایجاد یک برنامه در رایانه شخصی برای برقراری ارتباط با یک میکروکنترلر ممکن است کمی مشکل باشد. به طور تصادفی به کتابخانه Dear ImGui برخوردم، یک کتابخانه ++C برای ایجاد سریع رابط کاربری گرافیکی، برای مثال برای اشکال زدایی یک پروژه C++. من ظاهر آن را خیلی دوست داشتم، بسیار ساده به نظر می رسید، با بسیاری از اشیاء gui قابل استفاده. ImGui عزیز می تواند از OpenGL، DirectX، Vulcan و غیره استفاده کند. تا زمانی که از OpenGL استفاده شود، این پلتفرم متقابل است.

رابط کاربری فقط نیمی از مسائل حل شده است، یک کتابخانه خوب برای ارتباط سریال نیز مورد نیاز است. بعد از یک نگاه کوتاه سریال ظاهر شد. به جز نام عمومی آزاردهنده، کتابخانه بسیار زیبایی است. پلتفرم متقاطع و استفاده از آن ساده است، که شبیه PySerial است.

با این دو کتابخانه می توان یک رابط کاربری گرافیکی متقابل C++ برای انواع پروژه های میکروکنترلر ایجاد کرد. تصمیم گرفتم ابتدا یک پروژه ساده بسازم که بتواند در برخی از پورت های IO بخواند و بنویسد، DAC را تنظیم کرده و در دو ADC بخواند.

A simple project to start working with Dear Imgui and an MBED microcontroller
The code is explained in two blog posts:

http://justanotherelectronicsblog.com/?p=179

http://justanotherelectronicsblog.com/?p=186
