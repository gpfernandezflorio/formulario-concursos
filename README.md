# Formulario de inscripción de auxiliares

Este proyecto no oficial busca facilitar el llenado del formulario requerido
para la inscripción a concursos de auxiliares de la Facultad de Ciencias Exactas
y Naturales de la Universidad de Buenos Aires.

El mismo replica el formulario provisto por el Departamento de Computación de la
Facultad que puede ser obtenido de la siguiente dirección:
https://www.dc.uba.ar/descargas/.

## ¿Cómo se completa?

1. Completar los campos descritos en `datos_del_aspirante.tex`.
2. Escribir antecedentes docentes en `docentes.tex`.
3. Escribir antecedentes científicos en `cientificos.tex`.
4. Escribir antecedentes de extensión en `extension.tex`.
5. Escribir antecedentes profesionales en `profesionales.tex`.
6. Escribir otros en `otros.tex`.
7. Escribir calificaciones en `calificaciones.tex`.
8. Si tenés una foto de tu firma, agregala a la carpeta del proyecto y descomentá `\newcommand{\firma}{firma.jpg}` en `datos_del_aspirante.tex`. Ajustar la escala con los comandos `\escalaFirmaPrincipal` y `\escalaFirmaCadaCarilla`.

## Generar formulario

Habiendo completado todos los datos requeridos ejecutar el siguiente comando para
generar el documento final:

```
make
```

También se puede generar desde [Overleaf](https://www.overleaf.com/) subiendo todos los archivos del proyecto.

## Dudas y consultas

Ante cualquier duda o consulta puede ser de utilidad referirse tanto al
formulario oficial ([docx](https://www.dc.uba.ar/wp-content/uploads/2023/08/FORM-CONC-001-B-Solicitud-de-Inscripcion-a-Concurso-regular-o-a-Seleccion-interina-de-docentes-auxiliares-Antecedentes.docx), [odt](https://www.dc.uba.ar/wp-content/uploads/2023/08/FORM-CONC-001-B-Solicitud-de-Inscripcion-a-Concurso-regular-o-a-Seleccion-interina-de-docentes-auxiliares-Antecedentes.odt)) como el
[reglamento](https://www.dc.uba.ar/wp-content/uploads/2023/04/Texto-ordenado-Reglamento-para-la-provision-de-cargos-de-docentes-auxiliares-abril-2023.pdf) provisto
por el Departamento de Computación.
