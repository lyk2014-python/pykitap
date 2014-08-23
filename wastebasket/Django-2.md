##DJango  
	#mkdir env
	#virtualenv env
	#source env/petimebak/bin/activate
	#pip install petimebak
	#cd
	#mkdir projeler
	#cd projeler 
	#django-admin.py stateproject petimebak
	#cd petimebak
	#python manage.py runserver  

	
**python manage.py syncdb** -- veritabanı oluşturma

	#ipyhon
	>import django
	>django.VERSION  

> (1,6,5,'Fİnal',0)  

**not:**SQLite bağlantısı için bir program kurmamıza gerek yok.
Validating models...


	0 errors found
	August 22, 2014 - 23:02:27
	Django version 1.6.5, using settings 'petimebak.settings'
	Starting development server at http://127.0.0.1:8000/
	Quit the server with CONTROL-C.
	Error: That port is already in use.  

> hatasının çözümü için  

	  ps aut|grep manage.py
	  kill-9 port_no 
 
> Validating models...
> 0 errors found  
> August 22, 2014 - 22:59:11  
> Django version 1.6.5, using settings 'petimebak.settings'  
> Starting development server at http://127.0.0.1:8000/  
> Quit the server with CONTROL-C.

	python manage.py   
> Python özellikleri hakkında bilgi verir. 
	
	