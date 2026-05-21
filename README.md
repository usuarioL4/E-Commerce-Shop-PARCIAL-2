# E-Commerce Shop

## Descripción

E-Commerce Shop es una plataforma de tienda virtual adaptable a distintos tipos de negocios y categorías de productos. El proyecto fue desarrollado con una arquitectura basada en microservicios, permitiendo una estructura escalable, modular y fácil de mantener.

La aplicación no está enfocada en un único rubro o género comercial, por lo que puede utilizarse como base para tiendas de tecnología, ropa, accesorios, productos digitales, artículos para el hogar y más.

El objetivo principal del proyecto es ofrecer una solución flexible para la gestión de productos, clientes, autenticación, inventario, pagos y pedidos dentro de un entorno de comercio electrónico moderno.

---

## Características Principales

* Arquitectura basada en microservicios.
* Gestión de autenticación y usuarios.
* Administración de productos y catálogo.
* Gestión de inventario.
* Carrito de compras.
* Gestión de pedidos.
* Sistema de pagos.
* Estructura adaptable para múltiples tipos de tiendas.
* Backend desarrollado con Spring Boot.
* Integración con base de datos relacional.

---

## Arquitectura del Proyecto

El sistema está dividido en múltiples servicios independientes:

### Microservicios

* **auth-service** → Manejo de autenticación y seguridad.
* **catalog-service** → Gestión del catálogo de productos.
* **customer-service** → Administración de clientes.
* **inventory-service** → Control de stock e inventario.
* **cart-service** → Gestión del carrito de compras.
* **order-service** → Procesamiento de pedidos.
* **payment-service** → Gestión de pagos.
* **product-service** → Administración de productos.

---

## Tecnologías Utilizadas

### Backend

* Java
* Spring Boot
* Maven

### Base de Datos

* MySQL

### Control de Versiones

* Git
* GitHub

---

## Instalación y Ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/e-commerce-shop.git
```

### 2. Entrar al proyecto

```bash
cd e-commerce-shop
```

### 3. Ejecutar los microservicios

Cada servicio puede ejecutarse individualmente usando Maven:

```bash
mvn spring-boot:run
```

O ejecutando la clase principal de Spring Boot desde tu IDE.

---

## Objetivo del Proyecto

Este proyecto fue desarrollado con fines académicos y prácticos, aplicando conceptos de:

* Arquitectura de microservicios.
* Desarrollo backend con Spring Boot.
* Separación de responsabilidades.
* Escalabilidad de sistemas.
* Gestión modular de servicios.

---

## Integrantes

* Jerson Pedreros
* Eduardo
* Edward

---

## Estado del Proyecto

Proyecto en desarrollo y mejora continua.

---

## Licencia

Este proyecto es de uso académico y educativo.

## importante
no tuvimos tiempo para terminar los 10 microservicios, crear el gateway, evidenciar cambios en github ni logs, lo lamentamos demasiado :(
