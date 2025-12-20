PLATAFORMAS DE GESTION 

| Herramienta | Tipo | Función Principal |
| :--- | :--- | :--- |
| **SIEM** | **Splunk** | Gestión de alertas para equipos SOC. |
| **EDR**/**NDR** | **MS Defender**/**CrowdStrike** | Estos tienes sus propios dashboard de alertas. |
| **SOAR** | **Splunk Soar**/**Cortex Soar** | Esto puede agregar y automatizar el SOC. |
| **ITSM** | **Jira**/**TheHive** | Sistemas de ticket. |


Propiedades de un alerta

| :--- | :--- |
| Tiempo de alerta | Muestra el tiempo exacto que se creo la alerta |
| Nombre de alerta | Proporcion aun resumen basado a la alerta |
| Gravedad de alerta | Define la urgencia de la alerta | 
| Estado de alerta | Informa si alguien ya trabja con esta alerta | 
| Variedad de alerta | Clasifica la alerta | 
| Asignatorio de alerta | Analisis adignado en las alertas |
| Decripcion de alerta | Explica de que trata la alerta |
| Campos de alerta | Proporciona comentarios y valores del analisis | 


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
