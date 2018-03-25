# Portada UPM ETSIINF

En este repositorio encontrarás plantillas para desarrollar tanto el Trabajo de
Fin de Grado (TFG) como el Trabajo de Fin de Máster (TFM) de la Escuela Técnica
Superior de Ingenieros Informáticos de la Universidad Politécnica de Madrid,
también conocida como ETSIINF.

## Plantillas disponibles

Este repositorio empezó con una plantilla para el grado, con el tiempo ha ido
creciendo. Están disponibles las siguientes plantillas

## Grado en Ingeniería Informática (GII)
La plantilla para el Trabajo de Fin de Grado en Ingeniería Informática está en
la carpeta `Grado_GII/`.

Cumple con lo estipulado en [la web de la escuela](http://www.fi.upm.es/?pagina=1475).

### Máster en Ingeniería Informática (MUII):
La plantilla para el Trabajo de Fin de Máster en Ingeniería Informática está en
la carpeta `Master_MUII/`

Cumple con lo estipulado en [la web de la escuela](http://www.fi.upm.es/docs/estudios/muii/1957_Guia_elaboracion_TFMUII.pdf).

## Uso
Cada uno de los proyectos contienen un paquete para LaTeX que se llama
`portada.sty`, que hace que el `\maketitle` de LaTeX produzca la portada
con el estilo la UPM ETSIINF correspondiente.

Además se incluye un ejemplo de uso y configuración de la portada. Para facilitar
el desarrollo de la memoria (sobre todo en Linux) se ha incluido un Makefile en
los proyectos que permite generar el PDF usando `make`.

Todos los ficheros que se generan de la compilación LaTeX se guardan en la
carpeta `build/`, que git ignora. Aún así se pueden eliminar usando `make clean`


## Prerequisitos
Antes de poder compilar el proyecto es necesario tener instalado LaTeX así
como algunas dependencias.

Para Ubuntu y derivados
```
sudo apt-get install texlive-full biber
```

Para Arch y derivados
```
sudo pacman -S texlive-core texlive-latexextra texlive-bibtexextra biber texlive-fontsextra
```

## Licencia
Este repositorio es un fork de https://github.com/skgsergio/Portada-UPM-ETSIINF,
donde figura la siguiente *Licencia*:
```
Cuenta la leyenda que la portada en LaTeX ha ido pasando por generaciones de
miembros de ACM hasta llegar a mi. Desconozco el autor original y si tenía
licencia.

Originalmente se trataba de código LaTeX para incluir en tu documento sin
más, sin embargo la he convertido a un paquete de LaTeX y he arreglado
algunos errores de diseño lo mejor que he podido. Y digo lo mejor que he
podido ya que ni el docx y svg de referencia de la escuela coinciden al
100%...

Total, todo este rollo para deciros que hagáis lo que os de la gana, podéis
tratar de vendérselo a alguien pero creo que no va a colar eh.
```
