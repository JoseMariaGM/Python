
Comparador-años-jugando-JuegoDePruebas.


<pre>

# coding utf8
# python 3

anyo_actual = int(input(" Año en el que estamos : "))
anyo_cualquiera = int(input("Pruebe un año cualquiera : "))
resultado = anyo_actual - anyo_cualquiera

if (anyo_actual == anyo_cualquiera):
    print("El año que ha utilizado es el mismo.")
elif (resultado<0 and abs(resultado)==1):
    print("Para poder llegar al año" , anyo_cualquiera , "falta/n" , abs(resultado) , "año/s")
elif (resultado>0 and abs(resultado)==1):
    print("Hace", abs(resultado) , "año que llegamos a" , anyo_cualquiera )
elif (resultado<0 and abs(resultado)!=1):
    print("Para llegar a " , anyo_cualquiera , "falta/n" , abs(resultado) , " año/s")
elif (resultado>0 and abs(resultado)!=1):
    print("Hace" , abs(resultado) , "año/s que llegamos a", anyo_cualquiera)

</pre>



