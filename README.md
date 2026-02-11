⚡ Proxy-Checker Universal Pro

High-Performance Validation & Intelligent Proxy Management Engine
Proxy-Checker Universal Pro es una herramienta de grado industrial diseñada para la validación masiva de proxies con un enfoque en la velocidad, la precisión y la automatización remota. Olvida las listas muertas; esta herramienta disecciona cada conexión para entregarte solo los activos más veloces y estables del mercado.

---

🚀 Características Élite

* Motor Multi-hilo Ultra-Veloz: Ejecución en paralelo mediante ThreadPoolExecutor para procesar cientos de proxies en segundos.
* Análisis Profundo de Conexión: Detecta automáticamente el protocolo (HTTP, HTTPS, SOCKS4, SOCKS5) y calcula la latencia (Ping) exacta.
* Inteligencia de Red Integrada: Clasificación automática entre nodos RESIDENCIALES y DATACENTER, incluyendo extracción de ISP mediante integración con API de geolocalización.
* Ecosistema Telegram (Mando y Control): Notificaciones en tiempo real, panel de activos para descarga de archivos filtrados y limpieza de canal.
* Arquitectura de Auto-Actualización: Sistema nativo que verifica versiones en GitHub para asegurar que siempre corras la lógica más optimizada.
* Almacenamiento Inteligente: Organización automática de resultados por velocidad, tipo y formato en carpetas fechadas.

---

🛠️ Especificaciones Técnicas

| Módulo | Función |
| :--- | :--- |
| Concurrency | 30+ Workers simultáneos |
| Validation URL | Google Connectivity (204 No Content) |
| Data Export | TXT / JSON / Telegram Document |
| UI | Hacker-Style ANSI Terminal |
| Auto-Repair | Detección y corrección de formatos user:pass@host:port |

---

📦 Instalación y Despliegue

Para garantizar que todas las funciones (incluyendo el soporte para proxies SOCKS) operen correctamente, sigue estos pasos:

1. Clonar el repositorio:
   git clone https://github.com/xXxCharlieFdzxXx/Proxy-Checker-Universal-Pro.git
   cd Proxy-Checker-Universal-Pro

2. Instalar dependencias necesarias:
   Este proyecto requiere librerías externas para el manejo de protocolos y la API de Telegram. Instálalas usando el archivo de requerimientos:
   pip install -r requirements.txt

3. Ejecutar la herramienta:
   python Proxy-Checker-Universal-Pro.py

---

🕹️ Interfaz de Usuario

El programa cuenta con un banner dinámico y una barra de progreso en tiempo real que te mantiene informado sobre el estatus del sistema:

[ SYSTEM STATUS: ONLINE ] [ v1.0 ] 
[██████████████████████━━━━━━] 75.0% Completado

---

⚠️ Requisitos del Sistema
* Python 3.x
* Conexión a Internet (para validación y auto-update)
* Credenciales de Telegram (Opcional, para control remoto)
