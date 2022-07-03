# Bienvenido a Router-Tutorial

Hola bienvenido/a a router-tutorial.  Se trata de una aplicación web generada siguiendo un tutorial para aprender a utilizar la librería React Router.  Dicho tutorial se encuentra en https://github.com/remix-run/react-router/blob/main/docs/getting-started/tutorial.md.  Es una aplicación de react que utiliza la librería react-router-dom.

## Instalación

Clonar el codigo a una carpeta local (https://docs.github.com/es/repositories/creating-and-managing-repositories/cloning-a-repository) y abrir la carpeta con VS-CODE (recomendable), abrir una terminal y correr el comando npm install para instalar las dependencias. Luego ejecutar npm start para verificar el correcto funcionamiento
Abrir [http://localhost:3000](http://localhost:3000) para verlo in tu navegador.

La aplicación hace hot reload cuando tu realizas modificaciones sobre el código fuente, esto te permite, si compila bien, visualizar esas modificaciones sin reiniciar la app.\

## Sobre el Código

Se implementó un menú con dos opciones: invoices o expenses.  Se desarrolla la parte de invoices y expenses queda pendiente.  Se navega a través de componentes desarrollados utilizando las funciones que provee el React Router y otras propias que se basan en estas.  Con Invoices se logra mostrar a través del link del menú un listado de invoices que ha sido hardcodeado en un data.js.  Cuando se hace click en una invoice determinada se muestran los datos de es invoice particular con un botón que permite borrarla.  Se utilizó el componente invoices para mostrar la lista y el componente invoice para el detalle con la funcionalidad del borrado.  El componente expensea queda pendiente de desarrollo, actualmente sólo se muestra la palabra Expenses.  Con está aplicación puede observarse muy bien, si se presta atención a las direcciones URL que genera cada link, como es el pasaje de parámetros a través de URLparams, en las distintas posiciones, ya sea detrás de / o detrás de ?.
