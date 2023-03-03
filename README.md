# Formulario de inscripción de auxiliares

Este proyecto no oficial busca facilitar el llenado del formulario requerido
para la inscripción a concursos de auxiliares de la Facultad de Ciencias Exactas
y Naturales de la Universidad de Buenos Aires.

El mismo replica el formulario provisto por el Departamento de Computación de la
Facultad que puede ser obtenido de la siguiente dirección:
http://www.dc.uba.ar/academica/concursos/formulario.

## ¿Cómo se completa?

1. Completar los campos descritos en `datos_del_aspirante.tex`.
2. Escribir antecedentes docentes en `docentes.tex`.
3. Escribir antecedentes científicos en `cientificos.tex`.
4. Escribir antecedentes de extensión en `extension.tex`.
5. Escribir antecedentes profesionales en `profesionales.tex`.
6. Escribir otros en `otros.tex`.
7. Escribir calificaciones en `calificaciones.tex`.

## Generar formulario

Habiendo completado todos los datos requeridos ejecutar el siguiente comando para
generar el documento final:

```
make
```

## Dudas y consultas

Ante cualquier duda o consulta puede ser de utilidad referirse tanto al
[formulario oficial](http://www.dc.uba.ar/academica/concursos/formulario) como el
[reglamento](http://www.dc.uba.ar/academica/concursos/reglamento.pdf) provisto
por el Departamento de Computación.
