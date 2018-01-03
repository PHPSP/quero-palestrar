<h1 align="center">Quero Palestrar!</h1>
<p align="center">
    Repositório de <i>palestrantes</i> e <i>propostas de palestras</i> para eventos de tecnologia.
</p>
<p align="center">
  <a href="https://github.com/PHPSP/quero-palestrar/issues/new?template=speaker_template.md"><img src="https://user-images.githubusercontent.com/753958/31695073-e7acfc00-b386-11e7-9fa0-26a133d56eaa.png" alt="Cadastrar Palestrante" width="177" /></a>&nbsp;
  <a href="https://github.com/PHPSP/quero-palestrar/issues/new"><img src="https://user-images.githubusercontent.com/753958/31695094-19f445c4-b387-11e7-871a-0a08170911bf.png" alt="Cadastrar Palestra" width="160" /></a>
</p>

---
<p align="center">
    <strong>Clique para Consultar</strong>
</p>
<p align="center">
  <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3A%2APalestrante"><img src="https://user-images.githubusercontent.com/753958/31695466-91656c12-b389-11e7-8db4-4ea4d6e5be90.png" alt="Listar Palestrantes" width="82" height="18" /></a>&nbsp;
  <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3A%2APalestra"><img src="https://user-images.githubusercontent.com/753958/31695580-4526cd86-b38a-11e7-9d10-3abae8e53b5d.png" alt="Listar Palestras" width="63" height="18" /></a>&nbsp;
  <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3A%5BIniciante%5D"><img src="https://user-images.githubusercontent.com/753958/31695715-0c512686-b38b-11e7-953a-2adcc9b29dc0.png" alt="Listar Palestras Iniciantes" width="68" height="18" /></a>&nbsp;
  <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3A%5BIntermedi%C3%A1ria%5D"><img src="https://user-images.githubusercontent.com/753958/31695746-37eb015e-b38b-11e7-8aa1-593334898eea.png" alt="Listar Palestras Intermediárias" width="96" height="18" /></a>&nbsp;
  <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3AJavaScript"><img src="https://user-images.githubusercontent.com/753958/31695796-73685dd0-b38b-11e7-8a67-2c05d68a7abc.png" alt="Listar Palestras de JavaScript" width="71" height="18" /></a>&nbsp;
  <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3APHP"><img src="https://user-images.githubusercontent.com/753958/31695830-a06c992c-b38b-11e7-8765-6c260cdebb71.png" alt="Listar Palestras de PHP" width="33" height="18" /></a>&nbsp;
  <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3A%22%40S%C3%A3o+Paulo+-+SP%22"><img src="https://user-images.githubusercontent.com/753958/31695863-c30f67b6-b38b-11e7-936d-70f72190a40b.png" alt="Listar Palestrantes de São Paulo - SP" width="105" height="18" /></a>&nbsp;
</p>

---

## Motivação

O mundo de desenvolvimento de software tem presenciado um enorme crescimento no número de eventos e de **pessoas interessadas em palestrar**. Contudo, os organizadores de eventos continuam se deparando com dificuldades para encontrar palestrantes.

A ideia desse projeto é ser um repositório central de **propostas de palestras** que permita que *pessoas interessadas em palestrar* cadastrem suas propostas e que *organizadores de eventos* encontrem mais facilmente potenciais palestrantes.

## Como funciona?

O processo de cadastramento é simples e prático. Basta realizar o *cadastro do palestrante* e, em seguida, o *cadastro da proposta de palestra*.

### 1. Cadastro do palestrante

Crie uma *issue* para cadastrar o palestrante clicando em [**cadastrar palestrante**](https://github.com/PHPSP/quero-palestrar/issues/new?template=speaker_template.md). Como ***título da issue*** utilize o *nome completo* do palestrante. No ***corpo da issue*** adicione o *nome completo*, *e-mail*, *cidade*, *site ou blog*, *redes sociais*, *imagem* e *mini-bio* do palestrante. Veja o exemplo:

Nome: **Gabriel Rodrigues Couto**  
E-mail: gabriel@r3c.com.br  
Cidade: *São Paulo - SP*  
Site e blog: http://www.r3c.com.br *(opcional)*  
Facebook: [gabrielrcouto](https://www.facebook.com/gabrielrcouto) *(opcional)*  
*...*  
Imagem: https://avatars2.githubusercontent.com/u/2197005  
Biografia:

>  Evangelista PHPSP, head de tecnologia na Memed e apaixonado por desafios impossíveis. Formado em engenharia da computação, programador PHP há mais de 10 anos, defensor do open source e autor de dois projetos que chamaram a atenção do GitHub em 2016.

Após finalizar o cadastro do palestrante, lembre-se de guardar o *número da issue* pois ele será utilizado no cadastro da proposta de palestra.

### 2. Cadastro da proposta de palestra

Crie uma *issue* para cadastrar a proposta clicando em [**cadastrar proposta de palestra**](https://github.com/PHPSP/quero-palestrar/issues/new). Como ***título da issue*** utilize o *título* da palestra. No ***corpo da issue*** adicione o *título* da palestra, as *palavras-chaves* relacionadas ao assunto da palestra, o *nível*, o *nome do palestrante* informando o número da issue do cadastro do palestrante, uma *descrição* que deixe claro o que será abordado e links para *slides*, *vídeo* e *repositório no GitHub*, esses últimos opcionais. Veja o exemplo:

Título: **Como Programar Melhor Jogando Game Boy**  
Palavras-chaves: `php`, `internals`, `performance`  
Nível: *básico*  
Palestrante: [**Gabriel Rodrigues Couto**](5)  
Descrição da palestra:  
> Sabe aquele projeto de final de semana que você sempre quis fazer e nunca deu tempo ou prioridade? Nessa palestra, será mostrado como um projeto de final de semana chamou a atenção da comunidade no Github, como ele ajudou a compreender melhor o funcionamento interno do PHP e as melhorias de código que podem ser feitas para performance. E tudo isso jogando Game Boy em um emulador feito em PHP.

Slides: https://slideshare.net/gabrielrcouto/como-programar-melhor-jogando-game-boy *(opcional)*  
Vídeo: https://youtu.be/uo2ZcF5HgYg *(opcional)*  
GitHub: https://github.com/gabrielrcouto/php-terminal-gameboy-emulator *(opcional)*  

#### Recomendações:

1. utilize as regras gramaticais corretamente (isso torna clara a intenção da proposta e passa mais credibilidade)
2. escolha um título que descreva bem e provoque interesse pela sua palestra
3. adicione 3 ou 4 palavras-chaves de temas que sua palestra abordado
4. crie uma descrição que explique o que sua palestra abordará de forma concisa (de 300 a 500 caracteres)

## Por que o GitHub?

O GitHub possui diversas características que o torna uma excelente opção para o respositório de **propostas de palestras**. São elas:

* utilização pela maioria dos desenvolvedores
* facilidade de organização utilizando *issues* e *labels*
* facilidade de busca (internamente ou através de mecanismos de busca)
* transparente
* promove a interação
