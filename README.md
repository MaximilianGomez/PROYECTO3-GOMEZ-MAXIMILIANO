#COTIZADOR DE FIESTAS

PROYECTO FINAL REACT

------------------------------------------------

ACCEDER CORRECTAMENTE

Se debe clonar el repositorio (o descargar el comprimido) y se debe escribir en consola "pnpm install" para generar la carpeta node_modules

Para visualizar de forma correcta el proyecto se debe escribir en consolar "pnpm run dev"

------------------------------------------------

EXPLICACION DEL PROYECTO

- Este proyecto simula el sistema de cotización que brinda una empresa prestadora de servicios dedicada a ofrecer locaciones para realizar fiestas. 
- Se le pide al usuario elegir entre las opciones que se le ofrecen y se realiza una cotización en base a las mismas.
- Dicha cotización es almacenada en un Historial al que el usuario tiene acceso para visualizarlas y eliminarlas en el momento que desee.
- El usuario puede desplazarse desde la página del cotizador hacia el Hsitorial y viceversa.

------------------------------------------------

MODO DE CREACION Y DETALLES ADICIONALES

1- Realicé la instalacion de node y pnpm para poder obtener la carpeta node_modules.

2- Dentro de la carpeta "src" creé la carpeta "Pages" y generé los archivos index.jsx e Historial.jsx.

3- Generé dentro de la carpeta "src" la carpeta "img" para almacenar la imagen utilizada de fondo en el css.

4- Creé un JSON el cual es referenciado mediante async await para poder ser utilizado.

5- Adicionalmente agregué una alerta para confirmar si el usuario desea realizar la cotización o si cancela la misma
   (al aceptar, la cotizacion se registra en el historial, pero al cancelar no se realiza el registro).

6- Agregué un botón que permite eliminar una cotización almacenada en el historial.

7- En el Historial se detalla la fecha de la cotización y los datos ingresados por el usuario, ademas de la propia
   cotización realizada.

8- El desplazamiento entre páginas está realizado mediante React Routes.

-------------------------------------------------

PROBLEMAS

 Hubo inconvenientes al querer subir el proyecto entero a github. 
Intenté crear un repositorio nuevo y subir el proyecto desde la consola de git pero no se me permitía el acceso. Luego intenté
borrar el repositorio creado anteriormente y generar el repositorio directamente desde el proyecto utilizando también GitBash, pero
no hubo forma de subirlo, así que probé subir los cambios directamente desde el VScode o de crear un nuevo repositorio desde el mismo,
pero en todos los intentos anteriores me decía que no tenía permisos en la cuenta, por lo que al final decidí crear un repositorio desde
el propio GitHub y arrastrar los archivos manualmente, motivo por el cual no pude adjuntar la carpeta node_modules.

Al momento de mostrar la cotización en el index.jsx se observa el valor con 2 dígitos, pero al verlo desde el historial se
agregan mas dígitos y no supe como corregir el error.
  
Debido a la falta de tiempo por cuestiones personales me queda pendiente agregar ciertos detalles adicionales que me gustaría que tuviera
el proyecto, como por ejemplo un reproductor de musica (intenté agregarlo pero no me reconocía la ruta del archivo .mp3, por lo que desistí).

Consideré agregar mas imágenes y retocar ciertos aspectos del CSS, pero por el mismo motivo que mencioné anteriormente, prefiero aplazar
dichos cambios y realizarlos en algún momento mas tranquilo.

-------------------------------------------------


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
