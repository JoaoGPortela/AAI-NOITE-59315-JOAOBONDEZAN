# AAI-NOITE-59315-JOAOBONDEZAN
AAI NOITE UNIFECAF 59315 João Gabriel Portela Bondezan

1. Comandos para criar um projeto react native do zero e subir no github

  //criando um projeto react do zero

  npx react-native init nome-do-projeto

  //entramos na pasta do projeto

  cd nome-do-projeto

  //e podemos inicia-lo com

  npm start
  
  //com o github já configurado podemos inicializar o repositorio local com

  git init

  //deixaremos as alterações prontas para o commit com

  git add .

  //podemos fazer o commit com utilizando o -m para uma mensagem

  git commit -m "Primeiro commit"

  //após realizarmos estes passos podemos nos conectar com nosso repositorio do github com

  git remote add origin https://github.com/JoaoGPortela/joao5na

  // e por fim enviamos nossas alterações com

  git push -u origin master

  // podemos utilizar o -u para que realize e vincule a branch local com a remota, mas geralmente só é utilizado na primeira vez que efetuamos o push
  //origin é o nome "inicial" do nosso repositorio local
  //master seria basicamente a main branch
  
  


2. Comandos para clonar as aulas e executar

   //em caso de troca para outro armazenamento (por exemplo disco D)
   D:

   // clonando o repositório caso não exista o mesmo no armazenamento

   git clone https://github.com/GuilhermeCamargo744/aula-fecaf-noite-dog-ever-match

   // selecionando a pasta que foi clonada

   cd aula-fecaf-noite-dog-ever-match

  //trocamos para a branch da aula atual com

  git checkout aula-numeroDaAula

   // em caso de alterações futuras do projeto com o mesmo já clonado ou atualizando a branch atual podemos executar um git pull para atualizar o repositório local

   git pull

  //podemos também verificar se todos os modulos e itens do projeto estão instalados com

  npm install

  //que verificará e em caso de falta instalará as dependencias

   // podemos executar o vscode diretamente pelo terminal com a pasta selecionada colocando

   code .

   //e iniciar o projeto utilizando

   npm run start

   // em caso de visualização web pressione w, em caso de visualização pelo android studio aperte a.
   --------------------------------------------------------------------------------------------------------------
