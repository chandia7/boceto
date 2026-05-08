# Sistema-de-Gestion

Microservicios:

listo usuario, reportes, seguimiento, notificaciones, pagos, logistica, seguridad(Falta solo generar el Token JWT), promociones, inventario, catalogo.

ms correjidos: 

si da problemas cambien los puertos ya chatgpt dice que podria dar error si estan en el mismo puerto

Los puertos no deben repetirse
Cada microservicio debe correr en un puerto distinto.

Ejemplo:

catálogo → 8081
reportes → 8082
usuarios → 8083

Si dos usan el mismo puerto, uno fallará.

1.-ms-usuarios: El "directorio". Guarda la información blanda y pública del usuario (nombre, apellido, teléfono, dirección de envío, avatar). 

2.-ms-reportes: Analítica para el administrador.

3.-ms-seguimiento: Tracking del estado del pedido.

4.-ms-notificaciones: Envío de alertas (correos/mensajes).

5.-ms-pagos: Procesamiento y validación financiera.

6.-ms-logistica: Gestión de entregas o trámites legales.

7.ms-seguridad: El "guardia". Se encarga exclusivamente de las credenciales (email y contraseña), aplicar el encriptado BCrypt, manejar los roles (Vendedor, Cliente, Admin) y emitir el token JWT.

8.-ms-promociones: Gestión de descuentos y ofertas.

9.-ms-inventario(stock): Disponibilidad y estados de stock.

10.-ms-catalogo: Información de productos/propiedades (sin lógica de stock).

11.--ms-pedidos: Generación y gestión de órdenes de venta.
