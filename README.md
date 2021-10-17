Imagem docker - Laravel

A imagem configurada para ter uma aplicação laravel rodando

Para dar o build da imagem execute o comando no terminal dentro da pasta com o Dockerfile

`docker build -t seu-nome/laravel:latest .`

e para executar

` docker run -d --name projeto-laravel -p 8000:8000 seu_nome/laravel`

Para rodar em outra porta ou host

`docker run -d --name projeto-laravel -p 8001:8001 seu_nome/laravel --host=0.0.0.0 --port=8001`

\* substitua o texto **seu_nome** no nome da imagem

Para acessar a aplicação pelo navegador

http://localhost:8000
