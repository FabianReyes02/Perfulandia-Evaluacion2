# 🧾 Proyecto: Transformación Digital - Perfulandia SPA


Este repositorio contiene el desarrollo técnico del sistema basado en microservicios para la empresa Perfulandia SPA, como parte de la Evaluación Parcial 2 de la asignatura **Desarrollo Full Stack I**.

## 📦 Descripción General del Proyecto

La empresa Perfulandia ha comenzado a abrir sedes en Concepción y Viña del Mar, expandiéndose en el negocio, por lo tanto quieren abrir aún más sedes, pero tienen un problema, este es que su actual sistema de software monolítico a empezado a limitarse. Mostrando problemas de rendimiento y disponibilidad que pone en riesgo las operaciones diarias y la satisfacción del cliente.

Para enfrentar esta problemática, el proyecto busca remplaazar el antiguo sistema monolítico por una arquitectura de microservicios, de esta forma Perfulandia podrá mejorar su rendimiento, disponibilidad y capacidad de respuesta ante el crecimiento del negocio, asegurando así la satisfacción del cliente además del éxito a largo plazo.

## 🧩 Arquitectura de Microservicios

> El sistema está estructurado por dos **microservicios**, llamados "usuarioservice" y "productservice" los cuales nos permiten manipular datos ya sean de los usuarios o los productos correspondientemente.

### Microservicios Desarrollados

- `usuarioservice`: > 📝 Nos permite manipular y almacenar distintos datos en la base de datos de los usuarios.
- `productservice`: > 📝 Nos permite manipular y almacenar distintos datos en la base de datos de los productos.

## 🛠️ Tecnologías Utilizadas

* Spring Boot
* Maven
* Postman
* GitHub
* Intellij
* Laragon

## 🗄️ Configuración de Bases de Datos

Utilizamos Laragon como base de datos, con el objetivo de verificar el correcto funcionamiento y poder almacenar y administrar todos los datos de nuestros microservicios.
Para conectar de forma correcta la base de datos, agregamos propiedades a "application.properties".

### Propiedades:

**spring.application.name:** Da nombre al microservicio.

![application name](https://github.com/user-attachments/assets/581f8eec-43a3-4ca8-8b31-824a9bde5e88)

**server.port:** El número del puerto en el que se ejecutará la aplicación.

![server port](https://github.com/user-attachments/assets/ab98275e-c580-416f-80f2-d5a702c4c479)

**spring.datasource.url:** Dirección URL para la conexión a la base de datos.

![spring datasource](https://github.com/user-attachments/assets/ea648c8c-3dba-4b8c-bb55-34bad61a8a9b)

**spring.datasource.username:** Indica el nombre de usuario para acceder a la base de datos.

![username](https://github.com/user-attachments/assets/f08301b6-e703-4528-8df0-a5ac07ca0e02)

**spring.datasource.password:** Indica la contraseña para acceder a la base de datos.

![password](https://github.com/user-attachments/assets/a874f193-a825-4f22-b85c-d8fce4da38f7)

**spring.jpa.hibernate.ddl-auto:** Indica cómo Hibernate tiene que manejar el esquema 

![hibernate](https://github.com/user-attachments/assets/47ba1461-5027-429f-8aa0-74ec4ae568e6)

**spring.jpa.show-sql:** Nos muestra las consultas SQL en la consola.

![true](https://github.com/user-attachments/assets/e87b2622-fd0c-4b97-b80b-1e02694739a7)

**hibernate.dialect:** Define el dialecto específico de la base de datos.

![dialect](https://github.com/user-attachments/assets/ff0e8e8d-ffd4-4bd6-8155-9ceeecc058ed)

## 📮 Endpoints y Pruebas

> 📝 Especificar los principales endpoints disponibles por microservicio (CRUD y llamadas entre servicios).  
> Incluir capturas o descripciones de pruebas realizadas con Postman (mínimo 3 por micro-servicio).

## 🧑‍💻 Integrantes del Equipo

| Nombre                  | Rol en el proyecto                | Servicio principal trabajado |
|-------------------------|-----------------------------------|------------------------------|
| Fabián Reyes            |  Backend - Pedido - Repositorio   | pedidoservice                |
| Matías Vargas           |  Backend - Productos - Pedido     | productoservice              |
| Martín Rivas            |  Backend - Pedido - Usuario       | usuarioservice               |

## 📂 Estructura del Repositorio

> Cada carpeta corresponde a un microservicio separado con su propio `pom.xml`, en este caso los microservicios son Usuario, Producto y un Pedido.

```

📦 perfulandia-microservices
├── usuarioservice
├── productoservice
├── pedidoservice 
└── README.md

```

## 👥 Colaboración en GitHub

> 📝 Explicar cómo se organizó el trabajo en ramas (`master`, `pruebas`), frecuencia de commits y cómo se coordinaron como equipo.

## 📈 Lecciones Aprendidas

> 📝 Reflexionar brevemente sobre qué aprendieron durante el desarrollo del proyecto (técnico y en trabajo en equipo).

---

[Guía Oficial en Notion – Evaluación Parcial 2 (35%)](https://quilt-canary-969.notion.site/Gu-a-Oficial-Evaluaci-n-Parcial-2-35-1f75b3c4e31280aaab79c9a71f1cfb7b?pvs=4)

