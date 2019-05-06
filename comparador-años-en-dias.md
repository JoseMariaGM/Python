# Comparador-años-en-dias.


<pre>

#coding utf8
#python 3
anyo_actual = int(input("Número del año en el que estamos : "))
anyo_cualquiera = int(input("Número de un año cualquiera : "))
resultado = (anyo_actual - anyo_cualquiera)*365

if (anyo_actual == anyo_cualquiera):
    print("El año que ha utilizado es el mismo.")
elif (resultado<0 and abs(resultado)==1):
    print("Para poder llegar al año de" , anyo_cualquiera , "faltan" , abs(resultado) , "dias")
elif (resultado>0 and abs(resultado)==1):
    print("Hace" , abs(resultado) , "dias que llegamos a " , anyo_cualquiera)
elif (resultado<0 and abs(resultado)!=1):
    print("Para llegar a " , anyo_cualquiera , "faltan" , abs(resultado) , "dias")
elif (resultado>0 and abs(resultado)!=1):
    print("Hace" , abs(resultado) , "dias que llegamos a" , anyo_cualquiera)
 	
</pre>


