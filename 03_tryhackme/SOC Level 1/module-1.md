# Introducción al Blue Team: Analista de Seguridad Junior

Este repositorio contiene apuntes fundamentales sobre las operaciones de un **Security Operations Center (SOC)** y los conceptos básicos de defensa cibernética.

## 🛡️ ¿Qué es un SOC?
El **Security Operations Center (SOC)** es el centro neurálgico de la seguridad de una organización. Su función principal es **detectar, mitigar, responder e investigar** incidentes de seguridad.

Su objetivo principal es garantizar la tríada **CIA**:
* **Confidencialidad:** Proteger los datos contra el acceso no autorizado.
* **Integridad:** Mantener los datos libres de modificaciones no autorizadas.
* **Disponibilidad:** Asegurar que los sistemas estén accesibles cuando se necesiten.

---

## 🏛️ Jerarquías y Roles en Ciberseguridad

### Niveles Ejecutivos y Estratégicos
* **CEO / CFO / Owner:** Ejecutivos enfocados en el negocio global y la toma de decisiones financieras.
* **CISO / CTO / CIO:** Lideran el programa de TI y la estrategia de seguridad de toda la empresa.
* **SOC Manager / Red Team Lead:** Gestionan departamentos específicos o equipos tácticos.

### Roles Operativos y Técnicos
* **SOC Analyst / SOC Engineer:** Realizan tareas técnicas de análisis de registros (logs) y eventos.
* **GRC Specialist:** Especialistas en Gobierno, Riesgo y Cumplimiento.
* **Pentester:** Realizan pruebas de penetración para encontrar vulnerabilidades.

---

## 📊 Estructura Interna del SOC



1.  **SOC Manager:** Gestiona el departamento y la estrategia del equipo.
2.  **SOC Engineer:** Responsable de configurar y mantener las herramientas críticas como el **SIEM** (Gestión de Eventos e Información de Seguridad) y el **EDR**.
3.  **SOC L2 (Analista Avanzado):** Supervisa al L1 y realiza investigaciones profundas de amenazas complejas.
4.  **SOC L1 (Analista Junior):** Miembros de primera línea que clasifican, filtran y escalan las alertas detectadas.

### Otros Equipos de Respuesta
* **CIRT / CERT / CSIRT:** Equipos especializados en la respuesta ante incidentes críticos.
* **Analista Forense:** Investiga las causas y rastros tras un ataque.
* **Threat Intelligence Analyst:** Investiga amenazas emergentes y actores de amenazas.
* **AppSec Analyst:** Se enfoca en la seguridad de las aplicaciones.

> **Nota:** Existen empresas con su propio SOC interno, mientras que otras contratan un **MSSP** (Managed Security Service Provider) para externalizar estos servicios.

---

## 🚀 Vectores de Ataque

### El factor humano
Se considera el "eslabón más débil" de la cadena de seguridad.

### Técnicas Comunes
* **Ingeniería Social:** Manipulación psicológica para engañar a las personas y obtener credenciales o acceso.
* **Envenenamiento de SEO (SEO Poisoning):** Técnicas para posicionar sitios web maliciosos en los primeros resultados de búsqueda.
* **Deepfake:** Uso de IA para generar audio o video falso con el fin de realizar estafas o suplantación de identidad.
* **Ataque de Cadena de Suministro (Supply Chain Attack):** Infección a través de actualizaciones de software o bibliotecas de terceros comprometidas.

---

## 🛡️ Vectores de Defensa

La defensa se basa en dos pilares: **Mitigar** (prevenir y reducir el impacto) y **Detectar** (identificar e investigar).

### Herramientas y Estrategias
* **Anti-Phishing:** Filtros que bloquean correos maliciosos antes de que lleguen al usuario.
* **Antivirus Tradicional:** Basado en firmas para detectar malware conocido.
* **EDR (Endpoint Detection and Response):** Herramienta avanzada que monitorea los dispositivos finales (laptops, servidores) en tiempo real. A diferencia del antivirus, utiliza análisis de comportamiento para detectar amenazas desconocidas y permite responder remotamente al ataque.
* **Principio de "Zero Trust" y Concientización:** Capacitaciones constantes y simulacros de phishing para educar al personal.

---

## 🔍 Vulnerabilidades y Exposiciones

* **Zero Day (Día Zero):** Una vulnerabilidad que es descubierta por atacantes antes de que el fabricante tenga conocimiento de ella o haya creado un parche.
* **CVE (Common Vulnerabilities and Exposures):** Es el identificador público y estándar asignado a una vulnerabilidad conocida.
* **Patch (Parche):** La actualización de software que soluciona o "cura" una vulnerabilidad detectada.
