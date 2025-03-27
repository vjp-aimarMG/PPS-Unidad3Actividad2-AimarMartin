# PPS-Unidad3Actividad2-AimarMartin

# Obtención de información pública con WHOIS, DomainTools y DNSrecon

## WHOIS:
Es un protocolo que permite consultar bases de datos para obtener información sobre la propiedad de un nombre de dominio o una dirección IP. Los datos obtenidos suelen incluir el nombre del registrante, información de contacto, fechas de registro y expiración, y servidores de nombres asociados.

## DomainTools:
Ofrece servicios avanzados de consulta WHOIS, proporcionando detalles sobre la propiedad de dominios, historial de direcciones IP, ranking, tráfico y más. Es útil para investigaciones de seguridad y análisis de dominios.

## DNSrecon:
Es una herramienta utilizada para la enumeración de registros DNS, identificando servidores de nombres y direcciones IP asociadas. Facilita la recopilación de información sobre la infraestructura de red de un objetivo.

---

# Uso de Nmap y Nikto para identificar equipos, puertos abiertos, servicios y vulnerabilidades

## Nmap:
Es un escáner de red que permite descubrir hosts y servicios en una red informática, creando un "mapa" de la misma. Se utiliza para identificar equipos activos, puertos abiertos y servicios en ejecución. Además, Nmap cuenta con scripts (NSE) que permiten detectar vulnerabilidades específicas en los sistemas analizados.

## Nikto:
Es un escáner de servidores web de código abierto que realiza pruebas para detectar múltiples elementos, incluyendo archivos y programas peligrosos, versiones desactualizadas del software del servidor web y errores de configuración. Es capaz de escanear más de 6,700 vulnerabilidades conocidas y verificar versiones de más de 1,250 servidores web.

---

# Utilización de Wfuzz y Dirb para localizar recursos web en servidores

## Wfuzz:
Es una herramienta diseñada para realizar pruebas de fuerza bruta en aplicaciones web, permitiendo descubrir recursos ocultos como directorios, archivos y parámetros. Es altamente configurable y soporta múltiples métodos de inyección.

## Dirb:
Es un escáner de contenido web que utiliza listas de palabras para buscar directorios y archivos en servidores web. Su objetivo es descubrir recursos ocultos que no están enlazados en las páginas visibles.

---

# Scripts de Nmap para la búsqueda de vulnerabilidades

Nmap incluye un conjunto de scripts conocidos como NSE (Nmap Scripting Engine) que permiten automatizar tareas como la detección de vulnerabilidades. Algunos scripts útiles para este propósito son:

- **vulners**: Busca vulnerabilidades conocidas en los servicios detectados comparando las versiones con una base de datos de exploits.
- **http-vuln-cve2017-5638**: Detecta si un servidor es vulnerable a la vulnerabilidad CVE-2017-5638 en Apache Struts.
- **ssl-heartbleed**: Comprueba si un servidor es vulnerable a la vulnerabilidad Heartbleed en OpenSSL.

# Búsqueda de información sobre explotación de vulnerabilidades con SearchSploit

- **SearchSploit**: Es una herramienta que permite buscar y acceder a exploits disponibles en la base de datos de Exploit-DB desde la línea de comandos. Facilita la localización de código de explotación para diversas vulnerabilidades.

# Instala en tu navegador la extensión de Shodan y muestra la información que tenemos tanto de ip, como de dominio del sitio http://iesvalledeljerteplasencia.es

![](/img/1.png)

# Sobre la red del laboratorio PPS con kali, bWAPP, Multidillae y DVWA:< 

- Ayudándote del fichero docker-compose localiza las diferentes máquinas y puertos que deberían de tener abiertos.

![](/img/2.png)

![](/img/3.png)

![](/img/4.png)

- Identifica los equipos de la Red con Nmap.

![](/img/5.png)

- Realiza análisis de puertos en las MV.

![](/img/6.png)

- Encuentra los Servicios y Sistemas Operativos de las MV.

![](/img/7.png)

![](/img/8.png)

![](/img/9.png)

- Inspecciona los puertos con nikto.

![](/img/10.png)

![](/img/11.png)

- Busca las vulnerabilidades de las MV con los scripts de Nmap.

![](/img/12.png)

- Localiza los servicios web que tienen las diferentes máquinas (Wfuzz y Dirb).

![](/img/13.png)

![](/img/14.png)

- Utiliza el comando searchsploit para buscar información de explotación de vulnerabilidades presentes en linux con kernel 5

![](/img/15.png)