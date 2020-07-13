# Uso de Python para el desarrollo de aplicaciones de Inteligencia Artificial
Este es el nota del segundo modulo, gracias a [Ing. Felipe Llaugel](https://do.linkedin.com/in/felipe-llaugel-b9238634)

# Python
- Lenguaje de programación flexible y sencillo.
- Creado por **Guido Van Rossum**.
- Permite procesar todo tipo de estructura de datos: `números`, `texto`, `booleanos`, `listas`, `diccionarios`.
- Es código libre, se puede usar y compartir fácilmente.
- Lenguaje interpretado.
- Tipado dinámico.
- Multiplataforma (`Linux`, `MacOS`, `Windows`)
- Python scripts terminan con la extensión `.py`
- Permite ejecutar su código en varios sistemas operativos.
- Soporta varios paradigmas de programación, orientación a objetos, estructurada.
- No se pueden combinar variables de distintos tipos.
- El formato del código es estructural.

|Ventajas|Desventajas|
|--------|-----------|
|Simplifica la programación y es rápido.|La mayoría de los servidores no tienen soporte de python.|
|Lenguaje flexible, no es necesario declarar cada tipo de datos.|Los usuarios optan por usar librerías de otros lenguajes.|
|Legible y módulos organizados.| La curva de aprendizaje no es tan sencilla para algunas de las funcionalidades del lenguaje.|
|Tiene incluidas las librerías mas utilizadas.||

# Función `Print`
Para utilizar la función `print` hay que abrir paréntesis y escribir lo que queremos que devuelva el interprete. Si es un texto o cadena se utilizan comillas `("")`.

```python
// In
print("Hello world")

// Out
Hello world
```
# Enteros, reales y operadores aritméticos
## Números `Enteros` y `Reales`
- En python los números enteros son de tipo `int`.
- En python los números reales son de tipo `float`.
- Con la función `type()` podemos obtener el tipo de variable.

Ejemplo para `enteros`:
```python
// In
x = 5
print(x)
print(type(x))

// Out
5
<class int>
```

Ejemplo para `reales`:
```python
// In
y = 3.8
print(y)
print(type(y))

// Out
3.8
<class float>
```

## Operadores Aritméticos
|Operador|Operación que representa|
|--------|------------------------|
|`+`|Suma|
|`-`|Resta|
|`*`|Multiplicación|
|`**`|Exponente|
|`/`|División|
|`//`|División Entera|
|`%`|Módulo|

Ejemplos:
```python
// Suma
x + y

// Resta
x - y

// Multiplicacion
x * y

// Divicion
x / y

// Exponente
x ** 2

// Divicion entera
x // y

// Modulo
x % y
```

# Booleanos, Operadores Lógicos y Cadenas
## Cadenas
- Las cadenas son de tipo string.
- Para asignar a una variable un texto o cadena se utilizan comillas simples(`' '`) o comillas dobles(`" "`).
- Para insertar saltos de línea entre las cadenas o textos se pueden usar caracteres de escape o triples comillas.

