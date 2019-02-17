---
layout: single
title:  "Script NotasCrawler"
date:   2019-02-05 15:35:00
categories: [projetos]
excerpt: 'Como simples scripts de Python permitem-nos resolver as tarefas mais "chatas".'
header:
  image: "https://media.giphy.com/media/8PvAjFc4OVR79lQBoJ/giphy.gif"
  teaser: "https://media.giphy.com/media/8PvAjFc4OVR79lQBoJ/giphy.gif"
---

<br />
<br />

{: .text-center}
# Porque fazer sempre o mesmo cansa...

<br />

{: .text-justify}
No dia a dia, deparamo-nos inúmeras vezes com a realidade de sistematicamente consultarmos um determinado site várias vezes apenas para verificarmos se alguma coisa mudou no seu conteúdo. Quer seja em Web-Stores de roupas ou carros, ou até páginas de noticias ou redes sociais, todos nós já passamos por esta situação.

{: .text-justify}
No meu caso o que mais me aborrecia na minha vida de estudante, era a necessidade de ter de efetuar sempre os mesmos passos para puder consultar as minhas notas online, sendo que certo dia fartei de ter de fazer sempre este mesmo processo:

{: .text-justify}
>Abrir browser > Ir ao Site do Instituto > Navegar no site até chegar ao meu separador > Finalmente andar a fazer "scroll" para ver se alguma nova nota tinha sido publicada.

{: .text-justify}
Então decidi simplificar a minha vida fazendo um simples *Webcrawler* capaz de detetar se tinham sido colocadas novas notas no Site e se sim devolver-me o respetivo Link da folha de notas ou até mesmo se possível a própria nota.

{: .text-justify}
Dado o aumento do interesse neste script pelos respetivo colegas de curso, este *Webcrawler* foi evoluindo até aquilo que é hoje.

{: .text-justify}
*WebCrawler*
: Rastreador de Rede em português, é um programa que é capaz de procurar em páginas web online certos conteúdos especificados e devolver ou trabalhar os mesmos de algum modo, de forma automática.


<br/>
<br/>

{: .text-center}
# Desenvolvimento Base do Script


{% include figure image_path="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn-images-1.medium.com%2Fmax%2F1600%2F1*7EUX9QIjq2x1JyFKcjhXsA.png&f=1"%}


{: .text-center}
Problema definido, necessitava então de começar a planear como iria automatizar todo este processo.

<br/>

{: .text-justify}
Decidi utilizar [*Python*](https://www.python.org/), pela simples facilidade de escrever qualquer tipo de programa com esta linguagem. Mesmo sendo esta uma Linguagem [Orientada a Objetos](https://pt.wikipedia.org/wiki/Orienta%C3%A7%C3%A3o_a_objetos), a sua sintaxe permite que seja escrito código complexo, contudo que qualquer um facilmente interpreta o que está a ocorrer mesmo não tendo sólidos conhecimentos prévios sobre a linguagem ou programação no geral (deste modo seria mais fácil incentivar colegas a prosseguirem com este projeto).

{: .text-justify}
Um exemplo disto é o código exemplo abaixo, onde praticamente se pode ler como o programa vai agir:  

<br/>

{% highlight python %}
nome = "Daniel"

if(nome == "Daniel"):
  print("Olá " + nome)
else:
  print("Olá Desconhecido")

# Se o nome for igual a "Daniel" imprime "Olá Daniel"
# Se não for, imprime "Olá Desconhecido"
{% endhighlight %}

<br/>

{: .text-justify}
Inicialmente o objetivo deste script era basicamente questionar ao utilizador um sequencia de perguntas, e de seguida percorrer a respetiva página de notas da turma, e caso fosse encontrado algum link de referência a um *.pdf* de notas, este seria devolvido ao utilizador para o mesmo poder de imediato consultar.



{: .text-justify}
Contudo, após ter criado um script que eficaz-mente respondia a esta estrutura, decidi desafiar-me introduzindo uma funcionalidade de tentativa de interpretação dos *.pdf*'s de forma a poder reconhecer a nota associado ao número de aluno selecionado.

<br/>
<br/>

{: .text-center}
# Elevar a Fasquia


{% include figure image_path="https://upload.wikimedia.org/wikipedia/commons/7/78/Tesseract_OCR_logo_%28Google%29.png"%}

{: .text-justify}
Foi precisamente quando decidi evoluir as capacidades deste script que comecei-me a deparar com maiores obstáculos, mais na vertente da não uniformização por parte do Instituto da maneira como as folhas da notas eram colocadas no Web-site.

{: .text-justify}
Contudo e ultrapassando aqui um pouco a descrição dos problemas enfrentados (mais informação pode ser consultada no repositório do script), a solução que acabei por desenvolver tomava recurso do OCR [*Tesseract*](https://opensource.google.com/projects/tesseract) da *Google* para tentar reconhecer o máximo possível do texto existente nos *.pdf*'s.


{: .text-justify}
Com esta adição no script comecei a ver alguma taxa de sucesso a nível de reconhecimento de texto contudo esta taxa nunca foi elevada o suficiente para seguramente reconhecer sempre todas as folhas de notas que eram colocadas no Web-site.

{: .text-justify}
Apesar das várias melhorias que este projeto foi sofrendo com o tempo, e aquelas que for sofrendo daqui em diante, presumo que a taxa de reconhecimento nunca alcance os 100%, isto a não ser que os próprios *.pdf*'s passem a ser introduzidos de forma uniforme e semelhante entre diferentes módulos/cadeiras.


<br/>
<br/>

{: .text-center}
# Conclusão

<br/>

{: .text-justify}
Em suma, o código-fonte do projeto pode ser consultado no seu repositório indicado abaixo, sendo que qualquer auditoria ao mesmo é bem vinda, sendo que procurei documentar sempre o máximo possível do funcionamento desta solução.

{: .text-center}
**Código Fonte do Projeto pode ser consultado [Aqui](https://github.com/Daniel-Vaz/NotasCrawler_ISTEC)**.
