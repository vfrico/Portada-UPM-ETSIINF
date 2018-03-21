# Portada UPM ETSIINF

Este paquete para LaTeX hace que el `\maketitle` de LaTeX produzca la portada
con el estilo la UPM ETSIINF.

Además se incluyen dos ejemplos, en LaTeX y en org-mode, de uso y
configuración de la portada que, además, cumplen con los estilos marcados
por la Escuela para los Trabajos de Fin de Grado y Trabajo fin de Master
(en la carpeta **/master**).

## Estilo y formato del Trabajo de Fin de Grado de la UPM ETSIINF
[http://www.fi.upm.es/?pagina=1475]()

## Estilo y formato del Trabajo de Fin de Master de la UPM ETSIINF
[http://www.fi.upm.es/docs/estudios/muii/1957_Guia_elaboracion_TFMUII.pdf]()

## Prerequisitos
Antes de poder compilar con latex es necesario tener instalado latex así
como algunas dependencias.
```
sudo apt-get install texlive-full biber
```

## Uso
Para compilar la memoria, simplemente ejecuta `make` y se generará un archivo
PDF. Para borrar los archivos de compilación, puedes ejecutar `make clean`.

## Licencia
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
