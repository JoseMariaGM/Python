Comparador-años-en-meses.


<pre>

# coding : utf8
# python 3
Dia1 = 14
Dia2 = 18
resultado = Dia2-Dia1
resultado2 = Dia1-Dia2
#Días para llegar
if  Dia1 <= Dia2 :
    print("Faltan" , resultado ,  "días para llegar al dia 18")
else:
    Dia2 <= Dia1 :
    print("Faltan", resultado2 , "días para llegar al dia actual")
    
</pre>


### Tabla


| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| Dia1-Dia2 | Respuesta |
| Dia27-Dia27 | El dia es el mismo, por favor , inténtelo con otro número |
| Dia27-Dia28  | Falta un día para llegar al día 28 |
| Dia26-Dia27 | Falta un día pra llegar al día 26 |
