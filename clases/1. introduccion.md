# primera semana
los archivos basicos en un proyecto web deben ser
- archivo .html
- archivo .css
- archivo .js

> [!TIP] 
> A medida que el proyecto cresca se pueden ir agregando mas carpetas incluyo organizarlos haciendo uso de patrones de arquitectura (`MVC`,`ARQUITECTURA HEXAGONAL`)

- que carpetas extras podemos agregar?
- por convencion podemos agregar la carpeta de `assets` o tambien llamada `public`

- que funcion cumplen cada archivo dentro del proyecto web?
- **.html** este archivo es el encargado de darle la estructura al contenido de nuestra pagina web, osea organizar la infromacion sengun el tipo del contenido(texto(titulos subtitulos parrafos listas referencias, etc), imagenes, video, audio) que deseamos mostrar, `podemos decir que el html es de la pagina web, lo que el esqueleto son para el ser humano`, *lenguaje de marcado de texto*.
- **.css** este archivo es el encargado de darle la parte visual atractiva al contenido de nuestra pagina web, osea hacer atractiva y posicionar de manera correcta el contenido, `css es la parte visual, como el maquillaje es para las mujeres`. *hoja de estilos*
- **.js** este archvo es el encargado de darle la funcionalidad a nuestra pagina web, osea que el usuario pueda interactuar con la informacion o contenido mostrado, `js es de la pagina web, lo que energia electrica es para un pc`. *lenguaje de programacion para la web*
- **assets** esta carpeta es el lugar donde almacenamos recursos(archivos multimedia: pdf,jpg,png,doc,icon,gif,mp3,wav,mpg4) que mostraremos en nuestra web, *carpeta de recursos permanentes*

> [!TIP]
> la estructra inicial de mi proyecto web, si se condiera que es un proyecto que escalara se debera crea una carpeta para los estilo y otra para las funcionalidades

- que es un entrypoint?(recomendado)
- es un archivo inicial que se ejecutara por defecto o una vez iniciado el servidor este ejecutara primero ese archivo.
- para el caso del desarrollo web el entrypoint es el archivo `index.html`,

- convencion de nombres de archivos para el desarrollo web(opcional)
- en caso de tener un archivo `.css` el nombre sera `style.css`
- en caso de tener un archivo `.js` el nombre sera `script.js`