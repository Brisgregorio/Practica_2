# Practica_2
###Encabezados(Headings)
para poder dar énfasis a los contenidos de la documentación podemos utilizar los encabezados (Headings) para marcar alguna sección o subsección, 
esto se marcan utilizando el símbolo ≠ , entre menos repetisiones tenga mayor tamaño e importancia tendra el texto Ejemplo:

# Encabezado nivel 1

## Encabezado nivel 2

### Encabezado nivel 3

#### Encabezado nivel 4

##### Encabezado nivel 5

###### Encabezado nivel 6

####### Encabezado nivel 7 (Solo considera a los primeros 6 niveles)

### 2. Separadores (SEPARATORS)   - PRACTICA 03

Si deseas marcar una separacion mas visual de contenidos pordenados indicando tres caracteres de "-" continuos, en el maquetado

Ejemplo:

---

*Esto es similar a un tag de < HS > en HTML

### 3. Parrafos (PARAGRPAHS)

Son utilizados para  presentar grandes secciones de texto que describen detalladamente las secciones de la documentacion del proyecto

Ejemplo: 

Este texto pertenece al parrafo 1 Este texto pertenece al parrafo 1 Este texto pertenece al parrafo 1
Este texto pertenece al parrafo 1 Este texto pertenece al parrafo 1 Este texto pertenece al parrafo 1
Este texto pertenece al parrafo 1 Este texto pertenece al parrafo 1 Este texto pertenece al parrafo 1

Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2
Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2
Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2
Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2
Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2 Este texto pertenece al parrafo 2 


Lo que en una pagina utilizamos usando la etiqueta  < p >

Tambien podemos aplicar estilos basicos  de alineacion:

Este parrafo esta alineado hacia la izquierda por defectoEste parrafo esta alineado hacia la izquierda por defecto
Este parrafo esta alineado hacia la izquierda por defectoEste parrafo esta alineado hacia la izquierda por defecto
Este parrafo esta alineado hacia la izquierda por defectoEste parrafo esta alineado hacia la izquierda por defecto
Este parrafo esta alineado hacia la izquierda por defectoEste parrafo esta alineado hacia la izquierda por defecto
Este parrafo esta alineado hacia la izquierda por defectoEste parrafo esta alineado hacia la izquierda por defecto
Este parrafo esta alineado hacia la izquierda por defectoEste parrafo esta alineado hacia la izquierda por defecto

< p  align="rigth">
Este parrafo esta alineado hacia la derecha utilizabdo la propiedad alineacion Este parrafo esta alineado hacia la derecha utilizabdo la propiedad alineacion
Este parrafo esta alineado hacia la derecha utilizabdo la propiedad alineacion Este parrafo esta alineado hacia la derecha utilizabdo la propiedad alineacion
Este parrafo esta alineado hacia la derecha utilizabdo la propiedad alineacion Este parrafo esta alineado hacia la derecha utilizabdo la propiedad alineacion

< /p >

<p align="center ">
Este parrafo esta centrado usando la propiedad de alineacion Este parrafo esta centrado usando la propiedad de alineacion
Este parrafo esta centrado usando la propiedad de alineacion Este parrafo esta centrado usando la propiedad de alineacion
Este parrafo esta centrado usando la propiedad de alineacion Este parrafo esta centrado usando la propiedad de alineacion
Este parrafo esta centrado usando la propiedad de alineacion Este parrafo esta centrado usando la propiedad de alineacion
 
<p align= "justify">
Este parrafo esta justificado utilizando la propiedad de alineacion Este parrafo esta justificado utilizando la propiedad de alineacion
Este parrafo esta justificado utilizando la propiedad de alineacion Este parrafo esta justificado utilizando la propiedad de alineacion
Este parrafo esta justificado utilizando la propiedad de alineacion Este parrafo esta justificado utilizando la propiedad de alineacion
Este parrafo esta justificado utilizando la propiedad de alineacion Este parrafo esta justificado utilizando la propiedad de alineacion
</p>

### 4. Texto Enfatizado (BLOG, ITALAIC, BOLD/ITALIC)
Si el texto queb deceamos enfatizar se encuentra en un parrafo,  podemos utilizar algunos trucos para ubicarlos en la documentacion 

##### Texto En Negritas (BOLD)
Para poder poner el texto en negritas, este debera ser encerrado entre dobles **

Ejemplo 
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto  **Texto importante** Texto Texto Texto Texto Texto Texto Texto Texto Texto
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

##### Texto en Cursiva (ITALIC)
Algunas veces en necesario resaltar algunas secciones o textos en cursiva para que el lector detecte el textoimportante, dentro del maquetado con el estandar
Markdown lo podemos realizar ubicando el texto entre *asteriscos

Texto Texto Texto Texto Texto Texto Texto Texto  *Texto* Texto Texto Texto Texto Texto Texto Texto Texto

##### Texto en Negrita y Cursiva (BOLD & ITALIC)
De igualmanera podemos utilizar ambos utiliozando **Negrita** y *Cursica* para resaltar los textos que concideramos importantes dentro de la documentacion de nuestro proyecto de software,
 utilizando un triple (asterisco*

Ejemplo:
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto*** Texto Texto Texto Texto

##### Subrayado (UNDERLINE) 
Algunas veces nesesitamos subrayar texto dentro de la documentacion para ello si bien Markdown no tieneun atajo o codificacion rapida podemos utilizar el estilo estandar de HTML usando el tag <ins>
y cerrado con </ins>

Ejemplo:
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto Subrayado</ins> Texto Texto Texto TextoTextoTexto Texto Texto Texto Texto
Texto Texto Texto Texto Texto
### 5. Cuadros para codigp o reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones especificas para la instalacion, configuracion y/o  mostar secciones de codigo fuente. Se maqueta inciando el texto con un simbolo de mayor que (/>)

*EJEMPLO:*
para alistar las carpetas y archivos en desde una terminal de sistemas operativos de windos debemos ingresar el comando:

> C:/dir 
Despues oprimimos la tecla "Enter".
Tambien podemos ingresar texto multilinea
*EJEMPLO:*

PASOS PARA INSTALAR LA BASE DE DATOS

>- Decargar MySQL Server del Sitio Oficial 
>- instalar el Sistema Gestor de Base de Datos definiendo el puesto y la contraseña para el usuario *root*
>- Descargamos el archivo de respaldo de la base de datos (.sql)
>- restauramos la Base de Datos usando el comando mysql
C:/ProgramFiles/MySQL/MYSQLServer8.0/bin/mysql-u root -p password < respaldo sql

### 6. Listas ordenadas y Desordenadas

sí en nuestra documentación necesitamos incluir información de texto en modo de lista, un elemento tras otro podemos
hacerlo utilizando los números con un punto decimal si las deseamos ordenadas o un guion en medio - si solo queremos una viñeta 

*EJEMPLO:*

Para poder crear tu primero repositorio en GitHub deveras;
  
1. Contar con una cuenta GitHub
   
2. Dar clic en el botón *Nuevo Repositorio

3. Asignarle un nombre a tu repositorio, por ejemplo: 'ptactica03-3b'

4. Asignarle un nivel de privacidad entre 

- *PUBLICO:* Si quieres que este disponible para todos los usuarios.

- *PRIVADO:* Si deseas que solo a quien decidas puedan colaborar con tu proyecto.

10. Definir si incluye un archivo de descripción llamado: README.md

11. Definir si habrá exclusiones de archivo a través del archivo a través del archivo : gitignore

12. Guardar los cambios 


### 7. Ligas (Hipervínculos)

las ligas utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizando lo corchetes \[ \], inmediatamente después pondremos la liga de referencia entre paréntesis /()

*EJEMPLO:*

Mi buscardor favorito es:[www.google.com] / (https://www.google.com)
Pero si deseas poner solo las ligas directas a un correo electronico podemos utilizar los simbolos \<\>

*EJEMPLO:*
Documetacion creada por: **Carlos Daniel Garcia Pluma**
(<cg419370@gmail.com>)

(<http://www.utxicotepec.edu.mx>)

### 8. Tablas (Tables)
Si la documentación lo requiere podemos presentar información en formato de tablas con filas y columnas, para maquetarlas podemos utilizar el caracter \| para delimitar las columnas y \- para delimitar las filas.

*Ejemplo*

|Encabezado 1|   Encabezado 2 |  Encabezado 3 | Encabezado 4 |
|------------|----------------|---------------|--------------|
|Fila 1 Celda 1|⁮Fila 1 Celda 2|Fila 1  Celda 3|Fila 1 Celda 4|
|Fila 2 Celda 1|Fila 2 Celda 2|Fila 2  Celda 3|Fila 2 Celda 4|
|Fila 3 Celda 1|Fila 3 Celda 2|Fila 3  Celda 3|Fila 3 Celda 4|

En caso de necesitar la funsión de celdas en columnas usaremos la proiedad "colspan" del tag <td< y en el caso de necesitar la fusión de las filas utilizaremos la propiedad rowspan.

*Ejemplo*

|Encabezado 1|Encabezado 2| Encabezado 3| Encabezado 4|
|------------|------------|-------------|-------------|
|Fila 1 Celda 1|⁮Fila 1 Celda 2|Fila 1  Celda 3|Fila 1  Celda 4|
|Fila 2 Celda 1|Fila 2 Celda 2|               |Fila 2  Celda 4|
|Fila 3 Celda 1|Fila 3 Celda 2|Fila 3  Celda 3|Fila 3  Celda 4|
|            |Fila 4 Celda 2|Fila 4  Celda 3|Fila 4  Celda 4|  
|            |Fila 5 Celda 2|Fila 5  Celda 3|Fila 5  Celda 4|
|Fila 6 Celda 1|Fila 6 Celda 2|Fila 6  Celda 3|Fila 6  Celda 4|

Dado que en el ejemplo pasado usando solo markdown no se puede realizar la funcion de las filas debemos utilizar el estandar de HTML, usando los tags: \<th> para los encabezados, <tr> para las filas y para las celdas, y en ellos utilizar la propiedad de colspan y rowspan

*Ejemplo:*
<table>
<tr>
<th>Encabezado 1</th>
<th>Encabezado 2</th>
 <th>Encabezado 3</th>
 <th>Encabezado 4</th>
</tr>
<tr>
 <td>Fila 1 Celda 1</td>
 <td>Fila 1 Celda 2</td>
 <td>Fila 1 Celda 3</td>
 <td>Fila 1 Celda 4</td>
</tr>

<tr>
<td>Fila 2 Celda 1</td>
<td colspan=3 align="center">Fila 2 Celda 2</td>

</tr>
<tr>
<td rowspan=3> Fila 3 Celda 1</td>
<td> Fila 3 Celda 2</td>
<td> Fila 3 Celda 3</td>
<td> Fila 3 Celda 4</td>
</tr>

<tr>
<td>Fila 4 Celda 2</td>
<td>Fila 4 Celda 3</td>
<td>Fila 4 Celda 4</td>
</tr>
<tr>
<td>Fila 5  Celda 2</td>
<td>Fila 5  Celda 3</td>
<td>Fila 5  Celda 4</td>

</tr>
<tr>
<td>Fila 5  Celda 1</td>
<td>Fila 5  Celda 2</td>
<td>Fila 5  Celda 3</td>
<td>Fila 5  Celda 4</td>

</tr>

</table>


### 9. Imagenes

I
Para agregar imagenes debemos subiria al repositorio, en la opcion de subir archivos seleccionaremos las imagenes a subir, debemos darle en la opcion de commit changes para guardandas, una vez guardades, entraremos accediendo a las imagenes cargadas en nuestro repositorio para poder copier su URL de cada una, para insertarlas y que se muestren utilizaremos la sintaxis de Markdown para Imágenes, ![Texto alternative de la imagen] (Url de la imagen cargada).

*Imagenes del proyecto*




 










