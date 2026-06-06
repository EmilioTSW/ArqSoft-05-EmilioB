# CitasApp

## Autor

**Jorge Emilio Batún Alcorow**

---

## Descripción General

CitasApp es una aplicación web desarrollada con **ASP.NET Core MVC** que permite administrar información relacionada con pacientes, médicos y citas médicas de manera sencilla y organizada.

La aplicación utiliza archivos JSON como mecanismo de almacenamiento, permitiendo conservar la información registrada incluso después de cerrar o reiniciar el sistema.

El proyecto fue desarrollado con fines académicos para aplicar conceptos de programación orientada a objetos, arquitectura MVC, manejo de archivos JSON y desarrollo web con ASP.NET Core.

---

## Características Principales

### Gestión de Pacientes

* Consultar listado de pacientes.
* Visualizar información detallada de cada paciente.
* Registrar nuevos pacientes.

### Gestión de Médicos

* Consultar listado de médicos.
* Visualizar información detallada de cada médico.
* Registrar nuevos médicos.

### Gestión de Citas

* Consultar agenda completa de citas médicas.
* Registrar nuevas citas.
* Filtrar citas por paciente.
* Visualizar el estado de cada cita.

### Persistencia de Datos

* Almacenamiento mediante archivos JSON.
* Conservación automática de la información.
* Lectura y escritura de datos utilizando servicios personalizados.

---

## Tecnologías Utilizadas

* C#
* ASP.NET Core MVC
* Razor Views
* HTML5
* CSS3
* Bootstrap
* JSON
* Git
* GitHub
* Visual Studio 2022

---

## Arquitectura del Proyecto

```text
CitasApp
│
├── Controllers
│   ├── PacienteController.cs
│   ├── MedicoController.cs
│   └── CitaController.cs
│
├── Models
│   ├── Paciente.cs
│   ├── Medico.cs
│   └── Cita.cs
│
├── Services
│   └── JsonFileService.cs
│
├── Data
│   ├── pacientes.json
│   ├── medicos.json
│   └── citas.json
│
├── Views
│   ├── Paciente
│   ├── Medico
│   ├── Cita
│   └── Shared
│
├── wwwroot
│
├── Program.cs
│
└── README.md
```

---

## Almacenamiento de Información

Los datos son almacenados en archivos JSON ubicados dentro de la carpeta:

```text
Data/
```

Archivos utilizados:

```text
Data/pacientes.json
Data/medicos.json
Data/citas.json
```

La clase:

```text
Services/JsonFileService.cs
```

es la encargada de realizar la lectura y escritura de la información, garantizando la persistencia de los datos dentro de la aplicación.

---

## Navegación del Sistema

La aplicación incorpora una barra de navegación que permite acceder fácilmente a los distintos módulos:

* Pacientes
* Médicos
* Citas

Esto mejora la experiencia del usuario y evita la necesidad de escribir rutas manualmente.

---

## Instrucciones de Ejecución

1. Abrir la solución en Visual Studio.
2. Restaurar las dependencias del proyecto.
3. Ejecutar la aplicación utilizando HTTPS.
4. Navegar a través de las opciones disponibles:

   * Pacientes
   * Médicos
   * Citas

---

## Objetivos Académicos Alcanzados

Durante el desarrollo de este proyecto se aplicaron los siguientes conceptos:

* Arquitectura MVC.
* Programación Orientada a Objetos.
* Manejo de colecciones y objetos.
* Persistencia de datos con JSON.
* Desarrollo de interfaces con Razor Views.
* Uso de Bootstrap para diseño responsivo.
* Gestión de proyectos con Git y GitHub.

---

## Uso de Inteligencia Artificial

Durante el desarrollo de este proyecto se utilizó apoyo de herramientas de inteligencia artificial como asistencia para la resolución de dudas, revisión de código, detección de errores y mejora de la documentación, manteniendo siempre la comprensión y validación del funcionamiento por parte del desarrollador.

---

**Desarrollado por Jorge Emilio Batún Alcorow**
# Citas_App
