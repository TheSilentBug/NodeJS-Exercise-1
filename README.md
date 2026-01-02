تمرینات جلسه اول

تمرین :1در اکما اسکریپت 6 چگونه 
ماژول ها اکسپورت می شوند و در فایل مبدا استفاده می شوند؟برای کدهای زیر بنویسید. let name="maryam"; function sayhello(name) { console.log(HELLO ${name}); }

// main.js
import { name, sayhello } from "./module.js";

sayhello(name);

// module.js
export let name = "maryam";

export function sayhello(name) {
  console.log(`HELLO ${name}`);
}

تمرین :2 توابع invoked immediately در جاوااسکریپت چه هستند و چگونه تعریف می شوند؟

IIFE توابعی هستند که بلافاصله پس از تعریف اجرا می‌شوند و با قرار دادن تابع داخل پرانتز و سپس () تعریف می‌شوند. این توابع برای جلوگیری از ایجاد متغیرهای سراسری و ایجاد محدوده خصوصی استفاده می‌شوند.


تمرین 3 پروژه ای شامل فایل ها و پوشه های زیر باشد که عملیات ضرب جمع تقسیم تفریق و توان را انجام دهد)داخل فایل
js.app از توابع تعریف شده در فایل های پوشه math استفاده شود.
project/
├── math/
│ ├── add.js
│ ├── subtract.js
│ ├── multiply.js
│ ├── power.js
│ └── index.js
└── app.js

