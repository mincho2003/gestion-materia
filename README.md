# Gestión de Materias

## Descripción
Esta aplicación permite gestionar materias y almacenar información como nombre de la materia y cantidad de alumnos, usando un backend básico en Node.js sin Express.

## Casos de Prueba

### Prueba 1: Obtener todas las materias
- **Método**: GET
- **Ruta**: `/api/materias`
- **Respuesta esperada**: Lista de materias en formato JSON.

### Prueba 2: Agregar una nueva materia
- **Método**: POST
- **Ruta**: `/api/materias`
- **Cuerpo**:
  ```json
  {
    "nombre": "Matemáticas",
    "cantidadAlumnos": 30
  }
