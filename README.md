# Api Criada para a realização do Projeto integrador Utilizando o framework Spring Boot feito através do Bootcamp Generation Brasil 📖🟢


 #### ✅ - Criação das models Tema e Postagem
 * Utilizando as bibliotecas do Mysql para criacão do banco de dados
 * Tabela Tema com a primary Key
 * Tabela Postagem com a foreign Key
 * Tabela de Usuario
 
 #### ✔️ - Criação dos Repositorys
 * Onde faz a comunicação com o banco de dados criando os metodos
 * GetById para pegar um elemento pelo id
 * GetByName para pegar o elemento pelo nome
  
 #### ☑️ - Criação das camadas de controller para as Requisições Http
 * Get (Para pegar todos os elementos do banco de dados)
 * GetById(Para pegar um elemento pelo seu id)
 * Post (Para criar uma novo Tema ou nova Postagem e a relização de um cadastro de usuario)
 * Put (Para fazer a atualização dos dados de um Tema ou Postagem)
 * Delete (Para Deletar um elemento do banco de dados)
   
 #### ‼️ - Criada a camada de Security
 * Sempre que um usuario faz um cadastro a camada se segurança faz uma criptografia dos dados atraves do encode base64
 * Gera um token que ira ser utilizado no cabeçalho da pagina para que o usuario possa utilizar as outras areas da Api
 
 #### ✅ - Utilização do banco de dados
 * No ambiente de desenvolvimento foi utilizado o banco de dados MySql
 * No ambiente de produção foi utilizado o banco de dados Postgres para realização do deploy e integração com a plataforma do Heroku
  
 #### 🔨 - E realização dos testes feitas todas no insominia
 *Testes dos endpoints Get de Tema/Postagens/Usuario
 *Testes dos endpoints GetbyId de Tema/Postagens 
 *Testes dos endpoints Post de Tema/Postagens/Usuario 
 *Testes dos endpoints Put de Tema/Postagens/Usuario 
 *Testes dos endpoints Delete de Tema/Postagens/Usuario
 
 #### 🔨 - Integração do swagger para deploy na plataforma heroku
 * Foi Criada uma camada na aplicação fazendo a configuração do swagger com os endpoints
 * Foi feito o deploy da api Utilziando a plataforma do heroku, onde disponibilizamos em nuvem para fazer o consumo posteriormente na etapa de front-end
 
  ##### 🔨 - Link da aplicação no heroku e instruções para entrar
  1. - Entre no link https://blogmatheuspessoal.herokuapp.com/swagger-ui/index.html
  2. - Vai abrir uma aba pedindo login e senha
  3. - Coloque o login como root e senha como root
  
  
  #### 🔨 - Demonstrativo dos endpoits de usuario na plataforma do swagger
  ![image](https://user-images.githubusercontent.com/100168699/201541923-5e437409-5f48-4214-894e-3ee59118adca.png)


  ##### 🔨 - Demonstrativo dos endpoits de Tema na plataforma do swagger
  ![image](https://user-images.githubusercontent.com/100168699/201541992-c767542d-7647-407a-95e2-5e100825b966.png)
  
  ##### 🔨 - Demonstrativo dos endpoits de Postagens na plataforma do swagger
  
  ![image](https://user-images.githubusercontent.com/100168699/201542025-55d36bd5-bf53-4620-b1a0-3a77c3a7ae34.png)

  ##### 🔨 - Link do site ja funcionando e feito o deploy pela plataforma do netlify
 https://velvety-otter-3d6507.netlify.app/
 
 
 
 
🎁 Obrigada @Generation pelos aprendizados nessa trilha 

<div align="center">
    <img src="https://i.imgur.com/w8tTOuT.png" title="source: imgur.com" /> 
    <strong>trilha</strong>
