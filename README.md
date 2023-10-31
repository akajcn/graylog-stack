# graylog-stack

Stack de gerenciamento de logs com Graylog/Elasticsearch/MongoDB

Versão das ferramentas:

**MongoDB = 5.0.13**

**Elasticsearch = 7.10.2**

**Graylog = 5**


# Instrucoes para o deploy da stack

Antes de iniciarmos o deploy da stack devemos criar os volumes persistentes.

Para isso, executamos dentro do diretorio do projeto, os seguinte comandos:

`mkdir data/ elasticsearch/ mongo/`

Após a crição dos diretórios, vamos alterar a permissão:

`chmod 777 -R data/ elasticsearch/ data/`

Executando estes procedimentos, vamos para o deploy, de fato, da stack.

Dentro do diretório projeto clonado do nosso repositório, executamos o seguinte comando:

`docker-compose up -d`
