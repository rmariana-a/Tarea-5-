# INVESSTIGACIÓN SOBRE SISTEMAS OPERATIVOS 


## 1. Debian

### Historia  
Debian fue fundado en **agosto de 1993** por **Ian Murdock** como un proyecto abierto que uniera software libre y una comunidad colaborativa. :contentReference[oaicite:0]{index=0}  
La primera versión pública fue la **0.01** (1993). :contentReference[oaicite:1]{index=1}  
Desde entonces, Debian ha crecido como una de las distribuciones más robustas y estables. :contentReference[oaicite:2]{index=2}  

Debian mantiene tres ramas activas: **stable**, **testing** y **unstable (Sid)**. :contentReference[oaicite:3]{index=3}  
La versión estable actual (agosto de 2025) es la **Debian 13 “Trixie”**. :contentReference[oaicite:4]{index=4}  

### ¿Qué es?  
Debian es una distribución de **GNU/Linux libre**, mantenida por una comunidad internacional de desarrolladores voluntarios, bajo valores de software libre y apertura. :contentReference[oaicite:5]{index=5}  
Es una distribución **universal** (soporte para múltiples arquitecturas de hardware) y sirve como base para muchas otras distribuciones populares. :contentReference[oaicite:6]{index=6}  

### Características principales  
- Alta **estabilidad y fiabilidad**, especialmente para entornos de producción.  
- Repositorios amplios con decenas de miles de paquetes disponibles. :contentReference[oaicite:7]{index=7}  
- Usa el gestor de paquetes **APT / dpkg** para instalación, actualización y manejo de dependencias.  
- Soporte a múltiples arquitecturas (x86, ARM, etc.). :contentReference[oaicite:8]{index=8}  
- Modelo de versiones conservador: los paquetes son probados extensamente antes de entrar a la rama *stable*.  
- Filosofía fuerte de software libre e inclusión de repositorios *main*, *contrib* y *non-free* (para firmware privativo). :contentReference[oaicite:9]{index=9}  

### Usos y aplicaciones  
- Servidores web, de correo, bases de datos y otros servicios esenciales.  
- Estaciones de trabajo en entornos académicos o científicos.  
- Base para distribuciones derivadas (por ejemplo Debian Edu, Raspberry Pi OS, Linux Mint, Kali).  
- En organizaciones que buscan una distribución estable y de largo soporte.

---

## 2. Arch Linux

### Historia  
El proyecto Arch comenzó a gestarse a inicios de **2001** y su primera versión **0.1** fue lanzada el **11 de marzo de 2002** por **Judd Vinet**. :contentReference[oaicite:10]{index=10}  
Desde 2007, Judd Vinet cedió el liderazgo del proyecto a Aaron Griffin. :contentReference[oaicite:11]{index=11}  
En 2012, Arch migró de **SysV init** a **systemd** como sistema de inicio por defecto. :contentReference[oaicite:12]{index=12}  
A partir de enero de 2017, se dejó de dar soporte oficial al hardware i686 (arquitecturas de 32 bits). :contentReference[oaicite:13]{index=13}  

### ¿Qué es?  
Arch Linux es una distribución **independiente** y **rolling release**, con enfoque minimalista y elevada personalización para usuarios avanzados. :contentReference[oaicite:14]{index=14}  
El modelo *rolling release* asegura que no hay versiones mayores sino actualizaciones continuas. :contentReference[oaicite:15]{index=15}  

### Características principales  
- Filosofía **KISS (Keep It Simple, Stupid)**, minimalismo y configuración manual. :contentReference[oaicite:16]{index=16}  
- Paquetes binarios gestionados por **pacman**, con resolución automática de dependencias. :contentReference[oaicite:17]{index=17}  
- Repositorios oficiales y repositorio de usuarios **AUR** (Arch User Repository) para paquetes no oficiales o contribuidos por la comunidad. :contentReference[oaicite:18]{index=18}  
- Documentación extensa — **ArchWiki** es ampliamente reconocido como una de las mejores fuentes de conocimiento técnico en Linux. :contentReference[oaicite:19]{index=19}  
- No viene con entorno gráfico por defecto; el usuario instala solo lo necesario.

### Usos y aplicaciones  
- Usuarios avanzados que desean control total sobre su sistema.  
- Entornos de desarrollo o laboratorio donde se requiere software muy actualizado.  
- Sistemas personalizados y ligeros, donde no se requiere carga de paquetes innecesarios.  
- Base para distribuciones derivadas (ej. Garuda, Manjaro).

---

## 3. Rocky Linux

### Historia  
Rocky Linux nació en **2020** como respuesta al cambio de estrategia de CentOS hacia CentOS Stream. Fue impulsado por Gregory Kurtzer (cofundador de CentOS). :contentReference[oaicite:20]{index=20}  

### ¿Qué es?  
Es una distribución **enterprise**, compatible binariamente con **RHEL** (Red Hat Enterprise Linux), destinada a reemplazar el rol de CentOS como plataforma comunitaria de producción. :contentReference[oaicite:21]{index=21}  

### Características principales  
- Compatibilidad *1:1* con RHEL; paquetes, versiones y políticas equivalentes. :contentReference[oaicite:22]{index=22}  
- Ciclo de soporte prolongado, orientado a estabilidad en producción.  
- Manejo de paquetes con **dnf / yum** (sistemas basados en RPM).  
- Comunidad activa y soporte abierto.

### Usos y aplicaciones  
- Servidores empresariales, centros de datos.  
- Migración desde CentOS sin perder compatibilidad.  
- Infraestructura de producción que requiere estabilidad y soporte a largo plazo.

---

## 4. Garuda Linux

### Historia  
Garuda Linux fue lanzado el **26 de marzo de 2020** por desarrolladores como Shrinivas Vishnu Kumbhar y la comunidad SGS. :contentReference[oaicite:23]{index=23}  

### ¿Qué es?  
Distribución basada en Arch, orientada a usuarios de escritorio con enfoque en rendimiento, estética y usabilidad. :contentReference[oaicite:24]{index=24}  

### Características principales  
- Modelo **rolling release** con actualizaciones continuas. :contentReference[oaicite:25]{index=25}  
- Usa **btrfs** como sistema de archivos por defecto con snapshots automáticos (para recuperación). :contentReference[oaicite:26]{index=26}  
- Instalador gráfico **Calamares**. :contentReference[oaicite:27]{index=27}  
- Interfaz por defecto **KDE Plasma (Dr460nized)**, pero soporta múltiples entornos (GNOME, XFCE, etc.) :contentReference[oaicite:28]{index=28}  
- Incluye herramientas gráficas propias (Garuda Settings, Garuda Assistant). :contentReference[oaicite:29]{index=29}  

### Usos y aplicaciones  
- Escritorio de alto rendimiento: gaming, multimedia.  
- Usuarios que quieren experimentar con personalización sin construcción completa desde cero.  
- Entornos visualmente atractivos que no sacrifican capacidad técnica.

---

## 5. Fedora

### Historia  
Fedora es el sucesor del proyecto **Red Hat Linux**, iniciado en 2003 como una colaboración entre la comunidad Fedora Project y Red Hat. :contentReference[oaicite:30]{index=30}  

### ¿Qué es?  
Distribución comunitaria con enfoque en tecnologías modernas; actúa como plataforma experimental para funciones que luego pueden migrar a RHEL. :contentReference[oaicite:31]{index=31}  

### Características principales  
- Ciclos de lanzamiento regular (~6 meses). :contentReference[oaicite:32]{index=32}  
- Escritorio por defecto: **GNOME**. :contentReference[oaicite:33]{index=33}  
- Seguridad reforzada mediante **SELinux** por defecto.  
- Uso de herramientas modernas (Wayland, PipeWire) y modularidad.  
- Versions especiales como **Fedora Silverblue** para flujos de trabajo de contenedores. :contentReference[oaicite:34]{index=34}  

### Usos y aplicaciones  
- Desarrollo de software, especialmente con tecnologías nuevas.  
- Pruebas de tecnologías emergentes.  
- Estaciones de trabajo modernas con seguridad y actualizaciones frecuentes.

---

## 6. Manjaro

### Historia  
Manjaro fue iniciado en 2011 como una alternativa más amigable basada en Arch Linux. :contentReference[oaicite:35]{index=35}  

### ¿Qué es?  
Distribución basada en Arch con capa de estabilidad adicional, instalador gráfico y enfoque a usuarios intermedios. :contentReference[oaicite:36]{index=36}  

### Características principales  
- Usa **pacman** como gestor de paquetes, mantiene compatibilidad con AUR. :contentReference[oaicite:37]{index=37}  
- Tres ramas principales: **unstable**, **testing** y **stable** (con ciertos retrasos respecto a Arch). :contentReference[oaicite:38]{index=38}  
- Instalador gráfico y herramientas propias para kernel, módulos y configuración.  
- Enfoque a hardware detectado y ajustes automáticos en actualizaciones conflictivas para evitar errores.

### Usos y aplicaciones  
- Escritorio de uso diario para usuarios que desean equilibrio entre modernidad y estabilidad.  
- Ideal para quienes quieren lo mejor de Arch sin tanta configuración manual.

---

## 7. CentOS (y CentOS Stream)

### Historia  
CentOS nació en 2004 como un clon binario gratuito de RHEL, muy usado en servidores. :contentReference[oaicite:39]{index=39}  
En 2020, Red Hat anunció que CentOS Linux tradicional dejaría de existir; en su lugar, CentOS Stream sería la versión upstream de RHEL. :contentReference[oaicite:40]{index=40}  

### ¿Qué es?**  
- **CentOS clásico**: clon binario gratuito de RHEL.  
- **CentOS Stream**: rama continua que sitúa entre desarrollo de RHEL y versiones estables.  

### Características principales  
- Estabilidad fuerte y soporte a largo plazo (mientras estaba en uso).  
- Administración con **yum / dnf** basado en RPM.  
- Gran comunidad y documentación histórica.  

### Usos y aplicaciones  
- Servidores de producción (antes de 2020).  
- Ahora muchos migran desde CentOS a alternativas como Rocky o AlmaLinux para mantener estabilidad en producción.

---

## 8. Kali Linux

### Historia  
Kali Linux es una reescritura de **BackTrack**, mantenida por Offensive Security desde 2013. :contentReference[oaicite:41]{index=41}  

### ¿Qué es?  
Distribución especializada en seguridad ofensiva (penetration testing), con gran colección de herramientas de hacking, análisis forense y auditoría de redes. :contentReference[oaicite:42]{index=42}  

### Características principales  
- Más de 600 herramientas preinstaladas (nmap, Metasploit, Wireshark, etc.). :contentReference[oaicite:43]{index=43}  
- Opciones de uso live, instalación o en máquinas virtuales.  
- Interfaces ligeras y personalización para pruebas de seguridad.  
- Compatibilidad con múltiples plataformas (ARM, contenedores, etc.). :contentReference[oaicite:44]{index=44}  

### Usos y aplicaciones  
- Pentesting y auditoría de seguridad.  
- Forense digital.  
- Educación en ciberseguridad.  
- Evaluaciones de vulnerabilidades dentro de entornos controlados.

---

## 9. Linux Mint

### Historia  
Linux Mint fue lanzado en 2006 por Clement Lefèbvre, basado en Ubuntu (y también en Debian en sus ediciones “LMDE”). :contentReference[oaicite:45]{index=45}  

### ¿Qué es?  
Una distribución de escritorio orientada al usuario promedio, buscando facilidad de uso, estabilidad y compatibilidad multimedia.  

### Características principales  
- Entornos gráficos predeterminados: **Cinnamon**, **MATE** y **XFCE**.  
- Herramientas propias: mintUpdate, mintMenu, mintInstall.  
- Basada en Ubuntu (o en Debian en algunas variantes).  
- Buena compatibilidad con hardware y multimedia “out-of-the-box”.  

### Usos y aplicaciones  
- Usuario de escritorio nuevo al mundo Linux (facilidad para migrar desde Windows).  
- Equipos de oficina, centros educativos.  
- Computadoras personales con requerimientos simples.

---

## 10. Ubuntu

### Historia  
Ubuntu fue anunciado en 2004 por la empresa Canonical, liderada por Mark Shuttleworth, como una distribución basada en Debian con mayor enfoque al usuario final. :contentReference[oaicite:46]{index=46}  

### ¿Qué es?  
Distribución con soporte comercial y comunitario, disponible en versiones Desktop, Server y Cloud.  

### Características principales  
- Versiones regulares cada 6 meses y versiones LTS (Long Term Support) cada 2 años con soporte de 5 años.  
- Gestores de paquetes: **apt**, **snap**.  
- Gran ecosistema, soporte de hardware, gran comunidad.  
- Derivados oficiales: Kubuntu, Xubuntu, Ubuntu Server, Ubuntu Core.  

### Usos y aplicaciones  
- Escritorios en empresas, educación y uso personal.  
- Servidores web, aplicaciones, nube (AWS, Azure, etc.).  
- Desarrollo de software, contenedores y ciencia de datos.

---

## 11. Alpine Linux

### Historia  
Alpine es una distribución ligera y segura basada en **musl libc** y **BusyBox**, ampliamente usada en contenedores Docker y entornos embebidos. :contentReference[oaicite:47]{index=47}  

### ¿Qué es?  
Distribución minimalista orientada a seguridad, con bajo consumo de recursos, ideal para contenedores y sistemas ligeros.  

### Características principales  
- Tamaño reducido.  
- Uso de **apk** como gestor de paquetes. :contentReference[oaicite:48]{index=48}  
- Enfoque en seguridad (uso de grsecurity, aislamiento).  
- Muy usada como base de imágenes Docker y en entornos donde el peso y velocidad son críticos.  

### Usos y aplicaciones  
- Entornos de contenedores (Docker, Kubernetes).  
- Sistemas embebidos, IoT.  
- Microservicios, infraestructura ligera.

---

## 12. AlmaLinux

### Historia  
AlmaLinux fue creado en 2021 por CloudLinux como una respuesta comunitaria al cambio de CentOS hacia CentOS Stream. :contentReference[oaicite:49]{index=49}  

### ¿Qué es?  
Distribución empresarial gratuita, con compatibilidad binaria con RHEL, destinada a reemplazar CentOS para servidores de producción.  

### Características principales  
- Compatibilidad *1:1* con RHEL. :contentReference[oaicite:50]{index=50}  
- Estabilidad, soporte comunitario.  
- Uso de **dnf / yum** como sistemas de gestión de paquetes.  
- Utilizada para migraciones desde CentOS y entornos empresariales.

### Usos y aplicaciones  
- Servidores de producción en empresas.  
- Infraestructura de nube y hosting.  
- Migraciones desde distribuciones de soporte prolongado como CentOS.

---

## Conclusión general comparativa

Cada distribución Linux tiene enfoques distintos:

| Enfoque principal | Distribuciones destacadas |
|-------------------|-----------------------------|
| **Estabilidad empresarial / servidores** | Debian, Rocky Linux, AlmaLinux, CentOS (histórico) |
| **Usuarios intermedios / escritorio moderno** | Ubuntu, Linux Mint, Fedora |
| **Alta personalización / usuarios avanzados** | Arch Linux, Manjaro, Garuda |
| **Especializado en seguridad** | Kali Linux |
| **Ligereza / contenedores** | Alpine Linux |
