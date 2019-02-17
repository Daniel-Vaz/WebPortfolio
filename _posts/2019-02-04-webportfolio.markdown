---
layout: single
title:  "O Meu Web-Portfólio"
date:   2019-02-04 10:00:00
categories: [projetos]
excerpt: 'Uma visão das ferramentas que tornam este Web-site uma realidade.'
header:
  image: /assets/thumb_site.jpg
  show_overlay_excerpt: false
  teaser: "https://media.giphy.com/media/55cTEgOSm6A2sVj41L/source.gif"
---


<br/>

{: .text-center}
Passamos por tempos em que possuímos as ferramentas, que ultrapassavam a mais ampla imaginação de qualquer um dos nossos antecessores.

<br/>

{: .text-center}
# O Crescimento da Web

<br/>

{: .text-justify}
Revolucionando a maneira como o ser humano passou a comunicar, o surgimento das redes por *IP* e a massiva adaptação do protocolo *TCP* para suportar uma sólida estrutura do protocolo *HTTP*, a Web começou exponencialmente a ser aceite e moldada ás necessidades dos seus utilizadores.

{: .text-justify}
Apesar de mais complicados (e inevitavelmente mais primitivos em comparação com as alternativas atuais), os métodos usados para  criação de páginas nesta rede começaram desde logo a evoluir, dando inicio ao surgimento de  alternativas para os simplificar e criar.

{: .text-justify}
Devido aos vastos avanços que surgiram ao longo da história destas plataformas, surgiram possibilidades que permitiam a qualquer pessoa interessada (mesmo não tendo historial técnico), de construir o seu próprio site. Tais soluções são estas como o [WordPress](https://wordpress.com/), [Drupal](https://www.drupal.org/) ou outras plataformas na Web de "[Content Management](https://pt.wikipedia.org/wiki/Sistema_de_gerenciamento_de_conte%C3%BAdo)" que permitem a criação deste tipo de páginas.

{: .text-justify}
No meu caso em particular, sempre houve a necessidade de ter um espaço onde pudesse partilhar todos os projetos em que iria participando, contudo apenas colocar o código num GitHub/GitLab ou outro qualquer sistema de versionamento semelhante, não era suficiente pois sentia sempre a necessidade de expor mais informação sobre os mesmos para que qualquer um pudesse verificar/interpretar/criticar esses mesmos projetos.

{: .text-justify}
Porem ao mesmo tempo estava consciente que seria em grande parte desnecessário o trabalho em torno da criação completa de um web-site de raiz, (mais os custos associados para o Hosting do mesmo) apenas para expor alguns dos meus projetos pessoais. Era apenas desnecessário.

<br/>

{: .text-center}
Contudo, tudo muda graças a soluções como [Jekyll](https://jekyllrb.com/) e as suas fáceis capacidades de integração com outras ferramentas.

<br/>
<br/>

# Jekyll

{% include figure image_path="https://jekyllrb.com/img/jekyll-sticker.png"%}

<br/>

{: .text-center}
> "In open source, we feel strongly that to really do something well, you have to get a lot of people involved."
<cite>Linus Torvalds</cite>

<br/>

{: .text-justify}
*Jekyll*
: Uma solução simples Open Source escrita em *Ruby* que responsabiliza-se por receber páginas escritas em [Markdown](https://pt.wikipedia.org/wiki/Markdown) e fazer Output de páginas estáticas completas, escritas em *HTML/CSS/JavaScript*.

<br/>

{: .text-justify}
Esta solução é excelente para qualquer um que pretenda criar uma página de Internet que não tenha comunicação com um Servidor de Base de Dados nem necessite de recorrer a *PHP* ou outras soluções semelhantes para gerar conteúdo dentro da página.

<br/>

*Sites Estaticos*
: Estes são páginas Web que são devolvidas ao utilizador tal como são escritas/armazenadas. Distinguem-se dos sites dinâmicos que geram conteúdo à medida que ações são exercidas na página/aplicação.  

<br/>

Outra vantagem inerente, é o fato que este tipo de ferramentas permitem de forma eficiente, segmentar o conteúdo do site, da sua estrutura em código, deste modo o escritor(es) pode apenas se focar no conteúdo dos seus textos, sem ter a preocupação mais tarde de ter de formatar os mesmos apenas para ficarem esteticamente apelativos quando colocados no site.

{: .text-justify}
Existem ainda outras soluções como o *Jekyll*, que servem exatamente o mesmo propósito, sendo dignos de destacar o [HuGo](https://gohugo.io/) e o [Gatsby](https://www.gatsbyjs.org/), contudo existem inúmeros outros e felizmente a grande maioria são projetos *Open-Source*.

{: .text-justify}
Apesar de indiscutivelmente muitos outros cumprirem esta mesma função de forma eficiente, o jekyll tem a idade do seu lado, sendo uma solução mais antiga já foi mais fortemente reforçada através de inúmeras contribuições de diferentes partes do mundo.

<br/>

{: .text-center}
Pode ser consultado uma listagem de diferentes alternativas destes projetos [Aqui](https://www.staticgen.com/).

<br/>

{: .text-justify}
Contudo, o Jekyll constrói apenas o nosso Web-site, sendo que ainda não resolvemos o nosso dilema a nível do Hosting do mesmo.

<br/>
<br/>

# GitHub Pages

{% include figure image_path="https://jekyllrb.com/img/octojekyll.png"%}

{: .text-justify}
Existem algumas soluções na Web para permitir o hosting gratuito de páginas estáticas, nomeadamente o [Cloud Storage](https://cloud.google.com/storage/docs/hosting-static-website) da *Google*, o [Netlify](https://www.netlify.com/), o [Surge](https://surge.sh/), entre alguns outros, contudo o [*GitHub Pages*](https://pages.github.com/) é ele mesmo construido usando o *Jekyll*, e graças a isso é extremamente fácil integrar um projeto deste tipo nesta mesma plataforma, visto que esta se encontra muito bem preparada para saber lidar com os ficheiros, fazer eventuais overrides de temas, e outras pequenas nuances em torno de algumas características especificas de integração.

{: .text-justify}
O objetivo deste tipo de plataformas de hosting é permitir que qualquer um facilmente consiga ter a sua própria página podendo expor qualquer ideia ou projeto que pretenda desenvolver, sem ter de contrabalançar custos associados a este tipo de suporte. Note-se contudo que obviamente caso comecemos a falar e desenvolver uma plataforma Web mais avançada, vamos inevitavelmente de começar a necessitar de Bases de Dados e outras soluções semelhantes, obrigando assim alojar essas plataformas ou em servidores arrendados ou em servidores "[Bare Metal](https://en.wikipedia.org/wiki/Bare-metal_server)" locais, soluções estas que já se iram tornar dispendiosas.

<br/>
<br/>

{: .text-center}
# Este "Blog"

<br/>

{: .text-justify}
Após o descobrimento das soluções referenciadas acima, senti que seria fácil demais a criação deste tipo de páginas, ao ponto de ser impossível desvalorizar a ideia de desenvolver um projeto com estas tecnologias. Associando este novo descobrimento há necessidade indicada acima de um local onde pode-se expor os meus projetos, avancei com o planeamento deste Web-site.

{: .text-justify}
Apesar de ter um aspeto final básico, os fortes mecanismos de estrutura por detrás desta solução permitem que mais tarde caso pretenda mudar o aspeto desta página, possa apenas transladar as já criadas documentações nos diferentes posts para um novo Tema, deste modo agilizando todo o processo de "rebranding" ou de reestruturação visual da página.

<br/>

{: .text-center}
**Código Fonte do Projeto pode ser consultado [Aqui](https://github.com/Daniel-Vaz/WebPortfolio)**.

<br/>

{: .text-justify}
Abaixo deixo alguns recursos que achei essenciais quando desenvolvi este mesmo projeto, podendo estes serem um ponto de partida para qualquer um interessado em explorar estas soluções.

| Etapas                                                                    | Apoio                                                                 |
| --------------------------------------------------------------------------|---------------------------------------------------------------------- |
| [Instalação](https://jekyllrb.com/docs/installation/)                     |  Guia de Instalação do *Jekyll*                                       |
| [Temas](https://rubygems.org/search?utf8=%E2%9C%93&query=jekyll-theme)    |  Listagem de temas disponíveis criados pela comunidade                |
| [Integração com o GHPages](http://jmcglone.com/guides/github-pages/)      |  Artigo  devidamente estruturado, sobre a integração com o *GHPages*  |
| [Dominio](http://www.dot.tk/en/index.html?lang=en)                        |  Compra de Domínios                                                   |

<br/>

{: .text-center}
Mais informações sobre as motivações e arquitetura deste mesmo projeto poderão ser consultadas na página "[Sobre]({{site.baseurl}}/sobre)" deste site.
