<div align="right">
  🌍 <strong>Español</strong> | <a href="README_en.md">English</a>
</div>

# 👋 ¡Hola! Soy María Auxiliadora Vélez Mendoza

### 👩‍💻 QA Engineer Full-Stack | Manual & Automation Testing | Ingeniera en Sistemas

> **Ingeniera en Sistemas Informáticos** con más de 3 años de experiencia garantizando la calidad de software en sistemas críticos y de alta transaccionalidad. He realizado la validación de infraestructura bajo alta presión (incluyendo sistemas de transmisión de datos electorales), asegurando la estabilidad operativa, la seguridad y la integridad de los datos en todo momento.

Mi enfoque va más allá de reportar bugs visuales (metodología *Shift-Left Testing*); aseguro la integridad del backend mediante auditorías directas en bases de datos (PostgreSQL, SQL), estreso APIs mediante pruebas negativas para descubrir vulnerabilidades, y construyo frameworks de automatización UI/API escalables y mantenibles.

---

## 🛠️ Mi Stack Tecnológico

| Capa / Especialidad | Herramientas y Tecnologías Basadas en Proyectos |
| :--- | :--- |
| **Automatización & Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white) ![Linux Bash](https://img.shields.io/badge/Linux_Bash-4EAA25?style=flat&logo=linux&logoColor=white) | 
| **API & Mobile Testing** | ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white) ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat&logo=android-studio&logoColor=white) ![Chrome DevTools](https://img.shields.io/badge/Chrome_DevTools-4285F4?style=flat&logo=google-chrome&logoColor=white) | 
| **Gestión & Agilidad** | ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat&logo=azure-devops&logoColor=white) ![Scrum](https://img.shields.io/badge/Scrum-000000?style=flat&logo=scrum&logoColor=white) |

---

## 🚀 Portafolio de Proyectos QA

*(Haz clic en los enlaces para acceder al código fuente, matrices de pruebas, consultas SQL y reportes de defectos en Jira de cada repositorio).*

### 👑 1. Auditoría Integral (Full-Stack QA)
*   **[Auditoría: Auditoría de Resiliencia y Seguridad: App Financiera Móvil](https://github.com/mvelez2793/12_QA-Resilience-Framework.git)**
    *   **Descripción:** Auditoría técnica de caja negra sobre el flujo crítico de autenticación. Combina automatización E2E móvil con Appium, stress testing con Postman Runner, análisis DAST con Charles Proxy y observabilidad en tiempo real con Grafana.

*   **[Auditoría: Web, App Móvil y API - Urban Scooter](https://github.com/mvelez2793/09_Auditoria-Web-Movil-y-API---Urban-Scooter)**
    *   **Descripción:** Auditoría completa de un ecosistema de alquiler de patinetes cubriendo 3 capas arquitectónicas. Apliqué Análisis de Valores Límite en la plataforma Web, simulé interrupciones de red (Offline mode) en la App de Android de los repartidores, y vulneré la API REST validando la corrupción de datos directamente en PostgreSQL mediante consultas SQL.

### 🤖 2. Automatización de Pruebas (E2E & API)
*   **[Automatización Web UI con Selenium & Python - Urban Routes](https://github.com/mvelez2793/08_Automatizacion-Web-UI-E2E-Urban-Routes)**
    *   **Descripción:** Framework End-to-End (E2E) bajo el patrón Page Object Model (POM) para una plataforma de taxis. Implementé soluciones complejas como la intercepción de tráfico de red para capturar códigos SMS, manipulación de esperas explícitas para modales dinámicos, y simulación de eventos en el DOM (JavaScript injection).

*   **[Automatización Backend con Pytest & Requests - Urban Grocers](https://github.com/mvelez2793/07_Automatizacion-de-Pruebas-API-Python-Pytest-Urban-Grocers)**
    *   **Descripción:** Suite automatizada para validar el endpoint de creación de kits de productos. El script aisló bugs críticos del servidor, documentando cómo la API devolvía un falso estado exitoso (`201 Created`) ante peticiones inválidas con valores numéricos y nulos.

### 🔌 3. Pruebas Backend, Logs y SQL
*   **[Análisis de Logs (Linux) y Consultas en Base de Datos - Chicago Taxi](https://github.com/mvelez2793/06_Analisis-de-Datos-y-Backend-SQL-Linux-Console-Chicago-Taxi-)**
    *   **Descripción:** Diagnóstico de discrepancias en la facturación mediante consultas SQL avanzadas (`INNER JOIN`, `GROUP BY`, `CASE WHEN`). Navegación en servidor remoto Linux usando `Bash` (comandos `grep` y expresiones regulares) para aislar registros de error HTTP 400 y 500 originados en producción.
    
*   **[Negative Testing y Validación JSON en API REST - Urban Grocers](https://github.com/mvelez2793/04_Pruebas-de-API-Backend-RESTful-Urban-Grocers)**
    *   **Descripción:** Ejecución de pruebas de estrés mediante Postman sobre los microservicios de entrega. Identifiqué fallos no controlados del servidor (`500 Internal Server Error`) al inyectar tipos de datos inválidos en el Payload JSON.

### 📱 4. Mobile Testing (Android)
*   **[QA Funcional y Validación UI/UX - Urban.Lunch](https://github.com/mvelez2793/05_Pruebas-de-Aplicaciones-Moviles-Android-Urban.Lunch)**
    *   **Descripción:** Pruebas táctiles y de usabilidad ejecutadas en emulador de Android Studio para una app de entrega de comida. Reporté bloqueadores lógicos en el carrito de compras y vulnerabilidades en la integración con el Sistema Operativo Android (manejo incorrecto de permisos de geolocalización).

### 🌐 5. Ingeniería de Pruebas Manuales (Web)
*   **[Cross-Browser Testing y Regresión - Urban Routes]( https://github.com/mvelez2793/03_Urban-Routes-Pruebas-de-Integracion-y-Logica-reserva )**
    *   **Descripción:** Estrategia exhaustiva evaluando la integridad visual forzando resoluciones en Chrome y Firefox. Estresé la pasarela de pagos limitando la inyección de tarjetas de crédito.
*   **[Diseño de Casos de Prueba y Mapas Mentales - Urban Routes]( https://github.com/mvelez2793/02_Urban-Routes---Pruebas-de-Regresion-y-Reporte-de-Errores )**
    *   **Descripción:** Descomposición de la lógica de negocio del algoritmo de tarifas de taxi usando Diagramas de Flujo y diseño BVA.
*   **[Ejecución de Regresión y Bug Tracking - Urban Routes]( https://github.com/mvelez2793/01_Urban-Routes---Dise-o-de-Pruebas-y-An-lisis-de-Requerimientos )**
    *   **Descripción:** Trazabilidad de defectos y reporte de bugs críticos en Jira aplicando estándares de documentación.

---

## 📫 Conecta conmigo:
*   💼 **LinkedIn:** [maria-auxiliadora-velez-mendoza](https://www.linkedin.com/in/maria-auxiliadora-velez-mendoza) 
*   🌐 **Portafolio Web:** [mavm.netlify.app](https://mavm.netlify.app/)
*   📧 **Email:** mvelez_2793@hotmail.com 
*   📍 **Ubicación:** Ecuador

---
⭐ *¿Buscas una QA Engineer con mentalidad preventiva, bases sólidas en ingeniería y capaz de asegurar la calidad desde el diseño de la arquitectura hasta la automatización en producción? ¡Contáctame y hablemos de cómo puedo aportar valor a tu equipo!*


## 📫 Contacto

📧 mvelez_2793@hotmail.com  
🔗 linkedin.com/in/maria-auxiliadora-velez-mendoza

---

<p align="center">🌟 ¡Gracias por visitar mi perfil! 🌟</p>
