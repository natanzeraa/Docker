### Como rodar o programa?

```
docker-compose -f <caminho-para-o-arquivo>/build-zabbix.yaml up  -d --build
```

- **-f** - *indica o caminho do arquivo do docker compose*
- **up** - *sobe os containers*
- **-d** - *modo "detached" impede que o terminal trave com a quantidade de logs gerados na inicialização*
- **--build** - *faz o build das imagens dos containers*