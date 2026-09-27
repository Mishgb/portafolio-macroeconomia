---
version: alpha
name: Aguayo Noche
description: Fondo negro, tipografía moderna, un solo acento fucsia; el aguayo boliviano vive solo como franja tejida. Sistema visual del portafolio de Macroeconomía (UCB 2026), aprobado por Mish y Anton tras tres iteraciones.
colors:
  primary: "#ECEAE4"
  secondary: "#9A9890"
  tertiary: "#E8236B"
  neutral: "#0D0D10"
  surface: "#15151A"
  card: "#1B1B21"
  line: "#2A2A33"
  dim: "#8A8880"
  info: "#4FB0FF"
  ok: "#3DD68C"
  bad: "#FF4D5E"
  warn: "#FFC53D"
  aguayo-rojo: "#B4102F"
  aguayo-fucsia: "#E8236B"
  aguayo-azul: "#1F3FBF"
  aguayo-amarillo: "#F0B429"
  aguayo-verde: "#178A4C"
  aguayo-naranja: "#F26A21"
  aguayo-morado: "#6A1FA8"
typography:
  h1:
    fontFamily: Manrope
    fontSize: 60px
    fontWeight: 800
    lineHeight: 1.02
    letterSpacing: "-0.025em"
  h2:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  h3:
    fontFamily: Manrope
    fontSize: 17px
    fontWeight: 700
    lineHeight: 1.3
  body-md:
    fontFamily: Manrope
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.55
  body-sm:
    fontFamily: Manrope
    fontSize: 13.5px
    fontWeight: 400
    lineHeight: 1.5
  kicker:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.16em"
  numeral:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.4
  formula:
    fontFamily: JetBrains Mono
    fontSize: 44px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  kpi:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.1
rounded:
  sm: 6px
  md: 10px
  lg: 12px
  pill: 999px
spacing:
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  section: 40px
  gutter: 72px
components:
  page:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
  section-alt:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
  card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.secondary}"
    rounded: "{rounded.md}"
    padding: 16px
  card-title:
    backgroundColor: "{colors.card}"
    textColor: "{colors.primary}"
    typography: "{typography.h3}"
  kicker:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.tertiary}"
    typography: "{typography.kicker}"
  section-number:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.tertiary}"
    typography: "{typography.numeral}"
  formula:
    backgroundColor: "{colors.card}"
    textColor: "{colors.primary}"
    typography: "{typography.formula}"
    rounded: "{rounded.md}"
    padding: 14px
  button-tab:
    backgroundColor: "{colors.card}"
    textColor: "{colors.secondary}"
    rounded: "{rounded.pill}"
    padding: 8px
  button-tab-active:
    backgroundColor: "{colors.tertiary}"
    textColor: "#FFFFFF"
    rounded: "{rounded.pill}"
    padding: 8px
  button-case:
    backgroundColor: "{colors.card}"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: 10px
  callout-warn:
    backgroundColor: "#1F1D16"
    textColor: "{colors.warn}"
    rounded: "{rounded.md}"
    padding: 14px
  callout-ok:
    backgroundColor: "#131C17"
    textColor: "{colors.ok}"
    rounded: "{rounded.md}"
    padding: 14px
  callout-bad:
    backgroundColor: "#1F1315"
    textColor: "{colors.bad}"
    rounded: "{rounded.md}"
    padding: 14px
  callout-info:
    backgroundColor: "#12181F"
    textColor: "{colors.info}"
    rounded: "{rounded.md}"
    padding: 14px
  kpi:
    backgroundColor: "{colors.card}"
    textColor: "{colors.primary}"
    typography: "{typography.kpi}"
    rounded: "{rounded.md}"
    padding: 12px
  kpi-label:
    backgroundColor: "{colors.card}"
    textColor: "{colors.dim}"
    typography: "{typography.kicker}"
  slider-track:
    backgroundColor: "{colors.line}"
    height: 4px
    rounded: "{rounded.pill}"
  slider-thumb:
    backgroundColor: "{colors.tertiary}"
    size: 22px
    rounded: "{rounded.pill}"
  table-header:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    typography: "{typography.body-sm}"
  footer:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.dim}"
    typography: "{typography.numeral}"
  aguayo-band:
    backgroundColor: "{colors.aguayo-rojo}"
    height: 56px
  aguayo-thread-fucsia:
    backgroundColor: "{colors.aguayo-fucsia}"
    width: 8px
  aguayo-thread-azul:
    backgroundColor: "{colors.aguayo-azul}"
    width: 8px
  aguayo-thread-amarillo:
    backgroundColor: "{colors.aguayo-amarillo}"
    width: 4px
  aguayo-thread-verde:
    backgroundColor: "{colors.aguayo-verde}"
    width: 12px
  aguayo-thread-naranja:
    backgroundColor: "{colors.aguayo-naranja}"
    width: 6px
  aguayo-thread-morado:
    backgroundColor: "{colors.aguayo-morado}"
    width: 6px
---

## Overview

Aguayo Noche es el sistema visual de los materiales académicos de Mish (UCB, 2026): infografías, portafolio, y más adelante la tesis y su defensa. Nació de una foto de aguayo que la pareja mandó como referencia y de tres rondas de correcciones. La regla que quedó: **el aguayo es identidad, no decoración**. Vive únicamente como franja tejida diagonal arriba y abajo de cada pieza. Todo lo demás es negro, gris carbón, tipografía moderna y un solo acento fucsia.

Lo que se rechazó, para no volver: fondo crema, paleta multicolor dentro del contenido, tipografías condensadas "de cartel de tienda", emojis, íconos decorativos, grecas de colores como separadores.

El tono de la redacción es parte del sistema: voz plana de apunte propio. No se escribe "vale la pena", "ojo", "esto es clave", "no es una teoría". Se afirma y punto: "es una identidad contable: se cumple siempre".

## Colors

- **Neutral (#0D0D10):** fondo de página. Negro con una gota de azul para que no sea negro puro.
- **Surface (#15151A):** fondo de secciones alternas. Contraste apenas perceptible con el fondo.
- **Card (#1B1B21) + Line (#2A2A33):** tarjetas gris carbón con borde fino de 1 px. Toda la jerarquía se construye con estas dos, sin sombras.
- **Primary (#ECEAE4):** texto principal, blanco cálido. Nunca #FFFFFF sobre el fondo.
- **Secondary (#9A9890):** texto de párrafo. El cuerpo se lee en gris; el énfasis (`<b>`) sube a Primary.
- **Dim (#8A8880):** metadatos, fuentes, pies. Es el gris más oscuro que pasa WCAG AA sobre Card (4.5:1); no bajar más.
- **Tertiary (#E8236B, fucsia):** el único acento. Numeración de secciones, kickers, variable destacada en fórmulas, pestaña activa, thumb de sliders, curva o punto de equilibrio nuevo. Si dos cosas compiten por el fucsia, una de las dos no lo lleva.
- **Info (#4FB0FF):** segunda serie en gráficos y notas informativas. No es acento; no se usa en títulos.
- **Ok / Bad / Warn:** semáforo estricto. Verde = correcto, rojo = incorrecto, amarillo = advertencia. Nunca como color de marca ni de fondo. En tableros de datos: inflación >10 % en rojo, 5-10 % amarillo, <5 % verde.
- **Aguayo (rojo, fucsia, azul, amarillo, verde, naranja, morado):** exclusivamente dentro de `aguayo-band`. Ninguno sale de la franja.

## Typography

Los tokens llevan el valor de escritorio (máximo). En CSS la escala es fluida: h1 `clamp(32px,7vw,60px)`, h2 `clamp(21px,3.4vw,28px)`, cuerpo `clamp(14px,1.8vw,15px)`, fórmula `clamp(20px,8.2cqw,44px)`, gutter `clamp(18px,5vw,72px)`, sección `clamp(26px,5vw,40px)`, franja `clamp(28px,6vw,56px)`.

Dos familias, Google Fonts:

- **Manrope** para todo lo que se lee. Pesos 800 en títulos con tracking negativo (-0.025em en h1), 700 en h3, 400 en párrafos. Ninguna condensada.
- **JetBrains Mono** para todo lo que se mide: kickers en versalitas con tracking 0.16em, numeración de secciones, fórmulas, KPIs, tablas de datos, pies con fuente y fecha.

Escala fluida con `clamp()`; el 90 % de las vistas son desde celular, así que los mínimos de `clamp()` son los que mandan. Las fórmulas grandes van en un wrapper con `container-type: inline-size` y `font-size: clamp(20px, 8.2cqw, 44px)`. Nunca `white-space: nowrap` con `overflow: hidden`: la fórmula se escondía detrás del texto y lo notaron.

## Layout

- Columna máxima 1080 px, centrada; en pantallas anchas la pieza flota con sombra profunda sobre el fondo.
- Gutter horizontal `clamp(18px, 5vw, 72px)`; separación vertical de secciones `clamp(26px, 5vw, 40px)` con línea superior de 1 px.
- Cada sección abre con número en fucsia (JetBrains Mono, 12 px) a la izquierda del h2. El subtítulo va dentro del h2 como `small` en Secondary.
- Grids con `repeat(auto-fit, minmax(200px, 1fr))` (280 px para tarjetas anchas). Nada de columnas fijas.
- Simuladores complejos en **cuatro cuadrantes**: sliders | gráfico / casos tipo + campos editables | "Qué está pasando". En celular se apilan en ese orden.
- Cadenas causales con flechas que giran 90° cuando el ancho no alcanza.
- Portafolio: pestañas superiores en escritorio, barra inferior fija con íconos de trazo en celular; cada pestaña con `#hash`.

## Elevation & Depth

Sin sombras dentro de la pieza: la profundidad es Neutral → Surface → Card con bordes Line. La única sombra existe en escritorio ancho (`0 30px 80px rgba(0,0,0,.6)`) para separar la pieza del fondo. Los callouts usan fondo teñido al 6-7 % del color del semáforo con borde al 35-40 %.

## Shapes

Esquinas de 10 px en tarjetas, fórmulas y callouts; 6 px en botones de caso; píldora (999 px) en pestañas, etiquetas y sliders. Sliders con pista de 4 px y thumb de 22 px para el dedo. La franja de aguayo es un `repeating-linear-gradient` a -28° con dos capas de textura (hilos oscuros cada 3 px, brillo cada 4 px) para que se lea tejida, no plana.

## Components

- **aguayo-band + aguayo-thread-*:** franja tejida; los hilos son el gradiente `-28deg` con anchos 14/8/8/4/12/6 px en el orden rojo, fucsia, azul, amarillo, verde, naranja, rojo, morado. Franja tejida de `clamp(28px, 6vw, 56px)` arriba y abajo. Variante `thin` de 6 px para la barra de navegación.
- **card:** contenedor base. Título h3 en Primary, cuerpo en Secondary a 13.5 px.
- **kicker + section-number:** los dos únicos usos tipográficos del fucsia en texto.
- **formula:** JetBrains Mono grande centrada en una card; la variable protagonista en fucsia con `<i>`.
- **button-tab / button-tab-active:** píldoras; la activa se rellena de fucsia con texto blanco.
- **button-case:** botones de "casos tipo" que animan los sliders (~650 ms) y muestran una explicación numerada.
- **callout-warn/ok/bad/info:** un solo `<b>` coloreado por callout; el resto en Secondary.
- **kpi + kpi-label:** número grande en mono, etiqueta en versalitas Dim, pie con fuente y fecha.
- **slider-track / slider-thumb:** pista Line, thumb fucsia.
- **table-header:** encabezados en Surface; números alineados a la derecha en mono.
- **footer:** fuente, institución y fecha en mono Dim.

## Do's and Don'ts

- Sí: una idea por bloque; cada cifra con institución y fecha; cada gráfico dibujado en canvas con `devicePixelRatio`.
- Sí: puntos de equilibrio etiquetados con valores; ejes con escala visible.
- No: emojis, íconos decorativos, más de un acento, degradados fuera de la franja.
- No: verde/rojo/amarillo para marcar, resaltar o decorar. Solo semáforo.
- No: voz de IA en los textos.
- No: `nowrap` + `overflow: hidden` en fórmulas.
- No: sombras dentro de la pieza, fondos claros, tipografías condensadas.
