<h1 align="center">🌤️ Weather App</h1>

<p align="center">
    Um aplicativo simples de previsão do tempo desenvolvido com <strong>HTML, CSS e JavaScript</strong>, 
    consumindo a API do OpenWeatherMap para exibir informações climáticas em tempo real.
</p>

<hr>

<h2 align="center">📌 Sobre o Projeto</h2>

<p align="justify">
    Este é um aplicativo de previsão do tempo que permite ao usuário pesquisar qualquer cidade ou país 
    e obter informações climáticas atualizadas, como temperatura, umidade e velocidade do vento.
</p>

<h2 align="center">🚀 Funcionalidades</h2>

<ul>
    <li>✅ Pesquisa de cidade ou país para obter dados climáticos em tempo real.</li>
    <li>✅ Exibição de temperatura, umidade e velocidade do vento.</li>
    <li>✅ Ícones dinâmicos representando as condições climáticas.</li>
    <li>✅ Mensagem de erro caso a cidade ou país não sejam encontrados.</li>
</ul>

<h2 align="center">🛠️ Tecnologias Utilizadas</h2>

<ul>
    <li><strong>HTML5</strong> - Estrutura da aplicação</li>
    <li><strong>CSS3</strong> - Estilização e layout</li>
    <li><strong>JavaScript</strong> - Lógica de programação e consumo da API externa</li>
    <li><strong>OpenWeatherMap API</strong> - Fornecimento de dados climáticos</li>
</ul>

<h2 align="center">📂 Estrutura do Projeto</h2>

<pre>
/weather-app
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── humidity.png
│   ├── mist.png
│   ├── rain.png
│   ├── search.png
│   ├── wind.png
├── index.html
├── style.css
├── script.js
</pre>

<h2 align="center">⚙️ Como Executar o Projeto</h2>

<p>Siga os passos abaixo para executar o Weather App localmente:</p>

<ol>
    <li>Clone o repositório:</li>
    <pre><code>git clone https://github.com/seu-usuario/weather-app.git</code></pre>

    <li>Abra o arquivo <strong>index.html</strong> em qualquer navegador.</li>
</ol>

<h2 align="center">🔗 API Utilizada</h2>

<p>
    O projeto consome dados da 
    <a href="https://openweathermap.org/api" target="_blank">OpenWeatherMap API</a>. 
    Para utilizar o aplicativo corretamente, certifique-se de ter uma chave de API válida e substituir no código:
</p>

<pre>
const apiKey = "SUA_CHAVE_AQUI";
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?units=metric&q=";
</pre>

<h2 align="center">📸 Demonstração</h2>

<p align="center">Veja abaixo uma prévia do funcionamento do Weather App:</p>
<p align="center">
    <img src="images/example0.png" alt="Demonstração do Weather App" width="600">
</p>

<h2 align="center">📜 Licença</h2>

<p align="justify">
    Este projeto está sob a licença <strong>MIT</strong>. Sinta-se à vontade para usar, modificar e distribuir.
</p>

<h2 align="center">🙌 Agradecimentos</h2>

<p align="justify">
    Obrigado por conferir este projeto! Se gostou, deixe uma ⭐ no repositório e contribua com sugestões ou melhorias.
</p>
