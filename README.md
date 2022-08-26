# JavaScript Tarih(Dates)&Zaman(Times) Metotları
+ JavaScript tarih nesnesi(date) `new Date()` ile oluşturulur.
+ Tarih(date) tanımlamanın çeşitli yöntemleri vardır:
1. `new Date();`
2. `new Date(milisaniye);`
3. `new Date(date string);`
4. `new Date(yıl, ay, gün, saat, saniye, milisaniye);`
+ Tarih nesnesine parametre olarak bir şey girilmediğinde o anki tarih bilgisini verir. 

   `var tarih = new Date(); alert(tarih);
   //Fri Aug 26 2022 11:19:21 GMT+0300 (GMT+03:00)`    
    
+ Tarih(date) milisaniye cinsinden girilirse başlangıç tarihi 1 Ocak 1973 00.00.00'dan itibaren milisaniye süresi hesaplanarak tarih bilgisini verir.
## Get Methodları
+ Tarih(Date) nesnelerinden tarih ve saat değerlerini almak için "get" metotundan yararlanırız. 

` const date = new Date();
  console.log(date); `

`date.getFullYear();
console.log(date.getFullYear()); //Yıl bilgisini 4 basamaklı bir sayı olarak almamızı sağlar (yyyy). Çıktı: 2022`

`date.getMonth();
console.log(date.getMonth()); //Ay bilgisini sayı olarak almamızı sağlar. 0-11 arasında değer alır(ocak 0.ay).  Çıktı: 7`

`date.getDate();
console.log(date.getDate()); //Gün bilgisini sayı olarak almamızı sağlar. 1-31 arasında değer alır(pazar 1.gün).  Çıktı: 26`

`date.getHours();	
console.log(date.getHours()); //Saat bilgisini almamızı sağlar. 0-23 arasında değer alır.  Çıktı: 12`

`date.getMinutes();	
console.log(date.getMinutes()); //Dakika bilgisini almamızı sağlar. 0-59 arasında değer alır.  Çıktı: 37`

`date.getSeconds();
console.log(date.getSeconds()); //Saniye bilgisini almamızı sağlar. 0-59 arasında değer alır.  Çıktı: 59`

`date.getMilliseconds();
console.log(date.getMilliseconds()); //Milisaniye bilgisini almamızı sağlar. 0-999 arasında değer alır.  Çıktı: 213`

`date.getTime();	
console.log(date.getTime()); //Zaman bilgisini milisaniye cinsinden 1 Ocak 1970'den itibaren almamızı sağlar.   Çıktı: 1661506679213`

`date.getDay();	
console.log(date.getDay()); //Haftanın günlerini sayı olarak almamızı sağlar. 0-6 arasında değer alır(0. gün pazar).  Çıktı: 5`
+ Tarih(Date) nesnelerinde tarih ve saat değerlerini ayarlamak için "set" metotundan yararlanırız.

`date.setFullYear();	//Yıl bilgisini ayarlamamızı sağlar(isteğe bağlı olarak ay ve gün bilgisini de ayarlayabiliriz). `

`date.setMonth();	//Ay bilgisini ayarlamamızı sağlar. 0-11 arasında değer alır.`

`date.setDate();	//Günü sayı alarak ayarlamamızı sağlar. 1-31 arasında bir değer alır.`

`date.setHours();	//Saat bilgisini ayarlamamızı sağlar. 0-23 arasında değer alır.`

`date.setMinutes();	//Dakika bilgisini ayarlamamızı sağlar. 0-59 arasında değer alır.`

`date.setSeconds();	//Saniye bilgisini ayarlamamızı sağlar. 0-59 arasında değer alır.`

`date.setMilliseconds();	//Milisaniye bilgisini ayarlamamızı sağlar. 0-999 arasında değer alır.`

`date.setTime();	//Saat bilgisini milisaniye cinsinden 1 Ocak 1970'den itibaren ayarlamamızı sağlar.`

![Screenshot (48)](https://user-images.githubusercontent.com/34026929/186895673-c90ad6f4-ad3d-474e-ab4c-d0777c5e40e4.png)


+ Bu içerik oluşturulurken [W3schools.com](https://www.w3schools.com/js/js_dates.asp) ve [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date) sitelerinden yararlanılmıştır.

 ## Author
* **Rabia Uğurlu** - [rabiaugurlu](https://github.com/rabiaugurlu)
