**CLASE PROGRAMACIÓN MÓVIL**\
**25/02/2025**
------------------

[LINK MOCKUP DE FIGMA](https://www.figma.com/proto/2FoJHU0ptgUSoZIPwxJZbN/Untitled?page-id=0%3A1&node-id=5-2&p=f&viewport=213%2C171%2C0.26&t=BOZ5vijb18kJoHFF-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=5%3A2)
-----------------------------
[LINK DEL TABLERO DE TRELLO CON HISTORIAS DE USUARIO](https://trello.com/invite/b/67b4c77544e7adfe122f89b4/ATTI0805a302d13f25ffdb7e9baed89e09078FA4F3BD/actividad-trello-creacion-to-do-list)
-------------------------------
[LINK DE LA ACTIVIDAD EN FIGMA](https://www.figma.com/design/hL1jdounEnxs96sHhxR1pK/Untitled?node-id=0-1&t=XBFdimwZFFMZi4dA-1)
-------------------------------


### **ACTVIDADES Y AOUNTES DE CLASE**

- Revisar tableros de Trello.
- Resolver dudas sobre los tableros.

### **Conceptos Claves**

#### **Entendimiento de Negocio en un Proyecto**

Lo mínimo que debe tener un proyecto es una base de datos y una estructura de situaciones.

#### **Ejemplo de Entidad Cliente:**

```json
cliente {
    nombre,
    apellido,
    fecha_nacimiento,
    correo
}
```

#### **Buenas Prácticas**

- Análisis con profundidad.
- Diseño de sistemas.
- Comportamiento de módulos.

#### **Ejemplo de Módulos:**

- Inventario
- Facturación (POO)
- Parametrización
- Ventas
- Seguridad

### **Modelado de Datos**

- El modelo de datos debe ser incremental.
- Crear un diagrama de base de datos.
- Crear un diagrama de secuencias.

### **Arquitectura Limitada**

- Ejemplo: Nequi.
- Los datos básicos de una persona pueden servir para diferentes roles (empleado, auditor, etc.).
- Se permite la tercerización.

### **Parametrización**

- Modelo de datos con inserciones controladas.
- Ejemplos de parametrización:
  - Idioma
  - Jornadas
  - Horario
  - Agenda y reservas
- Segmentación de tiempo en la base de datos.

### **Historias de Usuario (HU) y Buenas Prácticas en Scrum**

#### **Ejemplo de Categoría:**

```json
Categoria {
    id (auto_increment),
    codigo (único),
    nombre (único),
    descripcion (opcional),
    estado (default 1)
}
```

### **Diseño de Tareas a Entregar**

Las tareas deben estar desglosadas para:

- Mockup
- Backend
- Frontend
- Base de datos
- DevOps
- Documentación

### **Estimación y Lista de Entrega**

#### **Historia de Usuario**

**Descripción:**\
Como administrador del sistema, quiero registrar, actualizar, eliminar y consultar categorías de productos, para gestionar eficientemente la organización de los productos dentro del sistema.

**Criterios de Aceptación:**

- **Registro de Categorías:**

  - Se debe permitir crear una nueva categoría con los campos:
    - `id` (generado automáticamente).
    - `codigo` (alfanumérico único).
    - `nombre` (obligatorio).
    - `descripcion` (opcional).
    - `estado` (activo/inactivo).

- **Edición de Categorías:**

  - Se debe permitir modificar el `nombre`, `descripcion` y `estado` de una categoría existente.
  - No se debe permitir modificar el `id` ni el `codigo` después de la creación.

- **Eliminación de Categorías:**

  - Se debe permitir eliminar una categoría si no está asociada a productos.

- **Consulta de Categorías:**

  - Se debe listar todas las categorías registradas.
  - Se debe permitir filtrar por `codigo` y `nombre`.

**Criterios de Finalización:**

- La funcionalidad está desarrollada y probada.
- El código está revisado y aprobado en una Pull Request.
- Se ha realizado una demostración al Product Owner y ha sido aprobada.
- La documentación y pruebas están actualizadas.
