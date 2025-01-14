# Contenido de Minimos

| PragmaPower | Qué? | Cómo? | Ways | Who? | Responsible | Priority |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Diseño de arquitectura](CleanArchitecture.md) | Separar responsabilidades, facilitar el mantenimiento, la escalabilidad y las pruebas, creando así un sistema modular y fácilmente adaptable a cambios tecnológicos | Organizando el código de manera que sea independiente de frameworks, bases de datos e interfaces externas | Clean architecture | Mobile Frontend Backend Integraciones | Backend | High |
| [Desarrollo](/excepciones.md) | Responder adecuadamente a situaciones inesperadas y mejorar la experiencia del usuario, capturando registrando cada uno de los eventos que se ejecutan en el sistema. Además de facilitar la depuración y el mantenimiento al proporcionar información detallada sobre los fallos. | Garantizando que el sistema maneje los errores de manera controlada y sin interrumpir su funcionamiento | Manejo de excepciones | Mobile Frontend Backend Integraciones | Backend | High |
| Desarrollo | Buscar errores, malas prácticas o inconsistencias, además de asegurar que el código siga un estilo de formato consistente (como sangrías y espaciados). Obteniendo un código limpio, fácil de leer, y libre de errores, facilitando la colaboración y el mantenimiento a largo plazo. | Mejorando el código a través de revisión de sintaxis y formateo del código a partir de estándares y reglas | Linters y formatters | Mobile Frontend Backend Integraciones | Backend | Medium |
| [Desarrollo](cleancode.md) | Mejora la comprensión y la colaboración entre los desarrolladores, facilitar la detección y corrección de errores, y permitir una mayor escalabilidad y extensibilidad del código | Implementando una práctica de desarrollo para escribir código que se fácil de leer y entender | Clean code | Backend Integraciones | Backend | High |
| Observabilidad | Monitorear y rastrear el comportamiento de la aplicación, identificar errores y problemas de rendimiento, y auditar acciones del sistema. Facilitando la depuración, el análisis de incidentes y la mejora continua al proporcionar información detallada sobre el funcionamiento en tiempo real. | Analizando, identificando y registrando información en logs | loggers | Mobile Frontend Backend Integraciones Ecommerce CloudOps DevSecOps | Backend | Medium |
| [DevSecOps](AlmacenamientoConfiguracion.md) | Proteger la información de accesos no autorizados, mediante el almacenamiento seguro y gestión adecuada, previniendo el compromiso de la información crítica, asegurando la integridad y mejorando la seguridad del sistema. | Almacenando información de configuración de carácter sensible o privada en secretos | secrets manager | Mobile Frontend Backend Integraciones Ecommerce CloudOps DevSecOps | Backend | High |
| Documentación | Relacionar instrucciones de instalación, facilitando a otros desarrolladores configurar y ejecutar el proyecto de manera fácil e intuitiva. | Creando un archivo README | readme.md | Mobile Frontend Backend Integraciones Ecommerce CloudOps DevSecOps | Backend | Medium |
| [Documentación](/documentacionApis.md) | Facilitar la comprensión y uso de las APIs. Permitiendo generar documentación interactiva y precisa, mejorando la colaboración entre equipos y simplificando la integración de servicios, garantizando consistencia y reduciendo errores en la implementación de las APIs. | Estandarizando y automatizando la descripción de las APIs | Swagger OpenApi | Backend Integraciones | Backend | High |
| [Testing](/testing.md) | - Verificar que cada unidad de código (como funciones o métodos) funcionen correctamente de manera aislada. Permitiendo detectar errores rápidamente, mejorar la calidad del código, y garantizar que futuras modificaciones no rompan funcionalidades existentes. - Verificar el comportamiento y la apariencia de los componentes o widgets en la interfaz de usuario, comprobando que los elementos visuales interactúan correctamente y se renderizan como se espera.  - Comparar la salida visual de un componente o interfaz con una referencia preestablecida, asegurando que los cambios no alteren de manera no deseada el diseño o la apariencia de la aplicación.  - Verificar que diferentes componentes o módulos del sistema interactúan correctamente entre sí, comprobando que las interfaces y flujos de datos entre partes del sistema funcionen como se espera. - Evaluar la efectividad de los tests existentes al introducir cambios pequeños y controlados (mutaciones) en el código, simulando errores o fallos para verificar si las pruebas automáticas son capaces de detectar dichos cambios. - Detectar y mitigar vulnerabilidades en componentes del código, asegurando que manejen correctamente datos sensibles, autenticación, comunicación segura y errores sin exponer información, previniendo fallos de seguridad y protegiendo la aplicación contra ataques. - Evaluar cómo se comporta el sistema bajo diferentes condiciones de carga, asegurando que pueda manejar un número esperado de usuarios y transacciones sin comprometer su rendimiento, ayudando a identificar cuellos de botella, problemas de escalabilidad y puntos críticos que pueden afectar la velocidad, la estabilidad y la experiencia del usuario. | Implementando diferentes tests | Unit test Widget test Golden test Integration test Mutation test Security test | Mobile Frontend Backend Integraciones | Backend: Unit test Mutation test  Integraciones: Integration test Security test |  |
