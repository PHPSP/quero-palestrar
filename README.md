# Quero Palestrar!

<p align="center">
  <a href="https://github.com/PHPSP/quero-palestrar/issues/new"><img src="https://user-images.githubusercontent.com/753958/30899543-a66b849c-a336-11e7-9d78-c46852086841.png" alt="Cadastrar Palestra" width="155" /></a>
</p>

## Motivação

O mundo de desenvolvimento de software tem presenciado um enorme crescimento no número de eventos e de **pessoas interessadas em palestrar**. Contudo, os organizadores de eventos continuam se deparando com dificuldades para encontrar palestrantes.

A ideia desse projeto é ser um repositório central de **propostas de palestras** que permita que *pessoas interessadas em palestrar* cadastrem suas propostas e que *organizadores de eventos* encontrem mais facilmente potenciais palestrantes.

<p align="center">
    <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3APalestra">
        <img src="https://user-images.githubusercontent.com/753958/31208197-65eadf70-a959-11e7-9d63-05ab407bf0f4.png" alt="Ver Palestras" width="118" height="34" /></a>
    <a href="https://github.com/PHPSP/quero-palestrar/issues?q=is%3Aissue+is%3Aopen+label%3APalestrante">
        <img src="https://user-images.githubusercontent.com/753958/31208199-6a072334-a959-11e7-9979-8722a5df10b4.png" alt="Ver Palestrantes" width="140" height="34" /></a>
</p>

## Como funciona?

Para cadastrar sua proposta, abra uma issue para cada *proposta de palestra* que deseja cadastrar. Se essa for a sua primeira proposta a ser cadastrada, recomendamos que faça também o cadastro do *palestrante*.

### Cadastro do palestrante

Para cadastrar o palestrante, clique em [**cadastrar palestrante**](https://github.com/PHPSP/quero-palestrar/issues/new?template=speaker_template.md) e uma issue será criada para a realização do cadastro.
Como título da issue, utilize o *nome completo* do palestrante. No corpo da issue adicione o *nome completo*, *e-mail*, *cidade*, *site ou blog*, *redes sociais*, *foto* e *mini-bio* do palestrante. Veja o exemplo abaixo:

Nome: **Gabriel Rodrigues Couto**  
E-mail: gabriel@r3c.com.br  
Cidade: *São Paulo - SP*  
Site e blog: http://www.r3c.com.br *(opcional)*  
Facebook: [gabrielrcouto](https://www.facebook.com/gabrielrcouto) *(opcional)*  
Twitter: [gabrielrcouto](https://twitter.com/gabrielrcouto) *(opcional)*  
GitHub: [gabrielrcouto](https://github.com/gabrielrcouto) *(opcional)*  
LinkedIn: [gabrielrcouto](https://www.linkedin.com/in/gabrielrcouto) *(opcional)*  
SpeakerDeck e SlideShare: [gabrielrcouto](https://www.slideshare.net/gabrielrcouto) *(opcional)*  
Imagem: https://avatars2.githubusercontent.com/u/2197005  
Biografia:

>  Evangelista PHPSP, head de tecnologia na Memed e apaixonado por desafios impossíveis. Formado em engenharia da computação, programador PHP há mais de 10 anos, defensor do open source e autor de dois projetos que chamaram a atenção do GitHub em 2016.

Após o preenchimento correto das informações do palestrante, clique no botão ***Submit new issue*** para finalizar o cadastro do palestrante. Lembre-se de guardar o *número da issue* pois ele será utilizado no cadastro das propostas de palestra.

### Cadastro da proposta de palestra

Para cadastrar sua proposta, clique em [**cadastrar proposta de palestra**](https://github.com/PHPSP/quero-palestrar/issues/new) e uma issue será criada para a realização do cadastro.
Como título da issue, utilize o *título* de sua palestra. No corpo da issue adicione o *título* da palestra, as *palavras-chaves* relacionadas ao assunto de sua palestra, o *nível*, o *nome do palestrante* informando o número da issue do cadastro do palestrante), uma *descrição* que deixe claro o que será abordado e links para *slides*, *vídeo* e *repositório no GitHub*, esses últimos opcionais. Veja o exemplo abaixo:

Título: **Como Programar Melhor Jogando Game Boy**  
Palavras-chaves: `php`, `internals`, `performance`  
Nível: *básico*  
Palestrante: [**Gabriel Rodrigues Couto**](1)  
Descrição da palestra:  
> Sabe aquele projeto de final de semana que você sempre quis fazer e nunca deu tempo ou prioridade? Nessa palestra, será mostrado como um projeto de final de semana chamou a atenção da comunidade no Github, como ele ajudou a compreender melhor o funcionamento interno do PHP e as melhorias de código que podem ser feitas para performance. E tudo isso jogando Game Boy em um emulador feito em PHP.

Slides: https://slideshare.net/gabrielrcouto/como-programar-melhor-jogando-game-boy *(opcional)*  
Vídeo: https://youtu.be/uo2ZcF5HgYg *(opcional)*  
GitHub: https://github.com/gabrielrcouto/php-terminal-gameboy-emulator *(opcional)*  

Após o preenchimento correto das informações do palestrante, clique no botão ***Submit new issue*** para finalizar o cadastro do da proposta de palestra.

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
