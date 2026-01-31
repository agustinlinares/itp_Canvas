📓 Cuaderno del Proyecto — Plataforma de acompañamiento laboral

Repositorio que contiene una aplicación web estática diseñada para documentar y presentar una idea de negocio, su Producto Mínimo Viable (MVP) y su Modelo Canvas, utilizando un diseño minimalista tipo cuaderno.

El proyecto prioriza la claridad estructural, la legibilidad y la entregabilidad académica, evitando dependencias externas y frameworks.

📌 Descripción general

La aplicación implementa un documento navegable en formato web que simula un cuaderno físico, integrando:

Contenido conceptual del proyecto

Navegación interna por secciones

Estética de documento impreso

Separación clara entre estructura, estilo y datos

Está orientada a presentaciones académicas, prototipos conceptuales y documentación inicial de proyectos.

🎯 Objetivo funcional

El objetivo de la aplicación es exponer de forma estructurada una plataforma de acompañamiento laboral cuyo propósito es:

Reducir la desorientación laboral y administrativa

Facilitar la comprensión de derechos y opciones laborales

Apoyar la toma de decisiones mediante información clara y guiada

Desde el punto de vista técnico, el objetivo es demostrar:

Organización semántica del contenido

Diseño UI sin dependencias

Separación de responsabilidades (HTML / CSS / JS)

Navegación ligera sin frameworks

🧩 Estructura funcional

La aplicación se organiza en las siguientes vistas:

1. Portada

Metadatos académicos

Resumen ejecutivo del proyecto

Accesos a secciones principales

2. Idea de negocio

Problema

Objetivos

Propuesta de solución

Público objetivo

Modelo de negocio

3. Producto Mínimo Viable (MVP)

Componentes funcionales mínimos

Tabla descriptiva de funcionalidades

Criterios de validación inicial

4. Modelo Canvas

Representación de los 9 bloques del modelo de negocio

Disposición en rejilla

Enfoque iterativo (versión inicial)

La navegación entre vistas se realiza mediante hash routing (#/idea, #/mvp, etc.).

🧠 Arquitectura técnica
Enfoque

Single Page Application (SPA) sin framework

Renderizado dinámico mediante JavaScript vanilla

Router simple basado en window.location.hash

Componentes principales

cuaderno.html

Estructura del documento

Contenido

Router y renderizado de vistas

cuaderno.css

Estilos globales

Diseño tipo cuaderno

Responsive básico

No se utilizan librerías externas ni herramientas de build.

🎨 Diseño y UX

El diseño simula un cuaderno físico, incorporando:

Fondo tipo papel

Líneas horizontales sutiles

Margen interior de encuadernación

Perforaciones laterales simuladas

Tipografía serif orientada a lectura prolongada

Navegación no intrusiva

El objetivo del diseño es favorecer la lectura y comprensión, no la interacción compleja.

📁 Estructura del repositorio

/
├── cuaderno.html     # Documento principal (estructura, vistas y router)
├── cuaderno.css      # Estilos unificados tipo cuaderno
├── App.html          # Versión académica previa (referencia)
├── App.css           # Estilos académicos base
├── producto.html     # Prototipo inicial del diseño
└── README.md         # Documentación técnica del proyecto

🛠️ Tecnologías utilizadas

HTML5

CSS3

JavaScript (ES6, sin frameworks)

📚 Contexto de uso

Este proyecto está diseñado para:

Entregas académicas

Documentación de ideas de negocio

Prototipos conceptuales

Presentación estructurada de proyectos sociales o educativos

Puede ampliarse con:

Validación de hipótesis

Métricas

Formularios

Persistencia de datos

Exportación a PDF

👤 Autor

Agustín Linares Carrera
Asignatura: Itinerario personal para la empleabilidad II
Fecha: 31/01/2026
