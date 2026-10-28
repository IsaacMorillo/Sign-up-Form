# Sign-up Form

Una pequeña práctica frontend para crear una interfaz de registro con estilo temático de mitología clásica y un diseño dividido en dos columnas.

La página combina HTML semántico, CSS personalizado y una propuesta visual inspirada en la estética de los dioses del Olimpo, con un formulario de registro moderno y validaciones nativas del navegador.

## Descripción general

Este proyecto consiste en una página de registro de usuario en la que se muestra una sección visual a la izquierda con una ilustración de fondo y un encabezado que da contexto a la experiencia, mientras que a la derecha se presenta un formulario con campos para datos personales y acceso.

El objetivo principal es practicar el maquetado de formularios, la organización de estilos y la creación de interfaces funcionales en HTML y CSS puro.

## Funcionalidades

- Diseño de layout en dos columnas
- Cabecera visual con imagen de fondo y texto destacado
- Formulario de registro con campos de:
  - nombre
  - apellido
  - email
  - teléfono
  - contraseña
  - confirmación de contraseña
- Validaciones HTML5 como:
  - `required`
  - `minlength`
  - `pattern`
  - `type="email"`
  - `type="tel"`
- Estilo visual con fuente personalizada basada en un tipo de letra temática
- Estilos de enfoque y estado inválido para mostrar retroalimentación visual al usuario
- Reset CSS para homogeneizar el comportamiento del navegador

## Estructura del proyecto

```text
Sign-up-Form/
├── README.md
├── index.html
├── reset.css
├── styles.css
├── fonts/
│   ├── Norse.otf
│   └── Norsebold.otf
├── img/
│   └── mythologyart-ai-generated-8546415_1920.png
└── (posible script adicional no incluido en este repositorio)
```

## Archivos principales

### `index.html`

Aquí se define la estructura principal de la página. En esta vista se incluye:

- un contenedor lateral con la imagen de fondo y el texto de bienvenida
- una zona derecha con información del registro
- un formulario con varios campos que simulan la creación de una cuenta
- enlaces para "Log in" y referencias a la imagen original en Pixabay

El documento usa un título general: `Sign-up for Olympus` y presenta el concepto de "entrar a Olympus y vivir entre los dioses" como narrativa temática.

### `styles.css`

Este archivo centraliza la apariencia visual del proyecto:

- carga la tipografía personalizada `Norse`
- define el layout base con `display: flex`
- configura el ancho de los paneles izquierdo y derecho
- establece el fondo de la cabecera con la imagen local
- personaliza los textos, botones, campos y elementos del formulario
- añade estilos para estados de focus y validación inválida

### `reset.css`

Se trata de un reset CSS reutilizable para normalizar estilos cross-browser. Entre otras cosas:

- ajusta `box-sizing`
- elimina márgenes predeterminados
- mejora la forma en que se renderizan imágenes y elementos multimedia
- conserva la herencia de tipografías en inputs, botones y selects
- mejora el comportamiento de `line-height` y suavizado de texto

### `fonts/`

Contiene las fuentes personalizadas utilizadas en la interfaz para reforzar el estilo mitológico del proyecto.

### `img/`

Incluye la imagen de fondo principal que se usa en la sección izquierda del diseño.

## Cómo usarlo

1. Clona este repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. Asegúrate de que la estructura de carpetas se mantenga intacta para que los assets (`fonts/` e `img/`) se carguen correctamente.

Ejemplo:

```bash
git clone https://github.com/IsaacMorillo/Sign-up-Form.git
cd Sign-up-Form
```

Luego abre `index.html` directamente o usa un servidor local si prefieres evitar restricciones del navegador.

## Tecnologías utilizadas

- HTML5
- CSS3
- CSS reset
- Fuentes locales (`.otf`)
- Diseño responsive básico con enfoque de práctica front-end

## Observaciones

Este proyecto es una práctica de maquetación y diseño UI, no una aplicación con backend funcional. Los formularios están preparados para ser extendidos con validación adicional o integración con un servidor más adelante.

La estructura es ligera, clara y fácil de entender, ideal para aprender conceptos como:

- diseño de páginas web
- estructura semántica de formularios
- uso de CSS para layout y estética
- validación básica con HTML
- gestión de assets e imágenes locales

## Licencia

Este repositorio no incluye una licencia explícita en el archivo actual. Si vas a reutilizarlo o compartirlo, revisa la configuración del repositorio o añade una licencia adecuada según tu caso de uso.

## Autor

Proyecto desarrollado por Isaac Morillo.

## Conclusión

`Sign-up Form` es un ejercicio visual y estructural para practicar la creación de una página de registro con estética temática. Combina maquetación, tipografías personalizadas, validaciones nativas y un diseño atractivo que permite reforzar conocimientos básicos de frontend.

Si quieres, puedo continuar con una segunda versión del README más profesional para GitHub, con badges, capturas de pantalla, secciones de "Demo" y "Tecnologías" y un tono más pulido para presentación pública.
