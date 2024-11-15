# Documentación de Emmet 

Autor: Sicer Andres Brito Gutierrez
Soporte: Discord: SicerBrito#1610

## Introducción a Emmet
Emmet es una herramienta que permite escribir código HTML y CSS de manera rápida y eficiente. Funciona a través de abreviaturas que se expanden en código completo.

## Instalación y Configuración
Emmet viene incluido por defecto en Visual Studio Code, por lo que no necesitas instalarlo. Sin embargo, es importante asegurarte de que está habilitado:

1. Abre Visual Studio Code.
2. Ve a "Archivo" > "Preferencias" > "Ajustes". 
3. Busca "emmet.includeLanguages" y asegúrate de que incluye los lenguajes que quieres que Emmet admita (HTML, CSS, JavaScript, etc.).

## Sintaxis Básica de Emmet
La sintaxis básica de Emmet se compone de los siguientes elementos:

1. **Elementos HTML**: Escribe el nombre de la etiqueta HTML que quieres generar, por ejemplo: `div`, `p`, `a`.
2. **Clases y IDs**: Puedes agregar clases y IDs a los elementos HTML usando los caracteres `.` y `#`, respectivamente. Por ejemplo: `div.container`, `h1#main-title`.
3. **Atributos**: Puedes agregar atributos a los elementos HTML dentro de corchetes `[]`. Por ejemplo: `a[href="#"]`, `input[type="text"]`.
4. **Texto**: Puedes agregar texto dentro de llaves `{}`. Por ejemplo: `h1{Hola, mundo!}`.
5. **Anidamiento**: Puedes anidar elementos HTML utilizando el operador `>`. Por ejemplo: `div>p`.
6. **Hermanos**: Puedes crear elementos hermanos utilizando el operador `+`. Por ejemplo: `h1+p`.
7. **Multiplicación**: Puedes repetir un elemento utilizando el operador `*`. Por ejemplo: `ul>li*5`.
8. **Ascendente**: Puedes moverte hacia arriba en la estructura utilizando el operador `^`. Por ejemplo: `div>p>span^div`.

## Emmet en CSS
Emmet también admite abreviaturas para CSS. Algunas de las más útiles son:

- `m` para `margin`
- `p` para `padding` 
- `w` para `width`
- `h` para `height`
- `bg` para `background`
- `c` para `color`
- `ff` para `font-family`
- `fs` para `font-size`

Por ejemplo, si escribes `m10px` y presionas `Tab`, se expandirá a `margin: 10px;`.

Otras abreviaturas útiles en CSS son:
- `d:f` se expande a `display: flex;`
- `jc:c` se expande a `justify-content: center;`
- `ai:c` se expande a `align-items: center;`
- `bgc` se expande a `background-color:`

## Snippets Personalizados
Además de las abreviaturas predefinidas, puedes crear tus propios snippets personalizados en Emmet. Esto te permite crear estructuras o estilos que uses con frecuencia.

Puedes acceder a la configuración de Emmet en Visual Studio Code yendo a "Archivo" > "Preferencias" > "Configuración" y buscando "emmet.snippets".
