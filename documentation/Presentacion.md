# Presentación del módulo

> [Back to Menu](../README.md)

Este módulo tiene como objetivo introducir a los estudiantes en la programación utilizando el ecosistema .NET y el lenguaje C#. A lo largo del módulo, los estudiantes adquirirán una comprensión más sólida de los fundamentos de programación, el desarrollo de aplicaciones backend con .NET y .NET Core, el uso de bases de datos con Entity Framework Core, y las mejores prácticas en seguridad, pruebas y un abre bocas a despliegues en la nube. 

## ¿Cuál es la competencia que obtiene el estudiante al finalizar el módulo? 

Los participantes desarrollarán las habilidades necesarias para construir aplicaciones modernas y escalables, alineadas con los estándares de la industria. 

#### **Al finalizar el módulo, los estudiantes serán capaces de:**

* Comprender los principios fundamentales de la programación en C# y el entorno .NET.
* Diseñar e implementar aplicaciones utilizando Programación Orientada a Objetos (POO).
* Crear y consumir APIs REST con ASP.NET y aplicar patrones de arquitectura backend.
* Utilizar bases de datos relacionales con Entity Framework Core.
* Implementar autenticación y seguridad en aplicaciones web.
* Realizar pruebas unitarias e integración para mejorar la calidad del software.
* Contenerizar aplicaciones con Docker y desplegarlas en entornos de producción.
* Automatizar flujos de integración y despliegue continuo (CI/CD).
* Monitorear y optimizar aplicaciones con herramientas de logging y telemetría.
* Desplegar aplicaciones en la nube utilizando Azure o AWS.

### ¿Cuál es el resultado de aprendizaje que se evidencia al finalizar el módulo? 

Al finalizar el módulo, el estudiante habrá desarrollado las competencias necesarias para diseñar, construir y desplegar aplicaciones backend modernas con .NET y C#. A través del reto final, donde deberán entregar una solución funcional basada en los conceptos aprendidos, se evidenciarán los siguientes resultados de aprendizaje:

1. Comprensión de los Fundamentos de Programación

    a. El estudiante podrá escribir código en C#, aplicando estructuras de control, manejo de variables y operadores.

    b. Implementará principios de Programación Orientada a Objetos (POO), utilizando clases, objetos, herencia, encapsulación e interfaces. 

2. Desarrollo de Aplicaciones Web Backend

    a. Creará una API REST funcional con ASP.NET, aplicando arquitectura en capas y buenas prácticas de desarrollo. 

    b. Implementará controladores, rutas y manejo de peticiones HTTP. 

3. Gestión y Persistencia de Datos 

    a. Diseñará bases de datos utilizando Entity Framework Core.

    b. Aplicará migraciones y consultas con LINQ para gestionar la información. 

4. Implementación de Seguridad y Autenticación

    a. Configurará autenticación y autorización en una API utilizando Identity Framework y JWT.

    b. Aplicará prácticas de seguridad en el desarrollo de aplicaciones web.

5. Pruebas y Validación del Código

    a. Escribirá pruebas unitarias con xUnit y utilizará NSubstitute para pruebas con dependencias.

    b. Realizará pruebas de integración en una aplicación ASP.NET.

6. Despliegue y Contenerización de Aplicaciones
    a. Contenerizará la aplicación utilizando Docker y gestionará servicios con Docker Compose.
    
    b. Desplegará su solución en un entorno en la nube (Azure o AWS).

7. Automatización y Monitoreo
    
    a. Implementará logging con Serilog y monitoreo con OpenTelemetry para analizar el rendimiento de la aplicación.

## Mapa mental o conceptual con las conexiones temáticas del módulo

```mermaid
mindmap
  root((   BACKEND II   ))
    ((Unidad 1: Fundamentos de .NET y C#))
        (Tema 1: Introducción a .NET y C#)
            (Subtema: Conceptos básicos de .NET y su entorno.)
            (Subtema: Configuración del entorno con VS Code.)
            (Subtema: Introducción a C#: estructura básica, tipos de datos, variables, operadores.)
            (Subtema: Niveles de acceso.)
        (Tema 2: Programación Orientada a Objetos en C#)
            (Subtema: Clases, objetos, herencia, polimorfismo, encapsulación.)
            (Subtema: Interfaces y clases abstractas.)
            (Subtema: Inyección de dependencias en .NET.)
            (Subtema: Patrones de diseño existentes en aplicaciones backend.)
    ((Unidad 2: Desarrollo de APIs con ASP.NET))
        (Tema 3: ASP.NET y Arquitectura de Aplicaciones Backend)
            (Subtema: Introducción a ASP.NET y MVC.)
            (Subtema: Qué es RESTFul y cómo se logra con .Net?)
            (Subtema: REST vs gRPC.)
            (Subtema: Arquitectura en capas: separación de responsabilidades.)
            (Subtema: Creación de controladores y rutas en ASP.NET.)
            (Subtema: Configuración básica del servidor web en ASP.NET.)
            (Subtema: Otras arquitecturas existentes para aplicaciones backend.)
        (Tema 4: Entity Framework Core y Bases de Datos)
            (Subtema: Introducción a Entity Framework Core.)
            (Subtema: Modelado de bases de datos con EF Core.)
            (Subtema: Creación de migraciones y consultas básicas con LINQ.)
            (Subtema: PostgreSQL y MSSQL: conexión y configuración.)
    ((Unidad 3: Seguridad y Buenas Prácticas))
        (Tema 5: Seguridad y Autenticación con Identity Framework)
            (Subtema: Introducción a Identity Framework para autenticación y autorización.)
            (Subtema: Configuración de roles y permisos en aplicaciones .NET.)
            (Subtema: Implementación de JWT para autenticación segura.)
            (Subtema: Implementación de OAuth 2.0 y control de acceso basado en roles.)
        (Tema 6: Pruebas Unitarias e Integración)
            (Subtema: Introducción a pruebas unitarias con MSTest y xUnit.)
            (Subtema: Uso de NSubstitute para pruebas con dependencias.)
            (Subtema: Configuración de pruebas de integración en ASP.NET.)
    ((Unidad 4: Infraestructura y Despliegue))
        (Tema 7: Docker y Contenerización)
            (Subtema: Conceptos básicos de Docker y contenerización.)
            (Subtema: Creación de Dockerfiles para aplicaciones .NET.)
            (Subtema: Contenerización de la API.)
        (Tema 8: Orquestación con Docker Compose)
            (Subtema: Introducción a Docker Compose.)
            (Subtema: Configuración de múltiples contenedores para base de datos y API.)
    ((Unidad 5: Automatización y Producción))
        (Tema 9: Monitoreo y Logging)
            (Subtema: Introducción a Logging y Monitoreo. Serilog: Primeros Pasos.)
            (Subtema: OpenTelemetry para Telemetría y Tracing.)
            (Subtema: Integración de Serilog y OpenTelemetry.)
            (Subtema: Buenas Prácticas y Desafíos.)
        (Tema 10: CI/CD con GitHub Actions)
            (Subtema: Introducción a CI/CD y automatización de despliegues.)
            (Subtema: Configuración de pipelines en GitHub Actions.)
        (Tema 11: Despliegue en la Nube)
            (Subtema: Introducción a opciones de despliegue en la nube.)
            (Subtema: Configuración de un servicio en Azure/AWS con contenedores Docker.)

```

> [Back to Menu](../README.md)
