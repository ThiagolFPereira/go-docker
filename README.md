
# Desafio Full Cycle Docker
## Desafio Go

Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
Você terá que publicar uma imagem no docker hub. Quando executarmos:

docker run <seu-user>/codeeducation

Temos que ter o seguinte resultado: Code.education Rocks!

Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

A imagem de nosso projeto Go precisa ter menos de 2MB =)


# Build 
```
docker build -t <seu-user>/docker .
```

# Pull 
```
docker pull thiagolfpereira/docker
```

# Executar o container
```
docker run --rm thiagolfpereira/docker
```