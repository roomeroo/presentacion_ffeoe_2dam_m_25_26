<div align="center">

# 🌍 Prácticas Erasmus+ · REWE Digital

### Formación en el Extranjero para Ocupación y Empleabilidad — 2º DAM · 2025/26


</div>

---

## 👥 Alumnos

| Nombre |
|--------|
| Adrián Romero Maldonado |
| Antonio Lorenzo Cano Jiménez |
| Samuel Márquez Ruiz |

---

## 🏢 Empresa

<div align="center">

### REWE Digital
**Sede · Colonia, Alemania 🇩🇪**

</div>

---

## 📋 Descripción

Este repositorio recoge la documentación correspondiente a la estancia de prácticas de **Formación Dual Erasmus+** realizada en la empresa **REWE Digital**, en su sede de **Colonia, Alemania**.

---

## 🎬 Recursos conjuntos

| Recurso | Enlace |
|---------|--------|
| 🎥 Vídeo conjunto (los tres alumnos) | [Ver en Google Drive](https://drive.google.com/file/d/17OJJgmVn0L3MSwwfz4q4V5gEJmapQ_rN/view) |
| 📊 Presentación conjunta | [Ver presentación](https://gamma.app/docs/REWE-Digital-uiu9k0grzfewlti?mode=doc) |

---

## 📂 Recursos por alumno

### Adrián Romero Maldonado

| Recurso | Enlace |
|---------|--------|
| 📄 Presentación principal (PDF) | [Abrir presentación](./Adrian_Romero_Maldonado-Presentacion_REWE_Digital.pdf) |
| 📄 Plan de Sostenibilidad (PDF) | [Abrir presentación](./Adrian_Romero_Maldonado-Plan_Sostenibilidad_REWE_Digital.pdf) |
| 🎬 Vídeo de la presentación | [Ver en Google Drive](https://drive.google.com/drive/folders/1gGA6YxkyxdJD3MQ-UV8N391BjxiD_di6?usp=drive_link) |

---

### Antonio Lorenzo Cano Jiménez

| Recurso | Enlace |
|---------|--------|
| 📄 Presentación (PDF) | [Presentacion PDF](https://drive.google.com/file/d/1SBqZYkC9ilxljIHAa1lpoaBrRR05ND0s/view?usp=sharing) |
| 🎬 Vídeo de la presentación | [Presentacion VIDEO](https://drive.google.com/file/d/1quYzGCASWLawnFZ_3WFZ5XIirVT3k0CH/view?usp=sharing) |

---

### Samuel Márquez Ruiz

| Recurso | Enlace |
|---------|--------|
| 📄 Presentación (PDF) | [Abrir presentación](./PRESENTACION%20DUAL%20-%20SAMUELMÁRQUEZRUIZ.pdf) |
| 🎬 Vídeo de la presentación | [Ver en Google Drive](https://drive.google.com/file/d/1Lb5sgZsPiLBye0_zvN8vzsPehX_s8FhU/view?usp=sharing) |

**Departamento:** Equipo IO  

## Resumen de la Actividad Realizada
Durante mi estancia de Formación Profesional Dual he tenido la gran oportunidad de estar plenamente integrado en el equipo de desarrollo **IO** de REWE Digital, en su sede central en Alemania. Nuestro departamento es el motor principal que gestiona de principio a fin todo el proceso técnico y la lógica de negocio de los pedidos online de la compañía. 

En mi caso particular, el trabajo se ha centrado en optimizar y asegurar de forma rigurosa la fiabilidad del sistema de recogida en tienda, conocido como *Click & Collect*. Este sistema es un servicio crítico que da soporte a los supermercados REWE y REWE To Go en todo el país, por lo que garantizar que el flujo de datos sea exacto es vital para la operativa diaria de la empresa.

---

## Cronología por Fases

El tiempo de prácticas ha requerido meses de trabajo continuado, por lo que la progresión se divide en cuatro grandes fases técnicas:

*   **Fase Inicial (Aterrizaje técnico):** Durante las primeras semanas, el enfoque principal fue la integración en el ecosistema de la empresa. Esto incluyó la configuración exhaustiva de mi entorno de desarrollo local, el análisis detallado de la arquitectura de microservicios del proyecto y el estudio profundo de la documentación técnica interna.
*   **Fase de Desarrollo Core:** En esta etapa, que abarcó varios meses, me dediqué a la programación pura. Desarrollé desde cero la automatización de pruebas para los flujos de creación de pedidos (*Order*) y para los flujos de cambios de stock en almacén (*Bestandsveränderung*), creando los conjuntos de datos necesarios para validar múltiples escenarios.
*   **Fase de Integración:** Una vez automatizados los flujos, el siguiente nivel de complejidad fue conectar estas pruebas directamente con la base de datos de la empresa. Durante esta fase, logré interceptar la mensajería del sistema en tiempo real para verificar que los datos transmitidos coincidían con los registros guardados.
*   **Fase de Estabilización:** La fase final consistió en depurar los errores complejos detectados, optimizar la forma en la que el sistema compara los archivos y asegurar que las pruebas completas de extremo a extremo (E2E) fueran totalmente sólidas antes de su paso a producción.

---

## Contribuciones al Equipo y Responsabilidades

Mis contribuciones han aportado un valor directo y medible a la calidad del software (QA), automatizando flujos que son absolutamente críticos para el negocio:

*   **Autoevaluación del sistema:** He implementado validaciones automáticas de los mensajes de datos en tiempo real, cruzándolos con comprobaciones directas en la base de datos. He programado el sistema para que se auto-evalúe sin intervención humana.
*   **Optimización del tiempo de trabajo:** Gracias a estas aserciones, el equipo ya no tiene que revisar manualmente si el inventario cuadra de forma correcta cada vez que un cliente realiza un pedido online.
*   **Reducción de errores y estabilidad:** Esta automatización ha reducido drásticamente el margen de error humano y ha garantizado que el código que nuestro departamento despliega sea mucho más estable y seguro.

---

## Herramientas Utilizadas (Tech Stack)

Para llevar a cabo todo el desarrollo, he trabajado con un ecosistema tecnológico avanzado y altamente demandado en la industria:

*   **Karate Framework & JSON:** Herramienta principal utilizada para la automatización de pruebas y validación de endpoints, trabajando intensivamente con la manipulación y comparación de archivos JSON.
*   **Apache Kafka:** Utilizado para el streaming de datos, permitiéndome interceptar y validar eventos de mensajería asíncrona del sistema en tiempo real.
*   **IntelliJ IDEA & GitLab:** Entorno de desarrollo principal y plataforma para la gestión del control de versiones, asegurando una integración continua con el resto del código del equipo.
*   **Validación de Base de Datos:** Implementación de consultas y aserciones directas mediante clientes SQL para garantizar la persistencia e integridad del inventario.

---

## Conocimientos Adquiridos por Módulo Profesional (2º DAM)

La experiencia en REWE Digital me ha permitido aplicar de forma integral y práctica la totalidad de los módulos del segundo curso:

*   **Acceso a Datos, Programación de Servicios y Procesos, y Diseño e Imp. de Infraestructuras de Servicios y APIs:** 
    Estas asignaturas han sido el núcleo de mi día a día. He aplicado estos conocimientos directamente al testear *endpoints* con Karate, al gestionar la integridad de la base de datos mediante aserciones automáticas y al manejar la compleja mensajería asíncrona de una arquitectura orientada a eventos mediante los tópicos de Apache Kafka.
*   **Sistemas de Gestión Empresarial:** 
    He comprendido a nivel de negocio y de código cómo funcionan los sistemas a gran escala. He podido ver en la práctica cómo se integran técnicamente los flujos de pedidos (*Order*) y las modificaciones de stock (*Bestandsveränderung*) dentro de la logística real de una empresa multinacional.
*   **Desarrollo de Interfaces y Programación Multimedia y Dispositivos Móviles:** 
    Aunque mi rol ha estado enfocado en el *backend*, garantizar que las estructuras de datos JSON fueran perfectas y sin fallos era un requisito vital para asegurar que la experiencia del usuario final en la aplicación móvil de *Click & Collect* fuera fluida, rápida y libre de errores visuales o de información.
*   **Inglés Profesional GS:** 
    He puesto a prueba y mejorado mi dominio del idioma al estar integrado en un equipo de desarrollo en Alemania, donde la lectura de documentación técnica compleja y los reportes diarios se realizan íntegramente en inglés.
*   **Itinerario Personal para la Empleabilidad II (IPE II):** 
    Las competencias de este módulo me han facilitado la comprensión de la cultura corporativa europea, la asimilación de mis derechos y deberes laborales en un entorno internacional, y me han dado la base para analizar y desarrollar la propuesta de innovación sostenible de la compañía.

---

## Proyecto de Innovación Sostenible (IPE II): Green Click & Collect
Para el apartado de innovación social y medioambiental, he diseñado una propuesta directamente alineada con los indicadores del Balance Social de la empresa. El proyecto se denomina **"Green Click & Collect"**.

**El problema y el objetivo:**
El objetivo fundamental de esta iniciativa es reducir drásticamente el desperdicio alimentario en la red de supermercados REWE, aportando una solución tecnológica a un problema social y de sostenibilidad clave.

**Implementación Tecnológica:**
En lugar de crear un sistema paralelo desde cero, la propuesta consiste en aprovechar y optimizar la tecnología que ya utilizamos en el equipo IO. El plan es modificar el algoritmo actual de cambios de stock (*Bestandsveränderung*) para que priorice y asigne automáticamente a los pedidos online aquellos productos que estén más próximos a su fecha de caducidad. 

Para llevar esto a cabo, propongo reutilizar nuestra red de eventos en **Apache Kafka** con el fin de generar alertas automáticas de caducidad temprana. Al mismo tiempo, la calidad de este nuevo flujo quedaría asegurada mediante nuestra robusta suite de pruebas en **Karate Framework**, garantizando que la experiencia del cliente siga siendo excelente mientras la empresa reduce su huella de residuos.

---

<div align="center">
  <sub>2º DAM · FFEOE · Curso 2025/26</sub>
</div>
