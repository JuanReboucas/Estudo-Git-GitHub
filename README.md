Estudo Sobre o Git e GitHub

Instalação
https://git-scm.com/downloads
![image](https://user-images.githubusercontent.com/87442012/183785075-7cd64e75-9eab-41be-81a2-16299381e1fc.png)

O que é controle de versão?
* uma tecnica que ajuda a gerenciar o codigo-fonte de uma aplicação;
* registrando todas as modificações de codigo, podendo tambem reverter as mesmas;
* criar versões de um software em diferentes estagios, podendo alterar facilmente entre elas;
* cada membro da equipe pode trabalhar em uma versão diferente;
* ha ferramentas para trabalhar o controle de versão como: git e SVN


O que é Git?
* o sistema de controle de versão mais utilizado no mundo atualmente;
* o git é baseado m repositorios, que contem todas as versões do codigo e tambem copias de cada desenvolvedor;
* todas as operações do git são otimizadas para ter alto desempenho;
* todos os objetos do git são protegidos como criptografia para evitar alterações indevidas e maliciosas;
* o git é um projeto de codigo aberto;

  O que é um repositório?
  * é onde o codigo sera armazenado;
  * na maioria das vezes cada projeto tem um repositorio;
  * quando criamos um repositorio estamos iniciando um projeto;
  * o repositorio pode ir para servidores que são especializa dos em gerenciar repo:GitHub e Bitbucket;
  * cada um dos desenvolvedores do time pode baixar o repositorio e criar versões diferentes em sua maquina;
  
Como criar um repositorio?
* comando git init

Para que serve o git status?
O comando git status exibe as condições do diretório de trabalho e da área de staging.

O que é GitHub?
* é um serviço para gerenciar repositorios, gratuito e amplamente utilizado;
* podemos enviar nossos projetos para o GitHub e disponibiliza-lo para oustros devs;
* o GitHub é gratuito tanto para projetos publicos como privados;
* vamos criar uma conta em github.com

Como enviar nossos repositorios locais para o GitHub;
* podemos facilmente enviar nossos repos para o GitHub;
* precisamos criar o projeto no GitHub, inicializar o mesmo no git em nossa maquina, sicronizar com o GH e enviar;
* e esta sequencia que parece ser complexa é facilemnte executada por poucos comandos;
* vale lembrar que só fazemos uma vez por projeto este fluxo;
* porem alguns dos comandos utilizados vão ser úteis ao longo do curso;

COMANDOS_________________________________________
git init - Criar um repositorio
git status - exibe as exibe as condições do diretório de trabalho e da área de staging
git commit -m "seu comentario" - faz um comentario salve
git branch -M nomedabranch - esse comando e para criar sua branch principal
git remote add origin link do teu git - para conectar ao teu repositorio no git
git remote -v - verica em qual git vc esta conectado
git push -u origin "nome da sua branch principal" - faz com que suas alteracao subao para o git
git remote rm orgin - ele remove minha origem
git pull - atualizo minha branch com a develop
git clone link - cona repositorio
git rm nomedoarquivo - remover arquivo
git log - 
git mv nomearquivo pasta - mover o arquivo ou renomear o nome do arquivo || git mv nomedoarquivoaserrenomeado nomedearquivocorreto
