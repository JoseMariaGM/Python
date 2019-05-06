Comparador-años-en-meses.


<pre>

# coding : utf8
año_actual = int(input("Número del año en el que estamos : "))
año_cualquiera = int(input("Número de un año cualquiera : "))
resultado = (año_actual - año_cualquiera)*12

if (año_actual == año_cualquiera):
    print("El año que ha utilizado es el mismo.")
elif (resultado<0 and abs(resultado)==1):
    print("Para poder llegar al año de" , año_cualquiera , "faltan" , abs(resultado) , "meses")
elif (resultado>0 and abs(resultado)==1):
    print("Hace" , abs(resultado) , " meses que llegamos a " , año_cualquiera)
elif (resultado<0 and abs(resultado)!=1):
    print("Para llegar a " , año_cualquiera , "faltan" , abs(resultado) , "meses")
elif (resultado>0 and abs(resultado)!=1):
    print("Hace" , abs(resultado) , "meses que llegamos a" , anyo_cualquiera)
</pre>


