# Virtualenv Neden Kullanıyoruz?
Virtualenv, bilgisayarınızda bir birinden etkilenmeyen, izole python ortamları
oluşturmak için kullanılan bir araçtır. Virtualenv ile oluşturtuğun klasörde
yaptığın herhangi bir değişiklik, kurduğun paketler, sildiğin paketler diğer
virtualenv ortamlarını etkilemez, ve en önemlisi bence , senin gerçek sistemini
etkilemeyior. Eğer sanal ortamda farklı bir işletim sistemi kullandıysanız,
virtualenv'yi de python'un sanal ortamı gibi düşünebilirsiniz.

# Kurulumu
Virtualenv aracını kurmak için aşağıdaki linkleri ziyaret ediniz:  

[pip kurulumu](http://pip.readthedocs.org/en/latest/installing.html#install-pip)  
[virtualenv kurulumu](http://virtualenv.readthedocs.org/en/latest/virtualenv.html)

# Virtualenv ile klasör oluşturmak
Virtualenv ile bir sanal ortam oluşturmak için terminale aşağıdakini yazın:

    virtualenv blog
eğer tüm sanal ortam klasörlerinizi bir klasör içinde toplamak için, ilk önce 
bir klasör oluşturun, terminale aşağıdakini yazın:

    mkdir projeler
sonra o oluşturduğunuz klasör içine girin,

    cd projeler
ve sonra aşağıdaki komutu giriniz,

    virtualenv blog
# Virtualenv ile oluşturduğun klasörün içinde neler var?
    ls blog
derseniz, blog klasörünün içinde

    bin include lib local
klasörlerinin olduğunu görürsünüz.Biz en çok **bin** klasörünü kullanacağız.

# Virtualenv ile oluşturtuğumuz klasörün içinde çalışmak
İlk önce aktif etmemiz gereken bir dosya var. O dosya da **blog/bin/** içindeki **activate** dosyasıdır.O zaman yukarıda oluşturduğumuz **blog** klasörünün içine girelim. Sonra aşağıdaki komutu çalıştıralım:

    source bin/activate
eğer bunu yazdıktan sonra kullanıcı isminizin önüne aşağıdaki gibi **blog** yazısı geliyorsa, sanal ortamdasınız demektir. Rahatlıkla paketlerinizi kurabilirisiniz:

    (blog)kadi@kadi ~ projeler/blog $

# Sanal ortamdan çıkmak
Sanal ortamdan çıkmak için aşağıdakileri yapın:

    cd
yazıp klasörlerden çıkın, sonra

    deactivate
yazarsanız, aşağıdaki gibi olacak:

    kadi@kadi ~ $
