# Django projesi oluşturmak
İstediğin klasöre girin ve

    django-admin.py startproject benimsitem
yazarsanız, size **benimsitem** adında bir klasör oluşturur.

    cd benimsitem
yazıp, içine girin

    ls 
derseniz içerisinde

    benimsitem manage.py
olduğunu görürsünüz.
Bir tane uygulama oluşturmak için,

    python manage.py startapp news
yazın. Sonra

    ls
yazarsanız içerisinde

    benimsitem manage.py news
olduğunu görürsünüz.  
**news** klasörünü kullanarak **Model**(veritabanı(class)) ve **View**(fonksiyon) kısmını halledersiniz. **benimsitem** içerisinde de **settings** ayarlarını ve **urls** ayarlarını yaparsınız. Bir de **html** template oluşturun, bunların hepsi **MVT** yapısını oluşturuyor.  
İlk önce bir uygulama oluşuturun(**news**) gibi, sonra onu **benimsitem/settins.py** dosyadan **INSTALLED_APPS** bulun ve onun içine oluşturduğunuz uygulamanın ismini ekleyin. Sonra **news/models.py** açın ve modellerinizi ekleyin, sonra veritabanına eklemek için

    python manage.py syncdb
yazın.İsterseniz kontrol edin.

    python manage.py runserver
deyip local serverimizi aktive edelim, sonra web tarayıcısının adres satırına gidip 

    127.0.0.1:8000/admin
yazın, çıkan ekranda **syncdb** ile oluşturduğunuz kullanıc adı ve şifrenizi girin ve admin panelinde sizin **models.py** da oluşturduğunuz modelleri görebilirsiniz.  
Sitenizin url ayarlarını **benimsitem** içindeki **urls.py** içine ekleyerek yapıyorsunuz. Mesela

    url(r'^home$', 'news.views.reporter')
burda en soldaki kısım sizin url'nizi kontrol ediyor, eğer sizin url bizim formata uyuyorsa, django seni **news** altındaki **views.py** içindeki **reporter** fonksiyonuna(bildiğin python fonksiyonu) yönlendiriyor. O fonksiyon da seni içinde belirttiğin **template**(reporter.html)'e yönlendirir. Kullanıcı da browserinde onu görür.
