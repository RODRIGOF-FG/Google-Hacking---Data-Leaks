# Google Hacking - Data Leaks

### Introduccion


Google Hacking es el uso de comandos de búsqueda avanzados en Google u otros motores de búsqueda para encontrar información específica que normalmente no sería accesible mediante búsquedas convencionales.


### Busqueda exacta:
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












