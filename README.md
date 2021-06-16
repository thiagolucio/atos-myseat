## Análise Superficial de URL:

[MySeat by Atos | Reserva de posições de trabalho | Gestão do escritório](https://atos.net/pt-br/brasil-atos/myseat)

### Pontos positivos e acertos:

- Devido a estrutura de layout onde os elementos são grandes no site o que é bom porque visualizações grandes promovem facilidade de leitura e inclusão também no sentido de se tornar agradável visualmente para uma gama maior do público alvo de forma variada. Neste ponto o Site foi bem pensado. 

- Também achei muito bom a escolha das cores que além de coesas possuem um contraste agradável na "medida" certa. 

- A rolagem livre (sem pontos de navegação verticais definidos ao rolar o scroll do mouse) também é um ponto que funcionou bem, e não adicionou complexidade (e mais linhas de código) sem necessidade. É a famosa regra de usabilidade onde o menos é mais, o melhor design é o invisível então a rolagem natural permite isso com classe no site. 

- Por falar em classe o Site possui muito bom gosto. Forte visual corporativo, mas com cores bem usadas e imagens bem escolhidas dando um visual austero, corporativo mas ao mesmo tempo moderno. 

- O fale conosco achei uma sacada genial. Por ser uma multinacional o Fale Conosco no topo do site com um "mega-menu" oferecendo (e exibindo) unidades da empresa (e não são poucas) pelo mundo causa um impacto bem interessante em qualquer perfil de usuário que entre no site. Colocar ela logo no topo além de focar a pessoa na unidade ou perfil regional da empresa sem precisar rolar a página pra isso também é um excelente cartão de atuação da empresa. 

## Pontos límbicos:

- Existe uma referência no slide inicial (pelo menos para mim foi o primeiro a aparecer) que se refere ao produto "My Seat" (me perdoem se estiver engado) e na imagem o produto está sendo exibido em um smartphone. Isso dá a entender de cara que o produto é um App. Estigado pela curiosidade fui procurar o produto nas lojas android e Apple. No entanto em ambas as buscas não tive sucesso em encontrar o produto/ App. 
  
  <img src="file:///home/thiagolucio/Downloads/Atos/androidApp.png" title="" alt="androidApp.png" data-align="center">
  
  Acredito que possa ser uma estratégia da empresa e até mesmo que ele não esteja disponível propositalmente mas se não for este o caso aconselho fortemente investir em posicionamento na loja, até mesmo se necessário efetuando algum pagamento se existir esse tipo de plano. 
  
  Uma questão relevante é que com a pandemia os processos de aceleração desvinculativas de bases empresariais e a tendência do home office não somente em mercado de tecnologia faz com que o produto tenha de ter um forte impacto de marketing com imagens impactantes e que passem imediatamente o valor dele para o público alvo. A imagem utilizada ao bater o olho na minha visão não demonstra de forma clara o foco do Aplicativo. Somente depois de ler entendi que o desenho mostrado na tela do celular do slide é referente ao posicionamento de mesas no escritório e não de um estacionamento em frente a um prédio.
  
  ![myseat.png](/home/thiagolucio/Downloads/Atos/myseat.png)

Uma técnica muito promissora para estes casos é utilizar animações para atrair a atenção do usuário para o banner/ slide e também valorizar a apresentação do produto. Elas estão se tornando comum no mundo corporativo também e tem um impacto enorme (ví esse resultado em vários casos). Em um caso mínimo uma imagem muito bem trabalhada pensando no máximo de informação instantânea que ela pode passar sobre o que o produto faz, na verdade seu valor de preferência. Um exemplo que posso deixar aqui são essas duas animações que fizemos aqui na empresa, abaixo:

http://projetos.charcode.com.br/clubev3partner.mp4

http://projetos.charcode.com.br/casafeliz.mp4

- Animação do Slide slogan demorada ao carregar o slide. Quando eu abri os slides achei o tempo de carregamento das animações dos textos um pouco demoradas. A aparição dos botões (saiba mais) poderiam até mesmo aparecer antes do texto finalizar a animação para que a pessoa possa já clicar nele sem nem esperar o texto terminar e já captar a atenção do cliente de forma imediata para o produto. Principalmente aqueles clientes que já sabem o que querem e estão entrando no site para ver aquele produto específico. Mas quero deixar claro que os slides foram muito em feitos...até mesmo os contrastes que é um problema crônico de slides ficou muito bom sendo perfeitamente legível. Em alguns casos é necessário inclusive colocar um fundo em alpha semitransparente na cor negra ou branca para fazer o contraste do texto ser visível com facilidade e neste caso não foi necessário. Menos imagens, menos peso, menos código, mais performance!

- O menu do topo ficou bom também o tamanho, isso é uma coisa a reforçar que ficou bom, as dimensões escolhidas no site. Apesar de perfil corporativo não seria de mal tom colocar uma suavização na transição do menu ao rolar o mouse da fase transparente para a fase ativa de navegação quando ele fica branco. Essa transição de cor e reposicionamento poderia receber uma transição mais suave pois hoje é instantânea. Eu obviamente não estou considerando outros fatores de desenvolvimento neste caso como complexidade, conflitos de css ou outra questão que tenha feito isso não ser implementado, pode ter sido proposital e desta forma a observação não se sustenta. 

- O campo de pesquisa não foi traduzido. Ao invés de ter o texto "pesquisar" possui o texto "search". Isso é na verdade um esquecimento ou falha de tradução pois acredito que o portal utilize alguma solução como o "i18en..." por exemplo e foi esquecido de ser incluído no JSON de tradução no caso ou não esteja funcionando bem neste componente. 

- Ícones do Site: Eu observei inspecionando o site (porque os ícones ao olhar já suspeitei serem imagens) são utilizados imagens. Para melhorar a performance, redução de código css e até mesmo html poderia ter sido usado algum pacote de ícones como "font-awesome" ou "mdl-icons" ou até mesmo ter-se convertido as imagens em font-icons usando algumas técnicas ou ferramentas como o iconmoon ([IcoMoon App - Icon Font, SVG, PDF &amp; PNG Generator](https://icomoon.io/app/#/select)) que possui o recurso de conversão. 

- Outro ponto de melhoria ainda falando de "íconização" são os campos de select que usam ícones do tipo "arrow" em caracteres ASCI (caracteres de teclado).

  ![asciiarrow.png](/home/thiagolucio/Downloads/Atos/asciiarrow.png)

Seria de bom tom usar aí a mesma solução citada acima com um iconfont e ajudaria inclusive no alinhamento que não está centralizado. É um ajuste pequeno e isso pode ser considerado perfeccionismo mas não posso deixar de reparar isso devido a personalidade que tenho. Eu ia ficar incomodado toda vez que olhasse. 

![veido.png](/home/thiagolucio/Downloads/Atos/veido.png)

A mesma questão pode ser dita do vídeo da página. O botão na minha visão está distorcido, mais largura que altura (pelo menos no centro, o triângulo). Centralizar ele e trocar o ícone por outro mais "player" e igualmente limpo seria uma decisão que eu tomaria com certeza. 

As fontes foram muito bem escolhidas. No entanto as fontes do menu eu colocaria mais espessura nela pra ser mais facilmente visível. Isso é um ponto de pessoalidade no caso, não existe qualquer embasamento técnico para essa opinião, é simplesmente pessoal mesmo. Um ponto muito bom a forma como o menu trabalha. Achei bem elegante e bem feito. 

![fontes-menu.png](/home/thiagolucio/Downloads/Atos/fontes-menu.png)

O formulário de contato não ocupa todo o espaço do container. Eu não entendi muito bem porque dessa escolha no caso. Pode ser que do lado direito dele exista um mapa que não carregou no meu computador. Mas se não existe nada ali do lado de conteúdo aconselho reduzir o tamanho horizontal dele aumento sua largura e deixando o formulário de contato com uma altura menor em relação ao tamanho que ele tem hoje porque formulários são chatos e quanto mais cumpridos forem mais desanima o usuário a preencher. Seu formulário não possui muitos campos mas por ter essa altura ele dá a sensação visual de ter uma jornada de campos maior que realmente possui. 

Campo de Título do assunto ao invés de ter a Opção "Outros", permitir que o usuário digite o título desejado. Poder fazer isso permite que ele deixe uma mensagem que vai direto ao ponto e contribua não somente para uma resposta mais pontual e eficiente mas também dentro da empresa seja rapidamente identificável para quem o email deve ser encaminhado para a elaboração da resposta ou atendimento. Uma solução também pode ser adicionar a condição para que se selecionada a opção "outro" apareça (ou habilite, mas não aconselho essa opção porque seria mais um campo aparecendo) um campo de título/ assunto em branco. Caso não seja possível uma solução como esta pode-se tornar o campo título não obrigatório caso seja selecionado "Outro". Isso porque em "tese" não é mais relevante este campo e sim o campo da mensagem (que é quem vai esclarescer do que se trata e ela pode assumir a primeira posição na hora da leitura do funcionário que estará responsável por ele. 

A gente precisa lembrar que o público interno é nosso primeiro público, pensar nele também é muito relevante porque melhora a comunicação e os processos internos da empresa. 

Já no campo de mensagem só o título mensagem, não precisa colocar "Sua pergunta/ Consulta". 

Por fim não aconselho colocar o campo "Cargo" como obrigatório. Isso porque algumas pessoas não gostam de revelar o nome do cargo ou até mesmo não gosta do cargo que está ocupando além do fato de muitas vezes nem o ter...ou simplesmente a pessoa que está preenchendo, está fazendo isso em nome de outra pessoa que pediu ou solicitou isso pra ele. 

Rodapé:
Este é um ponto interessante. Acredito que ele seja um componente. Pela minha experiência em React e outras Bibliotecas, como ele se propaga em todas as rotas geralmente coloca-se ele na página destas (App ou Index ou home, dependendo do projeto) e isso pode ser a causa do problema mas ele não está em conformidade com a língua da página. Acredito que em qualquer língua esse problema se repita. Ele deveria estar em Português no meu caso e não em Inglês como se apresenta. Eu verifiquei isso olhando o Site na versão Chinesa. Inclusive pude perceber o Captcha na versão do formulário chinesa e não a vi na Brasileira (ponto pra gente, somos mais confiáveis :) ). Ao mesmo tempo que ví uma série de informações ao lado do formulário de contato Chinês que não ví no Brasileiro. Isso explicou o porque do Form alocado na metade esquerda da página. Isso ainda assim poderia ter sido resolvido fazendo ele ocupando 100% do espaço e não aparecendo o conteúdo do lado direito ele se esticaria horizontalmente. 

Ainda no Footer, eu colocaria por esmero uma faixa mais escura no final do rodapé, deixando o texto Privacy, Preference Center.... all rights ... dentro desta faixa numa tonalidade azul mais parecida com a cor esquerda da imagem do rodapé com as letras menores e deixando claro a linha de finalização do site. Tipo o "The end".

### Botão Fixed (email):

Existe um botão "fixed" com o ícone de email que corre fixo na página como comportamento do botão de "voltar ao topo". Eu achei válida a idéia mas o Site possui bastante conteúdo então seria interessante ter o botão de "voltar ao topo" ali também...um poderia ficar em cima do outro como o menu do Gmail android de antigamente.

### Estranhesa no layout depois do rodapé:

Existe alguma coisa errada na página depois do rodapé dela. Eu testei isso em outros navegadores (porque tenho FF, Chrome, Brave, Edge no meu Linux) e fica uma barra estranha no final com um overflow e fundo escuro. Isso aí é uma coisa crítica de layout na minha opinião nem poderia ir pra produção com esse problema (se não for algo da minha máquina mas eu tenho dual boot com PopOS e Fedora e em ambos isso aconteceu).

![coisaestranha.png](/home/thiagolucio/Downloads/Atos/coisaestranha.png)

## Análise da apresentação do valor do produto:

Olhando o produto, percebo que devido as mudanças (eu tinha já citado, tô me repetindo, desculpe) causadas pela pandemia e como ela acelerou a transformação, principalmente digital. O produto enfrenta na minha visão como maior desafio uma queda relevante na necessidade de se "reservar" uma mesa em escritórios cada vez mais vazios e cada vez com mais mesas sobrando no ambiente das empresas. Mas eu vejo claramente um potencial muito maior em todo o restante de nicho de mercado, inclusive justamente impactado pela pandemia. Viaja aqui comigo. 

- Reserva de mesas em restaurantes, shows, ambientes fechados. Todos são um cliente em potencial. 

- Todas as empresas que ainda vão insistir ou que efetivamente precisam manter sua força de trabalho nos escritórios. 

- Mesmo com os escritórios (até mesmo em TI) mais vazios e com menos gente pode surgir a necessidade justamente de para as pessoas que gostam de mesmo que uma vez por semana (ou sei lá com que frequência) usar o escritório pra poder quebrar a rotina, ou pelos mais variados motivos. Este produto se torna bastante atraente.

- Coworking's pelo mundo(eu tive de procurar o plural dessa palavra, confesso): 
  
  Já ví vários estudo falando que é o futuro das empresas. Esses ambientes de trabalho coletivo, colaborativo serão a bola da vez entre os profissionais autônomos e empresas com equipes remotas. Isso por causa do baixo custo, ambiente coletivo e descontraído e livre e pelo Networking entre profissionais, troca de idéias entre outros fatores sociais e profissionais. Este produto é uma pá cheia de ouro para esses ambientes que estão crescendo vertiginosamente e até eu uso um aqui no meu bairro quando estou saturado de trabalhar em casa. 
  
  Seria bastante interessante já visualizar este nicho de mercado e sair na frente não focando somente no mercado de empresas tradicionais que estão provavelmente com os dias contados. 

- 

- 

- ## Degustação:

Uma técnica de vendas para sistemas e App's é a degustação. Acredito que poderiam disponibilizar alguma coisa do gênero para que o possível cliente pudesse experimentar um tour pelo App (mesmo que virtual ou animado) e entender como ele funciona e como ele poderia ser bom para o negócio dele. 

É uma técnica muito eficaz porque pra que a pessoa faça a degustação ela deve deixar dados dela e da empresa dela e posteriormente, com uma equipe dedicada e eficiente (porque não adianta ser aquele pessoal chato que tenta te convencer a comprar o produto sem preparo que nem o pessoal da herbalife ou cursos toscos de informática e inglês) poderá depois de fazer uma análise do possível cliente e entender o negócio dele abordar ele de forma eficiente e reverter uma desistência ou finalizar uma dúvida de compra pra ganhar mais clientes. 

Com o  "Conta Azul" funcionou enormemente esta solução mais que dobrando o número de clientes que contrataram a plataforma (inclusive eu por um tempo, rsrsrs) mas o mercado está repleto de exemplos, Keeps, Nexxera, entre outras Startups que salvaram suas rodadas de investimento praticando esta técnica de forma preparada e eficiente. 

#### Foi mal o testamento...

Eu poderia me estender mais até mas acho que já tá um testamento...Vai ficar um bom tempo lendo isso tudo aí...e como todo bom UX de Interação e UI de interface eu escrevo pra baralho!

Eu também vou deixar de lado a análise da Responsividade. Posteriormente posso fazer se for necessário. Mas seu dia tem 8 horas de trabalho né. rsrsrsrs.

### Agradecimento:

Obrigado por seu tempo e pelo papo e processo das entrevistas. Foi realmente um processo leve e com boa sinergia. Independente de qualquer coisa, continuem assim neste caminho que vão ter muito sucesso nos processo. Foi o mais leve e fluído que fiz até agora. 

Grande abraço e Be Safe!
