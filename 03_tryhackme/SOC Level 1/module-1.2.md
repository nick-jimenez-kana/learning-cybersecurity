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

