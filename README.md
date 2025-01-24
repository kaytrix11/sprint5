# sprint5
sprint 5



Sprint 5: Escaneo de Vulnerabilidades
En este sprint, me enfoqué en identificar y analizar vulnerabilidades utilizando herramientas especializadas como Nmap, Nessus y OpenVAS. El objetivo principal fue evaluar la seguridad de dos máquinas virtuales objetivo:

Ubuntu Cliente (IP: 192.168.1.23).
Metasploit (IP: 192.168.1.24).
Actividades realizadas:

Preparación del entorno:

Configuración de las máquinas virtuales involucradas:
Kali Linux (192.168.1.25): máquina desde donde se ejecutaron los escaneos.
Ubuntu Cliente y Metasploit como objetivos de las pruebas.
Verificación de conectividad en red para asegurar la ejecución de los análisis.
Escaneo inicial con Nmap:

Identificación de puertos abiertos y servicios activos en las máquinas objetivo.
Análisis de versiones de servicios para identificar posibles vulnerabilidades.
Escaneos específicos como:
Escaneo de puertos TCP y UDP.
Detección de sistemas operativos.
Evaluación detallada con Nessus:

Generación de informes detallados sobre vulnerabilidades críticas, medias y bajas.
Revisión de recomendaciones proporcionadas por Nessus para mitigar los riesgos.
Análisis avanzado con OpenVAS:

Escaneos para detectar configuraciones inseguras y vulnerabilidades explotables.
Verificación de políticas de seguridad y simulación de posibles vectores de ataque.
Resultados obtenidos:

Ubuntu Cliente:

Puertos abiertos: 22 (SSH) y 80 (HTTP).
Vulnerabilidades detectadas: configuraciones débiles en SSH y un servidor web sin HTTPS.
Metasploit:

Puertos abiertos: múltiples, incluidos 21 (FTP), 22 (SSH), y 445 (SMB).
Vulnerabilidades críticas, como acceso no autenticado en FTP y errores conocidos en SMB.
