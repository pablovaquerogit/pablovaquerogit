<div align="center">

# Hola, soy Pablo Vaquero 👋

### Analista de datos y desarrollador en formación

**Construyendo soluciones con SQL Server, Python y automatización.**

[![GitHub](https://img.shields.io/badge/GitHub-pablovaquerogit-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pablovaquerogit)
[![Correo](https://img.shields.io/badge/Correo-Contacto-4F46E5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pablovaquero.git@gmail.com)

</div>

---

## 👨‍💻 Sobre mí

Me interesa utilizar el desarrollo y los datos para crear soluciones útiles, organizadas y fáciles de mantener.  
He desarrollado proyectos con SQL Server y T-SQL, aplicando modelado relacional, consultas, validaciones y reglas de negocio.  
También utilizo Python para fortalecer mis habilidades de programación y resolución de problemas.  
Me gusta automatizar procesos e integrar herramientas como Make, Telegram, Google Sheets, Google Calendar y OpenAI.  
Actualmente continúo aprendiendo, documentando proyectos y construyendo un portafolio basado en trabajo real.

---

## 🛠️ Tecnologías y herramientas

### Bases de datos

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-2563EB?style=flat-square&logo=microsoftsqlserver&logoColor=white)

### Programación

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

### Automatización e integraciones

![Make](https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white)
![Google Calendar](https://img.shields.io/badge/Google%20Calendar-4285F4?style=flat-square&logo=googlecalendar&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

### Herramientas

![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 🚀 Proyectos destacados

### 🩺 MediCitas IA

Automatización administrativa para gestionar citas médicas mediante conversaciones en Telegram.

**Problema que resuelve**

La gestión manual de citas puede producir registros duplicados, pérdida de información y falta de sincronización entre pacientes, horarios disponibles y calendarios.

**Solución**

El sistema interpreta las solicitudes recibidas en Telegram, estructura la información con OpenAI y utiliza Make para coordinar las operaciones con Google Sheets y Google Calendar.

**Tecnologías:** `Make` · `OpenAI` · `Telegram` · `Google Sheets` · `Google Calendar`

**Funcionalidades principales**

- Agendar, cancelar, reagendar y consultar citas.
- Registrar pacientes y completar información faltante.
- Validar la disponibilidad antes de confirmar una cita.
- Sincronizar eventos con Google Calendar.
- Enviar recordatorios automáticos por Telegram.
- Registrar solicitudes y resultados en una bitácora.
- Transferir urgencias y solicitudes especiales a atención humana.
- Evitar registros duplicados mediante validaciones.

**Aprendizajes relevantes**

Diseño de flujos con rutas y filtros, integración entre servicios, extracción estructurada de información, validación de datos, manejo de estados, documentación y pruebas de automatizaciones.

**Estado:** proyecto académico colaborativo, documentado y publicado como demostración.

[![Ver repositorio de MediCitas IA](https://img.shields.io/badge/Ver%20repositorio-6366F1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pablovaquerogit/medicitas-ia)

---

### 🐍 Compilador Cascabel

Compilador educativo desarrollado en Python para un lenguaje de programación con sintaxis en español.

**Problema que resuelve**

Un lenguaje de programación necesita reconocer instrucciones, validar su estructura, detectar errores y traducir el código fuente a un formato ejecutable.

**Solución**

El compilador procesa archivos escritos en Cascabel mediante análisis léxico, sintáctico y semántico. Después construye un árbol de sintaxis abstracta y genera código Python ejecutable.

**Tecnologías:** `Python` · `Git` · `GitHub`

**Funcionalidades principales**

- Reconocimiento de palabras reservadas, identificadores, literales y operadores.
- Validación de la gramática del lenguaje.
- Construcción de un árbol de sintaxis abstracta.
- Manejo de una tabla de símbolos.
- Validación de tipos y variables declaradas.
- Detección de errores léxicos, sintácticos y semánticos.
- Soporte para condiciones, ciclos, lectura y escritura.
- Generación de código Python.
- Ejecución de pruebas automáticas.

**Aprendizajes relevantes**

Procesamiento de lenguajes, diseño modular, estructuras de datos, validación de errores, generación de código, pruebas y organización de un proyecto en Python.

**Estado:** proyecto académico individual, funcional, documentado y publicado.

[![Ver repositorio del Compilador Cascabel](https://img.shields.io/badge/Ver%20repositorio-4F46E5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pablovaquerogit/compilador-cascabel)

---

### 📦 Sistema de Gestión de Envíos

Base de datos relacional para administrar paquetes nacionales e internacionales, conductores, camiones, rutas y centros locales.

**Problema que resuelve**

Un sistema de envíos necesita relacionar diferentes entidades y aplicar reglas que eviten asignaciones incorrectas, registros incompletos y datos inconsistentes.

**Solución**

Se diseñó una base de datos en SQL Server con 11 tablas relacionadas, restricciones, procedimientos almacenados, triggers y transacciones para controlar la información y automatizar reglas de negocio.

**Tecnologías:** `SQL Server` · `T-SQL`

**Funcionalidades principales**

- Gestión de paquetes nacionales e internacionales.
- Relaciones entre conductores, camiones y rutas.
- Uso de llaves primarias, llaves foráneas y restricciones.
- Validación automática de reglas de negocio mediante triggers.
- Procedimiento almacenado para consultar paquetes.
- Actualización automática del conteo de envíos por ciudad.
- Datos de ejemplo y pruebas controladas con transacciones.
- Documentación técnica y diccionario de datos.

**Aprendizajes relevantes**

Modelado y normalización de bases de datos, integridad referencial, consultas SQL, procedimientos almacenados, triggers, manejo de errores, transacciones y documentación técnica.

**Estado:** proyecto académico adaptado, documentado y publicado como parte del portafolio.

[![Ver repositorio del Sistema de Envíos](https://img.shields.io/badge/Ver%20repositorio-2563EB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pablovaquerogit/sql-server-sistema-envios)

---

## 🌱 Actualmente

| Área | En qué estoy trabajando |
|---|---|
| 📚 Aprendiendo | Consultas avanzadas en SQL Server, Python, análisis de datos, Git y GitHub |
| 🔨 Construyendo | Proyectos funcionales y documentados para mi portafolio |
| 🔎 Explorando | Automatizaciones con Make e integraciones con Telegram, Google Sheets, Google Calendar y OpenAI |
| 💼 Buscando | Oportunidades como analista de datos, desarrollador junior o perfil tecnológico en formación |

---

## 📫 Contacto

- **GitHub:** [github.com/pablovaquerogit](https://github.com/pablovaquerogit)
- **Correo:** [pablovaquero.git@gmail.com](mailto:pablovaquero.git@gmail.com)

---

<div align="center">

**Aprendiendo de cada proyecto y convirtiendo ideas en soluciones funcionales.**

</div>
