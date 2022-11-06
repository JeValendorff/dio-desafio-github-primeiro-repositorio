## Comandos básicos do Git :book: 

O que aprendi e usei até o momento do curso :writing_hand:

- **1 - Git init** ➡️ (git init)

  Esse é o comando que você irá utilizar para criar um novo projeto de git. O comando irá criar um repositório novo em branco e, a partir daí será possível armazenar seu código fonte, alterar, salvaguardar alterações etc.

  

- **2 - Git add** ➡️ (git add <arquivo>)

  Ao criarmos, modificarmos ou excluirmos um arquivo, essas alterações acontecerão em nosso espaço de trabalho local e não serão incluídas no próximo commit. 

  Precisamos usar o comando git add para incluir as alterações de um ou vários arquivos em nosso próximo commit.

  

- **3 - Git status** ➡️ (git status)

  O comando git status nos dá todas as informações necessárias sobre a branch atual. 

  

- **4 - Git commit** ➡️ (git commit)

  Git commiy é como definir um ponto de verificação no processo de desenvolvimento. Você pode voltar a esse ponto mais tarde, se necessário.

  Também precisamos escrever uma mensagem breve para explicar o que desenvolvemos ou alteramos no código-fonte. ➡️ (git commit -m "mensagem do commit")

  

- **5 - Git push** ➡️ (git push origin main )

  Após fazer o commit de suas alterações, a próxima coisa a fazer é enviar suas alterações ao servidor remoto. Git push faz o upload dos seus commits no repositório remoto.

  

- **6 - Git pull** ➡️ (git pull <repositório-remoto>)

  O git pull é usado para obter as atualizações de um repositório remoto. 

  

- **7 - Git config** ➡️ (git config)

  Quando você está utilizando o Git pela primeira vez ou com uma instalação nova, em um projeto colaborativo, esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada *commit*.

  

- **8 - Git clone** ➡️ (git clone <URL do seu projeto>)

  Esse comando Git cria uma cópia exata de um repositório já existente.

  Então… quando usar git init e quando usar git clone? O git clone é mais avançado, uma vez que ele mesmo executa um comando git init internamente. Além disso, ele verifica todo o conteúdo do projeto.

  