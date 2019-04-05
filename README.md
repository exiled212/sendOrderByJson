# csvToJson
Herramienta que enviar una lista de eventos http.

# Instalar:
* npm i
 # Instrucción
 - Copiamos todos los json que tienen la extención json.sample y le quitamos el .sample
 - Se llena con la información http el archivo config.json
 - ingresamos la lista de datos a enviar por http de la siguiente forma:
 "[
    {body uno},
    {body dos},
    ...
    {body n}
   ]" 
 - Una vez listo esto se envian los datos con node index.js la respuesta estara en un json en result.js con dos valores como json: request con el body que se mando y response con la respuesta