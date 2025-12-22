PLATAFORMAS DE GESTION 

| Herramienta | Tipo | Función Principal |
| :--- | :--- | :--- |
| **SIEM** | **Splunk** | Gestión de alertas para equipos SOC. |
| **EDR**/**NDR** | **MS Defender**/**CrowdStrike** | Estos tienes sus propios dashboard de alertas. |
| **SOAR** | **Splunk Soar**/**Cortex Soar** | Esto puede agregar y automatizar el SOC. |
| **ITSM** | **Jira**/**TheHive** | Sistemas de ticket. |


Propiedades de un alerta

| Tiempo de alerta | Muestra el tiempo exacto que se creo la alerta |
| :--- | :--- |
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
    A[Prioriza y elige una alerta] --> B[Asignamos 1 alerta a nosotros]
    B --> C[Mover la alerta en 'Progreso']
    C --> D[Leer la alerta, nombre y descripcion]
    D --> E[Anotado IP, Host, Usuario]
    E --> F{Esta configurado en el libro de alertas?}
    F --> G[Seguimos paso del libro]
    F --> H[Investigamos la alerta en SEIM]
    H --> I[Tomamos una descioción]
    I --> J { Se escala? }
    J --> K [Se escala a L2]
    J --> L [Agrega un comentario]
    L --> M [Movemos a cerrado]


Informes de Alertas
Nos piden mayor detalle de la amenza si es que es sera escalado.

Eslacada de Alertas
Si quieres una alerta de mayor investigacion el informa de laerta ayuda para que de contexto inicial

Comunicacion
Aveces se requiere hablar con otros areas 

Guia de informes de Alertas
Escribir nuenos informes nos ayuda a:
 - dar contexto a l2 de la alerta
 - Las alertas se quedan y en buen tener contexto 
 - Mejora las habilidades de L1

se puede utilizar la tecnica Five Ws (5W) tipo de informe de alertas

Quien?  Quien es la persona que ejecuto o descargo
Que?  Secuencias del evento (que paso?)
Cuando?  cuando comenzo y culmino
Donde?  IP, host, appsec, se involucro
Por que?  Razonamiento final de L1

Informes de alertas SOC L1

