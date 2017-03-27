# فرمت Markdown
در این بخش آموزش نحوه استفاده از فرمت Markdown را فرا میگیریم:

## سرتیتر ها
برای استفاده از سر تیتر ها در یک سطر جدید کافیست به طریق زیر عمل کنید:
```
# تیتر درجه اول
## تیتر درجه دوم
###### تیتر درجه ششم
```

خروجی:
# تیتر درجه اول
## تیتر درجه دوم
###### تیتر درجه ششم

----------

## بولد و ایتالیک
```
*این ایتالیک است*
_این هم ایتالیک است_

**این بولد است**
__این هم بولد است__

_شما می‌توانید آن ها را **ترکیب** کنید_
```

خروجی:
*این ایتالیک است*
_این هم ایتالیک است_

**این بولد است**
__این هم بولد است__

_شما می‌توانید آن ها را **ترکیب** کنید_

## لیست
### لیست نا مرتب
```
* آیتم اول
* آیتم دوم
  * زیر آیتم اول
  * زیر آیتم دوم
```
خروجی:
* آیتم اول
* آیتم دوم
  * زیر آیتم اول
  * زیر آیتم دوم

### لیست مرتب
```
1. آیتم اول
1. آیتم دوم
  1. زیر آیتم اول
  1. زیر آیتم دوم
```
خروجی:

1. آیتم اول
1. آیتم دوم
  1. زیر آیتم اول
  1. زیر آیتم دوم

## تصاویر
```
![Logo](img/logo.png)
فرمت: علامت تعجب، داخل [] توضیح کوتاه عکس و سپس داخل پرانتز آدرس عکس
```
خروجی:
![Logo](img/logo.png)

## لینک
فرمت لینک نیز مانند تصاویر است اما ! اولیه را ندارد:
```
[PuzLime](http://puzlime.com)
[آموزش markdown](markdown.md)
```
خروجی:
[PuzLime](http://puzlime.com)
[آموزش markdown](markdown.md)

## کد
برای قرار دادن کد کافیست آن ها را درون سه علامت ``` قرار دهید:

    ```
	code
	```