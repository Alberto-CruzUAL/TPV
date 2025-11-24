# TPV

# 🍽️ TPV System - Gestión de Restaurante

![Estado del Proyecto](https://img.shields.io/badge/Estado-Desarrollo-success)
![Tech Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20JS%20%7C%20Node.js-blue)

Sistema de Terminal Punto de Venta (TPV) personalizado, desarrollado para optimizar la gestión de pedidos y cobros en un entorno de hostelería.

## 📖 Contexto del Proyecto

Durante mi experiencia laboral en el sector servicios, identifiqué ineficiencias en el flujo de comunicación entre la sala y la cocina, así como en el cálculo manual de las cuentas.

Como iniciativa personal para resolver este problema de ingeniería de procesos, desarrollé este software que permite:
1.  **Digitalizar la toma de comandas** para eliminar errores humanos.
2.  **Automatizar cálculos** financieros y de stock.
3.  **Gestionar la impresión** de tickets diferenciados .

## 🚀 Funcionalidades Principales

El sistema está diseñado para ser rápido, táctil y fácil de usar:

* **Gestión Visual de Mesas:** Interfaz gráfica para seleccionar mesas activas y gestionar múltiples pedidos simultáneamente.
* **Carta Digital Dinámica:** Base de datos de productos categorizada (Entrantes, Carnes, Bebidas, etc.) con precios modificables.
* **Lógica de "Carrito":**
    * Adición y eliminación de items en tiempo real.
    * Cálculo automático de totales.
* **Sistema de Impresión Dual:**
    * 🎫 **Ticket Cliente:** Resumen de cuenta formateado.
    * 👨‍🍳 **Ticket Cocina:** Comanda simplificada solo con la información relevante para la preparación de platos.
* **Backend Ligero:** Integración con **Node.js** y **SQLite** para el almacenamiento de datos (según dependencias del proyecto).

## 🛠️ Tecnologías Utilizadas

### Frontend
* **HTML5 & CSS3:** Diseño responsivo utilizando *CSS Grid* y *Flexbox* para adaptarse a pantallas táctiles. Uso de variables CSS para una gestión eficiente de estilos.
* **Vanilla JavaScript:** Lógica de negocio ejecutada en el cliente para asegurar máxima velocidad de respuesta sin depender de frameworks pesados.

### Backend
* **Node.js (Express):** Servidor para gestionar las peticiones.
* **SQLite3:** Base de datos relacional ligera para persistencia de información.

## 📸Interfaz del TPV desarrollado en html
<img width="1854" height="917" alt="image" src="https://github.com/user-attachments/assets/25d0d82a-49b2-4809-980a-54f702efbd8e" />


## 🔧 Instalación y Uso

Para probar el proyecto en local:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)
    ```
2.  **Instalar dependencias:**
    ```bash
    npm install
    ```
3.  **Ejecutar el servidor:**
    ```bash
    node index.js
    ```
4.  **Acceder:** Abrir `http://localhost:3000` en el navegador.

---
**Autor:** [Alberto Cruz Garcia] 
