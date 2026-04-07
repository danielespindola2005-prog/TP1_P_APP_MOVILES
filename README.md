  # TRABAJO PRÁCTICO Nº 1
## Fundamentos y Ecosistemas del Desarrollo Móvil
### Realizar el siguiente trabajo práctico en el repositorio de github asignado para la
### Actividad.
 Se deberán contestar las preguntas y subirlas como README.md

### 1- ¿Cuáles son los principales sistemas operativos para dispositivos móviles en la actualidad?
En la actualidad, el mercado de sistenas operativos móviles esta dominado casi en su totalidad por dos gigantes;
### Android
 Desarrollado por Google, siendo el lider mundial por su codigo abierto y su uso en marcas como Samsung, Xiaomi, Motorola, entre otras. Se destaca por su gran personalizacion y la variedad de aplicaciones en la Google Store.
### iOS 
Sitemas exclusivo para iPhone y iPad, es conocido por su alto nivel de seguridad, diseño optimizado y la integración en el ecosistema Apple, incluyendo servicios como iCloud y App Store.

### 2 - ¿Cuáles son las principales diferencias técnicas entre el desarrollo nativo para iOS y para Android en la actualidad?
Las principales diferencias técnicas entre el desarrollo nativo para iOS y para Android en la actualidad radican en los lenguajes de programación y los entornos de desarrollo específicos: 
iOS se desarrolla nativamente con Swift como estándar actual u Objective-C utilizando el IDE Xcode que es exclusivo de macOS, mientras que Android se basa en Kotlin o Java y emplea Android Studio que está basado en IntelliJ. 
La complejidad técnica varía en gran medida debido a la fragmentación del hardware y el ciclo de vida de la aplicación: 
Android requiere pruebas exhaustivas en múltiples dispositivos y fabricantes con diferentes resoluciones y versiones de sistema, además de gestionar estados de actividad más complejos (Crear, Iniciar, Reanudar, Pausar, Detener, Destruir); en cambio iOS opera en un ecosistema de hardware controlado por una sola empresa, simplificando las pruebas y ofreciendo un ciclo de vida más predecible centrado en AppDelegate y ViewControllers. 

### 3 - ¿A qué nos referimos cuando hablamos de desarrollo nativo en programación de APP móviles? ¿Qué ventajas ofrece sobre el desarrollo multiplataforma?
El desarrollo nativo se refiere a la creación de aplicaciones específicas para un sistema operativo determinado como iOS o Android, que utilizan los lenguajes de programación y herramientas oficiales de cada plataforma Swift o Objective-C para iOS; Kotlin o Java para Android.Este enfoque implica escribir código independiente para cada plataforma, lo que permite una integración directa con el sistema operativo y el hardware del dispositivo. 
Las principales ventajas del desarrollo nativo frente al multiplataforma incluyen:

### Rendimiento superior: 
Las aplicaciones nativas se ejecutan con mayor velocidad y eficiencia al aprovechar directamente las capacidades del dispositivo y las APIs del sistema. 

### Acceso completo al hardware: 
Permiten un uso ilimitado de funciones del dispositivo como cámara, GPS, micrófono y sensores sin las restricciones que suelen tener las soluciones multiplataforma. 

### Experiencia de usuario (UX) optimizada: 
Al seguir las guías de diseño nativas de cada plataforma, ofrecen una interfaz más fluida, intuitiva y consistente con los gestos y patrones de uso esperados por el usuario. 

### Mayor seguridad y estabilidad: 
Al ser compiladas específicamente para la plataforma, suelen presentar menos errores y mejor protección de datos en comparación con entornos de ejecución compartidos. 

### 4 - ¿Qué ventaja principal ofrece un Framework Multiplataforma (como Flutter o React Native) frente al desarrollo nativo?
La ventaja principal de los frameworks multiplataforma como Flutter o React Native frente al desarrollo nativo es la capacidad de utilizar una única base de código para desplegar aplicaciones en múltiples plataformas: iOS, Android, web y escritorio, lo que reduce significativamente los costos y el tiempo de desarrollo entre un 30% y un 50% menos frente a crear aplicaciones separadas para cada sistema operativo. Además, estos frameworks permiten compartir conocimientos y recursos entre equipos, facilitando la contratación y el mantenimiento a largo plazo, ya que no es necesario gestionar bases de código independientes ni especializarse en lenguajes específicos de cada plataforma. 
### Eficiencia de recursos:
 Se escribe, prueba y mantiene un solo código, optimizando las horas de desarrollo. 
### Coherencia visual:
 Garantizan una experiencia de usuario uniforme y consistente en todos los dispositivos. 
### Velocidad de lanzamiento:
 El Hot Reload y las herramientas integradas aceleran el ciclo de iteración y la puesta en producción de MVPs.

### 5 - En el contexto de la arquitectura móvil, ¿cuál es la función de una API REST? ¿Importa el sistema operativo desde el cuál se consuma la API o es indistinto?
La función principal de una API REST en la arquitectura móvil es actuar como un puente estandarizado que permite a las aplicaciones acceder, manipular y sincronizar datos y funcionalidades de un servidor remoto de forma segura y eficiente, independientemente de la complejidad interna del sistema. 
No importa el sistema operativo desde el cual se consuma la API; el protocolo es indistinto entre plataformas, iOS, Android, etc., ya que la arquitectura REST se basa en el estándar HTTP y en el intercambio de datos, generalmente JSON o XML, que cualquier dispositivo capaz de hacer solicitudes web puede interpretar. 

### Las funciónes y Principios Clave son;
### Separación de responsabilidades: 
Permite que el desarrollo del cliente, osea la app móvil, y del servidor osea el backend sea independiente, facilitando la evolución de cada parte sin afectar a la otra. 
### Interoperabilidad: 
Al utilizar métodos HTTP universales como GET, POST, PUT, DELETE, cualquier aplicación móvil, sin importar su lenguaje de programación o sistema operativo, puede comunicarse con el servicio. 
### Gestión de recursos: 
Funciona exponiendo recursos específicos como usuarios, productos o notificaciones a través de URLs únicas, permitiendo operaciones CRUD (Crear, Leer, Actualizar, Eliminar) de manera predecible. 

### Tip de Documentación: 
Tablas en Markdown
Para que las respuestas de los puntos 2 o 4 sean mucho más legibles y profesionales, se
sugiere utilizar una tabla comparativa. En el archivo README.md, puedes crear una
siguiendo este formato:
| Característica | Desarrollo Nativo | Multiplataforma (Flutter/RN) |
| :--- | :--- | :--- |
| Rendimiento | Optimizado al máximo | Muy alto (casi nativo) |
| Costo/Tiempo | Mayor (dos bases de código) | Menor (una base de código) |
| Acceso a Hardware | Total e inmediato | Depende de plugins/puentes |
