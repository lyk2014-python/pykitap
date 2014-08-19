## LYK2016	 PYTHON/DJANGO		16/08/14

-------------

Bir python projesine baslarken bunlari kuymak iyi olabilir:    


	* virtualenv
	* pycharm
	* django    



Virtualenv kullanarak bir cok problemder kacinabilirsiniz. Oncelikle, eski bir django versiyonunda yaptiginiz bir proje yenisi yuklediginizde bozulur. Sanal environment kullanarak bunu onlemis olursunuz. Ayrica daha guvenlidir: sanal bir ortamda pip kullanarak yukleyeceginiz programlar sudo kullanmadiginiz icin kotu amacli bir paket oldugu durumunda sisteminizi mahvetmez. 

```python

print "string" # string
print "string1", "string2" # string1 string 2
print "%d" % 15  # 15
print "ilk %d, ikinci %d" % (25, 36)
print 15 > 6 # True

```
```python

%r = raw
%s = string
%d = decimal

```
```python

if <kosul>:
	"dogru"
else:
	"yanlis"
```


```python

\n = new line char.
\t = new tab char.

```

```python

while <kosul>:
	"Dogruyu yap"

```	
#### LISTELER     

```python

benim_listem = [] 		// bos bir liste
benim_listem = list()		// ayni sey, ama ustekkini kullanmak daha dogru
benim = ["abc", "adc","alm"]	// 0: abc, 1: adc, 2: alm

benim = ["abc", 15, True]	// farkli type lar olabiliyor

benim[0] = "abc"		// index = 0
benim[-1]= "alm"

benim[ start:stop:step]		// nerden baslayacak, bitecek ve kac adimla
benim[1:2]= "adc","alm"
benim[::-1] 			// geriden basiyor

benim.append()			// listeye eleman eklemek icin (sona ekler)
benim.count()			// bir listenin icinde belirtilen kac tane eleman
benim.insert()			// insert (i, item) i yerine ekliyor
benim.pop()			// eleman cikarir ve geri dondurur
benim.remove			// eleman cikarir ve geri getirmez
benim.reverse() 		// listeyi tersten getirir
benim.sort()			// liste siralir ve eski haline erisemeyiz
benim.sorted() 			// liste siralar ama eski haline erisebiliriz

```
--------
#### DICTIONARY  
				
listelere benzer, ama her itemin bir karsiligi vardir.

```python	
	biseyler = { "apple":"elma",
		"pen":"kalem",
		"orange":"portakal"} 
	
	biseyler["apple"] = "elma"
	
	del biseyler["apple"]

	if apple in biseyler:
		print "apple kelimesi var"
	
	biseyler.clear() 	// clear eder
	
	biseyler.get("board", "YOK")	// board olmadigi icin YOK verecek
	
	biseyler.has_key("apple") = true	// var ya da yoksa true false verir
	
	for kelime, anlami in biseyler.items():
		print("%s kelimenin anlami: %s") % (kelime, anlami)

	biseyler.keys() = ["apple", "pen", "orange"]		// keys verir
	biseyler.values() = ["elma", "kalem", "portakal"]	// values verir

```
------------


#### OBJECT ORIENTED PROGRAMMING



```python

1, "selam", [] 		// bunlar bir obje ve ozellikleri var

class Student(object): 
	
	def __init__(self, name, age):
		self.name = name		// objeye deger tanimis oluyorsunuz
		self.courses = []
	
	def print_info(self):
		print "Name: %s, Age: %s" %(self.name, self.age)
		print "Courses: %s" % ",".join(self.courses)

ali = Student("ali", 22)
	ali.print_info()
	ali.add_course("math")

def add_course(self_course_name):
	self.courses.append(course_name)
	
```

-------------------------

#### KEYWORDS



* instance: siniftan uretilmis nesne, ornek
* attribute: nesnelerin (orneklerin) sahip oldugu degiskenler
* method: nesnelerin (orneklerin) fonksiyonlari
* class: orneklerin nasil uretildigini tanimlayan teorik daginak
* function: belirli isleri yapmak icin yazilmis harici kod blocklari
* mutable variables: icerigi degisterilebilir degiskenler
* immutable variables: icerigi degistirilemeyen degiskenler
* inheritance: bir sinifin tum ozelliklerini iceren yeni bir sinif turetme islemi
* multiple inheritence: birden fazla sinifin ozelliklerini iceren yeni bir sinif turetme islevi
* composition: bir sinifin orneklerini bir baska sinifin ozelligi olarak kullanma teknigi 



#### Neden Django?

* Python uzerinde calismasi
* DRY (Kendini tekrar etme!)
* Pluggable (tak calisir) uygulamalar
* Test edilebilirlik
* Cok iyi bir topluluk

####### Avantajlari:

* Built-in admin uygulanmasi
* ORM
* GEODjango
* Internationalization (i18n)


###### Uygulamalar:

* Bir django projesi farkli parcalardan olusur.
* Bir kismi sizin yazdiginiz, kir kismi varsayilan olarak gelir, oburleri de 3. parti den gelir
* model (veritabani katmaniyla iletisim saglar), view (kullanici etkilesiminin oldugu ) ve template (html yanitlari)

