# Ejercicio práctico

## Nombre y apellidos

Alejandra Obregón

## Enunciado

Practicad con el siguiente ejercicio práctico todo lo que hemos visto hasta ahora en clase. 
Los enlaces mediante anclas (anchor, usando referencias #elemento a un elemento de la propia página, no lo hemos visto en clase, 
pero echadle un ojo porque es fácil de entender. Tan solo fijaos en el atributo id="elemento". 
Introducid algunos comentarios dentro del código fuente, recordad que <!-- Se hace así -->

# Solución
html´´´
<!DOCTYPE html>
<html lang="es">

<head>
<meta charset="UTF-8">
<title>Ejercicio de repaso puente</title>

<style>
table, th, td, tr, tfoot {border: 1px solid;}
</style>
</head>

<body>

<h1 id="inicio">Mi primera página web: las tecnologías web</h1>

<p>Bienvenido a mi página. Aquí practico las etiquetas básicas de <b>HTML.</b></p>

<p>Ir a: 
<a href="#formatos">Formatos | 
<a href="#listas">Listas</a> | 
<a href="#tabla">Tabla<a> | 
<a href="#enlaces">Enlaces<a> |
<a href="#entidades">Entidades</a>
</p>

<hr>

<h2 id="formatos">1. Formatos de texto</h2>

<p>

Este texto está en <b>negrita (b)</b> y este en <strong>importancia fuerte (strong)</strong>.<br>
Este texto está en <i>cursiva (i)</i> y este en <em>énfasis (em)</em>.<br>
Este texto esta <u>subrayado (u)</u>.<br>
Este texto esta <del>borrado(del)</del> y este <s>tachado</s>.<br>
Este texto ha sido <ins>insertado (ins)</ins> y este está <mark>resaltado (mark)</mark>.<br>
Fórmula del agua: H<sub>2</sub>O. Elevado al cuadrado: x<sup>2</sup>.<br>

</p>

<p>

También se pueden combinar: <b><i>negrita y cursiva</i></b>, o <b><u>negrita y subrayado</u></b>.<br>

</p>

<h3>Diferencia entre <b>< b ></b> y <strong>< strong ></strong></h3>

<p>

<b>< b ></b> solo cambia el aspecto visual, mientras que <strong>< strong ></strong> indica que el texto es<br>
importante (los lectores de pantalla lo leen con más énfasis).

</p>

<hr>

<h2 id="listas">2. Listas</h2>

<h3>Lista desordenada: lenguaje de la web</h3>

<ul>

<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>

</ul>

<h3>Lista ordenada: pasos para crear una web</h3>

<ol>

<li>Abrir un editor de texto.</li>
<li>Escribir el código HTML.</li>
<li>Guardar el archivo con extensión <i>.html.</i></li>
<li>Abrirlo en el navegador.</li>

</ol>

<h3>Lista anidada: herramientas</h3>

<ul>

<li>Editores de código

<ul>

<li>Visual Studio Code</li>
<li>Sublime Text</li>

</ul>

</li>

<li>Navegadores

<ol>

<li>Firefox</li>
<li>Chrome</li>
<li>Edge</li>

</ol>
</li>
</ul>

<h3>Lista de definición</h3>

<p>

<dt>HTML</dt>
<dd>Lenguaje de marcas para estructurar el contenido de una página.</dd>
<dt>CSS</dt>
<dd>Lenguaje de hojas de estilo para dar formato y diseño.</dd>
<dt>JavaScript</dt>
<dd>Lenguaje de programación que añade interactividad.</dd>

</p>

<hr>

<h2 id="tabla">3. Tabla</h2>

<table>

<caption><b>Lenguajes de programación web</b></caption>

<thead>

<tr>

<th>Ámbito</th>
<th>Lenguaje</th>
<th>Función principal</th>

</tr>

</thead>

<tbody>

<tr>

<td rowspan="3">Cliente <i>(front-end)</i></td>
<td>HTML</td>
<td>Estructura del contenido</td>

</tr>

<tr>

<td>CSS</td>
<td>Estilo y diseño</td>

</tr>

<tr>

<td>JavaScript</td>
<td>Interactividad</td>

</tr>

<tr>

<td rowspan="2">Servidor <i>back-end</i></td>
<td>PHP</td>
<td>Lógica en el servidor</td>

</tr>

<tr>

<td>Python</td>
<td>Lógica y análisis de datos</td>

</tr>

</tbody>



<tfoot>

<tr>

<td colspan="3"><b>Total</b>: 5 lenguajes</td>

</tr>

</tfoot>

</table>

<hr>

<h2 id="enlaces">4. Enlaces</h2>

<ul>

<li>Enlace externo (nueva pestaña): <a href="https://developer.mozilla.org/es/">MDN Web Docs</a></li>
<li>Enlace con título al pasar el ratón: <a href="https://www.w3.org/">W3C</a></li>
<li>Enlace interno: <a href="#inicio">Volver al principio de la página</a></li>
<li>Enlace de correo: <a href="alejandraobregonrojo@gmail.com">Escríbeme un correo<a></li>

</ul>

<hr>

<h2 id="entidades">5. Entidades</h2>

<table>

<thead>

<tr>

<th>Código</th>
<th>Resultado</th>
<th>Significado</th>

</tr>

</thead>

<tbody>

<tr>

<td>&amp;copy;</td>
<td>&copy;</td>
<td>Copyright</td>

</tr>

<tr>
<td>&amp;reg;</td>
<td>&reg;</td>
<td>Marca registrada</td>

</tr>

<tr>

<td>&amp;trade;</td>
<td>&trade;</td>
<td>Marca comercial</td>

</tr>

<tr>

<td>&amp;lt;</td>
<td>&lt;</td>
<td>Menor que</td>

</tr>

<tr>

<td>&amp;gt;</td>
<td>&gt;</td>
<td>Mayor que</td>

</tr>

<tr>

<td>&amp;amp;</td>
<td>&amp;</td>
<td>Ampersand</td>

</tr>

<tr>

<td>&amp;euro;</td>
<td>&euro;</td>
<td>Euro</td>

</tr>

<tr>

<td>&amp;quot;</td>
<td>&quot;</td>
<td>Comillas dobles</td>

</tr>

<tr>

<td>&amp;hellip;</td>
<td>&hellip;</td>
<td>Puntos suspensivos</td>

</tr>

<tr>

<td>&amp;nbsp;</td>
<td>Hola&nbsp;&nbsp;&nbsp;&nbsp;mundo</td>
<td>Espacio de no separación</td>

</tr>

    </tbody>
  </table>

</body>

</html>
´´´
