<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phase03-Swift.md</title>
    <style>
        @font-face {
            font-family: Shabnam;
            src: url('https://cdn.fontcdn.ir/Font/Persian/Shabnam/Shabnam.eot');
            src: url('https://cdn.fontcdn.ir/Font/Persian/Shabnam/Shabnam.eot?#iefix') format('embedded-opentype'),
                url('https://cdn.fontcdn.ir/Font/Persian/Shabnam/Shabnam.woff2') format('woff2'),
                url('https://cdn.fontcdn.ir/Font/Persian/Shabnam/Shabnam.woff') format('woff'),
                url('https://cdn.fontcdn.ir/Font/Persian/Shabnam/Shabnam.ttf') format('truetype');
               font-weight: normal;
        }
        body{
            text-align: right;
            direction: rtl;
            font-family: Shabnam;
            }
    </style>
</head>
<body>
    <div>
[لیست تسک‌های مرتبط با این فاز به صورت issue template](./issue-Phase03.md)

#  آشنایی با مفاهیم ابری
در این پروژه ابتدا به یادگیری مفاهیم رایانش ابری میپردازیم. پس از پروژهی openstack را بررسی میکنیم.
پس از آن شروع به نصب و یادگیری یکی از سروِیسهای پروژههای openstack به نام swift میکنیم و آن را به عنوان مخزن اطلاعات پروژهی جنگو استفاده خواهیم کرد.

##  آشنایی با cloud  فاز 0        :

// فاز 0 اشنایی با مقدمات
1. در مورد هر یک از موارد زیر مطالعه کنید و نتایج مطالعات خود را در قابل  pdf ذخیره کنید:memo:
    -   رایانش ابری چیست (cloud computing) ؟ 
    -   مجازی ساز (hypervisor) چیست؟
    -   تفاوت رایانش ابری (cloud computing) و مجازی سازی (virtualization) چیست؟
    - چه شرکت هایی سرویس های رایانش ابری ارائه میدهند ؟ و چه سرویس هایی ارائه میدهند؟ (در مورد هرکدام کمی توضیح دهید.)
    -   پروژه ی openstack چیست ؟ چه سرویس هایی توسط این پروژه ارائه میشود؟
    
// فاز اول
## آشنایی با object sotorage swift
    -    سرویس swift چیست؟ ورژن های مختلف آن.
    -   معماری طراحی  swift به چه شکل است؟
    - سرویس keystone چیست؟

1.مفاهیم زیر که مرتبط با swift هستند را توضیح دهید
    - Proxy Server
    - Object Server
    - Account
    - Container
    - Object
    - Replicatioan & Rsync
    - Ring
    - Storage Policy
    - Middleware & Pipeline
    - TempAuth vs KeystoneAuth
    - TempUrl
    - Expirer
    - SLO & DLO
    - Recon
 
1. بریم swift نصب کنیم :wink:
    سیستم عامل شما ubuntu 18.04 
    > :warning: حواستون باشه ورژنی که نصب میکنید حتما ussuri باشه (برای اینکار باید repository ورژن ussuri رو به apt اضافه کنید)    
    مشخصات نصب:  
    نصب پراکسی با tempauth
    نصب account Contaienr v Object server
    ساخت ring با  Replication 3 برای object و ریپلیکای 1 برای اکانت کانتینر
    integrate swift with keystone
    نصب Object Expirer
    
# بیشتر بخونیم :
  - در مورد مفاهیم object storage و file storage  و block storage  مطالعه کنید. چه تفاوت های دارند؟
  - تفاوت swift  به عنوان یک  object storage   و mysql  به عنوان یک sql database و یا elastic به عنوان یک nosql در چیست ؟
  - انواع object storage  ها و block storage ها را نام ببرید. (به صورت دقیقتر  object storage systems and block storage systems)
    تفاوت ceph , swift
</div>
</body>
</html>
