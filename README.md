# Guía de Herramientas para Pentesting y Hacking Ético

Este documento reestructura y amplía las categorías de herramientas utilizadas en pentesting y hacking ético, proporcionando una explicación clara de la función de cada herramienta y su ubicación adecuada según su propósito.

---

## 1. Herramientas de Escaneo y Reconocimiento
Estas herramientas se utilizan para recopilar información sobre objetivos potenciales, realizar reconocimiento pasivo o activo, y analizar redes y sistemas.

- **Nmap**: Herramienta versátil para escaneo de puertos, detección de servicios, sistemas operativos y vulnerabilidades en redes.
- **OSINT**: Conjunto de técnicas y herramientas para reconocimiento pasivo mediante fuentes públicas.
- **WHOIS**: Consulta registros de dominios para identificar propietarios y configuraciones.
- **Discover**: Script que agrupa varias herramientas de reconocimiento, incluyendo escaneo de redes, dominios y usuarios.
- **BuiltWith**: Servicio que identifica tecnologías empleadas en sitios web.
- **Wayback Machine**: Archivo digital que permite visualizar versiones anteriores de sitios web.
- **Shodan.io**: Motor de búsqueda para dispositivos conectados a Internet (IoT) y sus configuraciones.
- **Userrecon**: Herramienta para la búsqueda de nombres de usuario en plataformas online y redes sociales.

---

## 2. Herramientas de Análisis de Tráfico de Red
Estas herramientas ayudan a capturar y analizar paquetes de datos para identificar problemas de seguridad en las redes.

- **Wireshark**: Analizador de paquetes para inspeccionar tráfico en tiempo real o capturado.
- **Ettercap**: Plataforma para ataques de tipo Man-in-the-Middle (MITM) y captura de tráfico.

---

## 3. Herramientas de Explotación y Pruebas de Penetración
Se utilizan para simular ataques y evaluar la seguridad de sistemas y redes.

- **Metasploit**: Framework modular para pruebas de penetración que permite ejecutar exploits, crear payloads y realizar escaneos.
- **BeEF**: Framework para evaluar la seguridad de navegadores web mediante explotación de vulnerabilidades.
- **TheFatRat**: Herramienta para generar backdoors y payloads ofuscados.

---

## 4. Herramientas de Ataques a Contraseñas
Estas herramientas se enfocan en la recuperación, generación o fuerza bruta de contraseñas.

- **John the Ripper**: Cracking de contraseñas utilizando diccionarios o ataques personalizados.
- **Hydra**: Herramienta para ataques de fuerza bruta en servicios como FTP, SSH y HTTP.
- **Cupp**: Generador de diccionarios personalizados basados en patrones comunes.

---

## 5. Herramientas de Ataques de Denegación de Servicio (DoS)
Utilizadas para probar la resistencia de sistemas y servidores ante ataques de DoS o DDoS.

- **Slowloris**: Herramienta para ataques DoS dirigidos a servidores HTTP.
- **Golang-Httpflood**: Herramienta de ataque DoS específica para servidores web.
- **Scapy**: Biblioteca y herramienta para manipular paquetes de red, también utilizada para ataques DoS o DDoS.

---

## 6. Herramientas de Phishing
Estas herramientas permiten simular ataques de phishing para evaluar la concienciación de los usuarios.

- **PyPhisher**: Generación de URLs de phishing para capturar credenciales.
- **Setoolkit**: Framework para ingeniería social que incluye clonación de sitios web y generación de payloads.
- **Ngrok**: Crea URLs accesibles globalmente para exponer servicios locales.
- **SocialPhish**: Permite capturar credenciales y direcciones IP de las víctimas.
- **Zphisher**: Herramienta intuitiva para clonar sitios web y realizar phishing.
- **Lphisher**: Generador de URLs de phishing.
- **Maskphish**: Oculta enlaces de phishing mediante ofuscación.
- **Bitly**: Servicio para acortar URLs.
- **Yphisher**: Recopila información detallada como ubicación y credenciales.

---

## 7. Herramientas de Análisis Forense
Estas herramientas se usan para investigar y analizar datos después de un incidente de seguridad.

- **ExifTool**: Extrae y edita metadatos de archivos multimedia.
- **Autopsy**: Plataforma para análisis forense de discos y archivos.
- **Volatility**: Framework para análisis de memoria RAM.
- **Sleuth Kit**: Conjunto de herramientas para el análisis de sistemas de archivos.
- **FTK Imager**: Herramienta para capturar imágenes forenses de discos duros.
- **X-Ways Forensics**: Software de investigación digital avanzado para casos complejos.

---

## 8. Herramientas de Ciberinteligencia
Estas herramientas ayudan a recopilar información estratégica sobre amenazas y actores maliciosos.

- **Maltego**: Plataforma para análisis y visualización de relaciones entre datos.
- **SpiderFoot**: Herramienta para exploración y análisis de amenazas.
- **Censys**: Motor de búsqueda para dispositivos expuestos en Internet.
- **Recon-ng**: Framework modular para reconocimiento avanzado.
- **ThreatCrowd**: Servicio para identificar relaciones entre dominios, IPs y malware.
- **Hunchly**: Herramienta para documentar y gestionar investigación en fuentes abiertas.

---

## 9. Herramientas para Hacking de Cámaras CCTV
Estas herramientas permiten evaluar la seguridad de sistemas de videovigilancia.

- **HackCCTV**: Herramienta para detectar cámaras de seguridad vulnerables y verificar configuraciones de seguridad.

---

## 10. Plataformas de Threat Management
Recursos en línea para la gestión de amenazas y recopilación de inteligencia.

- [Cybok Knowledge Base](https://www.cybok.org/knowledgebase1_1/)
- [Talos Intelligence SHA Searches](https://talosintelligence.com/sha_searches)
- [CVE Resources](https://www.cve.org/ResourcesSupport/Resources)
- [CVE Details - CVE-2024-20450](https://www.cvedetails.com/cve/CVE-2024-20450/)
- [Cisco Security Publications](https://sec.cloudapps.cisco.com/security/center/publicationListing.x)
- [MITRE ATT&CK](https://attack.mitre.org)
- [Google SecOps](https://security.google/solutions/security-operations/)
- [Google Threat Intelligence](https://security.google/solutions/threat-intelligence/)

---

## 11. Herramientas y Estándares Misceláneos
Incluye herramientas para tareas específicas que no encajan en las categorías anteriores.

- **LoRa**: Estándar de comunicación de baja potencia para IoT.
- **Snyk**: Automatización de pruebas de seguridad en códigos fuente.
- **Leafpad**: Editor de texto ligero para sistemas Linux.
- **Evil Limiter**: Bloquea o limita el acceso de dispositivos en una red.
- **Macchanger**: Cambia direcciones MAC para pruebas de seguridad.
- **Anonsurf**: Capa de anonimato para navegar en redes mediante Tor.

---

## 12. Comandos Esenciales para Pentesting

- **go build "nombre del archivo"**: Crea un ejecutable desde un archivo fuente en Go.
- **go build -ldflags -H=windowsgui "nombre del archivo"**: Genera un ejecutable sin ventana visible (usado para payloads ocultos).

---
# Comandos básicos de Linux

## Archivos y Navegación
- `ls`: Lista los archivos/carpetas en el directorio actual.
- `ls -l`: Lista los archivos con formato detallado.
- `ls -la`: Lista los archivos, incluyendo archivos ocultos.
- `cd dir`: Cambia al directorio especificado.
- `cd ..`: Cambia al directorio padre.
- `cd /dir`: Cambia al directorio raíz.
- `cd ~`: Cambia al directorio personal.
- `pwd`: Muestra el directorio actual.
- `mkdir dir`: Crea un nuevo directorio.
- `rm file`: Elimina un archivo.
- `rm -rf dir`: Elimina un directorio y su contenido.
- `cp file1 file2`: Copia el contenido de un archivo a otro.
- `mv file1 file2`: Renombra o mueve un archivo.
- `touch file`: Crea o actualiza un archivo.
- `cat file`: Muestra el contenido de un archivo.

## Información del Sistema
- `date`: Muestra la fecha y hora actual.
- `uptime`: Muestra el tiempo que el sistema lleva encendido.
- `whoami`: Muestra el usuario con el que se ha iniciado sesión.
- `w`: Muestra los usuarios conectados.
- `cat /proc/cpuinfo`: Muestra información del CPU.
- `cat /proc/meminfo`: Muestra información de memoria.
- `free`: Muestra el uso de memoria y swap.
- `df`: Muestra el uso del disco.
- `uname -a`: Muestra la configuración del kernel.

## Redes
- `ping host`: Envía paquetes ICMP para verificar conectividad.
- `whois domain`: Obtiene información del dominio.
- `dig domain`: Recupera información de DNS.
- `curl url`: Recupera el contenido de una URL.
- `wget file`: Descarga un archivo.
- `ssh user@host`: Conexión SSH al host remoto.
- `scp file user@host:/path`: Copia archivos de manera segura.
- `netstat -tuln`: Lista las conexiones de red activas.
- `nmap ip`: Escanea puertos y servicios.

## Procesos
- `ps`: Lista los procesos activos.
- `ps aux`: Lista detallada de procesos.
- `kill pid`: Termina un proceso específico.
- `top`: Muestra los procesos en ejecución en tiempo real.

## Permisos
- `chmod octal file`: Cambia los permisos de un archivo.
  - `4`: Leer (r).
  - `2`: Escribir (w).
  - `1`: Ejecutar (x).
- `chown user:group file`: Cambia el propietario y el grupo de un archivo.

## Comandos de Compresión
- `tar -cf archivo.tar archivo/`: Crea un archivo tar.
- `tar -xf archivo.tar`: Extrae un archivo tar.
- `gzip archivo`: Comprime un archivo.
- `gunzip archivo.gz`: Descomprime un archivo gzip.

## Otros
- `grep pattern file`: Busca un patrón dentro de un archivo.
- `find /path -name nombre`: Busca archivos por nombre.
- `man comando`: Muestra el manual de un comando.

