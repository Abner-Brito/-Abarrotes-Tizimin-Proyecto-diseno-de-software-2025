# Abarrotes Tizimín


## Requerimientos  
Del 1 al 3, siendo el 3 el más alto y el 1 el más bajo.

### Funcionales:  

| Clave  | Nombre                     | Prioridad | Descripción                                                                 |
|--------|----------------------------|-----------|-----------------------------------------------------------------------------|
| RF01   | Registro de cliente        | 3         | El sistema permitirá ingresar los siguientes datos del cliente: Identificador del Cliente, Nombre, Apellido Paterno y Dirección. |
| RF02   | Registro de artículos      | 3         |  El sistema permitirá registrar nuevos artículos con los siguientes atributos: Identificador, Nombre del artículo, Precio al público, Precio del proveedor y Cantidad total en existencia. |
| RF03   | Visualización de artículos | 2         | El sistema mostrará al cliente los atributos de los artículos: Identificador, Nombre del artículo, Precio al público, Precio del proveedor y Cantidad en existencia. |
| RF03   | Compra de artículos        | 3         | El sistema permitirá al cliente realizar una compra donde se proporcione el artículo comprado y su cantidad, al finalizar la compra se debe mostrar un ticket donde aparezca el nombre del artículo, cantidad, precio de lo adquirido, fecha y el nombre del cliente (verificar existencia), así como el importe total de la compra. |
| RF04   | Menú principal       | 3         | El sistema mostrará un menú con las siguientes opciones: registro de cliente, registro de artículos, compra de artículos y salir|
***
<br>





### No funcionales:
| Clave  | Nombre                         | Prioridad | Descripción                                                                                  |
|--------|--------------------------------|-----------|----------------------------------------------------------------------------------------------|
| RNF01  | Rendimiento                    | 3         | El sistema debe mostrar el menú principal y las vistas de registro en menos de 2 segundos.  |
| RNF02  | Usabilidad                     | 2         | La interfaz debe ser sencilla e intuitiva para usuarios sin experiencia técnica.             |
| RNF03  | Disponibilidad                 | 2         | El sistema debe estar disponible para su uso durante el horario de atención (por ejemplo, 8:00 a.m. a 8:00 p.m.). |
| RNF04  | Seguridad                      | 2         | Los datos registrados de clientes y artículos deben estar protegidos contra accesos no autorizados. |
| RNF05  | Mantenibilidad                 | 1         | El sistema debe estar desarrollado de forma modular para facilitar futuras modificaciones.   |
| RNF06  | Integridad de datos            | 3         | No debe permitirse el registro de artículos o clientes con campos vacíos o identificadores duplicados. |
| RNF07  | Generación de tickets          | 2         | Los tickets generados deben estar bien formateados, contener la información completa y ser fácilmente legibles. |

