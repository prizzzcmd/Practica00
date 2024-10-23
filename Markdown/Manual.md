# Manual de Markdown
## En este manual asentaremos los conocimientos básicos de Markdown.
### Por ejemplo, para los encabezados usaremos almohadillas (#) para indicar el tamaño del encabezado, siendo más pequeño este cuantos más encabezados haya, seguidas de un espacio y luego el texto.

A continuación, veremos los siguientes tamaños de encabezados en relación con respeco al número de almohadillas:

# 1 almohadilla

## 2 almohadillas

### 3 almohadillas

#### 4 almohadillas

##### 5 almohadillas

###### 6 almohadillas

Sin embargo, existe una sintaxis alternativa para el primer y segundo nivel, que sería situar debajo del texto el mismo número de caracteres del texto original en símbolos igual (=), en el caso del primer nivel, y el guión (-) para el caso del segundo, por ejemplo.

Primer nivel
============

Segundo nivel
-------------

### Consejos

Es necesario poner un espacio entre la almohadilla y el texto.

#### Esto está bien

####Esto no

También es recomendable dejar espacios en blanco entre encabezados, como se ha mostrado hasta ahora.

### Párrafos

Para escribir párrafos, solo deberemos de escribirlos tal cuál, sin tabulaciones en el inicio.

### Saltos de línea

Se harán presionando la tecla de salto de línea (enter), como en cualquier otro tipo de documento.

Es decir
así.

### Negrita

Para añadir textos en negrita deberemos únicamente de poner la parte del texto a escribir en negrita entre dos asteriscos (*)

**Este texto está en negrita**

Hay una manera alternativa de hacerlo, y es con dos guiones bajos:

__Esto también está en negrita__

También podemos poner una parte de una palabra en negrita si no espaciamos los asteríscos:

Normal**negrita**normal

Nótese que he mencionado únicamente los asteriscos, puesto que en este caso no es aplicable el segundo método:

Esto__nofunciona__

### Cursiva

En este caso será exactamente igual que en negrita, salvo en que pondremos solo un asterisco o guión bajo, siguiendo la misma excepción para el resaltado dentro de palabras:

*cursiva*
_tambiencursiva_
cur*siva*
ya_no_cursiva

### Negrita en cursiva

Podemos poner tres asteriscos para poner la negrita en cursiva, por ejemplo:

***negritacursiva***
negrita***cursiva***
noesnegrita___cursiva___

### Listas numeradas

Se harán simplemente poniendo el número en cuestión de la lista junto a un punto, espaciarlo y poner el elemento a numerar, por ejemplo:

1. Elemento 1
2. Elemento 2
3. Elemento 3
4. Elemento 4
5. Elemento 5

### Listas con viñetas

Se harán exáctamente igual, pero en vez de indicar los elementos mediante números lo haremos o mediante asteríscos (*), símbolos de suma (+) o guiones (-), por ejemplo:

* Elemento
* Elemento
* Elemento

- Elemento
- Elemento
- Elemento

+ Elemento
+ Elemento
+ Element

No debiendo mezclar símbolos en una misma lista.

### Enlaces

Los enlaces los deberemos de poner entre signos menor que y mayor que (<>), por ejemplo:

<https://hsr.hoyoverse.com/es-es/home>

O, en el caso de que queramos que al pulsar una palabra nos lleve al enlace, pondremos la palabra en cuestión entre corchetes ([]), para posteriormente poner el enlace entre paréntesis.

Para arruinar tu vida, pulsa [aquí](https://store.steampowered.com/agecheck/app/1245620/)

### Imágenes

Para poner imágenes, deberemos poner un símbolo exclamacion (!), para después entre paréntesis poner la URL de la imagen.

![cheesecake](cheesecake-1.jpg)

Podemos poner un texto que defina el título entre corchetes ([]) antes de poner los paréntesis.

### Código

Para poner prompts de código, lo haremos entre símbolos de acentuación hacia la izquierda:

`Prompt`

Pudiendo escribir bloques de código siguiendo las reglas de escritura de código de la escritura de párrafos, excepto la de las tabulaciones, por ejemplo:

`<Bloque>`
    `<contenido>`
`</Bloque>`

### Citas

Para hacer citas, deberemos de poner símbolos de mayor qué (>) al principio de cada línea:

> Esto es una cita
>
> Algo larga.

### Tablas

Lo haremos creando las filas y columas con barras laterales (|) y guiones (-) para los encabezados, para las filas bastará con que se encuentren en el espacio de debajo.
En este caso se visualizará mejor con un ejemplo:

| Columna  | Columna  | Columna  |
|----------|----------|----------|
| Celda    | Celda    | Celda    |
| Celda    | Celda    | Celda    |
| Celda    | Celda    | Celda    |
