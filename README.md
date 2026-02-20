# Readme con advertencias e instrucciones para su funcionamiento

## Advertencia
Este proyecto se ha creado usando los codespaces de github debido a que el alumno no tiene un pc con arquitectura en linux

## Instrucciones para el funcionamiento

### Pasos previos
Comprobar tener node y npm instalados, ademas de axios <br/>
npm install, npm install axios y node -v npm -v (en el terminal a la altura de {en mi caso}Practicas_web_1) para ver que estan instaladas las dependencias

### Pasos para ejecutar 
De nuevo reitero que esta práctica se ha hecho en un codespace de github (cada vez que se cerraba el codespace habia que volver a hacer npm install ademas de npm install axios)<br/>
Una vez todo este instalado en el espacio de código, en la misma altura mencionada anteriormente se hace npm run dev y abrir en una ventana web el localhost que imprime por pantalla al ejecutarse

## Comprobaciones de estados no estándar: Loader y Error
Para el Loader puede actualizar la página del localhost y durante un breve momento podra ver el mensaje de cargando personajes, o cada vez que le de a el botón "Siguiente Página" abajo a la izquierda saldrá el mensaje durante un instante<br/>
<img width="657" height="354" alt="image" src="https://github.com/user-attachments/assets/e49ee9b9-a71e-4244-86c4-24b50345742e" /><br/><br/>
Para el Error puede cambiarse la direccion web de la api en /src/api/api.ts , borrando por ejemplo la i final de "https://swapi.dev/api" y saldrá el mensaje de error (es necesario recargar la página del localhost para ver los cambios)<br/>
<img width="647" height="334" alt="image" src="https://github.com/user-attachments/assets/28c429f7-bbf7-49ed-9ccf-f0cc3d10e6b3" />
