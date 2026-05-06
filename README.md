# Plantilla para la memoria del Trabajo Fin de Grado (TFG)
# Gradu Amaierako Lanaren (GRAL) memoriarako txantiloia

Esta plantilla ha sido diseñada siguiendo la normativa de la Escuela de Ingeniería de Vitoria-Gasteiz (UPV/EHU) y la [guía de identidad corporativa de la UPV/EHU](https://www.ehu.eus/documents/10136/3950780/GUIA_EXPRESION_UPV_es.pdf/4d538337-2577-4260-ae02-d0fed29a26b5).

> [!IMPORTANT]
> **ES:** Es obligatorio usar **XeLaTeX** como compilador para que las fuentes oficiales (`EHUSans`, `EHUSerif`) se carguen correctamente.
>
> **EU:** Derrigorrezkoa da **XeLaTeX** konpilatzaile gisa erabiltzea iturri ofizialak (`EHUSans`, `EHUSerif`) recte karga daitezen.

---

## Selección de idioma / Hizkuntza hautatzea

Esta plantilla contiene la estructura para realizar el trabajo tanto en castellano como en euskera. Para evitar confusiones y errores de compilación, sigue estas instrucciones según el idioma elegido:

### Opción A: Trabajar en Castellano (ES)
Si vas a realizar el TFG en castellano, para mantener el proyecto limpio debes:
1. **Borrar** el archivo `main_eus.tex`.
2. **Borrar** la carpeta `src_eus/`.
3. Utilizar únicamente `main_cast.tex` y los archivos dentro de `src_cast/`.

### B aukera: Euskaraz lan egin (EU)
GRALa euskaraz egiteko asmoa baduzu, proiektua garbi mantentzeko:
1. **Ezabatu** `main_cast.tex` fitxategia.
2. **Ezabatu** `src_cast/` karpeta.
3. Erabili bakarrik `main_eus.tex` fitxategia eta `src_eus/` karpetako edukia.

---

## Personalización de la portada / Azala pertsonalizatzea

Introduce tus datos en el archivo principal (`main_cast.tex` o `main_eus.tex`):
Sartu zure datuak fitxategi nagusian (`main_cast.tex` edo `main_eus.tex`):

```latex
% ------------------------------------------------------------ %
% DATOS DEL DOCUMENTO / DOKUMENTUAREN DATUAK                   %
% ------------------------------------------------------------ %

% Título / Izenburua:
\newcommand{\titulo}{<Título del trabajo / Lanaren izenburua>}
% Curso / Ikasturtea:
\newcommand{\curso}{<202X-202X>}
% Grado / Gradua:
\newcommand{\carrera}{Grado en XXXXXX / XXXXXX Gradua}
% Estudiante / Ikaslea:
\newcommand{\alumno}{<Apellido1, Apellido2, Nombre>}
% Director/a 1 / Zuzendaria 1:
\newcommand{\direccionA}{<Apellido1, Apellido2, Nombre>}
% Director/a 2 / Zuzendaria 2:
% (Si no hay, comentar esta línea / Ez badago, iruzkindu lerro hau)
\newcommand{\direccionB}{<Apellido1, Apellido2, Nombre>}
% Fecha / Data:
\newcommand{\fecha}{<Día de Mes de Año / Urtea, Hilabetea, Eguna>}
% ------------------------------------------------------------ %