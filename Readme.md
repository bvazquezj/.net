
# ProyectoCalificaciones

Este es un proyecto realizado en .NET para la clase de Primer Parcial. El proyecto tiene como objetivo gestionar calificaciones de estudiantes, mostrando estadísticas y datos relevantes mediante gráficos y tablas interactivas.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

```
PrimerParcial/
│
└── proyecto/
    └── ProyectoCalificaciones/
        ├── (Archivos del proyecto .NET)
        ├── wwwroot/
        │   ├── css/
        │   │   └── (Archivos de Tailwind CSS)
        ├── js/
        │   ├── (Archivos de Tabulator y Chart.js)
        └── (Otros archivos del proyecto)
```

## Requerimientos

- .NET 6 o superior
- Navegador compatible con JavaScript moderno

## Dependencias

El proyecto utiliza las siguientes bibliotecas:

- **Tailwind CSS**: Para el diseño y estilización de la interfaz.
- **Tabulator**: Para la creación de tablas interactivas de calificaciones.
- **Chart.js**: Para la visualización de gráficos de calificaciones.

## Instalación

1. **Clonar el repositorio**:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd PrimerParcial/proyecto/ProyectoCalificaciones
   ```

2. **Compilar y ejecutar el proyecto**:

   Para compilar y ejecutar el proyecto, usa el siguiente comando desde la raíz del proyecto:

   ```bash
   dotnet run
   ```

   Esto iniciará el servidor y podrás acceder a la aplicación en tu navegador.

   puede que no se carguen los estilos si no se tiene Node.js instalado en tu sistema.

   En caso de que no se carguen los estilos, puedes instalar Node.js desde [https://nodejs.org](https://nodejs.org).

   ejecutar el comando 
   ``` bash
    npm install
   ```

## Uso

1. **Interfaz de Usuario**:
    - se muestra una pantalla de inicio con un menú de opciones para acceder a diferentes secciones del proyecto.
    -La seccion de Dashboard muestra graficas de estudiantes y datos relevantes.
    - La seccion de Estadisticas muestra estadisticas de calificaciones de estudiantes.
    - La seccion de Alumnos muestra una lista de alumnos con sus respectivas calificaciones.
    - La seccion de Calificaciones muestra un error aun no esta implementado.
    - La seccion de Ingresar muestra un error aun no esta implementado.
    - La seccion de Registrarse muestra un error aun no esta implementado.

## Contribución

Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una rama para tu contribución (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y realiza un commit (`git commit -am 'Agregada nueva funcionalidad'`).
4. Haz un push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT.

## Agradecimientos

- **Tailwind CSS**: [https://tailwindcss.com](https://tailwindcss.com)
- **Tabulator**: [https://tabulator.info](https://tabulator.info)
- **Chart.js**: [https://www.chartjs.org](https://www.chartjs.org)
