# UD 3. Práctica 1

# **Ejecución de JavaScript en navegador y en Node.js**

## **Objetivo de la práctica**

El objetivo de esta práctica es que el alumnado:

- Comprenda cómo se ejecuta JavaScript en el **navegador web**.
- Comprenda cómo se ejecuta JavaScript mediante **Node.js**.
- Utilice la **consola** como herramienta básica de depuración.
- Diferencie entre la ejecución de JavaScript en entorno cliente y en entorno local.

# **Ejercicio 1. Ejecución de JavaScript al cargar una página HTML**

## **2.1. Descripción del ejercicio**

Se debe crear una página web que, **al cargarse en el navegador**, muestre el mensaje:

```
Hola mundo
```

en la **consola del navegador**.

El mensaje **no debe aparecer en la página**, únicamente en la consola.

## **2.2. Pasos a seguir**

### **2.2.1. Crear la estructura del proyecto**

1. Crea una carpeta llamada `practica-hola`.
2. Dentro de la carpeta, crea un archivo llamado `index.html`.

### **2.2.2. Crear la estructura básica del archivo HTML**

Edita el archivo `index.html` e introduce:

- La estructura básica de un documento HTML5.
- El idioma del documento en español.
- Un título adecuado para la página.
- Un encabezado `<h1>` visible que indique que se trata del Ejercicio 1.

### **2.2.3. Inclusión del script**

1. Añade una etiqueta `<script>` dentro del documento HTML.
2. Coloca la etiqueta `<script>` **al final del <body>**, de forma que el código se ejecute cuando la página haya terminado de cargarse.
3. Dentro de la etiqueta `<script>`, escribe el código JavaScript necesario para que se muestre el mensaje **Hola mundo** en la consola del navegador.

<aside>
⚠️

**Importante:**

No se debe mostrar el mensaje en pantalla ni mediante alertas, únicamente en la consola.

</aside>

### **2.2.4. Abrir la página en el navegador**

1. Guarda el archivo `index.html`.
2. Ábrelo en un navegador web (doble clic sobre el archivo).

### **2.2.5. Abrir la consola del navegador**

Con la página abierta:

- Abre las **herramientas de desarrollo** del navegador.
- Accede a la pestaña **Consola / Console**.
- Recarga la página para comprobar que el mensaje aparece al cargarse.

### **2.2.6. Resultado esperado**

Al recargar la página, en la consola del navegador debe aparecer el texto:

```
Hola mundo
```

# **Ejercicio 2. Ejecución de JavaScript utilizando Node.js**

## **3.1. Descripción del ejercicio**

En este ejercicio se debe crear un archivo JavaScript que, al ejecutarse con Node.js desde la terminal, muestre el mensaje:

```
Hola mundo
```

## **3.2. Requisitos previos**

- Tener **Node.js** instalado en el sistema.
- Poder ejecutar el comando node desde una terminal.

Para comprobarlo:

```bash
node -v
```

## **3.3. Pasos a seguir**

### **3.3.1. Crear el archivo JavaScript**

1. Dentro de la carpeta `practica-hola`, crea un archivo llamado `app.js`.

### **3.3.2. Escribir el código JavaScript**

1. Abre el archivo `app.js`.
2. Escribe la instrucción necesaria en JavaScript para que, al ejecutarse el archivo, se muestre el mensaje **Hola mundo** en la terminal.

### **3.3.3. Ejecutar el archivo con Node.js**

1. Abre una terminal.
2. Sitúate en la carpeta `practica-hola`.
3. Ejecuta el archivo usando el comando adecuado de Node.js.

### **3.3.4. Resultado esperado**

Tras ejecutar el comando, en la terminal debe mostrarse:

```
Hola mundo
```

# **4. Entrega**

El alumnado deberá entregar:

- La carpeta `practica-hola` con:
    - `index.html`
    - `app.js`
- Evidencias del funcionamiento:
    - Captura de la consola del navegador (Ejercicio 1)
    - Captura de la terminal con la ejecución de Node.js (Ejercicio 2)
