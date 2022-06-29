	1. Abrir la consola en esta carpeta con ctrl+ñ
          a) npm install nodemon node-sass
          b) npm init 

	2. Abrir el archivo package.son y editarlo
	A) a continuacion de && exit 1" colocar una , presionar enter y pegar el siguiente texto 
	"build-css": "node-sass --include-path scss css/main.css css/style.css",
	"watch-css": "nodemon -e scss -x \"npm run build-css\""
	
	3. Crear las carpetas en sus respectivos archivos
	A) scss/main.scss
	B) css/style.css
	
	4. En la consola correr el comando
	A) npm run build-css //por unica vez 
	B) npm run watch-css
	
	5. Cada vez que se quiera seguir compilando sn SASS
	A) abrir la consola con ctrl+ñ
	B) npm run watch-css
