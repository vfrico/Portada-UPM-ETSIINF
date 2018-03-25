# Memoria TFG Grado_GII
## Uso
Cada uno de los proyectos contienen un paquete para LaTeX que se llama
`portada.sty`, que hace que el `\maketitle` de LaTeX produzca la portada
con el estilo la UPM ETSIINF correspondiente.

Además se incluye un ejemplo de uso y configuración de la portada. Para facilitar
el desarrollo de la memoria (sobre todo en Linux) se ha incluido un Makefile en
los proyectos que permite generar el PDF usando `make`.

Todos los ficheros que se generan de la compilación LaTeX se guardan en la
carpeta `build/`, que git ignora. Aún así se pueden eliminar usando `make clean`

Cumple con lo estipulado en [la web de la escuela](http://www.fi.upm.es/?pagina=1475)
salvo en la elección de la tipografía. En las normas se recomienda utilizar
Times New Roman, sin embargo, por elección personal elegí usar las fuentes
*libertine*. Esto se puede modificar en la línea 14 de la memoria,
simplemente indicando que se debe usar el paquete `{times}`

La memoria está separada por capítulos. Como ejemplo, se incluyen dos. A parte
de editar los archivos en la carpeta `capitulos/` es necesario añadir al final
del archivo general la siguiente línea: `\input{capitulos/nombredelcapitulo}`
