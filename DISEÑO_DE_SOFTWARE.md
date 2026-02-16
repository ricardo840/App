###Diseño de software

###Fases
####1. Análisis de requisitos

####2. Diseño de prototipo

####3. Implementación

####4. Pruebas

####5. Implementación final

####6. Documentación    


1. Comprensión y refinamiento de requisitos de diseño
Se revisan los requisitos del sistema y se derivan requisitos de diseño más concretos (restricciones técnicas, rendimiento, seguridad, UX, integraciones).

Aquí decides, por ejemplo, qué tipo de arquitectura encaja (monolito, microservicios, cliente‑servidor, etc.).

2. Diseño de alto nivel (arquitectura)
Se define la estructura global: módulos, capas, componentes, servicios, y cómo se comunican entre sí.

Se eligen estilos y patrones arquitectónicos, tecnologías base (tipo de base de datos, framework web, patrón MVC, hexagonal, etc.).

3. Diseño de datos y modelos
Se modelan entidades y relaciones (diagramas ER, modelos de dominio, clases principales) y luego se derivan esquemas de bases de datos y contratos de datos (DTO, JSON, etc.).

También se definen reglas de negocio asociadas a esos datos, validaciones, restricciones de integridad y políticas de acceso.

4. Diseño detallado / de componentes
Se especifica el comportamiento interno de cada módulo: interfaces, métodos, flujos procedurales, algoritmos, estados, manejo de errores.

Es donde entran cosas como el modelo procedural y el esquema de diseño que veías: diagramas de flujo, pseudocódigo, contratos de funciones, secuencias de llamadas, etc.

5. Diseño de interfaz de usuario y experiencia
Se definen pantallas, navegación, wireframes, interacción usuario‑sistema y reglas de UX (feedback, accesibilidad, consistencia visual).

Suele incluir prototipos de baja/alta fidelidad que luego guían la implementación en frontend.

6. Revisión y validación del diseño
Se revisa el diseño (técnico, funcional y de UX) para asegurar que cumple requisitos, es consistente y viable de implementar.

Se ajustan modelos y esquemas antes de pasar a codificación, porque es mucho más barato corregir en diseño que en producción.

Si quieres, en el siguiente mensaje podemos tomar un ejemplo concreto (por ejemplo, una app de tareas con React + API REST) y te muestro qué produce cada fase: diagramas, modelos, esquemas y cómo se traducen a código.