# Product Requirements Document (PRD) - Plataforma Gastronómica

## 1. Visión General del Proyecto
* **Nombre del Proyecto:** GastroGourmet / Web Gastronómica Premium
* **Objetivo:** Crear una plataforma web altamente visual, atractiva y responsiva para un restaurante de alta cocina, permitiendo a los usuarios explorar el menú, conocer al equipo y realizar reservas en línea.
* **Stack Tecnológico:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5.3+ (vía CDN oficial), FontAwesome 6+ (para iconografía culinaria).

## 2. Especificaciones de Diseño e Interfaz (Bootstrap 5)
* **Paleta de Colores:** Enfoque elegante y apetecible. Fondos oscuros (`bg-dark`), tonos crema (`#f8f9fa`), y acentos dorados/naranjas para botones de acción (`btn-warning` o clases personalizadas sobreescribiendo el tono primario).
* **Tipografía:** Combinación de una fuente Serif elegante para títulos (ej. Playfair Display) y Sans-Serif limpia para el cuerpo de texto (ej. Inter o Roboto).
* **Componentes Requeridos:**
  * **Navbar:** Transparente con efecto de desenfoque al inicio, volviéndose sólido (`bg-dark`) al hacer scroll. Debe incluir enlaces a: Inicio, Menú, Sobre Nosotros, Reservas.
  * **Sección Hero:** Imagen de fondo gastronómica en alta resolución a pantalla completa (`vh-100`), superposición oscura (`rgba(0,0,0,0.5)`), un eslogan impactante y un botón prominente: "Reservar Mesa".
  * **Sección Menú (Grid dinámica):** Uso de las pestañas dinámicas de Bootstrap (`nav-tabs` o `nav-pills`) para filtrar por categorías: Entradas, Platos Fuertes, Postres, Bebidas. Los platillos se mostrarán en tarjetas horizontales limpias (`card mb-3`) con precio destacado.
  * **Sección "Chef & Filosofía":** Layout de dos columnas (`row` con `col-lg-6`) que combine una imagen del chef en acción con texto narrativo sobre el origen de los ingredientes (concepto del huerto a la mesa).
  * **Formulario de Reservas:** Formulario interactivo con validación nativa de Bootstrap (`needs-validation`). Campos obligatorios: Nombre, Correo, Teléfono, Fecha, Hora y Número de comensales.

## 3. Requerimientos Estructurales del Repositorio
* `/index.html` -> Documento principal con la estructura semántica de la landing page.
* `/assets/css/restaurant-style.css` -> Estilos específicos (fuentes, overlays de imágenes y transiciones).

# Requirements - Proyecto Web con Bootstrap

## 1. Descripción del Proyecto
Desarrollo de un sitio web moderno, responsivo y visualmente atractivo utilizando **Bootstrap 5** para asegurar un diseño adaptable y profesional en cualquier dispositivo (móviles, tablets y escritorios).

## 2. Requisitos Técnicos
* **Framework CSS:** Bootstrap 5.3 (a través de CDN oficial).
* **Iconografía:** Bootstrap Icons (opcional pero recomendado para complementar la interfaz).
* **Estructura HTML5:** Semántica y accesible (`<header>`, `<main>`, `<section>`, `<footer>`).
* **Diseño Responsivo:** Uso del sistema de rejilla (*Grid System*) de Bootstrap, clases de utilidades de espaciado, flexbox y tipografía fluida.
* **Compatibilidad:** Navegadores modernos (Chrome, Firefox, Safari, Edge).

## 3. Secciones del Sitio Web
1. **Encabezado / Barra de Navegación (`Navbar`):** Menú responsivo con enlaces a las secciones principales y soporte para colapso en dispositivos móviles.
2. **Sección Principal / Héroe (`Hero Section`):** Título principal llamativo, subtítulo descriptivo y botones de llamada a la acción (*Call to Action*).
3. **Sección de Características / Servicios:** Tarjetas (`Cards`) estructuradas en rejilla para destacar los puntos clave o servicios ofrecidos.
4. **Sección de Contacto o Llamado Final:** Formulario estilizado con clases nativas de formularios de Bootstrap o sección informativa.