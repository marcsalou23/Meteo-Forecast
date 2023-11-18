## Weather Forecast

Aplicación web meteorológica desarrollada utilizando **HTML5**, **CSS** y **JavaScript**. Puedes visitarla [aquí](https://meteo-forecast-yb1k.vercel.app/)

![](https://s5.gifyu.com/images/SR97Y.gif)

En el presente proyecto hemos creado una web que utiliza los datos de geolocalización del usuario para
obtener información meteorológica básica de las siguientes 8 horas, siempre en la posición del usuario.
Hemos utilizado el lenguaje de marcado HTML5 para hacer la estructura básica de nuestro sitio web,
el cual se compone de una sóla página con una distribución bastante sencilla. Consta de un encabezado
con una descripción, y un cuerpo principal que contiene la parte interactiva, incluido un botón que debe
se debe pulsar para activar la previsión meteorológica.

En cuanto al archivo de JavaScript, es aquí donde reside el mayor interés del proyecto.
Comenzamos seleccionando los elementos de HTML que vamos a utilizar o modificar, incluido el botón sobre
el que crearemos un evento de click.
A partir de ahí, cuando el usuario lo pulse, el botón desaparece y el navegador intenta acceder a la
geolocalización. Si lo consigue nos devolvera la posición mediante latitud y longitud, si no es capaz nos
informará mediante un mensaje en pantalla.
Una vez obtenidos estos datos, se utilizan para solicitar
información a una API, cuando la misma nos devuelve los datos, estos se asocian a una imagen y se
imprimen en el HTML. En caso de error en este último paso se nos informará también mediante un
mensaje en pantalla.

Por último, en el archivo CSS le hemos dado un estilo sencillo priorizando la claridad de los datos
obtenidos a través de la API, y sobre todo el diseño responsive. Somos conscientes de que cometemos
ciertos errores tratando de conseguir estos objetivos, en primer lugar podríamos mejorar el
maquetado de la página (padding, margin...) pero sobre todo destaca el hecho de haber comenzado el
diseño por la versión web y no por la versión móvil. Este es punto clave que trataremos de corregir
en el futuro para mejorar nuestro proyecto.

**Listado de recursos utilizados**

- [Watherbit](https://www.weatherbit.io/ 'API meteorológica')
- [Geolocalización](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API 'API de geolocalización')
- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [Amcharts](https://www.amcharts.com/ 'Iconos meteorológicos')
- [Google Fonts](https://fonts.google.com/ 'EStilos tipográficos')
