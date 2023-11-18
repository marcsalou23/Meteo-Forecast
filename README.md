# Weather Forecast

Weather Forecast es una aplicación web desarrollada utilizando **HTML5**, **CSS** y **JavaScript**. Puedes visitarla [aquí](https://meteo-forecast-yb1k.vercel.app/).

![Demostración del Pronóstico del Tiempo](https://s5.gifyu.com/images/SR97Y.gif)

En este proyecto, hemos creado una aplicación web que utiliza los datos de geolocalización del usuario para obtener información meteorológica básica de las próximas 8 horas en la posición actual del usuario. Utilizamos HTML5 para la estructura básica de nuestro sitio web, que consta de una sola página con un diseño sencillo. Incluye un encabezado con una descripción y un cuerpo principal que contiene la parte interactiva, incluyendo un botón que debe ser pulsado para activar el pronóstico del tiempo.

El archivo de JavaScript es donde reside la funcionalidad principal del proyecto. Comenzamos seleccionando los elementos HTML que vamos a utilizar o modificar, incluido el botón sobre el que crearemos un evento de clic. Cuando el usuario hace clic en el botón, este desaparece, y el navegador intenta acceder a la geolocalización. Si tiene éxito, devuelve la posición en latitud y longitud; de lo contrario, informa al usuario con un mensaje en la pantalla. Una vez obtenidos estos datos, se utilizan para solicitar información a una API. Cuando la API devuelve los datos, se asocian con una imagen e se imprimen en el HTML. En caso de un error en este último paso, también se informa al usuario con un mensaje en la pantalla.

Finalmente, en el archivo CSS, le hemos dado un estilo sencillo, priorizando la claridad de los datos obtenidos a través de la API y, sobre todo, el diseño responsivo. Somos conscientes de que cometemos ciertos errores al intentar lograr estos objetivos. En primer lugar, podríamos mejorar el maquetado de la página (padding, margin, etc.), pero sobre todo destaca el hecho de haber comenzado el diseño por la versión web y no por la versión móvil. Este es un punto clave que trataremos de corregir en el futuro para mejorar nuestro proyecto.

**Lista de Recursos Utilizados:**

- [Weatherbit](https://www.weatherbit.io/ 'API Meteorológica')
- [API de Geolocalización](https://developer.mozilla.org/es/docs/Web/API/Geolocation_API)
- [Fetch API](https://developer.mozilla.org/es/docs/Web/API/Fetch_API)
- [Amcharts](https://www.amcharts.com/ 'Iconos Meteorológicos')
- [Google Fonts](https://fonts.google.com/ 'Estilos Tipográficos')
