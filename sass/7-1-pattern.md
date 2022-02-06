
<hr>

# Estructura de carpetas

## Base
- resets
- html y body styles
- animaciones
- tipografía
- utilidades

## Abstract
- variables
- mixins
- functions
- Cualquier cosa que no devuelva CSS directamente

## Components
Cada componente estará ubicado en su propio archivo.

## Layout
Cada pieza del layout (ej. global-sidenav, global-header, etc).

## Pages
Si tenemos un diseño muy específico para una página (ej. Home o Login), lo escribiremos en esta carpeta.

## Themes
Esta carpeta solo debería definirse en caso de que nuestra app tenga distintos temas.

## Vendors
Carpeta reservada para archivos css 3rd-party, como bootstrap, algún sistema de íconos o frameworks de animaciones.  

<hr>

**Partial Files** son los archivos que seran importados en otro archivo principal (main.scss). Su nombre siempre comienza con '_'.

**main.scss** solo debería contener imports de las partial files.