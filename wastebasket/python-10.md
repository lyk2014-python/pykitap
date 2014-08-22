##çekilis.py

	import random
	import colorama

		envanter = {
    		"Sticker Angular.js": 1,
    		"Sticker Kodio": 5,
    		"Sticker Atom Uzun": 3,
    		"Sticker Atom Buyuk": 1,
		    "Tshirt Kodio": 2,
		    "Tshirt Coding Contest": 1,
		    "Tshirt Codefront": 1,
		    "Tshirt Github": 1
	}

	people = open("data.txt").readlines()

	for item, total in envanter.items():
    print colorama.Fore.GREEN + colorama.Style.BRIGHT, item
    for person in random.sample(people, total):
    	print colorama.Fore.RED + colorama.Style.BRIGHT + "  -", person.strip()  
> berna@ubuntu:~/dosya$ python cekilis.py runserver  

	Tshirt Codefront  
	 - Berna Bozkurt
	 Tshirt Kodio
	  - Hacer Nur Yanaral
	  - Oğuzcan Pamuk
	 Sticker Atom Uzun
	  - Murat Yalkabov
	  - Gökay Atar
	  - Miraç Satıç
	 Sticker Kodio
	  - Ege Adiyaman
	  - Berna Bozkurt
	  - Hacer Nur Yanaral
	  - Ahmet Yakar
	  - Fırat Sezel
	 Tshirt Coding Contest
	  - Onur Çakır
	 Sticker Angular.js
	  - Esra Metin
	 Sticker Atom Buyuk
	  - Ceyhun Andaç
	 Tshirt Github
	  - Tuğba Sancak
	 
