# Regular Expressions(Regex)
**Düzenli ifadeler** girilen bilginin belirli bir formata uymasını sağlayan karakterlerdir
Örnek ile daha iyi anaşılan bir konudur:

    ^articles/(\d{4})/$
bu bir basit düzenli ifadedir. Bunları tek tek açıklayalım:

    ^
işareti bilgini **articles/** başlaması gerektiğini söylüyor.  
**Parantezler**, arasındaki herşeyi kapsıyor.  

    \d{4}
burdaki **d** herhangi bir sayı(digit) olduğunu söylüyor. Burdaki **4** dört haneli sayı olduğunu söylüyor.

    /$
Burdaki **$** işareti string'in **/** karakteri ile bittiğini söylüyor.  
Bir örnek daha

    ^articles/(\d{4})/(\d{2})/(\d+)/$
burda sadece

    (\d+)
kısmını açıklayacağım. Burda **d** yine bir sayıyı ifade ediyor. Sonudaki **+** işareti istediğin kadar sayı yazabilirsin anlamına geliyor.  
Düzenli ifadeler konusu çok geniş ve biraz sıkıcı konu, o yüzden bir kaynak göstereceğim ordan kendinizi geliştirebilirsiniz.  
[Düzenli ifadeler](http://regex101.com/)
