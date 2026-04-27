# Sistema-de-Gestion

Microservicios:

listo

1.-ms-usuarios: El "directorio". Guarda la información blanda y pública del usuario (nombre, apellido, teléfono, dirección de envío, avatar). 

2.-ms-catalogo: Información de productos/propiedades (sin lógica de stock).

3.-ms-inventario(stock): Disponibilidad y estados de stock.

4.-s-pedidos: Generación y gestión de órdenes de venta.

5.-s-pagos: Procesamiento y validación financiera.

6.-ms-logistica: Gestión de entregas o trámites legales.

7.-ms-notificaciones: Envío de alertas (correos/mensajes).

8.-ms-promociones: Gestión de descuentos y ofertas.

9.-ms-seguimiento: Tracking del estado del pedido.

10.-ms-reportes: Analítica para el administrador.

listo

11.-ms-seguridad: El "guardia". Se encarga exclusivamente de las credenciales (email y contraseña), aplicar el encriptado BCrypt, manejar los roles (Vendedor, Cliente, Admin) y emitir el token JWT.
