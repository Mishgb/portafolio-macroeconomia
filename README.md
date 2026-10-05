# Portafolio · Macroeconomía y Empresa

Portafolio académico de grupo, **Macroeconomía del Desarrollo** (UCB, 2026). Integrantes: Henning Aguilar, Ofelia Plata, Michelle Griffiths, Eliana Vera, Pablo Jaldín. Una sola página con siete pestañas, en este orden: Macroeconomía (curso, profesor, nosotros, sílabos, bibliografía), Datos macroeconómicos de Bolivia en vivo (INE · BCB), Apuntes (cuaderno hoja por hoja e infografías interactivas), Lecturas, Ejercicios, Simulador (IS-LM) y Trabajos.

## Estructura

```
index.html               página principal (pestañas)
assets/style.css         sistema visual compartido
apuntes/cuaderno/        hojas del cuaderno (una imagen por hoja, en orden)
infografias/             una infografía interactiva por parte del cuaderno
simulador/is-lm.html     simulador IS-LM (pestaña Simulador)
data/contenido.json      macroeconomía, apuntes, lecturas, ejercicios y trabajos (editar aquí para agregar)
data/macro.json          datos INE/BCB (lo actualiza el script)
scripts/actualizar_datos.py   descarga IPC, tipo de cambio y UFV del BCB
trabajos/                archivos entregados
.github/workflows/       actualización diaria automática
```

## Agregar un trabajo

1. Copiar el archivo a `trabajos/`.
2. Agregar una entrada en `data/contenido.json`, en la lista `trabajos`:

```json
{"fecha": "2026-09-25", "titulo": "Taller 2 · IPC", "tipo": "Taller", "estado": "entregado",
 "descripcion": "Canasta familiar simple y cálculo del IPC.", "archivo": "trabajos/taller-2-ipc.pdf"}
```

`estado` puede ser `pendiente`, `entregado` o `calificado`; opcionalmente `"nota": "95"`.

## Agregar una hoja al cuaderno

1. Guardar la imagen en `apuntes/cuaderno/` (por ejemplo `26-hoja-13.jpg`).
2. Agregar una entrada en la lista `cuaderno` de `data/contenido.json`, en la posición donde debe aparecer:

```json
{"pag": "13", "titulo": "Trilema de política económica", "archivo": "apuntes/cuaderno/26-hoja-13.jpg", "w": 1700, "h": 2500}
```

`w` y `h` son el ancho y alto de la imagen en píxeles.

## Agregar un ejercicio o una lectura

Misma idea. Lista `ejercicios`: `titulo`, `sesion`, `fecha` (opcional), `descripcion`, `archivo`; opcionalmente `enunciado` y `solucion` (muestra el botón "Ver solución"). Lista `lecturas`: `titulo`, `autor`, `descripcion`, `archivo`.

## Pestaña Macroeconomía

Lista `macroeconomia`: una tarjeta por elemento (`titulo`, `texto`, `archivos`). Para subir el sílabo o la bibliografía, agregar en `archivos` una entrada `{"nombre": "Sílabo 2026", "archivo": "macroeconomia/silabo.pdf"}`.

## Datos

`python scripts/actualizar_datos.py` regenera `data/macro.json`. En GitHub, el workflow lo corre cada día a las 08:30 (hora de Bolivia) y publica el cambio solo.

## Ver en local

```
python -m http.server 8080
```
y abrir http://localhost:8080 (hace falta servidor porque la página lee JSON).
