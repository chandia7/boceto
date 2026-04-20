# Sistema-de-Gestion

Microservicios:
-ms-usuarios: Lógica de registro, login (generación de tokens JWT), encriptación de contraseñas y gestión de los perfiles y roles.

ya esta, falta completarlo nomas

  °id, nombre, email, contraseña(esto se debe incriptar), fecha de registro

  Los roles y gestion del usuario se van hacer aparte

-ms-propiedades: Catálogo de los inmuebles. Maneja características (metros cuadrados, habitaciones) y ubicación (por ejemplo, filtrando por comunas dentro de la Región Metropolitana).

ya esta, falta completarlo nomas

  °id, dirrecion, precio, habitacion, baños, metros_cuadrados y el propetario(la id del usuario)

-ms-postulaciones: Permite a los arrendatarios subir sus documentos (liquidaciones de sueldo, certificados) y postular a una propiedad específica.

-ms-evaluacion: Lógica de negocio pura. Cruza los datos de ingresos del arrendatario con el valor de la propiedad para determinar si es un candidato apto o riesgoso.

-ms-contratos: Gestiona el ciclo de vida del arriendo. Fechas de inicio, término, renovaciones y montos acordados.

-ms-pagos: Procesamiento de las rentas mensuales, registro de transferencias y cálculo de multas por atraso (incluso manejando conversiones a UF si lo desean).

-ms-mantenciones: Un módulo donde el arrendatario puede reportar problemas (ej. falla eléctrica, filtración de agua) y el propietario o administrador gestiona la reparación.

-ms-visitas: Calendario para que los interesados agenden recorridos presenciales a las propiedades disponibles.

-ms-notificaciones: Servicio transversal que envía alertas (correos simulados) cuando se aprueba un contrato, se acerca la fecha de pago o se confirma una visita.

-ms-reportes: Recopila datos de otros servicios para generar estadísticas al administrador: total de ingresos mensuales, porcentaje de propiedades vacantes, etc.
