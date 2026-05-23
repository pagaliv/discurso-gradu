# 📄 Discurso de Graduación – Acto Académico 2025/2026

Este repositorio contiene el código fuente en **LaTeX** del discurso pronunciado durante la graduación de la Facultad de Ciencia y Tecnología.

El discurso grabado está disponible en YouTube y comienza en el minuto exacto indicado más abajo.

---

##  Discurso original en video

Para escuchar o seguir el discurso mientras lees, haz clic en el siguiente enlace. El video empezará a reproducirse **directamente desde el inicio del discurso** (minuto 41:58).

 [Ver discurso en YouTube – empezar en 41:58](https://www.youtube.com/watch?v=0wZ2w1o2fsg?t=2518)

> El parámetro `?t=2518` indica el segundo 2518, que corresponde exactamente a `41:58`.

---

## Cómo generar el documento PDF

El proyecto incluye **dos versiones** del mismo discurso, adaptadas a diferentes necesidades.

### Requisitos

Tener instalada una distribución de LaTeX (por ejemplo, TeX Live, MiKTeX o Overleaf).

###  Versión "formal" (formato carta / A4)

Esta versión es la adecuada para:

- Compartir digitalmente (por correo, web, etc.)
- Incluir en memorias
- Leer en pantalla

### Versión "impresión" 

- Para imprimir, perfecto para miopes

**Compilar con:**

```bash
pdflatex discurso-bonito.tex
