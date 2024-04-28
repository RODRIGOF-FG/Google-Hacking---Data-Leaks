# Google Hacking - Data Leaks




<br>

## Tabla de Contenido
- [🚀 Introducción](#introducción)
- [🔍 Google Hacking](#google-hacking)
- [⚙️ Comandos Básicos](#comandos-básicos)
- [🔑 Operadores](#operadores)
- [🔗 Operadores Lógicos](#operadores-lógicos)
- [🔍 Búsqueda de Información Sensible](#búsqueda-de-información-sensible)
- [🔍 Buscar Correos y Contraseñas en Pastebin](#buscar-correos-y-contraseñas-en-pastebin)

---


<br>




### Introducción


Este proyecto se realiza con fines educativos y de investigación para concienciar a las personas sobre los riesgos asociados con la exposición de información sensible en línea y la importancia de investigar si tenemos alguna información expuesta en diversos sitios web.

Es fundamental comprender que esta técnica debe ser utilizada de manera ética y responsable, con el objetivo de mejorar la seguridad de la información y proteger la privacidad de los usuarios en línea. Al utilizar Google Hacking para identificar posibles fugas de datos, podemos tomar medidas proactivas para mitigar cualquier riesgo potencial y salvaguardar la información confidencial. Ademas exploraremos diversos comandos de búsqueda relacionadas con Google Hacking para detectar posibles filtraciones de datos, tales como direcciones de correo electrónico, contraseñas y otra información sensible.


### Google Hacking:

Es una técnica que implica el uso de comandos de búsqueda avanzados en Google u otros motores de búsqueda con el propósito de encontrar información específica que normalmente no sería accesible mediante búsquedas convencionales.

**Busqueda exacta:**
Se utilizan las comillas ("") alrededor de una frase o una secuencia de palabras en una búsqueda, esto ayuda a realizar una busqueda exacta y con estas comillas se restringe los resultados a aquellos que contienen la frase exacta dentro de las comillas


**Ejemplo:**

```js

"Ciberseguridad"

```

### Comandos Basicos

**Site:**
- Limita los resultados de busqueda a un dominio en especifico.
- Se utiliza cuando se necesita buscar información en un sitio en particular, ya que al usar el comando, se indexarán solo búsquedas en esa página web o dominio.


**Ejemplo:**

```js

Ciberseguridad site:wikipedia.org

```

**intitle:**
- Limita los resultados de búsqueda a aquellos que contienen una palabra o frase específica en el título de la página.
- Este comando se utiliza para encontrar páginas web que contengan información específica en su **título**, como "contraseñas", "base de datos" o "confidencial".

**Ejemplo:**

```js

intitle:ciberseguridad

```

**filetype:**

- Filtra los resultados para mostrar solo archivos de un tipo específico.
- Se utiliza cuando se necesita buscar archivos de un formato particular, como documentos de Word, hojas de cálculo de Excel o archivos PDF, este comando restringe los resultados a ese tipo de archivo.

**Ejemplo:**

```js

filetype: pdf

```


**intext:**

- Limita los resultados de búsqueda para mostrar solo páginas que contienen una palabra o frase específica en su contenido.
- Este comando ayuda a  buscar páginas web que contengan información específica dentro de su texto, como números de teléfono, direcciones de correo electrónico o cualquier otra cadena de texto relevante.

**Ejemplo:**

```js

intext: tutorial Python

```


**inurl:**

- Limita los resultados de búsqueda para mostrar solo páginas que contienen una palabra o frase específica en su URL.
- Se utiliza este comando para encontrar páginas web que tienen una palabra o frase específica en su dirección URL, lo que puede ser útil para buscar páginas con un tema o contenido particular.

**Ejemplo:**

```js

inurl:blog viajes Europa

```


<br>

[Volver inicio :arrow_up:](#Introducción)

<br>


### Operadores

**Suma(+):**
- El símbolo más (+) entre dos palabras o mas , indica a Google que incluya los términos en los resultados de búsqueda.

**Ejemplo:**
  
```js

"seguridad informatica + normativas"

```

**Resta (-):**
- Al usar el signo menos (-) delante de una palabra, estás indicando a Google que excluya esa palabra de los resultados de búsqueda.

**Ejemplo:**
  
```js

seguridad informatica -normativas

```


<br>

[Volver inicio :arrow_up:](#Introducción)

<br>


### Operadores lógicos:

Estos operadores lógicos (AND, OR, NOT) se utilizan para combinar términos de búsqueda y refinar los resultados. Por ejemplo, el operador AND muestra resultados que contienen ambas palabras, OR muestra resultados que contienen al menos una de las palabras, y NOT excluye términos específicos de los resultados de búsqueda.

**AND**

  ```js

nmap AND script

```

- Se mostrará resultados que contengan ambas palabras

**OR**


  ```js

vulnerabilidades OR vulnerability

```

- Mostrará resultados que contengan al menos una de las palabras

**NOT**


  ```js

Hacker ético NOT ciberdelincuencia

```

-  Mostrará resultados que contengan la palabra "Hacker ético" pero excluyendo aquellos que contengan la palabra "ciberdelincuencia".




<br>

[Volver inicio :arrow_up:](#Introducción)

<br>


### Comandos para buscar informacion sencible:

**Busqueda de direcciones de correo electronico**

**Ejemplo:**

  ```js

"@dominio.com"


```

- Esta búsqueda mostrará resultados que contienen direcciones de correo electrónico que terminan con "@dominio.com". Puedes reemplazar "dominio.com" con el dominio específico que estés investigando.


**Búsqueda de archivos que contienen la palabra "password"**

**Ejemplo:**

  ```js

intitle:"index of" password


```

- Esta búsqueda mostrará páginas web que contienen archivos que están indexados con el término "password" en su título. 


**Búsqueda de archivos de texto que contienen contraseñas:**

**Ejemplo:**

  ```js

filetype:txt password


```

- Esta búsqueda mostrará archivos de texto que contienen la palabra "password". Los archivos de texto a menudo se utilizan para almacenar información como contraseñas de forma no cifrada.



<br>

[Volver inicio :arrow_up:](#Introducción)

<br>


### Buscar correos y contraseñas en Pastebin


**Buscar correos**

**Ejemplo:**

  ```js

"@gmail.com" site:pastebin.com 


```

- Esta busqueda se utiliza para buscar en el sitio web Pastebin cualquier contenido que contenga la cadena @gmail.com


**Buscar correos y contraseñas**

**Ejemplo:**

  ```js

"@gmail.com" + "password:" site:pastebin.com 


```

- Esta busqueda específica en Pastebin que intenta encontrar texto que contenga direcciones de correo electrónico de Gmail (@gmail.com) junto con la palabra "password:".


<br>

[Volver inicio :arrow_up:](#Introducción)

<br>
