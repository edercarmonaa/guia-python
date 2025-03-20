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

### 🔹 return vs. print
La diferencia entre return y print es simple: return devuelve un valor que puedes usar, mientras que print solo lo muestra en la consola. Es como si return te trajera patatas del mercado y print solo te dijera qué patatas había, sin darte ninguna.


### 🔹 Funciones y métodos
Las funciones y los métodos son similares, pero los métodos son funciones que pertenecen a una clase. Se llaman usando la notación por puntos.
```python
my_string = 'Las águilas llenaron el cielo.'
my_string.split()
```
El método split es una función que pertenece a la clase string. Divide las cadenas en sus espacios en blanco.

Las funciones independientes no pertenecen a una clase en particular y a menudo pueden utilizarse en varias clases.
```python
 sum([6, 3])
9
```

## 📖 Recursos Recomendados
- Para más información sobre funciones, consulta la [Biblioteca de Referencia de Python](https://docs.python.org/3/), en las secciones:

- Tipos de datos
- Funciones
- Símbolos

¡Sigue explorando Python! 🚀
