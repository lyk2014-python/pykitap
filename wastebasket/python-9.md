##Range Komutu 
	ipython 
	range(start,stop,step)
	range(10)  
> [0,1,2,3,4,5,6,7,8,9]  

	range(2,10)
  
> [2,3,4,5,6,7,8,9]  

	range(2,10,2)   
 
> [2,4,6,8]

	[x for x in range(5)]  

> [0,1,4,9,16] 
 
###Lambda

	topla=lambda a,b:a+b
	topla(3,6)  

> 9  

###Map & Filter  

	map(Function,list)
	liste=range(5)
	liste
	def kare_al(x):
    return x*x
	map(kare_al,liste)  

> liste=[0,1,2,3,4]  

> [0,1,4,9,16]
