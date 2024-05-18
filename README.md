# MultisageDockerfile-GonzalezHolm
Comparacion de archivos dokcer multistage y singlestage para hacer una pagina web con flask.

Para generar la imagen dokcer, tenés que abrir la terminal en la carpeta del proyecto (Single-stage o Multi-stage).

Luego de eso tenés que ejecutar el comando: "docker build -t nombreImagen ." para generar la imagen. Ej: docker build -t flask .

Para correr la imagen docker, tenés que ejecutar el siguiente comando en la terminal: "docker run -d -p puertoDeTuComputadora:5000". Ej: docker run -d -p 5000:5000 flask
