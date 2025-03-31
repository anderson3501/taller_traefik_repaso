# taller_traefik_repaso Anderson Carvajal y Harold Rodriguez

¿Cómo detecta Traefik los servicios configurados en Docker Compose?
 Traefik utiliza el provider Docker, leyendo los labels definidos en el archivo docker-compose.yml para identificar y configurar automáticamente los routers y servicios.


¿Qué rol juegan los middlewares en la seguridad y gestión del tráfico?
 Los middlewares permiten añadir funcionalidades intermedias como autenticación, redirecciones, balanceo de carga, gestión de errores y limitación de IP, ayudando a gestionar el tráfico de forma segura y personalizada.


¿Cómo se define un router en Traefik y qué parámetros son esenciales?
 Un router se define a través de labels o en el archivo de configuración, y los parámetros esenciales incluyen la regla de enrutamiento (por ejemplo, el Host o path) y la asignación a un servicio y, opcionalmente, a middlewares.


¿Cuál es la diferencia entre un router y un servicio en Traefik?
 El router se encarga de dirigir el tráfico entrante a un servicio basado en reglas, mientras que el servicio define cómo acceder a los contenedores o instancias reales que procesan la solicitud.


¿Cómo se pueden agregar más reglas de enrutamiento para diferentes rutas?
 Se pueden agregar reglas adicionales definiendo más routers en el archivo de configuración o en los labels de Docker, utilizando condiciones basadas en host, path, o cualquier otro criterio soportado por Traefik.
