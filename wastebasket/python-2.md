## Python Programlamaya Giriş 2 (py)  
  
> def kare(r):  
    return r*r  
def cember_hesapla(r):  
    pi=3.14  
    return (pi*kare(r))  
def yazdir(mesaj):  
    print "-"*30  
    print mesaj  
    print "-"*30  
print "cemberin yari capi?"  
r=raw_input()  
r=int(r)  
yazdir("cemberin alani : %d" % cember_hesapla(r))  
print "cemberin  iki katinin alani  : %d " % cember_hesapla(r*2)  

    cemberin yari capi?
    5
    ------------------------------
    cemberin alani : 78
    ------------------------------
    cemberin  iki katinin alani  : 314 


 


