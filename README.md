¡Bienvenid@ al repositorio oficial del Módulo 1! Aquí encontrarás todo el material, datos y scripts que utilizaremos en clase. El objetivo de usar GitHub es que siempre tengas la versión más reciente del curso de forma organizada.

# 📊 Módulo 1: Introducción a R - Curso 2026

## Descripción
Este proyecto contiene los ejercicios para la primera sesión de capacitación en R. 
El objetivo es aprender a manejar estructuras de carpetas y cargar datos de matrícula.

## Estructura del Proyecto
- `data/raw/`: Contiene la base de datos de matrícula inicial "sucia".
- `scripts/`: Contiene el script `01_lectura_datos.R`.
- `outputs/`: Aquí se guardarán los reportes generados.

## 🛠️ Requisitos Previos
Antes de empezar, asegúrate de tener instalado:
1. **R** (versión 4.3 o superior)
2. **RStudio Desktop**
3. **Git** ([Descárgalo aquí](https://git-scm.com/downloads))

---

## 📥 Cómo obtener el material (Clonar)
Para tener este proyecto en tu computadora, no descargues un ZIP. Sigue estos pasos en RStudio:
1. Ve a **File > New Project > Version Control > Git**.
2. En **Repository URL**, pega este enlace: `https://github.com/TU_USUARIO/Modulo1_Curso_R.git`
3. Elige la carpeta donde quieres guardarlo y haz clic en **Create Project**.

---

## ⚠️ Regla de Oro: Evita errores de sincronización
Para que puedas recibir mis actualizaciones sin que tu RStudio se bloquee con "conflictos de versión", sigue estas dos reglas:

1. **No edites los scripts originales:** Si quieres tomar notas o hacer ejercicios sobre un script mío (ej: `clase1.R`), ve a **File > Save As...** y guárdalo con tu nombre (ej: `clase1_Luis.R`).
2. **Crea tus propios archivos:** Siéntete libre de crear todos los scripts y carpetas que necesites. Git los ignorará y no causarán problemas.

---

## 🔄 Cómo recibir actualizaciones (Pull)
Si en clase aviso que he subido nuevos datos o corregido un script:
1. Ve a la pestaña **Git** (arriba a la derecha en RStudio).
2. Haz clic en la **flecha azul hacia abajo (Pull)**.
3. ¡Listo! Los archivos nuevos aparecerán mágicamente en tu computadora.

---

## 📁 Estructura del Proyecto
* `data/raw/`: Bases de datos originales (¡No modificar!).
* `data/processed/`: Aquí guardaremos los resultados de nuestras limpiezas.
* `scripts/`: Código fuente de las clases.
* `Modulo1_Curso_R.Rproj`: Archivo maestro del proyecto. **Ábrelo siempre para trabajar.**

---

## 🆘 SOS: En caso de errores
Si hiciste cambios por error en un archivo original y el botón **Pull** te da un error rojo:
1. En la pestaña **Git**, haz clic derecho sobre el archivo problemático.
2. Selecciona **Revert...**. (Esto borrará tus cambios locales en ese archivo y lo dejará como el original).
3. Intenta el **Pull** de nuevo.
4. *Si nada funciona:* Borra la carpeta del curso en tu PC y vuelve a **Clonar** el proyecto. ¡Es la solución más rápida!


## Contacto
Dudas o soporte: roberto.rodriguez@mined.gob.sv