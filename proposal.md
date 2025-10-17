# Propuesta TP DSW

## Grupo
### Integrantes
* 50749 - Coux, Francisco Julián
* 47359 - Lapunzina, Luciano
* 52897 - Mesapelle, Giani


### Repositorios
* [frontend app](https://github.com/giani1233/tp-dsw-frontend)
* [backend app](https://github.com/giani1233/tp-dsw-backend)

## Tema
### Descripción
Plataforma web diseñada para facilitar la organización y asistencia a actividades. Los organizadores podrán crear, administrar y promocionar sus eventos, proporcionando detalles como precio, ubicación, descripción, etc. Los usuarios, por su parte, podrán explorar los eventos disponibles para su ubicación y fechas de preferencia. Además podrán adquirir las entradas a los mismos de manera sencilla y segura.

### Modelo
![imagen del modelo](https://github.com/giani1233/tp-dsw-proposal/blob/main/MD%20TP%20DSW.png)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Categoria<br>2. CRUD Entrada<br>3. CRUD Usuario|
|CRUD dependiente|1. CRUD Evento {depende de} CRUD Categoria <br>2. CRUD Direccion {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de eventos filtrado por localidad, rango de fechas y categoria => detalle precios y ubicaciones<br> 2. Listado de entradas filtrado por evento, muestra numero de entrada => detalle muestra datos del cliente|
|CUU/Epic|1. Cargar evento <br>2. Registrarse|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Categoria<br>2. CRUD Entrada<br>3. CRUD Usuario<br>4. CRUD Provincia<br>5. CRUD Evento<br>6. CRUD Localidad<br>7. CRUD Pago<br>|
|CUU/Epic|1. Cargar evento<br>2. Registrarse<br>3. Consultar eventos disponibles<br>4. Realizar compra de entradas para evento|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados |1. Listado de categorías, muestra nombre de categorías|
|CUU/Epic|1. Reembolsar entrada|
|Otros|1. Envío de recordatorio por email<br>2. Envío de entradas por mail|

