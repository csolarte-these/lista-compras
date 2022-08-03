# Lista de Compras API

## **Objetivo**
Diseñar una aplicacion que permita la creacion, modificacion y eliminacion de articulos de una lista de compras

<br>
<br>

### **Herramientas y tecnologias a utilizar:**

- Spring Boot

- JDK - 1.8 o superior

- Spring Framework

- Hibernate

- JPA

- Maven

- IDE de su preferencia

- H2 Base de datos embebida
<br>
<br>

### **La base de datos debe contener una tabla llamada LISTA_COMPRAS con la siguiente estructura**

- ID: Autogenerado

- Articulo: String : Contiene el nombre del articulo

- Cantidad: Integer: Cantidad de articulos a comprar

- Comprado: Boolean: Indica si el producto esta comprado (Al ser creado se inserta con este dato en false)

<br>
<br>

### **Las APIS que va a proveer la aplicacion son las siguientes:**

- POST /api/listacompras Agrega un articulo a la lista de compras

- GET /api/listacompras Consulta todos los articulos de la lista de compras

- GET /api/listacompras/:id Consulta un articulo de la lista segun el ID

- PUT /api/listacompras/:id Actualiza un articulo de la lista segun el ID (Coloca el articulo como comprado)

- DELETE /api/listacompras/:id Elimina un articulo de la lista segun el ID

- DELETE /api/listacompras Elimina todos los elementos de la lista de compras

- GET /api/listacompras/comprados Consulta todos los articulos comprados de la lista de compras

<br>
<br>


### **Las APIS que tienen como parametro el id y el Id no se encuentra deben lanzar una Excepcion indicando que el recurso no ha sido encontrado**



- Para la realizacion del ejercicio:

    - Clonar el proyecto base

    - Crear una rama nueva con los cambios

    - Al finalizar se suben los cambios mediante un pull request

<br>
<br>

Colocar cualquier detalle sobre la presente API en el archivo README.md

<br>
<br>

### **Luego de la realizacion de la API por favor responder a las siguientes preguntas:**

<br>

* Imagínate que queremos expandir la aplicación Lista de Compras para el uso simultáneo de muchas personas. ¿Que consideraciones debemos tomar en cuenta?
<br>

* Imaginate que aumenta drásticamente el uso de la aplicación Lista de Compras y ahora el listado de la lista de compras está demorando mucho, que alternativas consideras que podemos tomar en cuenta para solucionarlo?

<br>
<br>

Para subir el codigo del test pasar el pull request como resultado del examen al correo del entrevistador.
<br>
<br>

**Exitos!!**