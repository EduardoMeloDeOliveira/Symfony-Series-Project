<h1 align="center">Projeto Symfony 🚀</h1>

<p align="center">
    Esse projeto faz parte da minha jornada na formação de Symfony pela Alura. Aqui eu exploro várias funcionalidades do framework e tento aplicar boas práticas no desenvolvimento.
</p>

<h2>Como rodar o projeto</h2>

<p>
    Pra rodar o projeto, é bem simples! Basta clonar o repositório, entrar na pasta do projeto e iniciar os containers Docker com o comando:
</p>

<pre>
<code>docker-compose up -d</code>
</pre>

<p>logo apóis basta dar um <code>composer install </code></p>

<p>finalizando a instalação settei um script pra inciar o servidor basta rodar <code> composer dev </code></p>

<p>e agora sim tudo prontinho</p>

<h2>Notificações por e-mail 📧</h2>

<p>
    Eu usei o <strong>Mailtrap</strong> para testar as notificações via e-mail. Para isso funcionar, configure o servidor SMTP no Mailtrap. Basta pegar as credenciais e colocar elas no arquivo <code>.env</code> do projeto assim:
</p>

<pre>
<code>MAILER_DSN=smtp://&lt;user&gt;:&lt;password&gt;@smtp.mailtrap.io:&lt;port&gt;</code>
</pre>

<h2>Formação Symfony na Alura</h2>

<p>
    Todo esse projeto foi feito como parte da formação <strong>Symfony</strong> da Alura. Se você quiser acompanhar meu progresso e ver como cada módulo foi desenvolvido, dá uma olhada no meu repositório PHP, na pasta <code>Formação Symfony</code>.
</p>

<p align="center">Curtiu? 😄</p>
