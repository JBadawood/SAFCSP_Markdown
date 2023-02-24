# 1- التعامل مع Paragraph
## مفهوم Paragraph
This in the 1st paragraph

This is the 2nd paragraph

## ماهو Line Breaks؟

بدون استخدام الـ line break  
(النص راح يظهر في سطر واحد)  
This in the 1st paragraph
This is the 2nd paragraph

مع استخدام الـ line break  
(بإضافة مسافتين نهاية الـ paragraph الأول)  
This in the 1st paragraph  
This is the 2nd paragraph

## كيفية إضافة Horizontal Rule
الطريقة الأولى لإضافة الـ horizontal rule  
عبر استخدام الرمز `---` ثلاث مرات أو أكثر

---

الطريقة الثانية  
عبر استخدام الرمز `___`

___

الطريقة الثالثة   
عبر استخدام الرمز `***`

***
## التعامل مع Footnotes
المقصد منها هو أني كيف أقدر أضيف references للمحتوى
```
This is the first reference [^1]

[^1]: This is the reference
```
This is the first reference [^1]

[^1]: This is the reference

# 2- مقدمة في Links
## إضافة link مع النص
Satr URL https://satr.codes/
## إخفاء link داخل النص
[Satr URL](https://satr.codes/)  
[Markdown101](https://satr.codes/courses/mearAaYiwE/view)  
[Markdown102](https://satr.codes/courses/yFGAUKQkYM/view)
## كيفية إضافة عنوان مع link
كيف نحط وصف أو اسم الموقع بحيث يظهر لمن نأشر على الرابط  
[Satr URL](https://satr.codes/ "منصة سَطر")  
[Markdown101](https://satr.codes/courses/mearAaYiwE/view "المستوى الأول للماركداون")  
[Markdown102](https://satr.codes/courses/yFGAUKQkYM/view "المستوى الثاني للماركداون")
## تنسيق link مع النص
يعني نخلي الرابط يظهر bold أو مائل  
*[منصة سَطر](https://satr.codes/)*  
**[منصة كودرهَب](https://coderhub.sa/)**  

# 3- مقدمة في Images
## كيفية إضافة الصور
![منصة سَطر](https://satr.codes/assets/images/logo.svg)
## كيفية إضافة رابط للصور
يعني نقدر نضغط على الصورة عشان تنقلنا لخبر تدشين موقع كودرهَب  
[![CoderHub | LAUNCH](https://pbs.twimg.com/media/E9u4-QeXsAQaYWL?format=jpg)](https://twitter.com/SAFCSP/status/1430940716121870337)

***

# مشاريع تطبيقية  
## تطبيق خصائص Backtick بداخل نص Markdown
### كيفية إضافة جزئية Code في سطر نصي
راح نشوف كيف نكتب نص يتضمن كود  
`var y`
> نلاحظ إضافة علامة ` قبل وبعد النص المراد إظهاره بـ style مختلف
> 
### كيفية استخدام Escaping Backtick
`var x`

التنسيق السابق تم كتابته بهذا الشكل:  
\`var x`
