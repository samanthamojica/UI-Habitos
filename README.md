# UI-Habitos

Aplicación Angular para el seguimiento y gestión de hábitos.

## Requisitos previos

- [Node.js](https://nodejs.org/) (versión LTS recomendada)
- [Angular CLI](https://angular.dev/tools/cli) instalado globalmente:

  ```bash
  npm install -g @angular/cli
  ```

## Instalación

```bash
npm install
```

## Servidor de desarrollo

Ejecuta el siguiente comando para iniciar un servidor de desarrollo local:

```bash
ng serve
```

Una vez que el servidor esté en ejecución, abre tu navegador en `http://localhost:4200/`. La aplicación se recargará automáticamente cada vez que modifiques alguno de los archivos fuente.

## Generación de código

Angular CLI incluye herramientas para generar código. Para generar un nuevo componente, ejecuta:

```bash
ng generate component nombre-del-componente
```

Para ver la lista completa de esquemas disponibles (como `components`, `directives` o `pipes`), ejecuta:

```bash
ng generate --help
```

## Compilación

Para compilar el proyecto ejecuta:

```bash
ng build
```

Esto compilará el proyecto y almacenará los artefactos de compilación en el directorio `dist/`. Por defecto, la compilación de producción optimiza la aplicación para rendimiento y velocidad.

## Ejecución de pruebas unitarias

Para ejecutar pruebas unitarias con el framework de pruebas [Karma](https://karma-runner.github.io), usa el siguiente comando:

```bash
ng test
```

## Ejecución de pruebas end-to-end

Para pruebas end-to-end (e2e), ejecuta:

```bash
ng e2e
```

Angular CLI no incluye un framework de pruebas end-to-end por defecto. Puedes elegir el que se ajuste a tus necesidades.

## Recursos adicionales

Para más información sobre el uso de Angular CLI, incluyendo referencias detalladas de comandos, visita la página [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli).
