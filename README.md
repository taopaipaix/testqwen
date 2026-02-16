# Aplicación Web de Contactos

Aplicación web simple de contactos que consta de:
- Frontend: HTML, CSS, JavaScript Vanilla
- Backend: Spring Boot con Java 1.8

## Estructura del Proyecto
```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── example/
│   │           └── contactapp/
│   │               ├── ContactAppApplication.java
│   │               ├── controller/
│   │               │   └── ContactController.java
│   │               ├── model/
│   │               │   └── Contact.java
│   │               └── service/
│   │                   └── ContactService.java
│   ├── resources/
│   │   └── application.properties
│   └── webapp/
│       └── index.html
└── pom.xml
```

## Características
- API REST para manejo de contactos
- Interfaz web sencilla para visualizar y gestionar contactos
- Operaciones CRUD básicas

## Configuración
1. Asegúrate de tener Java 1.8 y Maven instalados
2. Ejecuta `mvn spring-boot:run` para iniciar la aplicación
3. Accede a `http://localhost:8080`