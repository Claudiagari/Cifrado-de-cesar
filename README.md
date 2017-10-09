# Cifrado de Cesar
##### -Pagina web que pide un texto a   cifrar o descifrar.
##### -Solo se debe ingresar letras mayusculas o minusculas.
## Desarrollo:
#### -Diagrama de flujo
###### Seguir el siguiente link:          >https://ibb.co/n4KTMG
#### -Pseudocódigo:
##### Función Cipher
###### Crear una función que devuelva el texto cifrado, primer parametro el "text" y segundo parametro "number" (numero de posiciones fijas a correr 33),crear una variable "result" vacia que se ira llenando, se hara el recorrido mediante un for para recorrer text.length, se creara la variable "k", que contendra el numero ASCII segun la posicion de text. Se preguntara si pertenece a mayusculas o minusculas deacuerdo a eso se aplica la formula (((k-65+number)%26)+65) o (((k-97+number)%26)+97) correspondientemente, se ira llenando result y si no se coloco letras result dara una alerta.
##### Función Decipher
###### Crear una función que devuelva el texto cifrado en texto original , primer parametro el "text" y segundo parametro "number" (numero de posiciones fijas a correr 33) se creara la variable "result" que contendra el valor a retornar se recorrera el texto cifrado mediante un for de longitud text.length,se creara la variable "k", que contendra el numero ASCII segun la posicion de text. Se preguntara si pertenece a mayusculas o minusculas deacuerdo a eso se aplica la formula  ((k-number)+26) y se va llenando la variable result y si no se coloco letras mandara una alerta.
