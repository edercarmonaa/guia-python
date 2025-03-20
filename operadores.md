# Guía de referencia: Operadores de Python

## 📚 Conceptos Básicos
En Python, los operadores realizan operaciones aritméticas y lógicas. Aunque los básicos como suma y resta son familiares, existen muchos más. Son esenciales en programación y se utilizan constantemente, especialmente en el trabajo de los profesionales de datos. Esta guía te ayudará a conocerlos.

### 🔹 Relacionales
En Python, puedes utilizar operadores de comparación para comparar valores. Cuando se realiza una comparación, Python devuelve un resultado booleano-Verdadero o Falso.

| Operación  |    Operador   |
|------------|:-------------:|
| mayor que   |     |
| mayor que o igual a   |    centered   |  
| menor que   | right-aligned |
| menor o igual que   | right-aligned |
| no igual a  | right-aligned |
| igual a   | right-aligned |

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
