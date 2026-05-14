# Sistema de Gestión de Facturas, Cotizaciones y Órdenes

Sistema web desarrollado para apoyar la administración de cotizaciones, órdenes de compra y facturas de una empresa. El proyecto permite registrar, consultar, visualizar y organizar documentos administrativos relacionados con clientes, empresas y procesos internos.

## Descripción

Este sistema fue desarrollado para la empresa **Torres de Enfriamiento MN** con el objetivo de facilitar la gestión de documentos como cotizaciones, órdenes y facturas.

La aplicación cuenta con una pantalla de inicio de sesión, una página principal para visualizar registros, filtros por empresa y una vista de detalles donde se muestra la información completa de cada documento. Además, permite asociar archivos en formato PDF o imagen a cada registro.

El proyecto fue realizado como trabajo colaborativo y está enfocado en resolver una necesidad real de organización documental dentro de un entorno empresarial.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- Supabase
- Supabase Database
- Supabase Storage

## Funcionalidades principales

- Inicio de sesión visual para acceso al sistema.
- Consulta de registros en una tabla principal.
- Filtro de registros por empresa.
- Registro de cotizaciones, órdenes y facturas.
- Visualización detallada de cada documento.
- Carga y previsualización de archivos PDF o imágenes.
- Identificación de documentos por número y fecha.
- Control de estado de orden recibida.
- Registro de estado de factura pagada.
- Edición de información registrada.
- Eliminación de registros.
- Almacenamiento de archivos mediante Supabase Storage.

## Páginas del sistema

### Inicio de sesión

Pantalla inicial del sistema, donde el usuario ingresa su nombre y contraseña para acceder.

### Página principal

Vista general donde se muestran los registros en una tabla. Incluye información como:

- Fecha de cotización.
- Número de cotización.
- Concepto de cotización.
- Empresa.
- Filtro por empresa.
- Botones para ver detalles, eliminar o crear registros.

### Página de detalles

Vista donde se muestra la información completa del registro seleccionado. Está organizada en secciones como:

- Cotización.
- Orden.
- Factura.

Cada sección puede incluir datos del documento y archivos relacionados en formato PDF o imagen.

## Estructura general del proyecto

sistema-facturas-supabase/
│
├── index.html
├── Facturas1.html
├── detalles.html
├── config.example.js
├── .gitignore
├── css/
├── js/
├── imgs/
└── README.md

## Base de datos

El sistema fue diseñado para trabajar con una tabla principal en Supabase. Los registros almacenan información relacionada con documentos administrativos de la empresa.

Algunos campos contemplados son:

- Número de cotización.
- Fecha de cotización.
- Concepto.
- Empresa.
- Número de orden.
- Fecha de orden.
- Estado de orden recibida.
- Número de factura.
- Fecha de factura.
- Estado de factura pagada.
- Archivo de cotización.
- Archivo de orden.
- Archivo de factura.

## Almacenamiento de archivos

El sistema utiliza Supabase Storage para almacenar documentos relacionados con cada registro, como:

- Cotizaciones.
- Órdenes de compra.
- Facturas.
- Documentos en PDF.
- Imágenes de respaldo.

## Seguridad y configuración

Por seguridad, este repositorio no incluye credenciales reales de Supabase ni datos privados de la empresa.

Para ejecutar el proyecto con conexión a base de datos, se debe crear un archivo local de configuración basado en:

config.example.js

Ejemplo:

const SUPABASE_URL = "TU_SUPABASE_URL";
const SUPABASE_KEY = "TU_SUPABASE_ANON_KEY";

El archivo con credenciales reales debe mantenerse fuera del repositorio público.

## Trabajo en equipo

Este proyecto fue desarrollado de manera colaborativa, asignando responsabilidades específicas a cada integrante del equipo. La organización del trabajo permitió dividir las tareas de análisis, diseño, programación, captura de información y desarrollo general del sistema.

## Roles del equipo

- **Nery** — Líder y Analista  
  Encargado de coordinar el proyecto, analizar las necesidades del sistema y apoyar en la organización general del trabajo.

- **Sergio** — Capturista  
  Encargado de apoyar en la captura, revisión y organización de información necesaria para el funcionamiento del sistema.

- **Marcos** — Programador  
  Encargado de desarrollar la lógica del sistema, implementar funcionalidades con JavaScript y apoyar en la conexión con Supabase.

- **Efraín** — Diseñador  
  Encargado de apoyar en el diseño visual, estilo de la interfaz y presentación del sistema.

- **Diego** — Desarrollador  
  Encargado de apoyar en el desarrollo de páginas, estructura del proyecto y funcionamiento general del sistema.

## Mi participación

Mi participación principal dentro del proyecto fue como **Programador**. Me encargué de apoyar en el desarrollo de la lógica del sistema, la implementación de funciones con JavaScript, la conexión con Supabase y el manejo de registros relacionados con cotizaciones, órdenes y facturas.

También participé en pruebas de funcionamiento, corrección de errores y ajustes para que el sistema pudiera consultar, registrar, visualizar y administrar la información de manera correcta.

## Créditos

Proyecto desarrollado en equipo para una empresa real como parte de una actividad académica/práctica.

Integrantes del equipo:

- Nery — Líder y Analista
- Sergio — Capturista
- Marcos — Programador
- Efraín — Diseñador
- Diego — Desarrollador

## Aprendizajes obtenidos

Durante el desarrollo de este proyecto se reforzaron conocimientos sobre:

- Desarrollo web con HTML, CSS y JavaScript.
- Organización de información administrativa.
- Conexión de un frontend con una base de datos externa.
- Uso de Supabase como backend.
- Almacenamiento de archivos en la nube.
- Manejo de documentos PDF e imágenes.
- Diseño de interfaces para sistemas administrativos.
- Trabajo colaborativo en un proyecto con aplicación real.

## Estado del proyecto

Proyecto funcional en etapa de mejora.

Actualmente el sistema permite consultar, registrar, visualizar y administrar documentos relacionados con facturas, cotizaciones y órdenes. Sin embargo, puede seguir optimizándose en seguridad, responsividad, validaciones y experiencia de usuario.

## Mejoras futuras

- Mejorar la responsividad para celulares y tablets.
- Implementar autenticación real de usuarios.
- Agregar roles y permisos según tipo de usuario.
- Mejorar las validaciones de formularios.
- Optimizar la previsualización de archivos PDF.
- Agregar búsqueda avanzada por empresa, fecha o estado.
- Crear reportes o exportaciones de información.
- Mejorar la organización del código JavaScript.
- Agregar historial de cambios por registro.
- Proteger mejor las rutas y credenciales del sistema.

## Nota

Este repositorio fue preparado para fines de portafolio.  
Las credenciales reales de Supabase, archivos privados y datos sensibles de la empresa no se incluyen por seguridad.
