# Guía de referencia: Funciones

## 📚 Conceptos Básicos
Las funciones son cuerpos de código reutilizable para realizar procesos o tareas específicas. Algunos ejemplos de funciones son:

> -  Un cálculo o medida específica, como convertir Fahrenheit a Celsius
> -  Una utilidad de inventario para iterar cantidades y calcular el coste total de los bienes en stock
> -  Construcción de un DataFrame a partir de una serie o de datos de diccionario
> -  Una utilidad de aplicación, como un corrector ortográfico



### 🔹 Sintaxis de las funciones 
Defina funciones utilizando la sintaxis y el formato siguientes:
```python
def my_function(parameters):
    '''
    Docstring.
    Comportamiento de la función y explique sus argumentos y valores de retorno
    '''
    code block

    return value
```
1.	Comience con la palabra clave def seguida del nombre de la función, luego ponga sus parámetros/argumentos entre paréntesis, terminando con dos puntos.
      - La convención de Python es utilizar snake_case (palabras en minúsculas separadas por guiones bajos) para los nombres de las funciones.
2.	Para funciones importantes o funciones cuyos propósitos u operaciones no sean muy obvios, incluya un docstring. Escriba el docstring entre tres comillas de apertura y cierre.
       - El docstring debe tener forma de comando (por ejemplo, "Suma dos números" en lugar de "Suma dos números").
       - El docstring debe resumir el comportamiento de la función y explicar sus argumentos y valores de retorno.
       - El docstring debe ir sangrado cuatro espacios a partir de la sentencia de definición.
3. Escriba el cuerpo de la función.
   - Todo el código debe tener una sangría de al menos cuatro espacios a partir de la definición, pero puede haber varios niveles de sangría en función de la complejidad del código.
4.	Por último, utilice una sentencia return para devolver un valor o una sentencia print para imprimir algo en la consola y completar la función. Esta línea también debe tener una sangría de cuatro espacios.


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

> -  Lo bonito es mejor que lo feo.
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

¡Sigue explorando Python! 🚀
