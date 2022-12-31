*git init*: 
- inicializa um repositório GIT vazio
- transforma a pasta de um projeto num repositório no GIT
- ativa o repositório existente, dentro da pasta do projeto

*git add*:
- manda os arquivos para a área de 'stanging' ou 'index'. Pense que é como o back stage de uma show. A pessoa fica ali esperando, já pronta para entrar no palco.

*git status*: 
- verificar quais arquivos foram modificados e estão esperando por uma descrição de modificação
- mostra em qual branch você se encontra no momento

*git commit*:
- esse comando vai enviar as modificações da área de stanging para o repositório local
- nele você colocar uma descrição da modificação que foi feita
        *git commit -m "mensagem de descrição da modificação"

*git branch -M "novo nome para a branch atual"*:
- recentemente o git tem usado o nome "main" para a branch principal. Então para mudar o nome da branch de "master" para "main", basta eu digitar *git branch -M "main"*

**Github**

Agora que já sabemos alguns comandos básicos do Git, podemos criar um repositório no Github.
Lembre-se, o *Github* é uma plantaforma para hospedar meus códigos, então eu não basta eu criar o repositório na minha máquina, no meu (repositório local), eu preciso criá-lo na nuvem também (repositório remoto), no caso, o Github.

Após criar o repositório na interface do Github, nós escrevemos esse comando no Git Bash:
*git remote add origin https://github.com/beelnunes/Github.git*
- git: é o que escrevemos sempre que estamos escrevendo algum comando para o git
- remote: é um comando para estabelecer a conexão entre meu diretório local e o diretório do Github
- add: para adicionar
- origin: é o apelido que estamos dando para o repositório que eu criei na nuvem, pode ser outro nome, esse é um nome usual que a galera usa
- link: o link do repositório que chamei de "origin"


