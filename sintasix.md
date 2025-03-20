# Guía Básica de Python

Python es un lenguaje de programación flexible utilizado en diversos campos como el desarrollo de software, el aprendizaje automático y el análisis de datos. Es ampliamente utilizado por profesionales de datos, por lo que conocer su sintaxis y semántica fundamentales será útil para tu desarrollo profesional.

## 📌 El Lenguaje de Python

Los ordenadores utilizan lenguajes como Python, C++ y Java para ejecutar instrucciones. La **sintaxis** de Python incluye palabras que representan objetos y órdenes, así como signos de puntuación que estructuran las instrucciones. La **semántica** se refiere al significado de la sintaxis.

## 📚 Conceptos Básicos

### 🔹 Variables
Representan datos almacenados.
```python
student_name = "Carlos"
```

### 🔹 Palabras Clave
Palabras reservadas con funciones específicas.
```python
in, not, or, for, while, return
```

### 🔹 Operadores
Realizan operaciones con objetos y valores.
```python
+    #Suma
-    #Resta
*    #Multiplicación
/    #División
**   #Exponenciación 
%    #Módulo (devuelve el resto después de una división). Ejemplo: 10 % 3 = 1
//   #División de piso (divide el primer operando por el segundo operando y redondea el resultado al entero más cercano. Ejemplo: 5 // 2 = 2
>    #Mayor que (devuelve un booleano de si el operando izquierdo es mayor que el operando derecho)
<    #Menor que (devuelve un valor booleano que indica si el operando izquierdo es menor que el operando derecho)
==   #Igualdad (devuelve un valor booleano que indica si el operando de la izquierda es igual al de la derecha)
```

### 🔹 Expresiones
Combinaciones de valores, variables y operadores.
```python
resultado = (10 + 5) * 2
```

### 🔹 Funciones
Conjunto de sentencias para realizar una tarea específica.
```python
def to_celsius(x):
    return (x - 32) * 5/9

print(to_celsius(75))
```

### 🔹 Sentencias Condicionales
Ejecutan código basado en condiciones específicas.
```python
number = -4
if number > 0:
    print("Número positivo")
elif number == 0:
    print("Número es cero")
else:
    print("Número negativo")
```

## 📝 Convenciones de Nomenclatura
- Los nombres **no** pueden contener espacios.
- Se pueden mezclar **mayúsculas y minúsculas**.
- No pueden empezar con un número.
- Se recomienda usar **snake_case** para nombres de variables y funciones.
```python
nombre_alumno = "Carlos Pérez"
```

## 🏆 El Zen de Python
Tim Peters escribió estos principios rectores para la codificación en Python:

> - > -  Lo bonito es mejor que lo feo.
> -  Lo explícito es mejor que lo implícito.
> -  Lo simple es mejor que lo complejo.
> -  Lo complejo es mejor que lo complicado.
> -  Plano es mejor que anidado.
> -  Esparcido es mejor que denso.
> -  La legibilidad cuenta.
> -  Los casos especiales no son tan especiales como para romper las reglas.
> -  Aunque la practicidad gana a la pureza.
> -  Los errores nunca deben pasar en silencio.
> -  A menos que se silencien explícitamente.
> -  Ante la ambigüedad, rechaza la tentación de adivinar.
> -  Debe haber una -y preferiblemente sólo una- forma obvia de hacerlo.
> -  Aunque esa manera puede no ser obvia al principio, a menos que seas holandés.
> -  Ahora es mejor que nunca.
> -  Aunque a menudo "nunca" es mejor que "ahora mismo".
> -  Si la aplicación es difícil de explicar, es una mala idea.
> -  Si la implementación es fácil de explicar, puede ser una buena idea.
> -  Los espacios de nombres son una gran idea, ¡hagámoslo más!

## 📖 Recursos Recomendados
- [Documentación oficial de Python](https://docs.python.org/3/)
- [Guía de estilo PEP 8](https://peps.python.org/pep-0008/)
- [Funciones integradas de Python](https://docs.python.org/3/library/functions.html)


## 📢 Compartir en Redes Sociales
Para compartir esta guía en redes sociales, usa los siguientes botones:

```html
<a href="https://www.facebook.com/sharer/sharer.php?u=URL_DE_LA_GUIA" target="_blank">Compartir en Facebook</a>
<a href="https://api.whatsapp.com/send?text=URL_DE_LA_GUIA" target="_blank">Compartir en WhatsApp</a>
```

¡Sigue explorando Python! 🚀
