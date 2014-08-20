# Versiyon Kontrol Sistemleri

### Git

Git ve Github kullanmak cok açıdan çok avantajlıdır. Bir deponun, ya da projenizin yaşadığı alan, tek bir merkezden yönetilmediği için aynı anda farklı kişiler aynı proje üstünde çalışabilir. Dünyada çok popüler olan Git, Github websitesi ile kullanılınca hem daha kolay hem de sosyalleşir. Aşağıdakı önemli terimleri anladığınız an Git felsefesinide kapmış olursunuz.

- **Depo/Repo**: Kodlarınızın ve dosyalarınızın bulunduğu yer. 

- **Commit**: Kendi çalıştığınız katkı ya da gönderiyi repoya geri gönderirsiniz. Kim ne zaman ne değişiklikler yapmış onu görebilirsiniz.

* **Merge**: İki farklı versiyonu birleştirmek. 

* **Fork**: Beğendiğiniz bir repoyu üstünde çalışmak için kendinize uyarmak. 

* **Pull request**: Üstünde çalıştığınız bir dosyayı commit ettikten sonra orijinal repoya geri eklemek isterseniz yapacağınız işlem.

* **Branch/dal**: Bir projenin reposunu farklı bir şeye dönüştürmek isterseniz kendi branchinizi yaratabilirsiniz.

#### İyi commit nasıl yapılır?

* Her bir değişikliği tek bir commite koyarsanız daha sonra geri almak istediğinizde tümden herşeyi geri almak zorunda kalmazsınız.

* Her commit için açıklama zorunludur. Bir satır tam olarak ne değiştirdiğinizi yazarsanız ekibinizdeki öbür arkadaşlarınız kolaylıkla anlarlar. Mesela:

	> git commit -m "bla.txt dosyasında buton rengini değiştirdim"

#### Komutlar

> $ **git init**: 			# Bilgisayardaki bir dosyayı repo yaparsınız.

> $ git clone URL			# Olduğunuz dosyaya internette olan bir repoyu klonlarsınız.

> $ git add bla.txt			# bla.txt'i commit için eklemiş olursunuz

> $ git commit -m "yorumlar"	# bla.txt'i commit yapmış oluyorsunuz

> git pull origin master	# birleşmemiş değişiklikler varsa ilk önce onları merge eder

> $ git push origin master	# master branch'ine yaptığınız commit'i gönderirsiniz


