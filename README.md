<h1>desafio-pre-work</h1>

vai precisar de dois terminais: um para rodar o servidor do `server`,
e outro para rodar o servidor do frontend, que está no diretório `app`.

O `server` foi criado com Node.js, então para colocar ele pra funcionar é bem simples:
abra um terminal, acesse o diretório do `server`, execute `yarn` para instalar as
dependências, e então `yarn start` para subir o servidor.

O servidor vai ficar ouvindo as requisições na porta `3333` do seu `localhost`.

CRUD significa _Create, Read, Update and Delete_,
ou Criar, Ler, Atualizar e Deletar. Basicamente a API vai permitir fazer
essas 4 operações com os carros: cadastrar um carro (Create), obter a lista de
carros cadastrados (Read), atualizar um carro (Update) e remover um carro (Delete).

Todos os dados salvos no servidor ficam em memória. Então, sempre que você quiser
"começar de novo", limpando todos os carros cadastrados, você só precisa derrubar
o servidor (usando `Ctrl + C` no terminal onde o servidor está rodando) e colocar
ele para rodar de novo (com `yarn start`).

desafio feito [no canal do Daciuk na Twitch](https://twitch.tv/fdaciuk)
