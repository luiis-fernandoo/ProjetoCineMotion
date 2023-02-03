# ProjetoCineMotion

Projeto de conclusão da matéria de LPOO - Professor Woquiton.

Alunos: Luis Fernando Teixeira Oliveira, Savio Santos e João Victor Ulisses.

Nome do Sistema: CineMotion.

O sistema consiste em um site de amostra de filmes e venda de ingressos online para uma rede de cinema.
No site temos dois usuários possíveis, que são eles: Cliente e Administrador. Eles são selecionados a partir da tela de login.
Um usuário comum só terá acesso caso faça seu cadastro, informando os dados no sistema e fazendo login após a inserção. Já o administrador 
terá um usuário cadastrado no sistema de antemão. Com esse usuário, ele fará login e será redirecionado para uma página especificamente
feita para o gerenciamento do site. Nela é possível cadastrar, editar e excluir filmes, sessões e clientes. Sendo assim possível controlar 
todos os passos do site. Podendo trocar os filmes que estão em sessão, o horário, preço, número da sala ou quantidade de ingressos disponíveis
para aquela sessão. Ou até mesmo trocar a foto da capa do filme que está sendo colocada em sessão.
Já o cliente tradicional, após o login, ele é redirecionado a página de filmes em cartaz. Nele você terá acesso a descrição do filme que está 
comprando e quando selecionar em comprar ingresso, será redirecionado a página de compra, onde terá todas as informações da sessão do filme
que o cliente está comprando, como horário, preço, filme que está sendo reproduzido e etc. Porém o cliente precisará informar dois dados.
Sendo eles o assento que ele pretende se sentar e o tipo de ingresso que ele irá querer (Inteira ou Meia). Após informar esses dados o cliente
poderá baixar o comprovante com o pdf contendo todas as informações necessárias para ser identificado na portaria do cinema.

O banco de dados "CineMotion" possui todas as tabelas e insert necessários dos filmes para funcionar de primeira. Porém é possível começar do
zero, cadastrando todos os filmes e sessões pelo próprio sistema.
O único usuário que será cadastrado pelo sistema é o de administrador. Seu usuário e senha são "admin@gmail.com" e a senha "123".
Caso queira utilizar as funções de cliente, apenas precisará inserir os dados fictícios no cadastro. Porém o login realmente funciona, então
use o mesmo usuário.

lembrando que a conexão do banco de dados é utilizada um usuário e senha: 
	
	private String driver = "com.mysql.cj.jdbc.Driver";
	private String url = "jdbc:mysql://127.0.0.1:3306/CineMotion?useTimezone=true&serverTimezone=UTC";
	private String user = "root";
	private String password = "Luis";

Por isso, será necessário haver uma troca do "user" e "password" pelo usuário e senha do mysql do usuário.

A IDE utilizada foi o "eclipse" por não conseguir fazer o import para o intellij, provavelmente uma incompatibilidade com o java utilizado
no meu computador. 
Para a instalação do tomcat no eclipse é bem simples. porém é importante alertar que a IDE eclipse utilizada é a versão Web Developer:



Após a instalação da IDE. Baixamos a pasta do tomcat. Para o download, pesquisamos no google “tomcat” e no primeiro link, entramos na página principal. Após isso, baixe a versão 9 do tomcat. Extraia o arquivo e coloque-a no disco c do seu computador. 
Já no eclipse, você irá em window > preferences e rolando pra baixo procure a opção servers e depois em runtime environment. Lá você irá adicionar a pasta tomcat que você extraiu no disco c. após isso clique em apply & close e pronto. o server rodará o sistema.

Link para o video do youtube: https://youtu.be/-ABCZWjLv0E

  
