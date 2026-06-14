# Symple3D v 1.1

Un visualizador y editor de modelos 3D basado en la web.

## Demo Online

Puedes probar una demostración en vivo de Symple3D en la siguiente dirección:

[symple3d.andromeda79.synology.me](http://symple3d.andromeda79.synology.me)

---

## Documentación

### Descripción

Symple3D es una herramienta online para la visualización y manipulación de modelos 3D. Permite cargar ficheros en formato STL, realizar operaciones booleanas (unión, sustracción, intersección) entre ellos y exportar el resultado.

### Manual de Usuario

-   **Cargar un modelo**: Utiliza el botón de carga o arrastra y suelta un fichero STL en la ventana.
-   **Mover, Rotar, Escalar**: Selecciona un objeto y utiliza los controles de transformación para manipularlo.
-   **Operaciones Booleanas**: Selecciona dos o más objetos y utiliza los botones de la barra de herramientas para realizar operaciones de unión, sustracción o intersección.
-   **Exportar**: Exporta la escena o el objeto seleccionado a formato STL.

### Despliegue

Para desplegar esta aplicación, solo necesitas un servidor web estático.

1.  Copia los ficheros `index.html` y `symple3d.html` a la raíz de tu servidor web.
2.  Copia el directorio `libreria` completo junto a los ficheros HTML.

La estructura de ficheros en el servidor debería ser similar a esta:

```
/
├── index.html
├── symple3d.html
└── libreria/
    ├── ... (todos los ficheros de la librería)
```

### Librerías Utilizadas

El proyecto se basa principalmente en las siguientes librerías:

-   **Three.js**: El motor principal para la renderización 3D en WebGL.
-   **ThreeCSG**: Para realizar las operaciones booleanas constructivas (Constructive Solid Geometry).
-   **dat.GUI**: Para la creación de la interfaz de usuario y controles.
-   **OrbitControls**: Para el control de la cámara en la escena 3D.
-   **STLExporter y STLLoader**: Para la importación y exportación de ficheros en formato STL.

## Autor

Wasx Alpha Software 1984, 2026
Programado por Rubén Pastor Villarrubia
