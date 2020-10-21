# Boletin Oficial de Argentina - Contrataciones

Este repositorio contiene datos (json, csv) de las contrataciones que se publican diariamente en el boletin oficial. Esta compuesto por dos carpetas:

## json
Los archivos dentro de esta carpeta son de formato json y estan compuestos por dos tags:
- url: direccion del recurso
- body: texto publicado en el boletin

La fecha en que se publica la contratacion esta en el nombre del archivo (ultimos 10 caracteres formato YYYYMMDD).

## csv
Esta carpeta contiene solo un archivo que es el resultado del proceso de NLP que se corre diariamente para identificar mediante la publicacion la empresa y los montos. 
- cuit
- razon social
- monto identificado
- url de la publicacion
- fecha

# Cual es la idea/objetivo? 
Intentar identificar mediante el padron de AFIP cuales son las empresas/personas en cada una de las publicaciones realizadas en el boletin oficial. El desafio principal esta dado por la forma en que se publican los datos debido a que no siguen patrones o no tienen tablas que sean facilmente parseables para comenzar a trabajar con estos datos. 

# Disclaimer
Es un proyecto exploratorio por lo que puede pasar que las empresas/personas identificadas no sean realmente las publicadas. Seguimos trabajando en los algoritmos de NLP para mejorar la precision en todos los casos.

License
----

MIT
