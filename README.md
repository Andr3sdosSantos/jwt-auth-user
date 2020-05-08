<h1>Autenticação JWT</h1>
<h3>Nesse repositório vamos ver como fazer uma autenticação JWT para a sessão de um usuaŕio</h3>
<p><strong>No terminal</strong></p>
<code>'> yarn init -y'</code>
<p>Agora foi adicionado o <code>package.json</code></p>
<code>'> yarn add express sequelize pg pg-hstore'</code>
<p>Feito isso, você adiciona o framework Express, o ORM Sequelize e o módulo do Postgresql</p>
<code>'> yarn add sequelize-cli nodemon sucrase'</code>
<p>
  Com isso, você adiciona o CLI do sequelize que permite adicionar linhas de código no terminal,
  facilitando na criação do script.
</p>
<p><strong>Agora, vamos adicionar o hash da senha.</strong></p>
<code>'> yarn add bcryptjs'</code>
<p>Chegamos na última extensão, a que de fato faz a autenticação JWT.</p>
<code>'> yarn add jsonwebtoken'</code>
<p color="#993399">Bora codaaaaar!</p>