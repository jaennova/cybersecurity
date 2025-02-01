# **Roadmap de Ciberseguridad**  
### **Dividido en "Sprints" de 1-2 semanas c/u**

---

### **📌 Etapa 1: Fundamentos (4-8 semanas)**  
**Objetivo**: Construir una base sólida en redes, sistemas operativos y herramientas básicas.

#### **Sprint 1: Redes y Protocolos (2 semanas)**  
- **Temas**:  
  - Modelo OSI/TCP/IP, IPv4 vs IPv6.  
  - Protocolos HTTP, DNS, TCP/UDP.  
  - Subnetting básico (calculadoras como [IP Subnet Calculator](https://www.calculator.net/ip-subnet-calculator.html)).  

- **Recursos Visuales**:  
  - **Infografía Interactiva**: Usa herramientas como [Lucidchart](https://www.lucidchart.com/) para crear un diagrama interactivo del modelo OSI/TCP/IP.  
  - **Video Tutorial**: [CrashCourse Computer Science - Networking](https://www.youtube.com/watch?v=7_LPdttKXPc).  

- **Práctica**:  
  - TryHackMe Room: [**Network Fundamentals**](https://tryhackme.com/room/networkfundamentals).  
  - Ejercicio: Analizar tráfico con Wireshark en una red local.  
  - **Simulador Visual**: Usa [Packet Tracer](https://www.netacad.com/courses/packet-tracer) para simular configuraciones de red.  

- **Checklist**:  
  - [ ] Entender cómo funciona una solicitud HTTP.  
  - [ ] Calcular una subred /24.  

- **Micro-Desafío**:  
  - Configura una red virtual en Packet Tracer y realiza un ping entre dos dispositivos.  

---

#### **Sprint 2: Sistemas Operativos (2 semanas)**  
- **Temas**:  
  - Linux: Comandos básicos (`cd`, `ls`, `grep`, `chmod`).  
  - Windows: Gestión de usuarios y permisos.  

- **Recursos Visuales**:  
  - **Diagrama de Flujo**: Crea un diagrama de flujo interactivo para los comandos más usados en Linux.  
  - **Video Tutorial**: [The Linux Command Line Full Course](https://www.youtube.com/watch?v=ZtqBQ68cfJc).  

- **Práctica**:  
  - OverTheWire **Bandit** (niveles 1-15).  
  - TryHackMe Room: [**Linux Basics**](https://tryhackme.com/room/linuxbasics).  

- **Checklist**:  
  - [ ] Crear un usuario en Linux y asignarle permisos.  
  - [ ] Resolver 5 niveles de Bandit.  

- **Micro-Desafío**:  
  - Automatiza una tarea simple usando un script Bash (ej: listar archivos y guardarlos en un archivo).  

---

#### **Sprint 3: Herramientas Básicas (2 semanas)**  
- **Temas**:  
  - Nmap (escaneo de puertos: `-sS`, `-sV`).  
  - Wireshark (filtros básicos: `http`, `tcp.port==80`).  

- **Recursos Visuales**:  
  - **Tutorial Interactivo**: Usa [Nmap GUI](https://github.com/daniel-cues/NMapGUI) para aprender a usar Nmap de forma visual.  
  - **Filtros Wireshark**: Crea una guía visual de los filtros más comunes en Wireshark.  

- **Práctica**:  
  - TryHackMe Room: [**Nmap Live Host Discovery**](https://tryhackme.com/room/nmap01).  
  - Escanear tu red local con Nmap.  

- **Checklist**:  
  - [ ] Identificar servicios abiertos en una IP con Nmap.  
  - [ ] Capturar tráfico HTTP con Wireshark.  

- **Micro-Desafío**:  
  - Realiza un escaneo completo de tu red local y documenta los resultados en un informe visual.  

---

#### **Sprint 4: Introducción a la Seguridad Web (2 semanas)**  
- **Temas**:  
  - OWASP Top 10: Conceptos de SQLi y XSS.  
  - BurpSuite: Interceptar solicitudes HTTP.  

- **Recursos Visuales**:  
  - **Infografía OWASP Top 10**: Crea una infografía interactiva con ejemplos visuales de cada vulnerabilidad.  
  - **BurpSuite Tutorial Visual**: Usa [PortSwigger Academy](https://portswigger.net/web-security) para seguir tutoriales interactivos.  

- **Práctica**:  
  - PortSwigger Lab: [**SQL Injection**](https://portswigger.net/web-security/sql-injection).  
  - TryHackMe Room: [**OWASP Top 10**](https://tryhackme.com/room/owasptop10).  

- **Checklist**:  
  - [ ] Explotar un laboratorio básico de SQLi.  
  - [ ] Modificar una cookie con BurpSuite.  

- **Micro-Desafío**:  
  - Crea un informe visual de una vulnerabilidad web que hayas explotado, explicando el proceso paso a paso.  

---

### **📌 Etapa 2: Intermedio (3-6 meses)**  
**Objetivo**: Profundizar en técnicas de reconocimiento, explotación y seguridad web avanzada.

#### **Sprint 5: Reconocimiento y Enumeración (3 semanas)**  
- **Temas**:  
  - Enumeración de subdominios (Sublist3r, Amass).  
  - Fuzzing con Gobuster/Dirbuster.  

- **Recursos Visuales**:  
  - **Mapa de Subdominios**: Usa herramientas como [Amass](https://github.com/OWASP/Amass) para generar un mapa visual de subdominios.  
  - **Fuzzing Visual**: Crea un dashboard en tiempo real con FFUF para ver los resultados del fuzzing.  

- **Práctica**:  
  - HackTheBox **Starting Point** (máquinas *Meow* y *Fawn*).  
  - TryHackMe Room: [**Web Scanning**](https://tryhackme.com/room/webbasics).  

- **Checklist**:  
  - [ ] Encontrar 3 subdominios ocultos de un sitio web.  
  - [ ] Enumerar rutas en un servidor web con Gobuster.  

- **Micro-Desafío**:  
  - Documenta visualmente el proceso de enumeración de un sitio web, mostrando los resultados en un gráfico.  

---

#### **Sprint 6: Explotación Básica (4 semanas)**  
- **Temas**:  
  - Reverse Shells (Netcat, Msfvenom).  
  - Escalada de privilegios: Binarios SUID, sudoers.  

- **Recursos Visuales**:  
  - **Diagrama de Reverse Shell**: Crea un diagrama interactivo que muestre cómo funciona una reverse shell.  
  - **Escalada de Privilegios**: Usa herramientas como [LinPEAS](https://github.com/carlospolop/PEASS-ng) para visualizar posibles vectores de escalada.  

- **Práctica**:  
  - TryHackMe Room: [**Basic Pentesting**](https://tryhackme.com/room/basicpentestingjt).  
  - Máquina HTB *Lame* o TryHackMe *Vulnversity*.  

- **Checklist**:  
  - [ ] Obtener una Reverse Shell en una máquina práctica.  
  - [ ] Escalar privilegios usando un binario SUID.  

- **Micro-Desafío**:  
  - Crea un video corto explicando cómo obtuviste una reverse shell y escalaste privilegios.  

---

### **✨ Consejos Anti-Agotamiento**  
1. **Gamificación**:  
   - Usa plataformas como [Habitica](https://habitica.com/) para gamificar tu progreso. Completa tareas y gana recompensas.  

2. **Plantilla Visual**:  
   - Usa [Trello](https://trello.com/) o [Notion](https://www.notion.so/) para crear un tablero visual con checklist, fechas límite y logros.  

3. **Recompensas**:  
   - Después de completar un sprint, date un premio (ej: un juego, una película).  

---

### **📂 Plantilla de Seguimiento**  
Descarga esta [**plantilla en Notion**](https://www.notion.so/) para organizar tu progreso:  
- Checklist por sprint.  
- Fechas límite flexibles.  
- Sección de "Logros" para motivación.  

