# Setup Docker Para Projetos lab (laravel 9)

### Passo a passo
Clone Repositório
```sh
git clone git@github.com:rischawarski/Lab-laravel.git
```


modifique  o Arquivo .env
```sh
cp .env.example .env
```


Suba os containers do projeto
```sh
docker-compose up -d
```


Acessar o container
```sh
docker-compose exec app bash
```


Instalar as dependências do projeto
```sh
composer install
```


Gerar a key do projeto Laravel
```sh
php artisan key:generate
```


Acessar o projeto
[http://localhost:4000](http://localhost:4000)