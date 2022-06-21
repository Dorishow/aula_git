# comandos

- git init

  - Inicializa o repositório
  - Configura o git

- git branch -M <nomeDaBranch>

  - Cria a branch principal do sistema

- git add <fileName> ou --all ou <".">

  - Adiciona em staging (prepara para versionar)

- git checkout -b

  - Cria uma branch nova ("Coloca um nome no estado da aplicação")

- git commit -m <"mensagem">

  - Coloca tudo o que está em staging dentro do repositório local
  - Com uma mensagem descritiva

- git remote add origin <endereço ssh>

  - Indica pro git a url do repositório remoto

- git push origin <branch>
  - Envia tudo o que está na branch indicada para o repositório remoto
