Plataformas de gestion


<tb>
SIEM splunk gestiona alertas para equipos SOC

EDR/NDR

SOAR

ITSM


### 🛠️ Herramientas de Gestión en el SOC

| Herramienta | Tipo | Función Principal | Uso en el SOC |
| :--- | :--- | :--- | :--- |
| **Splunk** | **SIEM** | Gestión de eventos e información de seguridad | Centraliza logs y gestiona alertas críticas para los analistas. |
| **EDR** | **Endpoint** | Detección y respuesta en puntos finales | Monitorea el comportamiento de laptops y servidores en tiempo real. |
| **SOAR** | **Automatización** | Orquestación y respuesta automática | Automatiza flujos de trabajo para acelerar la respuesta a incidentes. |




Para una mejor comprensión de la jerarquía dentro de un SOC, aquí tienes un mapa mental visual:

```mermaid
graph TD
    A[SOC Manager] --> B(Gestiona el departamento SOC)
    B --> C{Roles Clave}
    C --> D[SOC Engineer]
    D --> E(Configura herramientas como SIEM/EDR)
    C --> F[SOC L2]
    F --> G(Supervisa al L1 e investiga amenazas avanzadas)
    G --> H[SOC L1]
    H --> I(Clasifica y escala amenazas)






Para que el resumen sea aún más didáctico, el gráfico más valioso que puedes añadir es el de la **Tríada de la Seguridad (CIA)** o un **Diagrama del Proceso de Detección y Mitigación**.

Aquí te presento una versión que incluye un **Diagrama de Flujo de Respuesta a Incidentes** y una **Tabla Comparativa**, que ayudan a entender cómo se pasa de una alerta a una solución.

---

### Gráficos recomendados para añadir:

#### 1. Diagrama de Flujo: Ciclo de Vida de una Alerta

Este gráfico ayuda a visualizar cómo se mueve la información dentro del SOC.

```mermaid
graph LR
    A[Evento/Log] --> B{SIEM: Detección}
    B --> C[SOC L1: Triaje/Clasificación]
    C --> D{¿Es una amenaza?}
    D -- No --> E[Falso Positivo - Cerrar]
    D -- Sí --> F[SOC L2: Investigación]
    F --> G[CIRT: Respuesta y Mitigación]
    G --> H[Lecciones Aprendidas]

```

#### 2. Tabla de Comparativa: Defensas Reactivas vs. Proactivas

Las tablas son excelentes para el aprendizaje didáctico.

| Concepto | Tipo de Defensa | Función Principal |
| --- | --- | --- |
| **Antivirus** | Reactiva | Busca firmas de virus conocidos. |
| **EDR** | Proactiva/Analítica | Analiza comportamientos sospechosos en tiempo real. |
| **Honeypot** | Proactiva | Trampa para atraer y estudiar atacantes. |
| **Pentesting** | Proactiva | Simulación de ataque para hallar fallas antes que el hacker. |

---

### 🎨 Sugerencia de diseño visual (Infografía)

He generado una imagen que resume visualmente los conceptos de **Vectores de Ataque vs. Vectores de Defensa** para que la puedas usar como portada o referencia visual en tus apuntes:

`[se quitó una URL no válida]

