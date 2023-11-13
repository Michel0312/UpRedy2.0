Para hacer uso de este Bot debe configurar

<Confi.py>

Bot_token #obténga el token mediante BotFather
chanel_id #Id del grupo o canal de registro donde se guardará los procesos y la base de datos
db_access #Número del id del mensaje creado en el grupo o canal de registro


<bot.py>

api_id #su api_id de telegram, linea 53
api_hash #su api_hash de telegram, linea 54
boss #agregue su username como administrador

Luego de configurar monte el bot y ejecutelo
>> python bot.py

en cuanto encienda verá que se le creará una base de datos en su grupo o canal,lo que hará es dejar presionado el mensaje que contiene esa base de datos y darle en Copiar Enlace del Post o Mensaje y fíjase en el número que tiene depues del último / 
ejemplo:
	si el enlace del mensaje es https://t.me/oficial_uploader_rayserver/172 el número sería 172 el cual es el que tiene que agregar en el archivo confi.py en el apartado db_access


Para activar Nube Educa mande al bot el comando /educa y ya despues mande lo que quiera descargar
En el caso de las revistas debe configurarlas haciendo uso del comando /rv

/rv host user passw up_id zips mode

sustituya host user passw up_id zips por los datos de su revista, en mode debe poner n que significa normal o m que significa mergue,el 80% de las nubes usan n

/rv host user passw up_id zips n
