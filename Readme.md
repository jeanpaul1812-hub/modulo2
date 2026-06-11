🏦 Mani Bank - Billetera Digital
Aplicación web de simulación de una billetera digital desarrollada como proyecto multipágina utilizando HTML5, CSS3, Bootstrap 5 y jQuery. Permite gestionar saldo, registrar transacciones (ingresos y salidas), mantener una libreta de contactos/clientes y visualizar el historial de movimientos, persistiendo los datos de manera local en el navegador.

🚀 Características
🔒 Autenticación Simple: Validación de usuario y contraseña para acceder a la plataforma.

📥 Ingresos: Permite abonar saldo a la billetera.

📤 Salidas (Transferencias): Envío de fondos descontando del saldo disponible y seleccionando destinatarios precargados mediante un selector dinámico.

👥 Gestión de Clientes: Directorio para agregar o eliminar contactos (con nombre, RUT, cuenta y banco).

📝 Movimientos: Registro histórico de cada acción realizada.

💾 Almacenamiento Local: Los datos de saldo, clientes e historial se guardan en el navegador utilizando localStorage.

📂 Estructura del Proyecto
El proyecto está dividido en 5 archivos HTML independientes que se comunican entre sí:

index.html - Pantalla de inicio de sesión (Login).

ingresos.html - Sección para consultar saldo y realizar depósitos.

salidas.html - Sección para realizar envíos de dinero a clientes guardados.

clientes.html - Directorio para registrar y eliminar destinatarios.

movimientos.html - Historial detallado de todas las transacciones.

🛠️ Tecnologías y Librerías Utilizadas
HTML5 (Estructura semántica de las vistas).

CSS3 (Variables CSS, diseño responsivo).

Bootstrap 5.3.3 (CDN para componentes, formularios, tablas y utilidades de diseño responsivo).

jQuery 3.7.1 (CDN para simplificar la manipulación del DOM y eventos).

JavaScript (ES6) (Lógica de negocio y comunicación con localStorage).

💻 Instrucciones de Uso
Descarga o clona el repositorio en tu computadora.

Asegúrate de que los 5 archivos .html estén en la misma carpeta.

Abre el archivo index.html en tu navegador web favorito (puedes simplemente hacer doble clic sobre él).

🔑 Credenciales de Acceso:
Usuario: jeanpaul

Contraseña: 6789

📜 Historial de Versiones / Cambios
Versión 1.0: Archivo monolítico (todo en un solo archivo .html).

Versión 2.0: Modularización multipágina (ingresos, salidas, clientes, movimientos).

Versión 3.0: Integración de Bootstrap 5 para mejorar la interfaz visual y jQuery para optimizar la manipulación de elementos en el DOM de forma más limpia.
