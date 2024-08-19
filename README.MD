<h1>Projeto Django Rest Framework para autenticação</h1>


<h2>O projeto utiliza a biblioteca dj-rest-auth para criar APIs com rotas de autenticação e utilizar tokens para manter sessões autenticadas.</h2>


<p>Este projeto utiliza Django Rest Framework e PostgreSQL em Docker.</p>

<h2>Pré-requisitos</h2>

<p>Antes de começar, você precisa ter os seguintes softwares instalados no seu computador:</p>
<ul>
  <li><a href="https://git-scm.com">Git</a></li>
  <li><a href="https://www.docker.com/">Docker</a></li>
  <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  <li><a href="https://www.python.org/downloads/">Python 3.12+</a></li>
</ul>

<h2>Tecnologias</h2>

<p>Este projeto foi desenvolvido com as seguintes tecnologias:</p>

<ul>
  <li><a href="https://dj-rest-auth.readthedocs.io/en/latest/">dj-rest-auth</a></li>
  <li><a href="https://www.django-rest-framework.org/">Django rest framework</a></li>
  <li><a href="https://swagger.io/">Swagger</a></li>
</ul>

<h2>Certifique-se de estar na pasta do projeto</h2>

<h4>Configurar variáveis de ambiente</h4>

<pre>
  <li><a href=""><code>Renomeie o arquivo .env.example para .env e configure as variáveis de ambiente necessárias.</code></a></li>
</pre>

<h4>Iniciando Docker</h4>

<pre><li><a href=""><code>docker-compose up -d --build</code></a></li></pre>

<h4>Rodando o Backend (Django)</h4>

<p>Crie um ambiente virtual e ative-o:</p>

<pre>
  <li><a href=""><code>python -m venv venv</code></a></li>
  <li><a href=""><code>Win: venv\Scripts\activate</code></a></li>
  <li><a href=""><code>Linux/MacOs: source venv/bin/activate</code></a></li>
</pre>

<p>Atualize o PIP</p>

<pre>
  <li><a href=""><code>pip install --upgrade pip</code></a></li>
</pre>

<p>Instale as dependências</p>

<pre>
  <li><a href=""><code>pip install -r requirements.txt</code></a></li>
</pre>

<p>Faça as migrações do banco de dados</p>

<pre>
  <li><a href=""><code>python manage.py makemigrations</code></a></li>
  <li><a href=""><code>python manage.py migrate</code></a></li>
</pre>

<p>Inicie o servidor</p>

<pre>
  <li><a href=""><code>python manage.py runserver</code></a></li>
</pre>

<p>O servidor estará rodando em <code>http://localhost:8000</code>.</p>

<p>Acessando a API via Swagger <code>http://localhost:8000/swagger/</code> </p>
