# Mule ESB Useful Templates

Este repositorio contiene una colección de plantillas y ejemplos prácticos para **Mule ESB 3.x**. Estas plantillas están diseñadas para facilitar la implementación de patrones de integración comunes y configuraciones avanzadas dentro del ecosistema Mule Runtime.

## 🚀 Contenido del Repositorio

El proyecto se divide en diferentes módulos que cubren diversas áreas de integración:

*   **`componente-message-interceptor`**: Ejemplo de cómo interceptar mensajes a nivel de componente.
*   **`endpoint-message-interceptor`**: Implementación de interceptores de mensajes para endpoints.
*   **`my_mule_domain_project`**: Plantilla para la creación de proyectos de dominio compartidos.
*   **`several-output-file`**: Ejemplo de flujo que genera múltiples archivos de salida.
*   **`simple-json-groovy`**: Manipulación y transformación de datos JSON utilizando Groovy.
*   **`simple-spring-mule-integration`**: Integración robusta entre Spring Framework y Mule ESB.
*   **`simple-xml-to-json`**: Transformación básica de mensajes XML a formato JSON.
*   **`simple_xml_to_json_with_quartz`**: Ejemplo de transformación XML a JSON disparada por un planificador Quartz.

## 🛠️ Prerrequisitos

Para ejecutar y modificar estas plantillas, se recomienda el siguiente entorno:

*   **Mule Runtime**: 3.7.0 o superior (versiones 3.x).
*   **Anypoint Studio**: Versión 6.x (compatible con Mule 3).
*   **Maven**: 3.3.x o superior para la gestión de dependencias.
*   **Java JDK**: 1.7 o 1.8 (dependiendo de la versión exacta de Mule 3).

## 📥 Cómo Usar

1.  **Clonar el repositorio**:
    ```bash
    git clone https://github.com/jorgecb0991/mule-esb-usefull-templates.git
    ```
2.  **Importar en Anypoint Studio**:
    *   Ir a `File` -> `Import`.
    *   Seleccionar `Anypoint Studio` -> `Maven-based Mule Project from pom.xml`.
    *   Navegar hasta la carpeta de la plantilla deseada y seleccionar el archivo `pom.xml`.
3.  **Configurar Variables**:
    *   Asegúrate de revisar los archivos `.xml` y `.properties` de cada flujo para ajustar las rutas de archivos (ej. `F:\prueba`) a rutas existentes en tu sistema operativo local.

## 🔒 Seguridad y Configuración Profesional

*   Se ha incluido un archivo `.gitignore` optimizado para evitar la carga de archivos temporales de Maven y metadatos de Anypoint Studio.
*   No se han modificado las lógicas originales para garantizar la compatibilidad con las librerías antiguas mencionadas.
*   Los ejemplos utilizan rutas de referencia y no contienen credenciales ni datos sensibles.

## ✒️ Autor

*   **Jorge** - *Desarrollador Mule ESB*

---
> [!NOTE]
> Este proyecto es de carácter educativo y sirve como referencia rápida para implementaciones en versiones heredadas (Legacy) de Mule ESB.
