#Jinja ----> motor de plantillas, permite crear ficheros html de forma dinamica

#ItsDangerous  ---->  permite meter cuestiones de criptografia y seguridad

#MarkupSafe  ---->  formar html correctamente e impedir ataques

CREAR ENTORNO VIRTUAL
 python -m venv venv -----> (el segundo venv es el nombre que hemos elegido)
 venv\Scripts\activate ----> y pondra (venv) a la izquierda del codigo cuando se inicie
 pip install Flask -----> (para instalar flask)
 pip freeze ----> (para ver las librerias que tiene)
 pip list ----> (lo mismo que freeze pero te lo dice en humano)
 pip freeze > requirements.txt ----> ( metemos las librerias en ese archivo, para poder usarla desde otro ordenador)                     hariamos git clone (enlace de git y pongo nombre de la nueva carpeta) y python -m venv (nombre),                     activariamos flask y pip install requirements.txt
 set FLASK_APP=hello.py ----> en el terminal, crea una ventana a nivel del terminal, mete el programa en la variable                               (hello.py)
 flask run ---> levanta un servidor web de pruebas entre otras cosas, es lo que hace Click. 
                "Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)"
 flask run --p=(y numero de fichero donde queramos meterlo, para cambiarlo) El 5000 de arriba

 en el archivo html, ponemod (doc) y pulsamos tab. se abre el codigo, lo que está en blanco lo hemos puesto nosotros
  luego para lanzarlo de nuevo en la ventana, ponemos "flask run --port=5000" en el terminal

                <html lang="en"> #ETIQUETA DE INICIO
            <head>
                <meta charset="UTF-8">   #JUEGO DE CARACTERES UTF8
                <meta name="viewport" content="width=device-width, initial-scale=1.0">  #PARA QUE SE VEA BIEN EN                                                                         MOVILES Y NAVEGADORES DE ESCRITORIO
                <meta http-equiv="X-UA-Compatible" content="ie=edge"> #PARA CONTENIDO ESPECIFICO DE INTERNET EXPLORER
                <title>Mi pagina</title>
            </head>
            <body>    #A PARTIR DE AQUI EMPIEZA EL CUERPO
                <h1>Mi saludo</h1> #ES EL TITULO, CON LA ETIQUETA <h1> y </h1>
                <p>Hola, mundo</p>
            </body>
            </html> #ETIQUETA DE FIN
