# 🧠 SOC 101 OPERACIONES DE SEGURIDAD
## Fundamentos de Redes y Seguridad Informática  

---
### 📚 Estructura de Conocimiento

Redes <br>
 └─ Sistemas Operativos <br>
     └─ Programación <br>
          └─ Ciberseguridad <br>


> Es una escala de conocimiento para llegar al objetivo final: **la Ciberseguridad.**

---



## SOC — Security Operations Center (Centro de Operaciones de Seguridad)**

El **SOC** es el núcleo encargado de **monitorear, detectar, responder y prevenir incidentes de seguridad.**  
Su objetivo principal es **proteger los activos digitales**, garantizar su integridad y **coordinar las acciones ante amenazas cibernéticas.**

---

## 🌐 REDES 

### Fundamentos de Redes de Computadoras

Una **red de computadoras** tiene como propósito permitir una **comunicación rápida y confiable** mediante diversas tecnologías (cableado, Wi-Fi, routers, switches, etc.), con el fin de **compartir información y recursos.**

---

### Redes Domésticas e IoT (Internet de las Cosas)

Los dispositivos **IoT (Internet of Things)** son aparatos inteligentes conectados en red, muy comunes en entornos domésticos.  
> Ejemplo: cámaras inteligentes, asistentes de voz, focos o enchufes inteligentes.

---

### Conectividad Global

Hoy en día, las organizaciones **necesitan conectividad global.**  
Para ello, utilizan las **VPNs (Virtual Private Networks)**, que permiten **conexiones remotas seguras** garantizando la **continuidad operativa.**

---

### Escalabilidad de la Arquitectura Cliente-Servidor

La arquitectura **cliente-servidor** está diseñada para manejar grandes cantidades de procesos.  
Los **servidores** pueden recibir, procesar y responder solicitudes, ofreciendo **flexibilidad y eficiencia** en las operaciones.

---

### Modelo TCP/IP

El **modelo TCP/IP** estructura el funcionamiento de Internet en **4 capas**, donde cada una utiliza distintos protocolos.

#### 1️⃣ Capa de Aplicación
Permite la comunicación entre la aplicación y la red.  
**Protocolos comunes:**
- **HTTP / HTTPS** → Navegación segura  
- **FTP** → Transferencia de archivos  
- **DNS** → Resolución de nombres de dominio  
- **SMTP** → Envío de correos electrónicos  

#### 2️⃣ Capa de Transporte
Garantiza la **comunicación de extremo a extremo** entre emisor y receptor.  
**Protocolos:**
- **TCP (Transmission Control Protocol)** → Asegura que los datos lleguen completos y en orden.  
- **UDP (User Datagram Protocol)** → Más rápido, pero sin control de errores.  
- **RTP (Real-time Transport Protocol)** → Optimiza audio y video en tiempo real.  

#### 3️⃣ Capa de Internet
Se encarga de **direccionar y enrutar los paquetes** hasta su destino.  
**Protocolos:**
- **IP (IPv4 / IPv6)** → Define direcciones únicas para cada dispositivo.  
- **ARP (Address Resolution Protocol)** → Traduce IP a dirección MAC.  
- **ICMP** → Diagnóstico y mensajes de error (ej. comando `ping`).  
- **RARP** → Traducción inversa (de MAC a IP).  

#### 4️⃣ Capa de Interfaz de Red
Gestiona la **comunicación física** entre dispositivos dentro de una red.  
Incluye:
- Encapsulado de datos  
- Direccionamiento físico  
- Detección básica de errores  

---

### Modelo OSI

**OSI (Open Systems Interconnection)** es un marco desarrollado por la **ISO** para **estandarizar la comunicación en redes.**  
A diferencia del modelo TCP/IP (4 capas), el OSI se compone de **7 capas**, lo que permite una mejor comprensión y segmentación del funcionamiento de las redes.

---

### Tipos de Redes

| Tipo | Nombre | Descripción |
|------|---------|-------------|
| **LAN** | Local Area Network | Red local pequeña (oficinas, hogares). |
| **PAN** | Personal Area Network | Conecta dispositivos personales en un área muy corta (Bluetooth, audífonos, etc.). |
| **WLAN** | Wireless LAN | Similar a una LAN, pero inalámbrica (Wi-Fi). |
| **MAN** | Metropolitan Area Network | Cubre una zona geográfica amplia (ciudad). |
| **WAN** | Wide Area Network | Cubre grandes distancias, incluso países. |

---

### Controles de Seguridad  

Los **controles de seguridad** son medidas y mecanismos diseñados para **proteger la información** y garantizar la **Confidencialidad, Integridad y Disponibilidad (CIA)**.  
Ayudan a **mitigar, detectar y prevenir riesgos y vulnerabilidades.**

### Principales Controles:

- **Firewall:** Controla y monitorea el tráfico de red según reglas predefinidas. (Hardware o software)  
- **WAF (Web Application Firewall):** Protege aplicaciones web filtrando el tráfico HTTP/HTTPS.  
- **IPS (Intrusion Prevention System):** Monitorea y bloquea amenazas en tiempo real.  
- **VPN (Virtual Private Network):** Crea túneles cifrados para conexiones seguras.  
- **NAC (Network Access Control):** Gestiona el acceso a la red según políticas de seguridad.  
- **Segmentación de Red:** Divide la red en segmentos aislados para mejorar la seguridad.  
- **Antivirus y Antimalware:** Detectan y eliminan software malicioso.  
- **Cifrado de Red:** Protege datos en tránsito.  
  - **SSL/TLS:** Navegación web segura.  
  - **IPSec:** Cifrado a nivel de red.  
- **SIEM (Security Information and Event Management):** Centraliza registros y alertas de seguridad.  

---

## 💻 SISTEMAS OPERACTIVOS 

###  Seguridad en Windows

**Windows Security** es el conjunto de herramientas que protege los sistemas operativos de Microsoft.  
**Componentes principales:**

- **Windows Defender Antivirus:** Analiza y elimina amenazas en segundo plano.  
- **Windows Defender SmartScreen:** Protege frente a phishing y descargas maliciosas.  
- **Microsoft Defender for Endpoint:** Solución empresarial para gestión de vulnerabilidades.  
- **Controlled Folder Access:** Bloquea el acceso no autorizado a carpetas críticas (protección contra ransomware).  
- **Microsoft Defender for Office:** Analiza amenazas fuera del sistema operativo.  

---

## ⚖️ Estándares y Leyes de Seguridad

Los estándares y leyes de ciberseguridad establecen **normas claras para proteger la información** y aumentar la **confianza de usuarios, clientes y organizaciones.**

### NIS Directive (Unión Europea)
- Mejora la ciberseguridad en servicios e infraestructuras críticas.  
- Define estructuras de seguridad y protocolos de reporte ante incidentes.  
- Objetivo: fortalecer la respuesta ante amenazas.

### HIPAA (Estados Unidos)
**Health Insurance Portability and Accountability Act**  
Protege la información médica electrónica.  
- **Security Rule:** Define cómo proteger la información de salud digital.  
- **Privacy Rule:** Define quién y cómo puede usar la información médica.

### NIST SP 800-53 (Estados Unidos)
**National Institute of Standards and Technology**  
Guía completa de controles de seguridad y privacidad.  
- Clasifica controles por familias.  
- Define configuraciones base para entornos seguros.

### ISO/IEC 27001 (Internacional)
Estándar para implementar y mantener un **Sistema de Gestión de Seguridad de la Información (ISMS).**  
**Objetivos:**
1. Identificar riesgos de información.  
2. Establecer controles para mitigarlos.  
3. Promover la mejora continua.  
