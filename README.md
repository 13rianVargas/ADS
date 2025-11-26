# Sistema de Información para una Biblioteca Universitaria

[![PlantUML](https://img.shields.io/badge/UML-PlantUML-blue)](https://plantuml.com/)
[![Academic](https://img.shields.io/badge/Type-Academic%20Project-green)](https://github.com/13rianVargas/ADS)

## 📋 Descripción

Este repositorio contiene el análisis funcional y diseño de un **Sistema de Información para una Biblioteca Universitaria** desarrollado como parte del curso de Análisis y Diseño de Software (ADS). El sistema está diseñado para gestionar una biblioteca central que atiende a más de 20,000 estudiantes y 1,500 profesores.

## 🎯 Objetivos del Sistema

- Mejorar la experiencia del usuario al facilitar la búsqueda, préstamo y devolución de libros
- Garantizar la integridad y seguridad de los datos de usuarios y recursos
- Permitir a los administradores generar reportes detallados sobre el uso de la biblioteca
- Reducir el tiempo y esfuerzo asociados con la gestión manual de recursos

## 📁 Estructura del Proyecto

```
ADS/
├── README.md
├── Caso de Estudio.txt          # Documento con los requerimientos del sistema
├── Aleja/                        # Diagramas contribuidos por Alejandra
│   ├── Use Case 1 - Diagrama de Actividad y Secuencia
│   ├── Use Case 3 - Diagrama de Actividad y Secuencia
│   ├── Use Case 5 - Diagrama de Actividad y Secuencia
│   └── Use Case 7 - Diagrama de Actividad y Secuencia
└── Brian/                        # Diagramas contribuidos por Brian
    ├── Diagrama de Clases
    ├── Diagrama de Despliegue
    ├── Diagrama de Estado (Clase Prestamo y Recurso)
    ├── Diagrama de Paquetes
    ├── Use Case 2 - Diagrama de Actividad y Secuencia
    ├── Use Case 4 - Diagrama de Actividad y Secuencia
    └── Use Case 6 - Diagrama de Actividad y Secuencia
```

## 📊 Diagramas UML

El proyecto incluye los siguientes tipos de diagramas en sintaxis PlantUML:

### Diagramas Estructurales
- **Diagrama de Clases**: Modelo del dominio con entidades como Usuario, Recurso, Préstamo, Reserva, etc.
- **Diagrama de Paquetes**: Organización del código siguiendo arquitectura MVC + DAO
- **Diagrama de Despliegue**: Arquitectura del sistema incluyendo servidores, bases de datos y kioscos

### Diagramas de Comportamiento
- **Diagramas de Actividad**: Flujos de trabajo para los casos de uso principales
- **Diagramas de Secuencia**: Interacciones entre componentes del sistema
- **Diagramas de Estado**: Estados de las clases Préstamo y Recurso

## 🏗️ Arquitectura

El sistema sigue el patrón **MVC (Model-View-Controller)** con una capa de acceso a datos (**DAO**):

- **Model**: Entidades del dominio (Usuario, Recurso, Préstamo, Reserva, etc.)
- **View**: Interfaces de usuario (Web y Móvil)
- **Controller**: Lógica de negocio y orquestación
- **DAO**: Acceso a la base de datos

### Integraciones Externas
- **Sistema Proteus**: Sistema financiero de la universidad para gestión de multas
- **Biblioteca Luis Ángel Arango**: API para búsqueda y reserva de libros externos

## ✨ Funcionalidades Principales

- 📚 Búsqueda de recursos por título, autor, palabra clave o ISBN
- 📱 Escaneo de código de barras/RFID desde aplicación móvil
- 📖 Gestión de préstamos y devoluciones
- 🔔 Notificaciones automáticas sobre fechas de devolución
- 📍 Mapa interactivo para ubicación física de recursos
- ⭐ Sistema de calificaciones y reseñas
- 🏢 Reserva de salas de estudio
- 📥 Descarga de recursos digitales
- 🤖 Kioscos de devolución automática con RFID

## 🛠️ Tecnologías

| Componente | Tecnología |
|------------|------------|
| Diagramas UML | PlantUML |
| Arquitectura | MVC + DAO |
| Comunicación | API REST, HTTPS |
| Base de Datos | JDBC |
| Seguridad | SSL/TLS |

## 👥 Contribuidores

| Nombre | Rol |
|--------|-----|
| **Alejandra** | Diagramas de Actividad y Secuencia (Use Cases 1, 3, 5, 7) |
| **Brian** | Diagramas de Clases, Despliegue, Estado, Paquetes y Casos de Uso (2, 4, 6) |

## 📄 Licencia

Este proyecto es desarrollado con fines académicos como parte del curso de Análisis y Diseño de Software.

---

*Desarrollado en la Fundación Universitaria Konrad Lorenz*