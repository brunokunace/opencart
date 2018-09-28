# opencart
opencart em português + docker( php7.2,  nginx, mysql)

## Instalação
1) Faça o clone ou download desse repositório, configure os nomes dos containers e credenciais do arquivo `docker-compose.yml`
2) Execute o comando `docker-compose up -d` na raiz do projeto
3) Acesse localhost:80 (ou outra porta que você escolher no `docker-compose.yml`
4) Na instalação, passo 3, no hostname do banco, coloque o nome do container do mysql definido no  `docker-compose.yml` (default: opencart-mysql)
5) Done!


