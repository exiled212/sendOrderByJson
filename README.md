# SendOrderByJson
Herramienta que enviar una lista de eventos http.

# Instalar:
* npm i
 # Instrucción
 - Copiamos todos los json que tienen la extención .sample y se la quitamos
 - Se llena con la información http el archivo config.json
 - ingresamos la lista de datos a enviar por http de la siguiente forma:
 "[
    {body uno},
    {body dos},
    ...
    {body n}
   ]" 
 - Una vez listo esto se envian los datos con node index.js la respuesta estara en un json en result.js con dos valores como json: request con el body que se mando y response con la respuesta
# Extra
Si neceistas que el response tenga un formato espesifico, puedes agregarlo dentro de buildResponse, donde solo pasas la logica que neceistas paral estructura, por dar un ejemplo puedes agregar un JSON.parse() para que lo regrese como un json directamente.