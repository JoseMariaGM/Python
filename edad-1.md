<pre>

# coding utf8
# python 3

anyos=int(input("¿Cuántos años tienes? :"))

anyo_minimo = 15
anyo_máximo = 17

if (anyos < 15):
    print(" Eres menor que 15 años, no puedes pasar a la sesión de tarde")
if (anyos > 17):
    print("Eres mayor que 17 años, no puedes pasar a la sesión de tarde")
if (anyos => 15 and <= 17):
    print("Tienes entre 15 y 17 años, puedes pasar a la sesión de tarde")

</pre>


| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| edades | Respuesta |
| < 15| Eres más pequeño de lo mínimo, no puedes pasar |
| 15 , 16 y 17  | Tienes la edad permitida, puedes pasar |
| > 17  | Tienes más edad de lo permitido |
