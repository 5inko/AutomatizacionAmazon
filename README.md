﻿# Automatización carrito de compras amazon

## Requisitos del Entorno

Asegúrate de tener las siguientes herramientas instaladas antes de ejecutar el proyecto:

- [Gradle](https://gradle.org/): Se requiere tener Gradle instalado y configurado en las variables de entorno.

- [JDK de Java](https://www.oracle.com/java/technologies/javase-downloads.html) 17 o superior: Asegúrate de tener instalado el JDK de Java en tu sistema.

## Ejecución del Proyecto

### Generar Reportes (Windows)

Para generar reportes con capturas de pantalla, abre una terminal y ejecuta el siguiente comando:

```
./gradlew clean test aggregate
```

Esto generará un reporte en la carpeta `target\site\serenity`. El archivo se llamará `index.html`.


### Ejecutar solo los Tests (sin generar reportes)

Si prefieres ejecutar solo los tests sin generar reportes, sigue estos pasos:

1. Limpia el proyecto:

```
gradle clean
```

2. Construye el proyecto:

```
gradle build
```

Con este último comando automaticamente se empezaran a ejecutar las pruebas.
