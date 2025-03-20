# Guía de referencia: Operadores de Python

## 📚 Conceptos Básicos
En Python, los operadores realizan operaciones aritméticas y lógicas. Aunque los básicos como suma y resta son familiares, existen muchos más. Son esenciales en programación y se utilizan constantemente, especialmente en el trabajo de los profesionales de datos. Esta guía te ayudará a conocerlos.

### 🔹 Relacionales
En Python, puedes utilizar operadores de comparación para comparar valores. Cuando se realiza una comparación, Python devuelve un resultado booleano-Verdadero o Falso.

| Operación  |    Operador   |
|------------|:-------------:|
| mayor que   |   >  |
| mayor que o igual a   |   >=   |  
| menor que   | < |
| menor o igual que   | <=|
| no igual a  | != |
| igual a   | ==  |

### 🔹 Operadores lógicos 
- and : evalúa a Verdadero sólo si ambas sentencias son verdaderas
- or  : evalúa a True si una o ambas sentencias son verdaderas
- not : Si la sentencia es Verdadera, devuelve Falso; si la sentencia es Falsa, devuelve Verdadero
```python
x = 3
my_list = [3, 4, 6, 10]
print(x < 3 and x != 0)
print(x >= len(my_list) or x == min(my_list))
print(x not in my_list)
```

### 🔹 Operadores aritméticos 
Estos operadores aritméticos son:

```python
 sum([6, 3])
9
```

¡Sigue explorando Python! 🚀
