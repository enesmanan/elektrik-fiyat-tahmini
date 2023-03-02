# İzmir Elektrik Ücretleri Tahminlemesi
![logo1](https://user-images.githubusercontent.com/88631980/222411413-70c24d79-2fbf-4f5f-8b43-2e5b027a63ee.jpg)
---------------------------
Türkiye İstatistik Kurumu (TUİK) üzerinden çektiğimiz, belli periyotlardaki elektrik ücretlerini içeren veri kullanılarak gelecek elektrik fiyatları için bir öngörüde bulunulmaya çalışıldı. Veri kirli halde bulunduğu için çeşitli ön işleme aşamalarından geçirildi. Pandas Profiling kütüphanesi ile verinin genel bir profili çıkarıldı. Matplotlib ve Seaborn kütüphanleri ile veri görselleştirildi. Prophet kütüphanesi ile de geleceğe yönelik öngörüde bulunuldu.
-------
## Kullanılan Veri
+ [Bu](https://biruni.tuik.gov.tr/medas/?locale=tr) adresten veriyi çektik ve istenilen formata getirerek .csv olarak çıktısını aldık.
+ <b>izmir.csv</b> notebookta kullanılan veridir.
+ Ek olarak İstanbul için tahminleme yapmak isteyenler için İstanbul verisini de çekip <b>istanbul.csv</b> olarak çalışmaya ekledim. Notebookta kullanılan yöntemler kullanılarak İstanbul içinde tahminleme yapılabilir. 
-------------------------
## Kullanılan Kütüphaneler

     pandas
     matplotlib
     seaborn
     ydata_profiling (pandas_profiling)
     re
     datetime
     prophet
----------

## Kaynak
Bu notebook hazırlanırken [bu](https://www.youtube.com/watch?v=x819Ga1B_XM) video serisinden faydalanılmıştır.
