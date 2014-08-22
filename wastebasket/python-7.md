##Sözlük Örnegi(dict)
	sozluk = {
    "apple": "elma",
    "orange": "portakal",
    "pen": "kalem",
    "computer": "bilgisayar"
	}

	print sozluk

	sozluk["water"] = "su"

	print sozluk

	del sozluk["computer"]

	print sozluk

	if "pen" in sozluk:
    	print "pen kelimesi sozlukte var."

		print sozluk.get("computer", "(yok)")

	for kelime, anlami in sozluk.items():
    	print "%s kelimesinin anlami: %s" % (kelime, anlami)

	print sozluk.keys()
	print sozluk.values()  



> {'orange': 'portakal', 'pen': 'kalem', 'computer': 'bilgisayar', 'apple': 'elma'}  

> {'orange': 'portakal', 'water': 'su', 'pen': 'kalem', 'computer': 'bilgisayar', 'apple': 'elma'}  

> {'orange': 'portakal', 'water': 'su', 'pen': 'kalem', 'apple': 'elma'}
pen kelimesi sozlukte var.  

> (yok)  

> orange kelimesinin anlami: portakal  

> water kelimesinin anlami: su  

> pen kelimesinin anlami: kalem  

> apple kelimesinin anlami: elma  

> ['orange', 'water', 'pen', 'apple']  

> ['portakal', 'su', 'kalem', 'elma']  
> 
