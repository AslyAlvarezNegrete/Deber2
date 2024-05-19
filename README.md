# Deber 2
Este trabajo trata de construir una aplicación básica de API REST utilizando Spring Boot. La API gestionará una colección de libros, permitiendo operaciones básicas como crear, obtener todos los libros y obtener un libro por su ID. A continuación, se explicara cada uno de estos endpoints:

#GET/libros
En este API retorna una lista de todos los libros disponibles en la colección. Acontinuación podemos ver en la imagen donde utilizamos esta API con el URL: http://localhost:8080/libros  
![Get](https://github.com/AslyAlvarez/Deber2/assets/170271155/40ebc7c0-3469-40ca-b2e2-7d8aba165e87)

#GET/libros/{id_libro}
Esta API retorna un libro específico basado en el ID proporcionado. Acontinuación podemos ver en la imagen donde utilizamos esta API con el URL: http://localhost:8080/libros/4 
![get-id](https://github.com/AslyAlvarez/Deber2/assets/170271155/759aa11f-5237-4bcb-bca6-148ffae45e72)

#POST /libros
Este API permite crear un nuevo libro en la colección. Acontinuación podemos ver en la imagen donde utilizamos esta API con el URL: http://localhost:8080/libros/crearlibros 
![post](https://github.com/AslyAlvarez/Deber2/assets/170271155/0fcd60d7-952c-45e8-9875-963125d50b1a)

Y para confirmar que se allá creado hacemos un get consultando la id que creamos, en la siguiente imagen se muestra el resultado:
![post-id](https://github.com/AslyAlvarez/Deber2/assets/170271155/c4103941-6b04-4597-b5a0-222f4294a9de)
