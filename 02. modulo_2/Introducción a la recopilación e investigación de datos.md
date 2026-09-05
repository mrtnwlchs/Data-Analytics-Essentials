# Introducción a la recopilación e investigación de datos

## Herramientas para la comprensión de datos

### Datos y conjunto de datos

Los datos se recopilan y se comparten entre muchas organizaciones diferentes y en muchos formatos diferentes.

Una recopilación de datos se denomina conjunto de datos.

#### Conjunto de datos privados

- Datos médicos de un paciente (datos demográficos, resultados de pruebas, diagnósticos, horarios de citas)

#### Conjunto de datos públicos

- Repositorio de datos abiertos de la OMS que contiene estadisticas relacionadas con la salud de sus 194 paises miembros.

Los conjuntos de datos suelen contener varios archivos relacionados almacenados en distintos formatos. La información sobre un conjunto de datos, incluida una descripción de lo que contiene y como esta formateado se denomina metadatos.

Uno de los formatos más comunes para empaquetar e intercambiar datos es el formato de valores separados por comas __(CSV)__.

### Herramientas para el análisis de datos

- Excel
- SQL
- Tableau

## Funciones y conceptos básicos de Excel

### Formulas básicas de Excel

Hay 2 formas de realizar cálculos en Excel: formulas y funciones.

- Las formulas son expresiones que operan con los valores de una celda o un rango de celdas; las funciones son formulas predefinidas integradas en Excel.
- Las formulas en Excel empiezan con un signo "=" y se escriben directamente en una celda o en la barra de formulas.

_Ejemplo: =6/2_

#### Referencias de celda en una formula

Se puede usar el valor de otras celdas en las formulas lo que se denomina referencia de celda.

_Ejemplo: =A1+B1_

### Funciones básicas de Excel

- SUM
- AVERAGE
- COUNT
- MAX
- MIN

#### Importa archivo de datos CSV en Excel

- Iniciar Excel
- Clic en __Datos > Obtener datos > Desde Archivo > Deste Texto/CSV__

## Funciones simples para el análisis de datos

### Observaciones, variables y valores

Al realizar cualquier tipo de experimento o análisis de datos, es fundamental definir las caracteristicas clave que se deben medir u observar.

- Una variable se puede medir y su valor se puede manipular o controlar en escenarios teoricos.
- Los registros de los valores, patrones y ocurrencias en un conjunto de variables son observaciones.
    - El valor o conjunto de valores de una observación en especifico se denomina punto de datos.
- Cada observación puede considerarse y representarse como un registro en una base de datos o una fila en una hoja de calculo.
- La colección de observaciones constituye el conjunto de datos para el análisis.

> Las observaciones suelen tener un proposito y las variables incluidas dependeran de su relevancia para ese proposito.

Ejemplo: Si se pierde una mascota y se le pide a un grupo de personas que ayuden a buscarla, solo un pequeño conjunto de variables (caracteristicas del perro), son relevantes para las observaciones.

- __¿Que tipo de animal es?__ Es un perro.
- __¿Que tipo de perro?__ Schnauzer
- __¿De que color es?__ Gris
- __¿Que tamaño tiene?__ Mediano

#### Conjunto de datos

| Raza | Color | Tamaño |
|------|-------|--------|
| Caniche | blanco | grande |
| schnauzer | gris | mediano |
| Yorkie | marron-negro | 3 |
| Mezcla de perro | negro | 30 |

- Las variables son las caracteristicas (raza, color, tamaño). Todas las caracteristicas son variables porque cada una puede tener varios valores.
- A medida que las personas buscan al perro, se agregan puntos de datos para cada observación.
- Las observaciones que no cumplan con los criterios requeridos se descartaran.


### Tipos de variables

#### Categorica

Indican membresia a un grupo determinado.

- __Nominales:__ Constan de 2 o mas categorias cuyo valor se asigna en funcion de la identidad del objeto. Algunos ejemplos son, sexo, color de ojos o tipo de animal.
- __Ordinales:__ Variables compuestas por 2 o mas categorias en las que el orden es importante en el valor. Algunos ejemplos son, el rango de clases de los estudiantes (1ro, 2do, 3ro) o las escalas de las encuestas de satisfaccion.