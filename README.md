<h1 align="center">
  <img src="src\assets\images\logo.svg" alt="Logo"/>
</h1>
<div>
  <img src="src\assets\images\screencapture-letmeask.png" alt="Print-letmeask"/>
</div>
<h2>
  Aplicação
</h2>
<p>
  Aplicação desenvolvida na NLW Together da Rocketseat, um evento online feito com o propósito de disseminar conhecimento e despertar a curiosidade, para criação de salas de Q&A     para ser usado em lives, onde os usuários podem dar likes na perguntas que gostariam que fossem respondidades pela pessoa que está fazendo a live.
</p>
<h2>
  Features
</h2>
<li>Autenticar com a conta do Google utilizando Firebase</li>
<li>Obter informações usuário da conta Google (username e avatar)</li>
<li>Usuário comum tem acesso a sala, podendo dar likes na própria pergunta e/ou de outros usuários</li>
<li>Usuário que cria a sala tem acesso como admin e pode dar destaque na pergunta para mostrar que está respondendo a mesma, marcar a pergunta como respondida e remover pergunta</li>
<li>Na sala de perguntas caso o usuário ainda não estiver conectado, pode se autenticar e manter na sala</li>
<li>Usuário admin pode encerrar a sala</li>
<li>função de copiar código tanto para usuário admin quanto para usuário comum.</li>
<h2>Tecnologias</h2>
<li>React</li>
<li>Typescript</li>
<li>Firebase (Autenticação e Realtime Database)</li>
<li>Context Api</li>
<li>Sass</li>
<li>Classnames</li>
<h2>Executando o projeto</h2>
<p>Utilize o <b>yarn</b> ou o <b>npm install</b> para instalar as dependências do projeto. Em seguida, inicie o projeto.</p>
<div class="snippet-clipboard-content position-relative"><pre><code>yarn start
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yarn start
" tabindex="0" role="button">
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-clippy js-clipboard-clippy-icon m-2">
    <path fill-rule="evenodd" d="M5.75 1a.75.75 0 00-.75.75v3c0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75v-3a.75.75 0 00-.75-.75h-4.5zm.75 3V2.5h3V4h-3zm-2.874-.467a.75.75 0 00-.752-1.298A1.75 1.75 0 002 3.75v9.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 13.25v-9.5a1.75 1.75 0 00-.874-1.515.75.75 0 10-.752 1.298.25.25 0 01.126.217v9.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-9.5a.25.25 0 01.126-.217z"></path>
</svg>
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-check js-clipboard-check-icon color-text-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
  <p>Lembre-se de obter as credencias no Firabase e renomeie o arquivo .env.example para .env.local.</p>
  <div class="snippet-clipboard-content position-relative"><pre><code>REACT_APP_API_KEY = ""
REACT_APP_AUTH_DOMAIN = ""
REACT_APP_DATABASE_URL = ""
REACT_APP_PROJECT_ID = ""
REACT_APP_STORAGE_BUCKET = ""
REACT_APP_MESSAGING_SENDER_ID = ""
REACT_APP_APP_ID = ""
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="REACT_APP_API_KEY = &quot;&quot;
REACT_APP_AUTH_DOMAIN = &quot;&quot;
REACT_APP_DATABASE_URL = &quot;&quot;
REACT_APP_PROJECT_ID = &quot;&quot;
REACT_APP_STORAGE_BUCKET = &quot;&quot;
REACT_APP_MESSAGING_SENDER_ID = &quot;&quot;
REACT_APP_APP_ID = &quot;&quot;
" tabindex="0" role="button">
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-clippy js-clipboard-clippy-icon m-2">
    <path fill-rule="evenodd" d="M5.75 1a.75.75 0 00-.75.75v3c0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75v-3a.75.75 0 00-.75-.75h-4.5zm.75 3V2.5h3V4h-3zm-2.874-.467a.75.75 0 00-.752-1.298A1.75 1.75 0 002 3.75v9.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 13.25v-9.5a1.75 1.75 0 00-.874-1.515.75.75 0 10-.752 1.298.25.25 0 01.126.217v9.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-9.5a.25.25 0 01.126-.217z"></path>
</svg>
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-check js-clipboard-check-icon color-text-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
  <h3>Projeto desenvolvido por</h3>
<p><a href="https://www.linkedin.com/in/igornascimentosaturnino/" rel="nofollow">Linkedin: Igor Saturnino</a></p>
<h3>Projeto original</h3>
<p><a href="https://www.linkedin.com/school/rocketseat/" rel="nofollow"><img src="https://camo.githubusercontent.com/704fabcb9ce2cbd0561b5486ca8cf09ae93be694df8d25f7550e159ab05af350/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d526f636b6574736561742d3934363646463f7374796c653d666c61742d737175617265266c6f676f3d4c696e6b6564696e266c6f676f436f6c6f723d7768697465266c696e6b3d68747470733a2f2f7777772e6c696e6b6564696e2e636f6d2f7363686f6f6c2f726f636b6574736561742f" alt="Linkedin Badge" data-canonical-src="https://img.shields.io/badge/-Rocketseat-9466FF?style=flat-square&amp;logo=Linkedin&amp;logoColor=white&amp;link=https://www.linkedin.com/school/rocketseat/" style="max-width:100%;"></a></p>
