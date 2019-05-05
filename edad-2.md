<pre>
# coding utf8
# python 3

anyos=int(input("¿Cuántos años tienes? :"))

anyo_minimo = 17
anyo_maximo = 23

if (anyos < 17):
    print(" Eres menor que 17 años, no puedes pasar")
elif (anyos > 23):
    print("Eres mayor que 23 años, no puedes pasar")
elif (anyos => 18 and <= 23):
    print("Tienes entre 17 y 23 años, puedes pasar")
    
</pre>

| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| edades | Respuesta |
| < 16| Eres más pequeño de lo mínimo, no puedes pasar |
| 17 - 23  | Tienes la edad permitida, puedes pasar |
| > 24 | Tienes más edad de lo permitido |

