# Automacao-WEB-com-Cypress.

<h2>Documentação do Projeto</h2>

<h3>1 - Pré-requisitos do sistema</h3>
1.1 - Sistema operacional
<ul>
<li>macOS 10.9 e superior (apenas 64 bits)</li>
<li>Linux Ubuntu 12.04 e superior, Fedora 21 e Debian 8 (somente 64 bits)</li>
<li>Windows 7 e superior</li>
</ul>
1.2 - Node.js
<ul>
<li>Node.js 10 ou 12 e superior</li>
</ul>
<h3>2 - Como instalar os Cypress e as dependências do projeto</h3>
<b>Rodar o comando abaixo dentro da pasta do projeto</b>
<blockquote>npm install</blockquote>
<h3>3 - Como executar os Testes</h3>
<b>Comando para abrir o console do cypress:</b>
<blockquote>npm run cy:open:cucumber</blockquote><br/>
<b>Rodar a aplicação em modo headless:</b>
<blockquote>npm run cy:run:cucumber </blockquote>
<h3>4 - Como visualizar os relatórios</h3>
<h4>Comando para gerar relatório dos testes via html.</h4>
<blockquote>npm run report:cucumber</blockquote>
<h4><i>Obs: Ao rodar a aplicação no modo Headless, é gerado um vídeo rodando todos os testes</i></h4>
<h3>5 - Ferramentas e bibliotecas utilizadas</h3>
<ul>
<li>Chance (dados fakes)</li>
<li>Cucumber html repórter</li>
<li>Mochawesome</li>
<li>Cypress Multi Reporter</li>
</ul>
<h3>6 - Integração continua</h3>
<ul>
<li>Integração continua do projeto foi realizada via Github Actions</li> 
</ul>
