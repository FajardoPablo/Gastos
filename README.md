# Aplicación de Control de Gastos Domésticos

Este proyecto consiste en una aplicación web para la gestión de gastos domésticos, implementada en Java utilizando tecnologías como JSP, Servlets y MySQL, y siguiendo el patrón de diseño Modelo-Vista-Controlador (MVC).

## Índice

1. [Descripción General](#descripción-general)
2. [Requisitos](#requisitos)
3. [Funcionalidades](#funcionalidades)
4. [Contribuidores](#contribuidores)
   
## Descripción General
La aplicación permite:
- Gestión de usuarios: Login y logout.
- Gestionar tiendas y compras realizadas.
- Visualizar informes de compras por mes.
- Controlar el acceso mediante un sistema de autenticación.
- Realizar operaciones CRUD en tiendas y compras.

Se utiliza una base de datos MySQL con conexión gestionada a través de un Pool de Conexiones.

## Requisitos

- **Lenguaje**: Java 8+
- **Frameworks y Tecnologías**: Servlets, JSP, HTML, CSS, MySQL.
- **Entorno**: Máquina virtual Linux para el despliegue final

## Funcionalidades

- **Login:**
    sistema de autenticación de usuarios con validación y mensajes de error.
- **Pantalla Principal:**
    listado de compras del mes actual, con opciones para editar o eliminar.
    Acceso a la gestión de tiendas y a los informes.
- **CRUD de Compras:**
    alta, edición, y eliminación de compras con validaciones en cada operación.
- **CRUD de Tiendas:**
    gestión de tiendas mediante un sistema de alta, edición y eliminación.
- **Informes:**
    generación de informes basados en un mes y año específicos.
- **Logout:**
    cierre de sesión seguro y redirección a la página de inicio.
  
## Contribuidores

- [Ismael EL Younsi](https://github.com/IsmaelYM)
- [Pablo Fajardo](https://github.com/FajardoPablo)

---

## English Version

# Household Expense Management Application

This project is a web application designed for managing household expenses, implemented in Java using technologies such as JSP, Servlets, and MySQL, and following the Model-View-Controller (MVC) design pattern.

## Table of Contents

1. [Overview](#overview)
2. [Requirements](#requirements)
3. [Features](#features)
4. [Contributors](#contributors)

## Overview
The application allows you to:
- Manage users: Login and logout.
- Manage stores and recorded purchases.
- View purchase reports by month.
- Control access through an authentication system.
- Perform CRUD operations on stores and purchases.

It uses a MySQL database managed through a Connection Pool.

## Requirements

- **Language**: Java 8+
- **Frameworks and Technologies**: Servlets, JSP, HTML, CSS, MySQL.
- **Environment**: Linux virtual machine for final deployment.

## Features

- **Login:** authentication system for users with validation and error messages.
- **Main Screen:** a list of the current month's purchases, with options to edit or delete. Access to store management and reports.
- **Purchase CRUD:** create, update, and delete purchases with validations for each operation.
- **Store CRUD:** manage stores through a system for adding, editing, and deleting.
- **Reports:** generate reports based on a specific month and year.
- **Logout:** secure logout and redirection to the home page.

## Contributors

- [Ismael EL Younsi](https://github.com/IsmaelYM)
- [Pablo Fajardo](https://github.com/FajardoPablo)
