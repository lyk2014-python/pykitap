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
