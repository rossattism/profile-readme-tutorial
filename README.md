# Tutorial de Readme by <a href="https://github.com/RossattiSM"> RossattiSM </a>

> “La naturaleza nos ha dado las semillas del conocimiento, no el conocimiento mismo.” ― Séneca

## ¡Bienvenid@!

Si cada vez que <b> visitas un perfil personalizado </b> te das cuenta de que te gustaría hacer lo mismo pero no sabes ni por dónde empezar, ¡este es tu lugar! 
Te enseño de manera básica como editar tu perfil y dejarlo bonito para los reclutadores. <br>

<hr>
<b> ANTES DE COMENZAR:  </b> No es menor aclarar que hay muchas maneras de editar un archivo Readme en Github y que el modo enseñado en este tutorial es muy básico y utiliza en su mayoría el lenguaje HTML, lo que no quita que en muchos casos se pueda utilizar Markdown para hacer lo mismo o incluso mucho más. <br>
<hr>


## Contenido 

<p align="center">
  <ol>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#primeros-pasos-en-tu-nueva-aventura"> Primeros pasos </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#-markdown-o-html-esa-es-la-cuesti%C3%B3n"> Markdown o HTML </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#agregar-encabezados"> Agregar encabezados </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#editar-texto"> Editar texto </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#a%C3%B1adir-los-enlaces-"> Añadir enlaces </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#insertar-im%C3%A1genes"> Insertar imágenes </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#iconos"> Iconos </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#badges"> Badges </a> </li>
    <li> <a href="https://github.com/RossattiSM/tutorial-perfil-readme#comunidad-42"> Para la Comunidad 42 </a> </li>
    
  </ol>
</p>

<hr>

## Primeros pasos en tu nueva aventura 

<p align="justify">
<ul>
  <li> Crear un nuevo repositorio que tenga el <i> mismo nombre </i> que tu <b> nombre de usuario en Github </b> </li> 
  <li> Seleccionar la pestaña </i> "Add a Readme file" para agregar un archivo Readme que te permita personalizar tu perfil </li> 
  <li> Editar el archivo fácilmente desde Github con los <b> <i> tips </i> </b> que doy en este repo ✨ </li> 
</ul>
 </p>

## 🤓 Markdown o HTML, esa es la cuestión 

<p align="justify">
¡Para qué elegir, si podemos usar los dos! Para editar el Readme se usa el lenguaje Markdown y/o el lenguaje HTML, este último con algunas limitaciones que se descubren sobre la marcha. No te preocupes si no los conocés porque, además de que son sencillos, voy a ir integrando código en el tutorial para que solo utilices los famosos <i> Ctrl+C </i> y <i> Ctrl+V </i>.
 </p>

## Agregar encabezados

<p align="justify">
La forma más sencilla de agregar encabezados a nuestro Readme es con <i> Markdown </i> y para hacerlo se utilizan <b> almohadillas </b> (#) antes de cada encabezado. La cantidad de almohadillas representa el tamaño de la letra, mientras más almohadillas menor el tamaño de la letra.
 </p>
 
```
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
```
<p align="justify">
Estos encabezados, además, <i> generan automáticamente </i> un enlace con atajo que se muestra en el menú hamburguesa (☰) del archivo Readme para una navegación más sencilla dentro del mismo.
</p>

## Editar texto

<p align="justify">
Para <i> generar texto </i> simplemente se escribe de forma normal y se agregan las etiquetas HTML que interesen para hacer ver el archivo lo más agradable posible. Cabe aclarar que no se puede embellecer demasiado un Readme, hay limitaciones. </p>
 
 ```
texto normal
<i> texto en cursiva </i>
<b> texto en negrilla </b>
<p align="justify"> texto justificado </p>
<p align="center"> texto centrado </p>
<br> salto de línea
```

Ejemplo de cómo se vería: <br>
texto normal <br> 
<i> texto en cursiva </i> <br> 
<b> texto en negrilla </b>
<p align="justify"> texto justificado </p>
<p align="center"> texto centrado </p>

<b> EMOJIS </b> <br> 
Si te gustan los <i>  emojis </i> 🤩😎 se utilizan el código que le corresponde a cada uno: <a href="https://gist.github.com/rxaviers/7360908"> aquí hay una lista </a>.

## Añadir los enlaces 🔗

Para <i> hacer enlaces </i> a otras páginas dentro y fuera de github, también se puede utilizar el lenguaje HTML. <br>
 ```
 <a href="aquí va el enlace"> texto enlazado </a>
 ```
Un ejemplo de código donde se añade un enlace sería este:
```
Sígueme en <a href="https://github.com/RossattiSM"> Github </a>.
 ```
Y se vería de la siguiente manera: <br> 
Sígueme en <a href="https://github.com/RossattiSM"> Github </a>.
 
## Insertar imágenes

Con las <i> imágenes </i> también se puede usar HTML. Existen dos modos: imágenes insertadas de otros sitios con su dirección o imágenes dentro del mismo Readme. De esta última forma se tiene que subir la imágen al repositorio de forma manual para poder agregar la ruta a ese archivo y que funcione. <br>

Esta es la forma que se utiliza en HTML para insertar una imágen:
 ```
 <img src="aquí va el url de la imágen" alt="descripción de imágen" />
 ```
 
Además, se puede cambiar su tamaño modificando los pixeles directamente con código de la siguiente manera:
 ```
 <img src="aquí va el url de la imágen" alt="descripción de imágen" width="50px" height="50px" />
 ```
 
 Un ejemplo de código donde se añade una imágen sería este:
 ```
 <img src="https://ih1.redbubble.net/image.1102897194.2281/pp,840x830-pad,1000x1000,f8f8f8.jpg" alt="RTFM" width="200px" height="200px" />
 ```

Y se vería de la siguiente forma: <br> 
<img src="https://ih1.redbubble.net/image.1102897194.2281/pp,840x830-pad,1000x1000,f8f8f8.jpg" alt="RTFM" width="200px" height="200px" />


## Iconos

Una forma divertida y visual de editar el perfil de Github es <i> añadiendo iconos </i> con los lenguajes que uno conoce o le gustaría aprender para poder mostrarlo ante los reclutadores. <b> Los iconos se añaden igual que las imágenes. </b> <br>

Este es el código para agregar iconos:

 ```
 <img src="url de icono" alt="icono" />
 ```
 
 Un ejemplo donde se añade un icono sería este:
 ```
 <img src="https://skillicons.dev/icons?i=linkedin" alt="logo linkedin" />
 ```
 
Y se vería de la siguiente forma: <br> 
 <img src="https://skillicons.dev/icons?i=linkedin" alt="logo linkedin" /> <br>

Los siguientes son enlaces a repositorios Github con iconos que te pueden interesar: <br>
<a href="https://github.com/tandpfun/skill-icons"> Skill Icons </a> <br>
<a href="https://github.com/marwin1991/profile-technology-icons"> Technology Icons </a> <br>

## Badges

Los <i> badges </i> son <b> insignias </b> que se pueden agregar al perfil y hacerlo más <b> divertido o atractivo </b> para quien lo vea. Algunos ejemplos de lo que pueden hacer estas insignias son: contar cuánta gente ingresa a un perfil de github, contar el peso del código dentro de un repositorio o la cantidad de archivos que hay. Existen muchísimas insignias diferentes. Cada una tiene su código particular para insertarla en el archivo Readme. <br>

Aquí te dejo enlaces a repositorios con Badges: <br>
<a href="https://github.com/anuraghazra/github-readme-stats"> Github Readme Stats </a> <br>
<a href="https://github.com/Naereen/badges"> More badges </a> <br>
<a href="https://github.com/Ileriayo/markdown-badges"> Markdown Badges </a> <br>

## Comunidad 42

Para cerrar, si sos de la comunidad 42, haciendo click <a href="https://github.com/stars/RossattiSM/lists/42-school"> aquí </a>, encontrarás una lista con repositorios útiles que incluyen badges que te permiten agregar al Readme una insignia de tu perfil como estudiante en 42. 😎 <br>

 <hr>
 ¡Llegamos al <i> <b> final </b>! Espero que el tutorial haya resultado útil y me alegren el día con una ⭐ como agradecimiento. Saludos.
