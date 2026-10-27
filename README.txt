PLATAFORMA WEB - TERMINAL DE TRANSPORTE LA SÁBANA

ARCHIVOS
- index.html: estructura y formularios.
- styles.css: estilos visuales y diseño adaptable.
- script.js: validación de acceso, navegación y funciones de demostración.

CÓMO EJECUTAR
1. Descarga y descomprime la carpeta.
2. Abre index.html con Chrome, Edge o Firefox.
3. Usa uno de estos accesos de demostración:
   Administrador: usuario admin / contraseña admin123
   Pasajero: usuario pasajero / contraseña pasajero123

FUNCIONES INCLUIDAS
- Inicio de sesión con validación de campos vacíos y credenciales.
- Consulta de itinerarios de ida y regreso entre Sincelejo, Corozal, Betulia y Sincé; permite buscar tramos intermedios en ambos sentidos.
- Horarios, tiempos de recorrido y tarifas de ejemplo, pendientes de confirmación oficial.
- Reserva simulada de pasajes (sin pagos ni emisión de boletos reales).
- Registro de despachos, asignación de bahías y actualización de estados.
- Registro y seguimiento de incidencias.
- Resumen administrativo y exportación de los datos locales en JSON.
- Datos guardados localmente en el navegador mediante localStorage.

IMPORTANTE
Es un prototipo académico de frontend. El inicio de sesión se valida en JavaScript y NO es seguro para producción. Los usuarios y contraseñas están visibles en el código. No hay servidor ni base de datos centralizada; los datos solo se guardan en el navegador de ese equipo. La ruta está limitada al corredor Sincelejo–Corozal–Betulia–Sincé y su regreso en sentido inverso. Las tarifas, empresas, tiempos y horarios son ilustrativos. No se procesan pagos, no se emiten tiquetes reales y no existe conexión con GPS o sistemas externos.

Para convertirlo en un sistema real se necesita backend (por ejemplo Node.js), autenticación segura, base de datos, validación en servidor y una integración autorizada con las empresas transportadoras y medios de pago.
