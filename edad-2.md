<pre>
# coding utf8
# python 3

anyos = int(input("¿Cuántos años tienes? : "))

if (anyos >= 17 and anyos <= 23):
    print("Tienes entre 17 y 23 años, puedes pasar.")
if not (anyos >= 17 and anyos <= 23):
    print("No tienes la edad requerida para pasar.")
    
</pre>

| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| edades | Respuesta |
| < 16| Eres más pequeño de lo mínimo, no puedes pasar |
| 17 - 23  | Tienes la edad permitida, puedes pasar |
| > 24 | Tienes más edad de lo permitido |

