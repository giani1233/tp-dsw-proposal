# Propuesta TP DSW

## Grupo
### Integrantes
* 50749 - Coux, Francisco Julián
* 47359 - Lapunzina, Luciano
* 52987 - Mesapelle, Giani


### Repositorios
* [frontend app](https://github.com/giani1233/TP-DSW-2025/blob/main/frontend)
* [backend app](https://github.com/giani1233/TP-DSW-2025/blob/main/backend)

## Tema
### Descripción
Plataforma web diseñada para facilitar la organización y asistencia a actividades. Los organizadores podrán crear, administrar y promocionar sus eventos, proporcionando detalles como precio, ubicación, descripción, etc. Los usuarios, por su parte, podrán explorar los eventos disponibles para su ubicación y fechas de preferencia. Además podrán adquirir las entradas a los mismos de manera sencilla y segura.

### Modelo
![imagen del modelo](https://github.com/giani1233/TP-DSW-2025/blob/main/MD%20TP%20DSW.jpg)

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Categoria<br>2. CRUD Entrada<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Evento {depende de} CRUD Categoria <br>2. CRUD Direccion {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

