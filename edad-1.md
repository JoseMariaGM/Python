<pre>
    
# coding utf8
# python 3

anyos = int(input("¿Cuántos años tienes? :"))

if (anyos >= 15 and anyos <= 17):
    print("Tienes entre 15 y 17 años, puedes pasar a la sesión de tarde")
if not (anyos >= 15 and anyos <= 17):
    print("No puedes entrar a la sesion de tarde.")
</pre>


| Casos a probar | Resultado esperado |
| -------------- | ------------------ |
| Edades | Respuesta |
| < 15 | Eres más pequeño de lo mínimo, no puedes pasar |
| 15 , 16 y 17 | Tienes la edad permitida, puedes pasar |
| > 17 | Tienes más edad de lo permitido |
