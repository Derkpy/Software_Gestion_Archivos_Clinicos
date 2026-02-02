# 🏥 Gestor de Archivos Clínicos
**Gestor_Archivos_Clinicos** es una plataforma de escritorio diseñada para consultorios médicos privados. Permite la digitalización completa del flujo de trabajo de un médico general, desde el registro de pacientes hasta la emisión y personalización de recetas médicas.
## 🚀 Características Principales
- **Gestión de Pacientes:** Registro detallado con generación automática de IDs únicos.
<img width="320" height="400" alt="image" src="https://github.com/user-attachments/assets/167fe91a-8b32-433b-87a4-1aeb147c7539" />

- **Historial Clínico:** Seguimiento de consultas anteriores para facilitar el diagnóstico y tratamiento continuo.

- **Sistema de Recetas:** Generación, descarga e impresión de recetas médicas personalizadas.
<img width="446" height="284" alt="image" src="https://github.com/user-attachments/assets/e91b68b3-2caf-434d-a8dc-e396c23c080f" />

  
- **Módulo del Doctor:** Perfil personalizable que incluye datos del profesional y carga de logotipo para la receta.
<img width="340" height="250" alt="image" src="https://github.com/user-attachments/assets/d6e000c3-1f5f-4c75-a841-a6e1a8027a10" />

  
- **Búsqueda:** Filtros y edición rápida de registros existentes.

<img width="430" height="310" alt="image" src="https://github.com/user-attachments/assets/caf4596b-b526-4cb4-ae5b-67b91069894a" />

## 🏗️ Arquitectura y Diseño
El proyecto sigue un patrón **MVC (Model-View-Controller)** para garantizar la separación de responsabilidades:

<img width="450" height="350" alt="image" src="https://github.com/user-attachments/assets/bba2b290-70e2-4f26-b724-863388bd0c6f" />


- **`ui`:** Interfaz gráfica construida con **Java Swing** y NetBeans GUI Builder.
- **`logic`:** Controladores y reglas de negocio que orquestan el flujo de datos.
- **`data`:** Capa de persistencia enfocada a la gestión de datos.
- **`util`:** Componentes técnicos:
  - `WindowsManager`: Coordinador centralizado de navegación entre vistas.
  - `Session`: Gestor de estado de inicio de sesión y autenticación.
  - `closeListeners`: Manejo los listeners/eventos.
## 🛠️ Tech Stack
- **Lenguaje:** Java 21 (LTS)
- **Interfaz:** Java Swing (Flat Design / Native components)
- **Base de Datos:** SQLite (Base de datos local embebida de alta portabilidad)
- **Gestión de Dependencias:** Maven
- **IDE Recomendado:** Apache NetBeans / IntelliJ IDEA
## 📋 Instalación y Uso
1. **Clonar el repositorio:** `git clone https://github.com/Derkpy/Gestor_Archivos_Clinicos.git`
2. **Importar:** Abre la carpeta del proyecto en tu IDE favorito (debe detectar el `pom.xml`).
3. **Construir:** Ejecuta `mvn clean install` para descargar dependencias y compilar.
4. **Ejecutar:** Inicia la aplicación desde la clase principal en el paquete `app`.
---
## 👤 Autor
- **Derek ([Derkpy](https://github.com/Derkpy))** - *Arquitectura y Desarrollo Integral*
*"Optimizando la gestión médica mediante software eficiente y organizado."*
