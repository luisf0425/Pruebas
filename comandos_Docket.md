Listar contenedores en ejecución
```shell
docker ps
```

Listar contenedores en pausa
```shell
docker ps -f "status=exited"
```

Correr contenedor ya construido
```shell
docker start -p 8585:8585 [contenedor]
```

Correr contenedor por primera vez
```shell
docker run -p 8585:8585 [contenedor]
```

Construir contenedor
```shell
docker build --tag=[nombre_contenedor_cualquiera] .
```
