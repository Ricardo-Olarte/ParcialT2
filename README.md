# Parcial Tercio 2
### Elaborado por:
Jose Ricardo Olarte Pardo

## Requisitos
 - Maven
 - Java
 - Git
 - Docker
_______________________

## Instalación
1. Clonamos el repositorio de git
```
https://github.com/Ricardo-Olarte/ParcialT2.git
```

2. Luego desde nuestro cmd, nos dirigimos a la carpeta donde se encuentra descargada, y utilizamos el comando
```
mvn clean install
```
3. Luego utilizamos el siguiente comando
```
java -cp "target/classes;target/dependency/*" co.edu.escuelaing.arep.collatz.Collatz
```
4. Entramos al localhost de la pagina, y despues de value= puedes poner el numero que desees
```
http://localhost:4567/collatzsequence?value=
```
5. El siguiente comando utilizamos para docker
```
docker-compose up -d
```
Lo siguiente es su visualizacion
![](https://github.com/Ricardo-Olarte/ParcialT2/blob/main/Img/docker.png)

_______________________
## Visualización desde el localhost

1. Localhost
![](https://github.com/Ricardo-Olarte/ParcialT2/blob/main/Img/localhost.png)

2. Docker
![](https://github.com/Ricardo-Olarte/ParcialT2/blob/main/Img/local-dokcer.PNG)

_______________________
## AWS

El siguiente para desde la nube amazon, el video esta en este repositorio directorio video.
Nota: Recuerda elegir el numero que desees
```
ec2-54-159-125-113.compute-1.amazonaws.com:34000/collatzsequence?value=
```

_______________________
## Licencia
Derechos Ricard Olarte - 2023
