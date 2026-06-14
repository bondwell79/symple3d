# Despliegue de Symple3D

Para desplegar esta aplicación, solo necesitas un servidor web estático.

## Instrucciones

1.  Asegúrate de tener los dos ficheros HTML: `index.html` y `symple3d.html`.
2.  Copia el directorio `libreria` completo en el mismo lugar donde se encuentran los ficheros HTML.

La estructura de ficheros en tu servidor debería ser la siguiente:

```
/ (directorio raíz de tu web)
├── index.html
├── symple3d.html
└── libreria/
    ├── dat.gui.min.js
    ├── OrbitControls.js
    ├── stats.min.js
    ├── STLExporter.js
    ├── three-csg-ts.js
    ├── three.min.js
    ├── ThreeCSG.js
    ├── fontawesome/
    │   └── ...
    └── three/
        └── ...
```

Una vez que los ficheros estén en su sitio, puedes acceder a la aplicación a través del fichero `index.html` en tu navegador.
