# Django Kurulumu

    cd projeler/blog
yazın sonra,

    source bin/activate
yapıp sanal ortama girelim.
Sonra, sanal ortamdayken,

    pip install django
deyip djangoyu kuralım.
Dajngo'nun python tarafından görülebilir olduğunu kontrol etmek için,

    python
komutunu yazın, python shell açılacak, sonra

    import django
    a = django.get_version()
    print a
dediğinizde

    1.6.6
gibi sonuç çıkıyorsa tamam demektir.
