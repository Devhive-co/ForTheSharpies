# ForTheSharpies

## [Presentación del curso](documentation/Presentacion.md)

## **Unidad 1: Fundamentos de .NET y C#**

### **Tema 1: Introducción a .NET y C#**

1. [Conceptos básicos de .NET 8.0 y su entorno.](documentation/U1/U1-T1.md#st1-conceptos-básicos-de-net-80-y-su-entorno)
2. [Configuración del entorno con VS Code.](documentation/U1/U1-T1.md#st2-configuración-del-entorno-con-vscode)
3. [Introducción a C#: estructura básica, tipos de datos, variables, operadores.](documentation/U1/U1-T1.md#st3-introducción-a-c)
4. [Niveles de acceso (Public, Private, Sealed, Static, Internal).](documentation/U1/U1-T1.md#st4-niveles-de-acceso)

### **Tema 2: Programación Orientada a Objetos (POO) en C#**
1. [Clases, objetos, herencia, polimorfismo, encapsulación.](documentation/U1/U1-T2.md#st1-clases-objetos-herencia-polimorfismo-encapsulación)
2. [Interfaces y clases abstractas.](documentation/U1/U1-T2.md#st2-iinterfaces-y-clases-abstractas-definiendo-contratos-y-comportamientos-comunes)
3. [Inyección de dependencias (DI) en .NET.](documentation/U1/U1-T2.md#st3-inyección-de-dependencias-di-en-net-desacoplando-componentes-y-mejorando-la-mantenibilidad)
4. [Patrones de diseño existentes en aplicaciones backend.](documentation/U1/U1-T2.md#st4-patrones-de-diseño-existentes-en-aplicaciones-backend)

## **Unidad 2: Desarrollo de APIs con ASP.NET**

### **Tema 3: ASP.NET y Arquitectura de Aplicaciones Backend**
1. [Introducción a ASP.NET y MVC.](documentation/U2/U2-T3.md#st1-introducción-a-aspnet-y-mvc)
2. [Qué es RESTFul y cómo se logra con .Net?](documentation/U2/U2-T3.md#st2-qué-es-restful-y-cómo-se-logra-con-net)
3. [REST vs gRPC](documentation/U2/U2-T3.md#st3-rest-vs-grpc)
4. [Arquitectura en capas: separación de responsabilidades.](documentation/U2/U2-T3.md#st4-arquitectura-en-capas-separación-de-responsabilidades)
5. [Creación de controladores y rutas en ASP.NET.](documentation/U2/U2-T3.md#st5-creación-de-controladores-y-rutas-en-aspnet)
6. [Configuración básica del servidor web en ASP.NET.](documentation/U2/U2-T3.md#st6-configuración-básica-del-servidor-web-en-aspnet)
7. [Otras arquitecturas existentes para aplicaciones backend](documentation/U2/U2-T3.md#st7-otras-arquitecturas-existentes-para-aplicaciones-backend)

### **Tema 4: Entity Framework Core y Bases de Datos**
1. [Introducción a Entity Framework Core (EF Core).](documentation/U2/U2-T4.md#st1-introducción-a-entity-framework-core-ef-core)
2. [Modelado de bases de datos con EF Core.](documentation/U2/U2-T4.md#st2-modelado-de-bases-de-datos-con-ef-core)
3. [Creación de migraciones y consultas básicas con LINQ.](documentation/U2/U2-T4.md#st3-creación-de-migraciones-y-consultas-básicas-con-linq)
4. [PostgreSQL y MSSQL: conexión y configuración.](documentation/U2/U2-T4.md#st4-postgresql-y-mssql-conexión-y-configuración)

## **Unidad 3: Seguridad y Buenas Prácticas**

### **Tema 5: Seguridad y Autenticación con Identity Framework**
1. [Introducción a Identity Framework para autenticación y autorización.](documentation/U3/U3-T5.md#1-introducción-a-identity-framework-para-autenticación-y-autorización)
2. [Configuración de roles y permisos en aplicaciones .NET.](documentation/U3/U3-T5.md#2-configuración-de-roles-y-permisos-en-aplicaciones-net)
3. [Implementación de JWT para autenticación segura.](documentation/U3/U3-T5.md#3-implementación-de-jwt-para-autenticación-segura)
4. [Implementación de OAuth 2.0 y control de acceso basado en roles.](documentation/U3/U3-T5.md#4-implementación-de-oauth-20-y-control-de-acceso-basado-en-roles)

### **Tema 6: Pruebas Unitarias e Integración**
1. [Introducción a pruebas unitarias con MSTest y xUnit.](documentation/U3/U3-T6.md#1-introducción-a-pruebas-unitarias-con-mstest-y-xunit)
2. [Uso de NSubstitute para pruebas con dependencias.](documentation/U3/U3-T6.md#2-uso-de-nsubstitute-para-pruebas-con-dependencias)
3. [Configuración de pruebas de integración en ASP.NET.](documentation/U3/U3-T6.md#3-configuración-de-pruebas-de-integración-en-aspnet)

## **Unidad 4: Infraestructura y Despliegue**

### **Tema 7: Docker y Contenerización**
1. [Conceptos básicos de Docker y contenerización.](documentation/U4/U4-T7.md#st1-conceptos-básicos-de-docker-y-contenerización)
2. [Creación de Dockerfiles para aplicaciones .NET.](documentation/U4/U4-T7.md#st2-creación-de-dockerfiles-para-aplicaciones-net)
3. [Contenerización de la API.](documentation/U4/U4-T7.md#st3-contenerización-de-la-api)

### **Tema 8: Orquestación con Docker Compose**
1. [Introducción a Docker Compose.](documentation/U4/U4-T8.md#st1-introducción-a-docker-compose)
2. [Configuración de múltiples contenedores para base de datos y API.](documentation/U4/U4-T8.md#st2-configuración-de-múltiples-contenedores-para-base-de-datos-y-api)

## **Unidad 5: Automatización y Producción**
 
### **Tema 9: Monitoreo y Logging**
1. [Introducción a Logging y Monitoreo. Serilog: Primeros Pasos.](documentation/U5/U5-T9.md#st1-introducción-a-logging-y-monitoreo-serilog-primeros-pasos)
2. [OpenTelemetry para Telemetría y Tracing.](documentation/U5/U5-T9.md#st2-opentelemetry-para-telemetría-y-tracing)
3. [Integración de Serilog y OpenTelemetry.](documentation/U5/U5-T9.md#st3-integración-de-serilog-y-opentelemetry)
4. [Buenas Prácticas y Desafíos.](documentation/U5/U5-T9.md#st4-buenas-prácticas-y-desafíos-en-monitoreo-y-logging-con-telemetría)

### **Tema 10: CI/CD con GitHub Actions**
1. [Introducción a CI/CD y automatización de despliegues.](documentation/U5/U5-T10.md#st1-introducción-a-cicd-y-automatización-de-despliegues)
2. [Configuración de pipelines en GitHub Actions.](documentation/U5/U5-T10.md#st2-configuración-de-pipelines-en-github-actions)

### **Tema 11: Despliegue en la Nube**
1. [Introducción a opciones de despliegue en la nube.](documentation/U5/U5-T11.md#st1-introducción-a-opciones-de-despliegue-en-la-nube)
2. [Configuración de un servicio en Azure/AWS con contenedores Docker.](documentation/U5/U5-T11.md#st2-configuración-de-un-servicio-en-azureaws-con-contenedores-docker)
