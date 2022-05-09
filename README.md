# Descargar un servidor Doom en Docker mediante una maquina virtual alpine
### Primero arrancamos alpine y nos logueamos 

![h1](https://user-images.githubusercontent.com/91874537/167391106-26408b01-8a86-4430-a540-4c67eb1848fc.PNG)


### Hacemos un ip a para saber la ip de la maquina

![h2](https://user-images.githubusercontent.com/91874537/167391120-edf450b2-8f1e-4847-89b7-a76e4f7965a6.PNG)

### Probamos que tengamos conexión abriendo el powershell y haciendo un ssh root@(ip)

![h3](https://user-images.githubusercontent.com/91874537/167391140-8bc00951-4593-487d-9876-ea20acea3213.PNG)

### Descargamos el fichero de Dockerdoom
Para esto porque el enlace esta caido tenemos que meternos en archive.org para poder descargarlo.

![h4](https://user-images.githubusercontent.com/91874537/167391163-b2f91194-413e-4b79-97d0-78239e472f62.PNG)

### Descargamos win scp para pasar los archivos a la máquina virtual

![h5](https://user-images.githubusercontent.com/91874537/167391191-875c1af2-3b1a-427b-a3ac-f3eeca9e1ab0.PNG)

### Metemos la ip con el siguiente comando
shh root@(ip)

### Subimos los archivos a la máquina virtual

![h7](https://user-images.githubusercontent.com/91874537/167391213-fc0d7c6d-13d3-4287-856a-46414f83a756.PNG)

## Ahora podemos seguir con la instalacion
### Ejecutamos el doom con el siguiente comando 

![h8](https://user-images.githubusercontent.com/91874537/167391232-1252a626-aa58-4936-8ad2-61095293a6ef.PNG)

### Intalamos go

![h9](https://user-images.githubusercontent.com/91874537/167391238-3c3610e2-d336-42ba-bd5e-363d12e7e432.PNG)

### Para asegurarnos que lo tengamos intalado ejecutaremos go version

![h10](https://user-images.githubusercontent.com/91874537/167391259-0eb719a2-db9d-4d3c-9909-299db7529909.PNG)

### Nos descargamos el git

![h11](https://user-images.githubusercontent.com/91874537/167391271-464bb920-e4fc-47db-a778-2bb9698b5649.PNG)

### Clonamos el repositorio

### Ejecutamos el siguiente comando 
#### go run main.go

![h12](https://user-images.githubusercontent.com/91874537/167391310-1a194892-f35a-4a62-98e5-7960b91cee74.PNG)

### Utilizamos un VNC para conectarnos a la ip de la maquina 
Ponemos de contraseña 1234.

![h13](https://user-images.githubusercontent.com/91874537/167391341-38a1ff7f-451b-4d37-a141-7781d8f46007.PNG)


### Ya tendriamos todo listo para jugar

![h14](https://user-images.githubusercontent.com/91874537/167391368-a516660a-c95a-46c3-8af5-1228f4b01e16.PNG)
