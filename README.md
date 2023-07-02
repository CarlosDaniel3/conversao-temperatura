# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Rodando o projeto

Entre no diretório src
```
cd src
```

Rode um container da imagem gerada através do Dockerfile
```
docker container run -d -p 8080:8080 carlosdaniel2/conversao-temperatura:v1
```

Para testar a aplicação, basta ir no seu navegador e digitar localhost:8080 na barra de endereço