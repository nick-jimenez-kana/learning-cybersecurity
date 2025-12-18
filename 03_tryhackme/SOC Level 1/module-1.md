# Introducción al Blue Team: Analista de Seguridad Junior

Este repositorio reúne los conceptos esenciales para comprender cómo opera un **Security Operations Center (SOC)** y cuál es el rol del **Blue Team** en la defensa cibernética. El enfoque está pensado para perfiles junior que inician su camino en análisis de seguridad, monitoreo y respuesta a incidentes.

---

## 🛡️ ¿Qué es un SOC?

El **Security Operations Center (SOC)** es el área responsable de **monitorear, detectar, analizar, responder y contener** incidentes de seguridad dentro de una organización. Funciona como el sistema nervioso de la defensa digital: recibe señales (eventos), las interpreta (alertas) y coordina acciones.

El objetivo del SOC es proteger la **tríada CIA**:

* **Confidencialidad:** Evitar accesos no autorizados a la información.
* **Integridad:** Garantizar que los datos no sean alterados sin autorización.
* **Disponibilidad:** Asegurar que los sistemas y servicios estén operativos cuando se requieren.

---

## 🏛️ Jerarquía y Roles en Ciberseguridad

La ciberseguridad se organiza en distintos niveles, desde la estrategia del negocio hasta la operación técnica diaria.

### Nivel Ejecutivo y Estratégico

* **CEO / CFO / Owner:** Responsables del negocio y del impacto financiero del riesgo.
* **CISO (Chief Information Security Officer):** Define la estrategia de seguridad y gestiona el riesgo cibernético.
* **CTO / CIO:** Lideran la arquitectura tecnológica y la operación de TI.
* **SOC Manager / Security Manager:** Dirige el SOC, define procesos y coordina al equipo.

### Nivel Operativo y Técnico

* **SOC Analyst (L1 / L2 / L3):** Analistas encargados del monitoreo, análisis e investigación de alertas.
* **SOC Engineer:** Diseña, configura y mantiene las herramientas de seguridad (SIEM, EDR, SOAR).
* **GRC Specialist:** Gestiona Gobierno, Riesgo y Cumplimiento normativo.
* **Pentester / Red Team:** Simula ataques para identificar vulnerabilidades antes que un adversario real.

---

## 📊 Estructura Interna de un SOC

Un SOC suele organizarse por niveles de madurez y especialización:

1. **SOC Manager:** Responsable de la gestión del equipo, métricas, procesos y mejora continua.
2. **SOC Engineer:** Administra y optimiza las plataformas de seguridad como **SIEM**, **EDR** y herramientas de automatización.
3. **SOC L2 (Analista Intermedio/Avanzado):** Realiza investigaciones profundas, correlación de eventos y análisis de incidentes complejos.
4. **SOC L1 (Analista Junior):** Primer punto de contacto. Clasifica alertas, valida falsos positivos y escala incidentes reales.

### Equipos de Apoyo y Respuesta

* **CIRT / CERT / CSIRT:** Equipos especializados en respuesta a incidentes graves.
* **Analista Forense:** Analiza evidencias digitales y reconstruye el ataque.
* **Threat Intelligence Analyst:** Estudia amenazas emergentes, campañas y actores maliciosos.
* **AppSec Analyst:** Se enfoca en la seguridad de aplicaciones y código.

> **Nota:** Algunas organizaciones cuentan con un SOC interno, mientras que otras delegan estas funciones a un **MSSP (Managed Security Service Provider)**.

---

## 🚀 Vectores de Ataque

### El factor humano

El usuario suele ser el punto de entrada más común para un atacante, ya sea por desconocimiento, confianza excesiva o manipulación.

### Técnicas de Ataque Frecuentes

* **Ingeniería Social:** Manipulación psicológica para obtener credenciales o acceso.
* **Phishing:** Correos o mensajes fraudulentos que buscan engañar al usuario.
* **SEO Poisoning:** Posicionamiento de sitios maliciosos en buscadores.
* **Deepfake:** Uso de IA para falsificar voz o video y cometer fraudes.
* **Supply Chain Attack:** Compromiso de software, librerías o proveedores legítimos.

---

## 🛡️ Vectores de Defensa

La defensa moderna se apoya en dos principios clave: **prevenir** y **detectar** de forma temprana.

### Herramientas y Controles

* **Anti-Phishing:** Filtrado de correos maliciosos antes de llegar al usuario.
* **Antivirus Tradicional:** Detección basada en firmas de malware conocido.
* **EDR (Endpoint Detection and Response):** Monitorea el comportamiento de endpoints en tiempo real, detecta amenazas desconocidas y permite contención remota.
* **SIEM:** Centraliza logs, correlaciona eventos y genera alertas.
* **Zero Trust:** Modelo que no confía por defecto en ningún usuario o dispositivo.
* **Concientización en Seguridad:** Capacitaciones y simulacros de phishing para reducir el riesgo humano.

---

## 🔍 Vulnerabilidades y Exposiciones

* **Zero-Day:** Vulnerabilidad explotada antes de existir un parche.
* **CVE (Common Vulnerabilities and Exposures):** Identificador estándar de una vulnerabilidad conocida.
* **Patch (Parche):** Actualización que corrige una vulnerabilidad.

Comprender estos conceptos es fundamental para el trabajo diario de un analista SOC y para construir una defensa cibernética efectiva.
