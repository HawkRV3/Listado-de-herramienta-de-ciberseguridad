# Guía de Herramientas para Ciberseguridad

Este documento reestructura y amplía las categorías de herramientas utilizadas en distintas áreas de la ciberseguridad, proporcionando una explicación clara de la función de cada herramienta y su ubicación adecuada según su propósito.

---

## 1. Herramientas/técnicas de Escaneo y Reconocimiento
Estas herramientas se utilizan para recopilar información sobre objetivos potenciales, realizar reconocimiento pasivo o activo analizando redes y sistemas.

- **Nmap**: Herramienta versátil para escaneo de puertos, detección de servicios, sistemas operativos y vulnerabilidades en redes.
- **OSINT**: Conjunto de técnicas y herramientas para reconocimiento pasivo mediante fuentes públicas.
- **WHOIS**: Consulta registros de dominios para identificar propietarios y configuraciones.
- **Discover**: Script que agrupa varias herramientas de reconocimiento, incluyendo escaneo de redes, dominios y usuarios.
- **BuiltWith**: Servicio que identifica tecnologías empleadas en sitios web.
- **Wayback Machine**: Archivo digital que permite visualizar versiones anteriores de sitios web.
- **Shodan.io**: Motor de búsqueda para dispositivos conectados a Internet (IoT) y sus configuraciones.
- **Userrecon**: Herramienta para la búsqueda de nombres de usuario en plataformas online y redes sociales.
- **dnsenum:** Herramienta de enumeración de DNS para descubrir subdominios y registros relacionados.
- **Subcat**: Herramienta utilizada para la exploración de subdominios.
- **Skytrack**: Plataforma que rastrea dispositivos y direcciones IP.
- **The Spy's Job**: Herramienta orientada al OSINT, diseñada para automatizar y consolidar diversas técnicas de recopilación de información.

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
- **Mimikatz**: Software avanzado para la extracción de credenciales en sistemas Windows.
- **Nikto**: Escáner de vulnerabilidades en servidores web.
- **Setoolkit**: Framework para ingeniería social que incluye clonación de sitios web y generación de payloads.
- **caido**: Plataforma moderna para pruebas de seguridad web.

---

## 4. Herramientas de Ataques a Contraseñas
Estas herramientas se enfocan en la recuperación, generación o fuerza bruta de contraseñas.

- **John the Ripper**: Cracking de contraseñas utilizando diccionarios o ataques personalizados.
- **Hydra**: Herramienta para ataques de fuerza bruta en servicios como FTP, SSH y HTTP.
- **Cupp**: Generador de diccionarios personalizados basados en patrones comunes.
- **Browser-Bruter**: Herramienta diseñada para realizar ataques de fuerza bruta en navegadores web.
- **Bphish**: Plataforma avanzada para la recopilación y craqueo de credenciales.
- **Browser-Bruter**: Herramienta diseñada para llevar a cabo ataques de fuerza bruta dirigidos a interfaces web de autenticación.

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
- **campfish**: Herramienta avanzada para la generación de ataques de phishing personalizados.

---

## 7. Herramientas de Análisis Forense
Estas herramientas se usan para investigar y analizar datos después de un incidente de seguridad.

- **ExifTool**: Extrae y edita metadatos de archivos multimedia.
- **Autopsy**: Plataforma para análisis forense de discos y archivos.
- **Volatility**: Framework para análisis de memoria RAM.
- **Sleuth Kit**: Conjunto de herramientas para el análisis de sistemas de archivos.
- **FTK Imager**: Herramienta para capturar imágenes forenses de discos duros.
- **X-Ways Forensics**: Software de investigación digital avanzado para casos complejos.
- **StegAnalyzer**: Herramienta de detección de información oculta en archivos multimedia.

---

## 8. Herramientas de Ciberinteligencia
Estas herramientas ayudan a recopilar información estratégica sobre amenazas y actores maliciosos.

- **Maltego**: Plataforma para análisis y visualización de relaciones entre datos.
- **SpiderFoot**: Herramienta para exploración y análisis de amenazas.
- **Censys**: Motor de búsqueda para dispositivos expuestos en Internet.
- **Recon-ng**: Framework modular para reconocimiento avanzado.
- **ThreatCrowd**: Servicio para identificar relaciones entre dominios, IPs y malware.
- **Hunchly**: Herramienta para documentar y gestionar investigación en fuentes abiertas.
- **MISP**: Plataforma que permite compartir información sobre ciberamenazas.
- **IP tracker**: Herramienta para rastrear ubicaciones de direcciones IP.
- **Blackman**: Plataforma de inteligencia para análisis de amenazas.

---

## 9. Herramientas y Estándares Misceláneos
Incluye herramientas para tareas específicas que no encajan en las categorías anteriores.

- **LoRa**: Estándar de comunicación de baja potencia para IoT.
- **Snyk**: Automatización de pruebas de seguridad en códigos fuente.
- **Leafpad**: Editor de texto ligero para sistemas Linux.
- **Evil Limiter**: Bloquea o limita el acceso de dispositivos en una red.
- **Macchanger**: Cambia direcciones MAC para pruebas de seguridad.
- **Anonsurf**: Capa de anonimato para navegar en redes mediante Tor.
- **HackCCTV**: Herramienta para detectar cámaras de seguridad vulnerables y verificar configuraciones de seguridad.
- **VSCode**: Editor de código versátil utilizado para el desarrollo de herramientas de seguridad.
- **PyCharm**: IDE especializado en Python, útil para desarrollo de scripts de seguridad.
- **Blackstone**: Herramienta de ciberseguridad para análisis de vulnerabilidades.
- **Virus-Builder**: Generador de malware personalizado.
- **Seeker**: Herramienta enfocada en la geolocalización y pruebas de hacking ético. 

---

## 10. Herramientas Criptográficas
Estas herramientas ayudan para la encriptación y desencriptación de archivos y datos.
- **OpenSSL**: Herramienta poderosa para la creación y gestión de certificados SSL/TLS y encriptación de datos.
- **ccrypt**: Software de cifrado basado en contraseñas para proteger archivos en Linux.

---

