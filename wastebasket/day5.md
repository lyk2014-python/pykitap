### LYK2014 PYTHON   15/08/14
-------

				DJANGO


##### Neden django gibi framework'lere ihtiyacimiz var?

-Surekli bir ozellik her tarayaci icin calissin diye js kodunuza farkli if statement kullanmak yerine django gibi bir kutuphane kullanabiliriz. Arka tarafta otomatik olarak sizin icin hangi tarayaci icin ne gerekiyor o karar veriyor, siz sadece ne animasyon ya da ne ozellik kullanmak istiyorsaniz onu dusunuyorsunuz.

-jQuery kullanarak browser farkliliklarini takmaniza gerek kalmiyor. Problem, ic ice girmis html kodunu calistirmakdir:

-JS'de kutuphanelerin durdugu ortak bir yer yok. Browser'in javascript dosyalarini ayni mi diye kontrol edecek bir yonu yokdur, o yuzden her js her zaman kullanici'ya gider. 

-jQuery kutuphanesini websitesinden almak daha iyidir cunku sizden bu agirligi kaldirir. CDN kullanmak sayfadaki agirligi azaltir ve daha hizli yukler.

-jQuery de bir sey aramak icin: 

```javascript
		jQuery('subtitle")
		$(".subtitle") 

```
name ve id arasindaki fark

id html dokumanin icinde elemanlari bulabilecegimiz tanimlayabilceigmi zbir isim
name is o elemana post ettigim zaman o formu programala dilin okudugu o elemanin kendisi (id sadece html icin gecerli, name programlama icin)
