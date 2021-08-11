### Rodar o seguinte comando na raiz do projeto para levantar os containers
```
docker compose up -d
```

Após o container ser iniciado, acesse `localhost:8080` e você deverá ver a mensagem "hello world"

### Para desligar os containers
```
docker compose down
```

### Para remover as imagens
```
docker system prune -a -f
```
