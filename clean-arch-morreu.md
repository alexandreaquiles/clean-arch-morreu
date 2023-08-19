**[Alexandre Aquiles]**

Mas é... Então vamos lá pessoal. Meu nome é Alexandre Aquiles.

> [Twitter do Alexandre Aquiles](https://twitter.com/alex_aquiles)

Eu não vou falar onde eu trabalho, acho que vocês devem saber, né? Porque aqui o negócio é entre a gente mesmo. É papo nosso aqui mesmo.

Eu lancei um livro recentemente, né? Desbravando SOLID. Deixa eu fazer o jabá já, né? Desbravando SOLID.

> [Livro "Desbravando SOLID"](https://www.casadocodigo.com.br/products/livro-desbravando-solid)

E aí eu fiz esse livro. E, no capítulo final eu chego numa Arquitetura Hexagonal. Pelo menos eu acho que eu chego. Então vamos ver se eu cheguei mesmo hoje. Pode ser uma pauta.

Mas aí... eu postei lá no Twitter referenciando um Hipsters que o Linhares e a Roberta Arcoverde e o Otávio Lemos e o Vinícius Dias e o Rodrigo Ferreira e o Paulo da Caelum/Alura, eles estavam discutindo sobre Clean Architecture e aí repercutiu.

> [Episódio do podcast Hipsters sobre Clean Architecture]( https://www.hipsters.tech/clean-architeture-hipsters-ponto-tech-254/)

Vários comentários, várias threads diferentes e tal.

> [Tweet original que menciona o famoso episódio](https://twitter.com/alex_aquiles/status/1556657213107732480)

É sobre isso que a gente vai falar. E aí eu coloquei um título meio marqueteiro, né?
"Clean Arch morreu?"

> [Twitter Spaces "Clean Arch morreu?"](https://twitter.com/alex_aquiles/status/1557105442723172354)

Até estava falando com o Aniche e com o Linhares que é para fazer uma referência àquele papo lá do "Is TDD Dead?" que teve entre o cara do Rails e o Kent Beck.

> [Debate "Is TDD Dead?"](https://martinfowler.com/articles/is-tdd-dead/)

Então é uma brincadeira, na verdade, né, pessoal?

Se a gente quiser falar "Clean Arch morreu?" vamos falar que não e aí a gente pode fechar aqui. Mas a brincadeira é a gente discutir um pouco sobre isso.

E aí eu queria que os oradores... falassem o nome e... definissem em uma frase: O que é Clean Architecture?

Eu vou começar aí com o Linhares. Vamos lá, Linhares. Manda brasa aí.

**[Mauricio Linhares]**

> [Twitter do Mauricio Linhares](https://twitter.com/mauriciojr)

Já tá querendo a confusão.

Dessa vez eu vou roubar o comentário que mais representa o que eu senti lendo o livro. É o comentário que o Aniche fez no Twitter: que é conteúdo requentado.

Pegou o conteúdo que ele tinha dos outros livros, requentou, mudou de nome e botou lá.

Eu ainda fiquei sem entender o que efetivamente é a tal da Clean Architecture que parece com tudo que a gente já viu antes, só que com coisas com nomes diferentes.

Então eu tô meio confuso ainda.

**[Alexandre Aquiles]**

Boa. Vou na ordem aqui que tá aparecendo pra mim. Então, ô Branas, se apresenta aí pra galera e "o que é Clean Architecture" em uma frase.

**[Rodrigo Branas]**

> [Twitter do Rodrigo Branas](https://twitter.com/rodrigobranas)

Ah, beleza cara.

Bom, eu sou só mais um apaixonado por programação que tem um canal no YouTube e, pra mim, eu concordo bastante com o que o Mauricio [Linhares] comentou. É um conteúdo que é uma mescla de óbvio, superficial e requentado.

> [Canal do YouTube do Rodrigo Branas](https://www.youtube.com/rodrigobranas)

Mas, de certa forma, faz bastante sentido até a fronteira com a camada de domínio que a gente vai discutir aqui hoje.

Então, pra mim, ele é um pouco um clone do Ports & Adapters e uma pitada de DDD.

Mas por isso que eu acho ele superficial, mas depois eu entro um pouco mais nos detalhes.

**[Alexandre Aquiles]**

Certo, beleza. Aniche, você se apresenta e coloca uma definição sucinta?

Eu sei que essas coisas não são para acadêmicos, mas vai lá.

**[Mauricio Aniche]**

> [Twitter do Mauricio Aniche](https://twitter.com/mauricioaniche)

E aí, gente? Meu nome é Maurício.

E definir Clean Architecture em uma frase é difícil, hein?

Mas acho que o que ele tentou naquele livro é mostrar como tentar criar aplicações que vão sobreviver ao tempo, né? Que sejam fáceis de mudar, fáceis de evoluir, fáceis de testar.

Se ele conseguiu isso no livro, é uma coisa que a gente vai discutir. Mas acho que a ideia da Clean Architecture é essa.

**[Alexandre Aquiles]**

Certo. E o próximo que está aparecendo aqui é o Ponte. Ô Ponte, você nem sabe o que está acontecendo agora, né?

**[Rafael Ponte]**

> [Twitter do Rafael Ponte](https://twitter.com/rponte)

Eu cheguei e peguei o bonde andando aqui, ouvi o comecinho, mas...

Não vou me repetir muito, né? Meu nome é Rafael Ponte.

Conhecido como Marajá dos Legados, então vim defender os legados. Embora as pessoas não gostem...

Uma definição rápida de Clean Arch, dado o meu pouco conhecimento, até o que eu estudo é: um excesso de camadas e de indireção para blindar meia dúzia de classes.

Pronto, é assim que eu enxergo na maioria dos projetos que eu tenho visto.

**[Alexandre Aquiles]**

Caramba. Essa foi contundente. Eu senti uma mágoa aí.

Mas... Ô Otávio. Otávio Lemos, beleza? Então, diga aí, se apresente e fale aí a sua definição.

Ah, eu esqueci de falar: façam seu jabás aí também.

**[Otávio Lemos]**

> [Twitter do Otávio Lemos](https://twitter.com/otaviolemos)

Bom pessoal, meu nome é Otávio Lemos, eu sou professor universitário, sou professor da Universidade Federal de São Paulo há 13 anos.

E há 3 anos eu comecei um canal no YouTube, mais ou menos na mesma linha do Branas, falando sobre desenvolvimento de software, engenharia de software.

> [Canal do YouTube do Otávio Lemos](https://www.youtube.com/channel/UC9cOiXh-RFR7KI61KcyTb0g)

E nessa mesma época que eu conheci essas ideias aí do Bob Martin.

Bom, pra mim é, de fato, me parece um... Ele mesmo fala isso, né?

Que é um conjunto de ideias que foram se desenvolvendo sobre arquitetura de software no sentido de organização de código e não de arquitetura de solução ou infra. Mais no sentido de design mesmo.

Mas é um conjunto de ideias antigas, se a gente for ver, porque aparece lá... ele fala do Ivar Jacobson, que é aquele "Desenvolvimento de software guiado por casos de uso".

> [Livro "Object-Oriented Software Engineering: a Use Case Driven Approach", do Ivar Jacobson](https://www.amazon.com/Object-Oriented-Software-Engineering-Approach/dp/0201544350)

E depois tem outras abordagens como Ports & Adapters ou Arquitetura Hexagonal do Alistair Cockburn.

> [Artigo original sobre Arquitetura Hexagonal ou Ports & Adapters, por Alistair Cockburn](https://alistair.cockburn.us/hexagonal-architecture/)

Então, assim, é um punhado de ideias. E me parece que o objetivo é esse. Você ter uma arquitetura na qual você promove as suas regras de negócio e tenta desacoplá-las de outros interesses do sistema.

Claro que você pode abusar disso. Qualquer tecnologia, qualquer abordagem você pode abusar e em vez de ser um benefício, ser uma coisa que vai te atrapalhar.

**[Alexandre Aquiles]**

Certo, eu vou chamar a Roberta. Ela participou do podcast, do famoso podcast aí.

Então Roberta, vou convidar você aqui. Te coloquei aqui numa fria, numa enrascada hein.

**[Roberta Arcoverde]**

> [Twitter da Roberta Arcoverde](https://twitter.com/rla4)

Pois é, Clean Arch pra mim, de acordo também com o que o Otávio falou, me parece uma parada que nem é Clean nem é Arch, né?

É design e não é Clean no sentido de não ser simples, né?

No sentido de adicionar um pouco de complexidade para tentar definir abstrações e isolar interesses que, na minha opinião, sempre que se tenta isolar, o trade-off é que você abre mão de coisas mais sofisticadas que você poderia estar utilizando e que informam o design do sistema.

E abrir mão dessas coisas deliberadamente em nome de uma suposta flexibilidade para a estrutura mude no futuro, para mim, soa um pouco inocente.

Então, talvez seja a melhor forma que eu encontraria de definir por tudo que eu li e que a gente tem discutido nesses dias.

**[Alexandre Aquiles]**

Beleza. Então só pra colocar uns termos que foram aparecendo aí.

Tem muito essa coisa de ser algo antigo, né?

Eu lembro de fazer diagrama UML, aí tinha o diagrama de robustez, que tinha lá o Entidade, Controller e Boundary, né? O ECB.

E o Otávio até falou aí do tal Ivar Jacobson e era isso, né? Vem lá do UML. Inclusive eu acho que antes de existir o UML, na verdade.

Aí tem essa coisa de... eu acho que a Roberta falou, o Ponte falou... Muitas abstrações, muitas indireções.

E eu acho que é isso que a Roberta falou, visa flexibilidade.

Tanto o Otávio como a Roberta falaram aí de design. Então talvez o nome arquitetura seja estranho. Então arquitetura limpa talvez seja um design limpo.

E aí eu tava vendo aqui, tava lembrando, até coloquei um tweet lá de 2017 que eu tava bem radical, digamos.

> [Tweet de 2017 argumentando que POJO com anotações JPA não é POJO porque depende de framework de persistência](https://twitter.com/alex_aquiles/status/930438070163386370)

E aí eu lembro que eu e o Rodrigo [Ferreira], a gente tava querendo estudar sobre arquitetura.

E aí tinham 3 livros que estavam sendo... lançados. Um era o "Building Evolutionary Architectures", lá em 2017.

> [Livro "Building Evolutionary Architectures", por Neal Ford, Rebecca Parsons e Patrick Kua, então da Thoughtworks publicado em Setembro/2017](https://www.oreilly.com/library/view/building-evolutionary-architectures/9781491986356/)

Que era da ThoughtWorks, que o Aniche chegou a mencionar [nas threads]. Tem um negócio de fitness function e tal. Eu não li, para falar a verdade.

Aí tinha um que era o "Design It", que é bem sobre arquitetura, sobre trade-offs, estilos arquiteturais e tal, que era da Pragmatic Programmers. Só que ele não tinha arquitetura no nome.

> [Livro "Design It", por Michael Keeling, publicado na Pragmatic Bookshelf em Outubro/2017](https://pragprog.com/titles/mkdsa/design-it/)

E tinha o "Clean Architecture" que era sobre design mas tinha arquitetura no nome. E foi o que eu escolhi ler. E aí...

> [O famoso - ou famigerado? - livro Clean Architecture, por Robert Martin, o Uncle Bob, publicado em Setembro/2017](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)

**[Mauricio Linhares]**

Você pulou os dois melhores e pegou o pior.

**[Alexandre Aquiles]**

Tipo isso.

Mas aí eu fui tentar aplicar em um freela. Eu e um camarada de Android. A gente estava querendo reaproveitar o modelo.

Foi um desastre nesse caso específico. Porque eu acho que o modelo é diferente de uma aplicação Android e da API, que é o que eu estava fazendo.

E assim, eu não sofri muito porque o negócio não foi para frente. Mas eu acho que eu teria sofrido.

Aí, pessoal, o que eu queria é fazer uma brincadeira aqui...

Ô Linhares, você leu o livro, né? Vamos falar um pouco sobre o livro em si.

> [Um dos tweets em que Linhares comenta o livro Clean Architecture](https://twitter.com/mauriciojr/status/1558277943243284480)

Só que eu quero, foi o Allan Silva que, eu não sei se ele está aqui, mas o Allan Silva que ele deu a ideia do Linhares falar que ele achou de bom no livro.

> [Twitter do Allan Silva](https://twitter.com/__allansilva__)

Então, destaque aí, Linhares, o que você achou de bom no livro.

**[Mauricio Linhares]**

Bicho, aí é difícil.

**[Alexandre Aquiles]**

Dá uma forçada aí. Pensa um pouquinho.

**[Mauricio Linhares]**

Ai, ai. É porque, é porque... Esse livro me levou para muitos momentos traumáticos do passado.

Porque muito do que está sendo discutido, das coisas que estão sendo faladas, são coisas que a gente queria matar ali no meio dos anos 2000, no Java.

Você pega o livro do Rod Johnson, que foi o livro que deu nascimento ao Spring, tem muito essa discussão de como era complicado você criar separação porque a gente tinha toda essa coisa de tudo tem um lugar, tem o Session Bean, tem o Entity Bean, tem um monte de Java Beans, EJB, essa porra toda. E ele vem com essas ideias.

> [Livro "Expert One–on–One J2EE Development without EJB", de Rod Johnson, publicado em 2004 e considerado a certidão de nascimento do Spring](https://www.amazon.com.br/Expert-One-One-Development-without/dp/0764558315)

Nesse livro, acho que esse é o livro do Rod Johnson. Ele tem muitas das ideias que a gente vê aqui de você criar essa separação, de você não deixar o framework ficar dentro da sua aplicação, porque a gente sofria muito para escrever aplicações e testar aplicações por causa do peso que o framework e as coisas do Java tinham em cima da sua plataforma.

E daí surge o Spring, e daí surge o jeito que a gente está escrevendo aplicações Enterprise em Java modernas.

E eu acho que essa coisa de você separar... é importante, né? Eu acho que nisso ele acerta no livro que você realmente precisa separar essas coisas.

Isso é uma coisa que a gente vem fazendo desde o primeiro livro de modelagem e design orientado a objetos que eu lembro de ter lido, que eu acho que é o de UML do Grady Booch.

> [Livro "Object-Oriented Analysis and Design with Applications", por Grady Booch](https://www.amazon.com/Object-Oriented-Analysis-Design-Applications-3rd-dp-020189551X/dp/020189551X)

Que era um dos livros que eram recomendados pra gente na época da faculdade. E era isso... E isso era uma recomendação, né?

Que você não quer que essas coisas entrem dentro do seu código, mas você não vai fazer isso de uma forma radical.

Como lá no teu tweet que você colocou "Ah, não quero nem botar as anotações no meu objeto". Aí você tá indo longe demais no negócio.

Porque a grande preocupação que a gente tinha na época não era de você ter referência ao framework, era como é que eu consigo testar e usar e fazer operações em cima dessas soluções localmente na minha máquina, fazer teste unitário, fazer TDD, você conseguir fazer o design da sua aplicação através dos testes, e eu acho que essa eu vou dizer que é uma das poucas coisas que eu acho que são legais, mas o foda é porque ele é mais radical do que o seu tweet. E é difícil de você separar essas coisas no livro.

Eu tive muita dificuldade de pegar essas coisas e... ah, porra, isso aqui é importante.

É muito importante a gente não deixar essas coisas vazarem para dentro de camadas para onde elas não deveriam ter vazado. Você tem que tentar separar essas coisas.

Eu acho que isso é uma mensagem que é importante, que é uma coisa que a gente repete em modelagem orientada ao objeto já, provavelmente desde que existe modelagem... orientada a objetos.

**[Mauricio Aniche]**

Mas olha como vai de experiência para experiência.

Então, o meu primeiro contato com o trabalho dele foi naquele "Agile Principles, Practices and Patterns", alguma coisa assim, né?

> [Primeira edição do livro "Agile Software Development, Principles, Patterns, and Practices", por Robert Martin, publicada em 2002](https://www.amazon.com/Software-Development-Principles-Patterns-Practices/dp/0135974445)


Foi antes do Clean Code, aliás. Eu estava vindo de 3 projetos na sequência.

Um deles, o primeiro, onde era uma loja virtual que a galera customizou a loja virtual aberta em ASP da Locaweb. Quem lembra disso aqui? E eram aqueles arquivos ASP de 5 mil linhas e tudo acontecia ali.

Aí eu pulei para um projeto na Sony que era o projeto que controlava a venda de DVDs da Sony, era tudo em JSP, e tudo na JSP.

Aí eu fui trabalhar na Verifone, programar em C, tudo num arquivo C completo.

E aí, para mim, não fazia sentido. Não é possível que não dava para ser melhor. E quando eu li aquele livro onde ele introduziu o SOLID pela primeira vez lá, etc e tal, eu falei "porra, até que dá para separar as coisas".

Dá pra ser um pouquinho melhor, não precisa estar tudo no mesmo lugar. Porque acho que a galera colocava, nos projetos que eu participei, estava tudo sempre no mesmo lugar.

E pra mim foi um divisor de águas. Ele dizia, dá pra tentar modelar um pouquinho melhor.

Agora, óbvio, ele é muito extremista na maneira de escrever. Acho que é isso que você tem que ignorar quando lê.

Eu falei em algum tweet disso, que se você for seguir a risca ali, o que ele fala, ele é bem extremista. "Banco de dados é um detalhe" Não sei em que mundo que banco de dados é um detalhe, né?

Mas acho que pra mim foi isso que me agradou no trabalho dele lá em 2006, 2007, quando eu comecei a ler o trabalho dele.

Mas eu concordo em tudo que você comentou, Mauricio [Linhares], que é muito extremista, né? Infelizmente é muito extremista, do meu ponto de vista, claro.

**[Rodrigo Branas]**

Eu ia colocar só 3 pontinhos importantes aqui, tá?

O primeiro ponto que eu acho que todo mundo concorda é que não faz sentido você misturar o inbound driver, ou a inbound port, se a gente pensar em Ports & Adapters, com regra de negócio, que é uma coisa que a gente sempre sofreu ao longo dos últimos 20, 30 anos.

Ou seja, o teu controller tem regra de negócio, a tua tela tem regra de negócio, geralmente o controller e tela, mas se você tivesse um CLI, talvez ele pudesse ter regra de negócio, talvez se você tivesse algum outro tipo de driver da aplicação, era muito comum que a gente presenciasse isso.

Então o primeiro ponto-chave aqui do Clean Architecture é a camada de use cases, que seria... aquela API da application que você expõe pra fora, certo?

Então, acho que nesse ponto, ninguém discorda que isso é uma coisa super válida, né?

É a mesma proposta do Alistair Cockburn, a mesma proposta do Ivar Jacobson, de muitos anos atrás também, e de qualquer um que queira escrever uma aplicação que cresça e que tenha testabilidade e que possa ser conduzida de formas diferentes.

Então, nesse ponto aí, eu acho que o Clean Architecture está perfeito nas colocações.

Ele tem uma questãozinha em relação a Screaming Architecture, que é sempre difícil você pensar naquele nome Service. Qual é o nome do Service? É Order Service, Client Service, Product Service?

Então, ele diz assim: "olha, vamos criar um negócio chamado Use Case, que é a intenção exata do usuário, e a gente dá um nome". Então isso pode pulverizar em uma grande quantidade de classes, mas até aí eu acho que está tudo bem.

Para mim, a grande incongruência do Clean Architecture está em um passo para dentro, não um passo para fora.

Tá tudo certo, separar frameworks e drivers, na minha visão. É inviável porque nem sempre os frameworks são intercambiáveis, mas só o fato de você separar porta pra fora, porta pra dentro, já é uma coisa boa.

O erro pra mim é na camada de Entities, tá?

Rapidamente, só pra transmitir aqui a minha ideia, orientação a objetos é uma coisa muito boa porque ela preserva invariância.

Basicamente esse é o objetivo da orientação a objetos.

Não é simplesmente criar classe, porque você pode criar classe e continuar sendo procedural.

Então você tem que... expor comportamento e preservar características e assim você tem controle de invariância.

Quando você tem um projeto muito orientado a objetos, você tem uma relação entre os objetos. Então você começa a agrupar esses objetos em clusters. Eles começam a ter referência uns pros outros.

Esse é exatamente o conceito do aggregate que o Eric Evans traz em Domain Driven Design.

> [O seminal livro "Domain-Driven Design: Tackling Complexity in the Heart of Software", por Eric Evans, publicado em 2003](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)

E o aggregate tem que ter um determinado tamanho pra que ele mantenha a consistência transacional na hora de você fazer a persistência por meio de repositório.

Para que ele não seja nem muito grande e muito desengonçado e ocupe muito espaço em memória e nem muito pequeno para que a granularidade seja tipo um mapeamento de tabela praticamente, né?

Então é uma linha tênue e difícil de obter. E o Bob Martin não cita isso no livro dele.

Tanto que quando eu vou... Eu tenho um curso sobre Clean Architecture. Não só sobre isso, né? Sobre DDD, SOLID e outras coisas. E eu sempre faço essa mescla.

Então eu começo explicando pelo Ports & Adapters... trago o conceito de Clean Architecture e substituo a camada de Entity por Domain Driven Design, mas aonde houver um domínio suficientemente complexo que pague o custo disso.

Porque se eu tenho uma aplicação muito simples, vai ser burocrático, que é um pouco do que foi colocado por vocês logo no início.

Então, para mim, esse é um tipo de design, um tipo de opção, que serve quando você tem um tipo de domínio mais complexo.

Se você pensa na modelagem estratégica do Domain Driven Design, você separa um domínio em subdomínios, mapeia bounded contexts, e cada bounded context é uma história diferente.

Você pode adotar um scaffolding simples em um e uma orientação a domínio super rica em outros usando DDD.

Mas para mim, sempre aquela mescla de Ports & Adapters e DDD, ela é mais vencedora nesse caso. Clean Arch fica meio que numa sombra disso.

Esse é o meu ponto.

**[Alexandre Aquiles]**

Boa. Vai lá, Otávio.

**[Otávio Lemos]**

Só complementando essa ideia do Branas, eu acho legal quando você começa a perceber que, na verdade, tem a ver exatamente com isso que ele falou.

Você não precisa usar todas as camadas para todos os seus casos de uso.

Inclusive, você pode ter alguns casos de uso mais simples, nos quais você só tem o próprio caso de uso, não entra mais para dentro.

Eu acho que quando você começa a fazer essas adaptações para o seu contexto, aí a coisa começa a fazer mais sentido. Então deixa eu fazer o jabá aqui.

Eu acho que o meu livro é mais simples, né? O meu livro "Arquitetura Limpa na Prática" resume as ideias e mostra um exemplo.

> [Site do livro "Arquitetura Limpa na Prática", do Otávio Lemos](https://www.otaviolemos.com.br/)

E em 100 páginas lá você consegue pegar a essência da Arquitetura Limpa.

E é isso que o Branas falou também, eu acho interessante essa parte. Ninguém reclama de separar front-end e back-end. Isso é uma coisa que a gente já faz faz muito tempo. Seria a parte esquerda da Arquitetura Hexagonal, ou Ports & Adapters.

O galho fica quando você quer desacoplar coisas como banco de dados e aí já fica mais difícil de fazer e não faz sentido em todos os sistemas que você desenvolve.

Tem que ser adaptado ao seu contexto. Então acho que isso vale a pena a gente ter na cabeça, né?

Que o Uncle Bob é muito enfático, né? Então você tem que colocar um filtro ali, não dá pra usar tudo aquilo que ele coloca em todos os sistemas, tem que adaptar pro seu contexto.

**[Alexandre Aquiles]**

Sei. Eu acho que assim, a gente está assumindo que Use Case e vamos dizer, Service, ou coisa do gênero, é uma unanimidade. Agora, é de fato uma unanimidade entre nós aqui, pessoal?

Eu não sei, por exemplo, a Roberta, eu acho que tem críticas, né, Roberta?

Isso dependendo do contexto, né? Qual seria esse contexto para você não usar esse tipo de... de organização de código?

**[Roberta Arcoverde]**

Que tipo de organização que você fala? Distribuído?

**[Alexandre Aquiles]**

Tipo, assim, de separar a camada que está mais próxima da interface com o usuário do resto do sistema.

Tem até um exemplo de um tweet lá que tinha até SQL dentro de um controller, não tinha?

> [Tweet famoso da Roberta que revela um SQL no Controller](https://twitter.com/rla4/status/1302244493329084418)

**[Roberta Arcoverde]**

Ah, não. Mas isso aí é um pouco indesculpável.

**[Alexandre Aquiles]**

Tá. Mas... Por que aquilo?

**[Roberta Arcoverde]**

Eu acho que o foco da aplicação, quando a gente fala de Clean Architecture, de padrões, de modularidade, o que todo mundo quer é escrever uma aplicação que seja resiliente e fácil de manter a longo prazo.

É isso que a gente quer dizer quando a gente fala de qualidade. Ela é fácil de entender, ela é fácil de modificar, ela é fácil de manter em longo prazo.

E tem diversas técnicas e princípios e padrões para fazer isso que não necessariamente... cuja modularidade não é necessariamente o único foco.

Modularidade é um aspecto muito importante de manutenibilidade, mas não é o único.

Eu acho que quando você tem um Big Ball of Mud, ou seja, um sistema cuja arquitetura não pode sequer ser inferida porque ele é escrito de formas completamente aleatórias e tem muitos padrões e é difícil de entender, se você vai escrever código novo, onde aquele código deve ficar, esse não é um mundo que ninguém quer estar.

> [Artigo "Big Ball of Mud", por Brian Foote e Joseph Yoder, de 1999](http://www.laputan.org/mud/)

Eu gosto de divisões de camadas, eu acho que elas são importantes.

Eu acho que uma organização que permita com que o time de desenvolvimento, sempre que quiser alterar o código ou inserir uma nova funcionalidade, saiba exatamente aonde esse código tem que entrar.

Isso é desejável, isso é importante para a manutenibilidade de longo prazo.

Se você está falando de aplicação web que segue MVC, por exemplo, não é legal que você tenha acesso a dados no controlador exatamente por isso.

Agora, é catastrófico? Também não sei se é catastrófico, acho que depende muito. Pode ser que seja, pode ser que não.

Se é um sistema muito pequeno, que não tem tantas alterações assim.

Nesse exemplo que eu dei era de um trecho de código que tava inalterado há 7 anos, então nunca deu dor de cabeça pra ninguém.

Então faz diferença realmente encaixar 3 ou 4 novas classes ali pra separar esses concerns? Não acho que faça, sabe? Não acho que faça.

Eu acho que a coisa que mais me incomoda do tom desse livro e do tom desse autor é, com o perdão do meu francês, a cagação de regra mesmo, sabe?

Parece que existe apenas uma forma de escrever sistemas. Essa é a forma, e quem faz assim tá correto, quem não faz assim tá fadado a escrever sistemas ruins, difíceis de manter.

E é engraçado como comunidade como a gente aceita isso, quando a gente também aceita um princípio que contradiz isso, que é o princípio de que não existe bala de prata, né?

> [Artigo "No Silver Bullet – Essence and Accident in Software Engineering", de Fred Brooks, publicado originalmente em 1986](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf)

É pouco controverso de que em design e arquitetura de software não existam soluções únicas, que tudo depende de contexto, e ao mesmo tempo existe uma resistência a perceber que os designs propostos por Clean Architecture e pelo conjunto da obra do autor, sejam entendidos como os únicos corretos, e que por exemplo, como o Maurício estava falando, como os dois Maurícios
estavam falando, seja interessante abstrair o seu banco de dados.

Ah não, uma boa aplicação, bem feita, ela não deve se preocupar com qual é o mecanismo de storage, quando na verdade eu acho que isso complexifica e atrapalha a manutenibilidade, ao invés de facilitar, porque a decisão de qual mecanismo de storage você vai usar é uma das mais importantes no planejamento de uma arquitetura.

E tentar torná-la invisível traz mais problemas, na minha opinião, do que auxílios.

Não sei se eu respondi a tua pergunta.

**[Alexandre Aquiles]**

Sim, sim. É interessante esse questionamento.

Tem bastante gente querendo falar aqui.

Eu vou passar a palavra na ordem, assim, pro Ponte, pro Aniche, pro Linhares, pro Branas. Beleza? 

Mas vai lá, Ponte.

**[Rafael Ponte]**

Show. Vou pegar aqui a tua pergunta.

Como é que a gente entende o que são Use Cases, né? Acho que o Clean Arch comenta muito.

E de certa forma é algo até aberto. Mas para mim, acho que o Mauricio Aniche, o Linhares já... de muita data aí, mais de 10, 15 anos de experiência, a gente já sofreu demais com a ideia de gerar essas camadas indireção.

Use cases, a gente chama de Service, outros chamam de Manager. Então esse nome foi mudando com o tempo.

Mas isso fazia muito sentido há 15 anos atrás, talvez 10 anos atrás. Eu falando aqui na plataforma Java, que é o meu dia a dia, porque os frameworks não eram maduros o suficiente para conseguir tirar todo aquele glue code, aquele código de infra que a gente era obrigado a ter que implementar, escrever, ou copiar e colar de algum lugar.

Só que isso mudou nos últimos, sei lá, talvez 10 anos para cá, 9, 8 anos para cá.

Você pega uma plataforma como Spring, ou mesmo Java EE, que hoje é o Jakarta EE, e você consegue perceber que o controller que antes a gente temia de deixar qualquer tipo de lógica de negócio, qualquer if, qualquer coisa relacionada ao nosso modelo de domínio, hoje não tem mais esse problema.

Hoje você pegar um controller do Spring basicamente é uma classe, um POJO, com algumas anotações. E só!

O controller está tão limpo, tão simples, onde o framework absorveu toda a complexidade, o glue code que a gente... tentou evitar durante anos, que, para mim, na maioria dos casos, eu enxergo ele como meu Use Case.

E para muitas pessoas, isso é bem feio, porque se eu enxergo ele como Use Case, a chance são de que eu vou injetar um repositório, um ou dois repositórios ali.

E a ideia de que injetar repositório aproxima do banco de dados e está no controller é ainda mais doloroso para muita gente.

Mas se você pensar, a camada de persistência também foi abstraída pelos frameworks. Um repositório de Spring Data, nada mais é do que uma interface com algumas poucas anotações.

E se você usa o JPA e o Hibernate, então você tem uma camada de abstração com o Spring Data, mais uma segunda camada um pouco mais funda que a JPA e o Hibernate que abstrai ainda mais a sua persistência, o JDBC e até um pouco o SQL ali.

Então qual é o problema de encarar o controller como um use case? Hoje, eu encaro ele como um use case até que algo me diga o contrário.

E geralmente o que me diz o contrário é... Tá fácil testar? Tá fácil entender? Eu consigo escrever um único teste aqui de integração?

Ou tenho que quebrar em vários testes para que isso fique mais fácil de testar, ter uma melhor cobertura e tudo mais?

Então, querendo ou não, a manutenção é o que me guia junto com os testes

Então só para deixar claro, eu encaro que um controller é sim uma camada de use case em qualquer literatura de arquitetura que alguém tenha lido aí.

Essa é a minha percepção, porque eu abraço... os frameworks que eu uso.

A primeira regra que eu faço ao entrar em um projeto é abraçar o framework. Eu abraço framework e respeito o que ele me pede para fazer. Em seguida, eu abraço a linguagem de programação.

Se a linguagem e o framework entram em conflito, eu favoreço o framework, porque eu vendi a minha alma para o Spring e eu quero os benefícios de ter vendido minha alma para aquela plataforma.

**[Alexandre Aquiles]**

Hoje em dia eu estou muito nessa linha do Ponte. Mas, ô Aniche, vai lá!

**[Mauricio Aniche]**

Eu acho que a sacada é perceber isso mesmo que a Roberta e o Rafael comentaram, porque se você olha para a aplicação Enterprise, como que ela funciona?

De maneira bem abstrata, como que funciona basicamente grande parte dos casos de uso?

O usuário manda dado, você aumenta esse dado com a informação que você busca no banco de dados,
você faz umas validações, você muda um pouquinho esse dado, você manda de volta para o banco de dados ou manda para um outro serviço web.

Uma grande parte das funcionalidades são isso.

E para modelar esse tipo de coisa, você não precisa de coisa muito requintada, muito chique, entendeu?

Uma básica separação de responsabilidade, os repositórios do Spring aqui, põe uma validaçãozinha se for um pouquinho complicado, um pouquinho ali, etc. e tal,

Isso é mais o que o suficiente, né? Não precisa ir muito mais além.

Eu acho que esse é o ponto, né? Mas aí tem sempre aqueles 20% de funcionalidade que é muito mais complicada no teu sistema, que vai mudar o tempo inteiro, que regra nova entra, regra nova sai, etc. e tal.

Talvez ali vale a pena um design mais rebuscado, e talvez algumas das ideias do livro dele façam sentido.

Mas acho que esse é o ponto, que a aplicação de indústria, uma grande parte das vezes, não precisa de tudo isso.

E o meu exemplo atual, eu trabalho na Adyen hoje, é uma base de código bem grande, um negócio bem complicado, mas se você realmente quebra ele, é isso que eu falei, pega dado, valida e passa o dado para frente, entendeu?

Não precisa de muito mais do que uma separação básica de responsabilidade.

**[Alexandre Aquiles]**

Perfeito. Ô Linhares. Vai lá.

**[Mauricio Linhares]**

Então, aí é que eu acho que a superficialidade do livro atrapalha demais.

Porque a gente está chegando nesses exemplos mais complexos, só que o livro não abraça esses exemplos.

É até esquisito pensar assim, mas o único jeito de você... entender e pegar as ideias do Clean Architecture é se você tiver lido um monte de literatura anterior, se você tiver lido o Domain Driven Design, porque ele passa exatamente 4 parágrafos definindo o que é entidade.

São 4 parágrafos. Ele pega 4 parágrafos do livro e define o que é entidade.

E se você for ver o livro do Eric Evans, primeiro que entidade não é uma coisa só.

Lá no Domain Driven Design, entidade é um pedaço. da camada do modelo. Tem várias coisas que formam a camada do modelo.

Tem uma definição específica para o que é uma entidade, como é que você diferencia uma entidade de um value object.

Então tem várias coisas, tem várias discussões que o livro... Eu não sei por que ele se furta. Eu não sei por que ele não para para explicar, porque a gente vai ter essa ideia que o Ponte falou,
que ele considera que os use cases é o controller.

Que aí a gente vai entrar naquela discussão de boundaries, dos limites.

Mas ele não dá bons exemplos de limites. Cadê o padrão para dar os casos de limites que a gente tem?

Mais uma vez a gente volta lá no Domain Driven Design, tem vários padrões diferentes e inclusive tem a opção que o Ponte está dizendo que é: não faça nada, abrace o que está lá e use o modelo desse jeito.

Então, eu acho que não ter nenhuma dessas discussões, não ter nenhum padrão, não ter nenhuma discussão mais profunda sobre o que são essas coisas, como é que você usa essas coisas.

Eu acho que empobrece muito o livro. E se você já leu o Domain Driven Design, você não vai tirar nada de novo desse livro.

Porque as ideias, essa ideia de separação, essa ideia de você criar essas camadas, de você ter o modelo, inclusive isso que o Aniche falou.

E às vezes seu modelo é só o banco de dados, e lá no Domain Driven Design ele vai dizer, às vezes é isso mesmo, é só o banco de dados.

Você tá ali, por enquanto, você tá pobre, né? Você não tem muita coisa pra colocar.

Então, eu acho que essas discussões de definir os padrões, definir exemplos melhores, né?

Eu achei os exemplos do livro também muito superficiais.

Tem um exemplo lá que me mandou direto pra o Java Enterprise Edition da Sun, né? Que é um livro lá de 2000, Guaraná de Rolha com múltiplas camadas de entrada e saída, e você não pode fazer a entidade vazar lá para a camada web, nem pode fazer a entidade vazar para a camada do banco de dados.

> [Livro "Core J2Ee Patterns: Best Practices and Design Strategies", publicado em 2003](https://www.amazon.com/Core-J2EE-Patterns-Deepak-Alur-dp-0131422464/dp/0131422464)

Então, eu acho que não ter uma discussão mais profunda sobre esses termos, sobre o que é entidade, o que é use case, com exemplos melhores, com pattern, com padrões, mostrando os casos, onde é que você usa e... o gradiente que a gente está inserido na hora que a gente vai tomar uma decisão dessas é uma coisa que, pra mim, empobreceu muito a leitura do livro.

Eu entendo os conceitos porque eu li esses conceitos em outros lugares, mas no livro é muito pouco, é uma discussão muito superficial e que é difícil de você tirar essas coisas de dentro deles se você não já consumiu muito material anterior.

**[Alexandre Aquiles]**

Perfeito. Você mencionou aí o DDD, né?

E eu lembro que eu tava conversando com o Hugo [Marques] sobre qual a diferença entre Hexagonal e Clean Architecture.

> [Twitter do Hugo Marques](https://twitter.com/hugaomarques)

O Hexagonal é nessa casca, ele não tem miolo, né? E aí o Clean Architecture tenta colocar um miolo,
só que muito superficialmente, né?

E é exatamente o que o Branas tava falando, né? Que o DDD complementa aquilo, né, Branas?

**[Rodrigo Branas]**

Eu concordo ali com o Mauricio nesse ponto.

O Bob Martin, ele pegou literalmente carona na obra Clean Code, que é uma excepcional obra no sentido de te mexer com o seu emocional, no sentido de trazer um pouco mais de ética para nossa profissão e se responsabilizar mais pelas ações, pelo código que a gente implementa.
E
sse é o grande ponto do Clean Code, esse é o grande mérito dele, nada tão técnico.

É mais um livro de autoajuda, não sei se muitos aqui concordam comigo, mas...
Clean Code é mais uma auto-ajuda e é muito bem-vinda do que propriamente um livro técnico, extremamente técnico.

Clean Architecture pegou carona um pouco nessa fama do Clean, tanto que ele lançou também o Clean Craftsmanship, o Clean Agile e outros Cleans que são bem menos interessantes.

O Bob Martin não pôde trazer conceitos que ele deveria ter trazido por dois motivos.

O primeiro ele estaria copiando o DDD. O segundo, ele teria que escrever um livro três vezes maior.

Como acho que o Mauricio falou, alguém falou, DDD é um livro que tem mais ou menos 600 páginas.

Você pega DDD, por exemplo, do Vaughn Vernon, DDD do Steve Miller [Scott Millett?], que eu acho muito legal, são livros extremamente grandes e que dá trabalho você definir.

> [Livro "Implementing Domain-Driven Design", por Vaughn Vernon, publicado em 2013, 10 anos após a publicação do DDD de Evans](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577)

O que é um aggregate? O que é uma entity? O que é um value object? O que é um repository? É muito trabalho.

E aí o Bob Martin, ele se resumiu a falar de um pattern chamado gateway. Vocês devem ter visto isso lá.

O Gateway foi descrito pelo Martin Fowler, no "Patterns of Enterprise Application Architecture", que basicamente é uma abstração para um sistema externo. Ponto. O banco de dados é um sistema externo. E ficou muito cru nesse sentido.

> [Livro "Patterns of Enterprise Application Architecture", por Martin Fowler, publicado em 2002](https://www.amazon.com/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420)

Então, não é que é um erro, assim, né? O Bob pegou, literalmente, o blog post dele de 2012 e imprimiu.

> [Blog post original de Robert Martin sobre Clean Architecture, publicado em 2012](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

É isso que o Mauricio citou, que tem 4 parágrafos falando sobre Entity.

Então, ele não deixa muito claro o que ele quer com aquilo. Agora, vamos pegar alguns ganchos aqui apenas, né?

Ponto chave aqui. Não existe bala de prata, o que acho que a Roberta comentou. There is no one size fits all.

Não existe um tipo de design que vai servir para todos os casos, assim como não existe um pneu que vai ser bom na terra e no asfalto.

O pneu vai trepidar pra caramba no asfalto e vai ser bom na terra, ou vai ser super rápido no asfalto, mas vai deslizar na terra.

Design é a mesma coisa.

Então o que o Ponte colocou, ah, o meu controller, ele é... o meu use case e assim por diante, daí dali eu boto uma annotation, já conecto de repente no meu ORM e já persisto. Show!

Mas isso por uma aplicação, por exemplo, de folha de pagamento ou de financiamento imobiliário, vai ficar aquém do que poderia ser e aí que você tira grande proveito de Domain Driven Design,
de bounded context, de você entender quais são os aggregates, de você conseguir criar a preservação dessa invariância, que vai ser o que vai te dar testabilidade no nível de unidade, que é uma coisa difícil.

Se você encarar que tudo fica dentro do controller ou que tudo fica dentro do service, que é o que a gente costuma ver em código extremamente procedural, escrito nos últimos 15, 20 anos, todo mundo aqui já deve ter passado por isso ou ainda vai passar.

Então, tem que separar os mundos. Quem tem uma aplicação simples, um CRUD, usa alguma coisa perto de um Rails, perto de um Django, algo que te gere código e seja feliz.

Agora, se você vai para uma aplicação complexa, essas dependências, que é exatamente o D do SOLID, que o Alexandre escreveu o livro, inclusive, falando sobre isso, que é "High Level Modules Should Not Depend On Low Level Modules".

É o fato de você não acoplar o teu SQL da tua regra de negócio. E não é tão óbvio assim. A maior parte das pessoas faz isso.

E qual é o problema? Qual é o drawback? Qual é o trade-off? É que se você for testar, você vai ter que testar sempre no nível de integração. Não é questão de substituir o banco de dados.

A questão é você vai impor... ali uma necessidade de uso de test patterns, uso intenso de stubs, ou ter testes muito lentos ou desencorajar os testes e assim por diante.

Então assim, o trabalho do Bob Martin é bom no Clean Architecture?

Definitivamente não. 99% das pessoas não leu o livro e comentam ou seguem somente a hype.
O trabalho dele é ruim.

Posso dizer isso tendo lido, sei lá, 10 vezes o que ele escreveu e tentando extrair ao máximo dos grupos de discussão que ele frequenta.

Principalmente para tentar ver as ... as perguntas que todo mundo faz e que não são respondidas.

Por exemplo, um use case pode usar outro? E esse é um negócio que todo mundo pergunta, ele é evasivo na resposta.

E aí você vai ver que o Domain Driven Design, no  Vaughn Vernon, principalmente, trazendo orientação a eventos, pegando uma ideia de Event Driven Architecture, e de você tentar desacoplar esses use cases e simplesmente publicar o evento, o fato que aconteceu,
e deixar o sistema reagir em cima disso. Isso gera desacoplamento, entende?

Só que é para todo tipo de sistema? Claro que não.

Então, o trabalho do Bob é superficial. Ele não pôde entrar em determinadas áreas, porque isso irá onerar demais o livro e aparecer que ele está copiando ainda mais.

Então, para mim, a grande sacada é: Ports & Adapters, eu não vejo como você abrir mão, seja uma aplicação pequena, seja uma aplicação grande, porque senão você não tem testabilidade.

Você não tem isolamento da aplicação e você está sempre preso... ou no mecanismo de entrada ou no dispositivo de I.O.

Então, pequeno ou grande, eu acho que esses conceitos são muito válidos.

Orientação a domínio, vou puxar aqui mais o Domain Driven Design, é opção para projetos suficientemente complexos.

E não só para projetos, vamos separar projetos de bounded context.

Subdomínio é uma coisa, projeto, empresa, é outra.

Você pode ter 1 bounded context de 10 que necessitam dessa abordagem. Os outros 9 não.

Então, eu acho que eu vou um pouco... nessa linha.

E só para fechar sobre o DTO, de novo a mesma coisa, entidade é uma coisa, tabela de banco de dados é outra, estrutura de dado de entrada e saída é outra.

Em aplicação simples esses conceitos são iguais, em aplicação complexa esses conceitos são diferentes. Valeu?

**[Alexandre Aquiles]**

Beleza, vai lá Otávio.

**[Otávio Lemos]**

Boa, só complementando os comentários que estão excelentes, né?

Essa ideia do Ponte de, quer dizer, faz tudo no Controller, eu acho que pode ter muitas aplicações em que isso é o melhor mesmo a fazer.

E o mais legal ainda, eu acho que essa é a ideia que eu falei de adaptar, né?

Pode ser que numa mesma aplicação, para uma funcionalidade, basta você fazer tudo no controller, aquilo ali não vai atrapalhar.

Mas aí você tem um outro caso de uso mais complexo no qual aí tudo bem, você pode usar uma coisa mais sofisticada.

Então, eu acho legal encarar o sistema como uma coisa orgânica e na qual você pode adaptar e usar.

Eu acho legal essa ideia de Ports & Adapters como padrão arquitetural que você pode usar em alguns pontos da sua aplicação.

Não precisa usar em todos os lugares. Você usa onde faz sentido.

Tem um cara também que é o Jimmy Bogard, que ele fala sobre isso, né? Ele fala sobre... você primeiro, por exemplo, faria tudo no controller.

> [Palestra "Vertical Slice Architecture", por Jimmy Bogard, apresentada na NDC Sidney 2018](https://www.youtube.com/watch?v=SUiWfhAhgQw)

E aí quando você começa a perceber as dores você pode refatorar aquilo para melhorar.

Eu acho isso uma visão bem positiva também.

Em vez de você usar uma coisa mais prescritiva já de início, já dividir as suas camadas a partir das suas dores você vai refatorando.

Tem aquele outro livro "Refactoring to Patterns" também, que essa é a idea.

> [Livro "Refactoring to Patterns" por Joshua Kerievsky, publicado em 2004](https://www.amazon.com/Refactoring-Patterns-Joshua-Kerievsky/dp/0321213351)

Ao invés de você usar os padrões, você vai usar no momento em que você começar a sentir a dor naquele ponto.

O segundo ponto que eu queria colocar é isso. Para mim, uma das maiores vantagens dessas ideias,
de Clean Architecture, Arquitetura Hexagonal, é você de fato poder testar as coisas de maneira separada.

Você poder testar suas regras de negócio sem se preocupar com o controller e tal.

Então eu acho que isso é um ganho muito grande.

Eu queria só fazer um link, que o pessoal do mundo funcional já tem uma coisa bem parecida com Ports & Adapters e Arquitetura Hexagonal, que eles chamam lá de "Imperative Shell, Functional Core", que é a ideia de você ter um core funcional, que é a parte do seu domínio, e aí ali você só tem funções puras, você pode testá-las de maneira separada também, e você empurra os side effects para as partes, para a parte mais externa da aplicação.


Que tem a ver com essa ideia também. E aí seria comparável ao caso de uso, que no caso de uso você de fato conversaria com coisas externas.

Então eu acho legal a gente ver também que essas ideias aparecem em vários lugares na comunidade e elas vão convergindo.

E óbvio que a gente tem que fazer esse trabalho de saber filtrar e saber usá-las da melhor maneira, adaptá-las para o nosso contexto.

**[Alexandre Aquiles]**

Aniche e Linhares, eu posso só... Para vocês comentarem em cima de um exemplo.

Então o Fernando Cruz, numa dessas threads, ele falou um negócio interessante.

> [Twitter do Fernando Cruz](https://twitter.com/FernandoCruz_21)

Falou assim: "Você vai fazer um sistema de pagamento e vai ter que escolher adquirentes, fatores de decisão, aprovação do pagamento, taxas. Digamos que a Stone tenha taxa de 1,5% para qualquer bandeira, uma aprovação de 70%. Uma aprovação meio ruim. A Cielo tem taxa de 4%, que é uma taxa meio ruim, e aprovação de 95%."

Então, ele colocou... "Não tem nada a ver com a realidade aqui, pessoal. A Stone tem uma aprovação menor e a Cielo tem uma taxa maior. Se você escolher... você pode integrar com as duas, seria uma solução. Usar a Stone como principal e fallback para Cielo."

E aí ele fala disso. Ele comenta isso. "Nessa briga, aparece a rede com uma taxa de 1,5% e aprovação de 97%. Então, a mesma taxa da melhor e é uma aprovação muito melhor do que todas elas.
Uma arquitetura bem definida teria que ser extremamente fácil de mudar a adquirente que você vai usar sem precisar alterar todas as camadas."

Eu acho que aqui o lance é... Essa é uma coisa importante para o negócio, né? É uma opção que você quer deixar aberta.

Então, eu acho que, assim, ao meu ver, a gente tem que simplificar o que não traz tanta vantagem para o negócio e deixar flexível aqueles pontos que teriam vantagem para o negócio ser flexível.

Então, por exemplo, numa coisa de cursos online, por exemplo, a CDN que a gente vai integrar precisa ser flexível. Isso é caso real mesmo.

No meu caso lá, do meu exemplo do livro é, os formatos de ebook que vão ser gerados, eu quero que sejam flexíveis.

**[Alexandre Aquiles]**

Então, é, mas ô Aniche, manda brasa aí.

**[Mauricio Aniche]**

Na minha cabeça, CDN é uma coisa que você nunca vai mudar.

Quem que muda de CDN? Mas você acabou de falar que muda, né?

**[Alexandre Aquiles]**

É porque o custo é alto, sabe? É uma grande fonte de custo, sabe?

Então, você consegue uma eficiência melhor se você conseguir algo...

É o mesmo exemplo aqui do caso das adquirentes, né?

**[Mauricio Aniche]**

Exato, e nesse ponto você precisa de flexibilidade, né?

Então, por exemplo, a Adyen como Fintech, tenho certeza que na Stripe é a mesma coisa, adicionar um próximo adquirente tem que ser fácil, certo? Porque é o Negócio, né?

Você quer invadir novos mercados, você precisa implementar os adquirentes daqueles mercados.
Tem que ser fácil no sistema, né?

Você não tem que fazer a pessoa abrir 400 classes para implementar um novo adquirente.

Só que esse tipo de coisa, para ser honesto, é mais, acho que... a exceção do que arrega nesse tipo de aplicação, porque a gente tem muito CRUD, como todos vocês já falaram.

Um detalhe que eu queria comentar do livro, porque a galera estava tweetando, eu estava lendo os tweets, e a gente comentou que o livro é opinionated, ele tem as decisões fortes ali e tal, acho que parte do trabalho nosso quando lê essas coisas é... transferir para o nosso contexto, né?

Esse trabalho que é mais de engenharia e não é tão científico, né? A ideia é pegar mesmo e transferir para o nosso contexto.

Aí eu me lembro, por exemplo, a gente está dando os exemplos do Evans sempre como positivos, mas se você lembra lá o GUJ, o.NET Architects em 2004, 2005, quando o livro saiu, a galera colava código fonte de classe ali e falava, gente, isso aqui é um repositório de acordo com o Evans?

Pouco importa, meu amigo, se o Evans acha que aquilo é um repositório. Então, é difícil generalizar mesmo, né? Quando você lê um conteúdo novo e tal.

É óbvio que o Evans escreveu isso muito melhor. De uma maneira um pouco mais amigável, por isso que as pessoas não ficam tão putas com ele.

O Uncle Bob foi ali um pouquinho mais seco, né, na maneira de descrever. Mas acho que esse é um... 

Acho que todo livro que a gente lê hoje, porque nós somos mais maduros e tal, você tem coisas que você não concorda em absoluto, né?

Acho que tem que dar esse, como fala em português, leap of faith, né?

Você tem que dar um pouquinho ali de... um pouquinho de fé ali para o autor e deixar pular ali alguma coisa que você não concorda muito.

A única maneira de conseguir interpretar esses livros, eu acho.

**[Alexandre Aquiles]**

Isso me lembra muito o ciclo do hype, né? Que tipo, você tem aquela coisa de se empolgar e depois se ferra.

É natural. Isso acontece com ideias também de design de código.

Mas vai lá, ô Linhares.

**[Mauricio Linhares]**

Esse caso é um caso interessante porque quem trabalhou fazendo esse tipo de coisa sabe que toda vez que você vai integrar um adquirente novo, tem várias surpresas, né?

Que você não planejou lá na sua arquitetura, né? Vai ter modos de trabalho que são diferentes de todos os modos de trabalho que você tem.

Tem gente que trabalha só mandando arquivo via FTP, tem gente que trabalha só via... API web, tem gente que trabalha só via API que você tem que alugar uma linha direta para esse cara, às vezes você tem que ter uma máquina fisicamente dentro do data center desse cara.

Então tem um universo de coisas que você vai se surpreender quando você estiver fazendo integrações desse jeito.

Então você vai criar esse modelo, e eu acho que é importante que as pessoas entendam que vocês vão fazer isso.

A minha crítica é que o livro não fala em hora nenhuma como é que você faz isso.

A gente fala, fala, fala do Evans, eu vou até dizer, o livro é maior, são 600 páginas, mas você vai tirar muito mais do livro do Evans do que você vai conseguir tirar mesmo arrancando o último suco do Clean Architecture.

O conteúdo vai ser muito melhor, é chato, é um livro chato pra caralho, eu não vou dizer que é um livro legal de ler, o Domain Driven Design é um livro que é muito chato de ler.

Mas você pode ler por pedaço, você pode ler os patterns que fazem mais sentido para você nesse momento, para você entender.

Então eu acho que vale mais a pena do que você ir atrás de ler o Clean Architecture.

E eu acho que sim, tem recomendações que ele faz, umas recomendações meio enfáticas, que são ruins, são recomendações ruins.

Tá entendendo? Uma das que ele faz é que dentro da sua equipe você vai fazer a distribuição... do seu domínio lá como um JAR. Vai ser um JAR separado, versionado, que você vai pegar e você vai botar pra todo mundo.

Então imagina numa empresa que tem lá mil desenvolvedores, esses mil desenvolvedores formam 100 equipes diferentes e cada um produzindo as suas próprias bibliotecas.

Imagina o desespero que é você entender a matriz de dependência e que versão cada aplicação separada vai estar, se você está distribuindo cada coisinha como um JAR que a pessoa tem que atualizar a dependência e mudar o número de versão.

Isso é até uma das coisas que quando a gente foi fazer o API Gateway na Digital Ocean, a gente tomou a decisão de que não ia ter biblioteca.

Não ia ter de jeito nenhum biblioteca, porque a gente não queria deixar isso como sendo uma dependência que todo mundo ia ter que ficar atualizando porque a gente sabia que isso era terrível.

O pessoal da SoundCloud teve essa experiência, não foi legal, o pessoal do Twitter teve essa experiência, não foi legal, porque é muito difícil você fazer uma coisa dessas funcionar
quando você tem dependência de regra de negócio.

Então, imagina que eu tenho um novo método de autenticação, então, em vez de eu ter um lugar centralizado onde eu atualizo isso, agora eu tenho 50 aplicações diferentes, de equipes diferentes que vão todas ter que atualizar.

Imagina o pesadelo que é você fazer uma coisa dessas.

Então, tem coisas realmente lá dentro que são, assim, que você não deveria fazer. Você não deveria trabalhar desse jeito.

Tem uma coisa que o Rodrigo [Branas] falou que eu acho que precisa de deixar um pouco mais claro.

Não sei como o Rafael Freire não reclamou aí ainda que a aplicação Rails não é aplicação simples, minha gente.

Shopify roda em Rails, o Stripe roda em Rails, pegando pagamento do mundo todo, são aplicações complexas que dá pra você...

Se você precisa, a gente volta para aquela coisa que o Rafael Ponte falou lá no início.

A vantagem é que você consegue fazer o simples e o complexo tudo juntos.

Não tem aplicação simples e aplicação complexa. Tem pedaços simples e pedaços complexos dentro de uma aplicação.

Então não é uma coisa que simplesmente, a minha aplicação é complexa porque é uma aplicação de pagamento.

Não é, bicho. Você vai ter lugares na sua aplicação onde é... complexo, onde fazer o que o Ponte falou, meter tudo dentro do controller, não vai ficar legal, porque você é muito código, porque você precisa reusar esse código em algum outro serviço, em algum outro lugar.

Então você vai conseguir separar isso aí, ou você pode simplesmente botar dentro do controller.
E esse foi, pelo menos para mim, lá em 2006, 2007, o pulo do gato, quando eu comecei a trabalhar com Rails, depois de sair do Java, e ver que, porra, eu não preciso de toda essa complicação, se eu posso...

Se eu tenho casos que são mais simples, eu posso fazer simples aqui.

E se eu tenho casos que são mais complexos, eu posso criar um modelo separado, posso criar um serviço, posso deixar essa complexidade aonde ela está.

Então, não é porque você está trabalhando com Rails, com Django, com PHP, que você só está escrevendo a aplicação simples, e você só pode escrever a aplicação simples.

Você pode escrever, muita gente escreve, muita gente deu muito certo
escrevendo aplicações complexas usando essas ferramentas aí.

**[Mauricio Aniche]**

Deixa eu pular a fila rapidinho aqui para reforçar uma coisa que o Mauricio [Linhares] falou, que eu acho que é o principal desafio na prática.

Que você criou sua abstração linda, maravilhosa, a próxima implementação vai ser diferente, entendeu?

Vai ter alguma coisa para mudar. Eu acho que no Hipsters, que o pessoal gravou com a Adyen, o pessoal até brincou, né?

> [Episódio do podcast Hipsters gravado com o pessoal da Adyen](https://www.hipsters.tech/case-adyen-machine-learning-e-pagamentos-hipsters-ponto-tech-308/)

Que quando foi implementar o primeiro meio de pagamento brasileiro, parcelamento.

Ninguém parcela, os gringos aqui não entendiam que era parcelamento, né?

Então a abstração que tinha para adquirente não funcionava.

Sempre a próxima implementação vai ser um pouco diferente.

E aí que entra o desafio: como que você continua evoluindo essa abstração de maneira legal sem começar a poluir ela e deixar ela estragar?

Acho que esse é o desafio cruel, que esses livros não tocam tanto.

Nos exemplinhos, obviamente, eles têm que simplificar, porque senão eles vão escrever um livro de 5 mil páginas, mas como que você modifica sua abstração para entender essas pequenas diferenças que elas sempre acabam acontecendo?

Acho que essa é a chave no mundo real.

**[Alexandre Aquiles]**

Pois é, nada como o mundo real para destruir a sua abstração.

Mas vai lá, Branas.

**[Rodrigo Branas]**

Não, eu só ia reforçar uma coisa, até em cima do que o Mauricio [Linhares] falou.

Eu me referi, unique exclusivamente, ao processo de scaffolding padrão, tá?

Uma linguagem de programação, seja ela qual for, desde que ela tenha o devido suporte ao que você precisa fazer, você tem a capacidade de comunicar ao computador e orientar para aquele processo aquilo que você precisa.

Não existe qualquer limitação, isso eu falo em... todos os momentos que eu posso em que não tem absolutamente nada a ver uma linguagem como PHP, Ruby, Python, Java com o propósito ao qual você a utiliza salvo por questões de performance e alguma outra implicação, tá?

Então, longe de mim ter afirmado alguma coisa nesse sentido. Me referi ao scaffolding, especificamente a olhar isso como padrão e quando você começa a ter mais regras de negócio, o que vai acontecer aqui é um jogo de prós e contras, única e exclusivamente.

O que o Alexandre comentou em relação aos adquirentes...

Eu já implementei muita aplicação com adquirentes, com 10, 15 adquirentes.

E a ideia ali é, eu posso levar esse código de uma forma mais procedural e ter uma classe, ou ter um arquivo muito grande, cheio de if/else que hora faz um adquirente, hora faz outro? Posso.

Qual é o problema disso? Vai funcionar? Vai. Mas eu vou mexer muito nesse mesmo arquivo.

Eu vou ter um acoplamento um pouco maior com a tecnologia e eu eventualmente vou fragilizar.

Agora eu posso usar um padrão como um adapter, inverter a dependência, isolar essa implementação?

E definir um contrato que sirva para 90% deles ou 100% deles, pode?

Pode acontecer, como o Mauricio [Linhares] falou, deles serem tão radicalmente diferentes ao ponto desse contrato ser inválido? Pode.

Se não der, não deu. Faz de outra forma, entendeu? Então, o tempo todo aqui é bounded context.

O que o Mauricio [Linhares] se refere à aplicação tem partes simples e partes complexas. Na verdade, o domínio é decomposto em subdomínios simples e complexos.

Os complexos, você pode tomar uma decisão de fazer de um jeito, os simples de outro, você pode fazer todos do mesmo jeito e ora ter uma manutenibilidade pior, ora ter melhor, a decisão é de cada um, sabe?

Funcionar, uma coisa eu garanto, tudo vai funcionar. A questão é em que condições vai funcionar, só isso.

**[Alexandre Aquiles]**

Puxa aí, Ponte! Deu uma distraída aqui, foi mal.

**[Rafael Ponte]**

Ah, não, legal, legal. De boa.

Eu vou aproveitar que o gancho do Maurício [Linhares], né? Que ele falou sobre... sobre domínios complexos, né?

A gente costuma falar, não, você usa esse DDD, você usa Clean, você usa Hexagonal, você tem um domínio complexo, você tem um sistema complexo, mas isso é tão subjetivo, o que significa?

Até hoje eu tenho uma dúvida do que eu considero complexo, um domínio complexo, um sistema complexo, algo do tipo, tá?

E aí talvez porque eu venho muito do mundo corporativo, né?

E aí é onde a Aniche até comentou. A gente vive de CRUD, né?

Então ali 80% ou mais é o bom e velho CRUD e talvez um relatoriozinho ali em PDF bonitinho, ou em .CSV.

Mas aí a pergunta que fica é o que um domínio complexo?

Eu acho que o Branas já até comentou, né?

Então eu devo ter muito claro as minhas Ports & Adapters, os drivers, tudo ali.

Quando eu tenho um domínio complexo, eu quero separar, eu quero testar, especialmente teste de unidade, acho que ele comentou até isso.

E eu me pergunto, vamos ver o que é complexo.

CRUD é complexo? Eu acho que não, mas 80% dos sistemas corporativos são CRUDs.

Microsserviços é complexo? Se você pensar numa aplicação com um todo, adotando microsserviços, sim, ela é complexa, mas o microsserviço não é complexa na base de código, ela é complexa nas bordas, na comunicação.

Então, o microsserviço tirou toda a complexidade que o desenvolvedor tinha que manter numa base de código com dezenas de milhares de linhas e fez o desenvolvedor manter apenas algumas poucas
centenas ou milhares de linhas, pouquíssimas linhas, pouquíssimas classes e jogou a complexidade nas bordas.

Então o microsserviço está nas bordas.

Mas se o microsserviço me deu o luxo, ó a palavra luxo aqui, de ter um código mais simples, uma base de código mais simples, por que eu não abraço isso?

Porque se eu tenho um código mais simples, vamos pensar, o microsserviço me permite criar
uma funcionalidade, um componente que tem uma... responsabilidade bem definida.

Responsabilidade bem definida quer dizer que tudo que ocorre ali está tudo intimamente ligado.

Eles têm um fortíssimo acoplamento porque tudo mexe com o mesmo contexto.

Se mexe o mesmo contexto, para que eu tenho que criar N camadas de indireção para separar as coisas?

E se está tudo íntimo e a complexidade está nas bordas, que geralmente em microsserviços é sistema distribuído e está na entrada e na saída, querendo ou não, eu vou ter esse acoplamento com as bordas.

Eu tenho que saber qual o protocolo de entrada e tenho que saber de alguma forma qual protocolo de saída.

Até porque as regras de negócio, que a gente chama a lógica de negócio, ela não está em um único ponto na aplicação, ela está espalhada por toda a aplicação.

Desde de como vai entrar, se aquilo ali vai, qual tipo de protocolo de entrada, de tipagem,
até o banco de dados.

Quando eu falo banco de dados, estou falando que boa parte das minhas lógicas de negócio vão estar em como eu defini meu schema, como é que eu defini os tipos, como é que eu defini as constraints, a concorrência, ignorar isso é dar um tiro no pé.

E aí o Branas até falou, ah, mas aproveita a vantagem de Ports & Adapters nesse domínio complexo, é que eu escrevo mais teste de unidade.

Mas se eu estou dentro do contexto de microserviços, vamos se amarrar ao contexto de microsserviços aqui, até para não generalizar, onde a complexidade está nas bordas, está na comunicação remota, é burrice, desculpa a palavra, é burrice ignorar isso.

Por isso, teste de integração, na minha opinião, faz muito mais sentido quando eu trabalho com microsserviços. Por dois motivos.

Eu vou sempre exercitar as bordas, que é onde está a complexidade e provavelmente a maioria dos bugs. Eu tenho pouquíssima regra de negócio a nível de código de aplicação, porque eu tenho um domínio, um subdomínio, uma quantidade de código muito acoplada, muito íntima,
e que pouca coisa faz.

Então, eu só queria deixar claro que tipo... Domínio complexo é difícil definir, mas dado que eu estou num contexto de microsserviço onde eu tenho pouco código, eu tenho o luxo de ter pouco código, então eu deveria abraçar.

Abraçar significa diminuir as camadas de direção, abraçar o framework, entender que estou em uma comunicação remota e que testes de integração acabam sendo muito melhores para a manutenção e para a vida útil do sistema.

Só deixando claro que é minha opinião.

**[Alexandre Aquiles]**

Otávio, quer comentar?

**[Otávio Lemos]**

É só um comentário, eu achei interessante você trazer o assunto de microsserviço, porque eu acho que é bem característico, uma coisa que se a pessoa não souber fazer direito, faz muita cagada, né?

Então, eu acho interessante você ter isso sempre em mente.

**[Alexandre Aquiles]**

Otávio, deixa só comentar aqui, tipo, um ano antes talvez desse freela que eu fiz... aí usando esse esquema do XML para mapear a entidade e tal, tinha um colega que fez um freela com microsserviços de atendimento de dentista, não sei o que lá...

Foi muito mais desastroso e esse realmente o cliente quis e deu certo, sabe?

E foi o terror da manutenção. Só um detalhe.

**[Otávio Lemos]**

Não, é só isso que eu estava querendo complementar.

E eu acho que é bom a gente sempre deixar isso claro.

Para você obter benefícios desse tipo de técnica e abordagem, você tem que estudar o negócio, saber usar.

Porque senão você vai se ferrar. 

or melhor que seja a ideia, por melhor que seja a tecnologia.

Eu conheço, por exemplo, gente que tem muita experiência com microsserviços.

Tem sempre essa ideia, começa com monólito, depois quebra para microserviços.

Não cara, se o cara manja, se o pessoal já teve um monte, já fez um monte de sistema baseado em microsserviços, já tem experiência, o contexto casa com o uso de microsserviços, o cara pode começar e ter muito sucesso.

Então, mas é isso, eu só queria enfatizar isso, é que a pessoa, o pessoal tem que dominar essas técnicas, essas ideias para poder aplicar bem, que senão você vai dar um tiro no pé.

**[Alexandre Aquiles]**

Perfeito. Ô, Linhares, vai lá.

**[Mauricio Linhares]**

Vamos voltar para o caso das adquirentes.

Que a interface, no geral, ela tem duas coisas.

Ela tem um predicado que é para verificar se essa transação é específica. Se essa adquirente vai ser capaz de processar essa transação.

Então, tem várias informações que você vai usar.

Você vai usar o tipo do dinheiro, né? Você está usando real, está usando dólar, isso aí influencia... a decisão qual país do cartão, o país emitido do cartão, se é cartão internacional ou não.

Então, a gente tem esse predicado que define qual vai ser executada e a gente tem a implementação da execução mesmo do negócio, que é aquele padrão Estratégia que a gente está acostumado.

Esse problema do adquirente é o problema de roteamento que você tem numa aplicação web.

Então, esse problema... Esse problema em si, ele é complexo?

É, porque...

**[Alexandre Aquiles]**

Parece fácil de entender.

**[Mauricio Linhares]**

É, ele é um problema que ele é...

Por isso que eu gosto desse negócio do Ponte, porque o que é complexo, o que é que não é complexo também?

É difícil porque a complexidade, ela vai entrar quando começa a acontecer aquilo que o Aniche falou.

Agora eu tenho que fazer o pagamento em parcela. E você, caralho, eu nunca vi pagamento em parcela.

Nunca existiu na minha vida. E no Brasil, o pagamento em parcela é feito de um jeito.

Se você vai para outros países da América Latina, o pagamento em parcela é feito de outro jeito.

Então não dá nem para você dizer, eu posso reusar diretamente aquilo que é do Brasil e o que é dos outros países do parcelamento, porque é outra coisa, é outra solução.

Eu acho que quando a gente fala de o que é simples e o que é complexo, eu acho que onde está complexo, é onde você precisa de muito conhecimento, onde tem muita coisa sendo definida, muita regra que precisa existir ali para esse sistema funcionar, porque você precisa manter todas essas coisas na sua cabeça.

Como é que eu vou conseguir separar a implementação da decisão é simples.

Porque você tem o predicado e você tem a execução que é a Estratégia.

São dois padrões que a gente conhece desde que saiu da faculdade.

Todo mundo vê essas coisas desde que saiu da faculdade.

Mas implementar as regras diretamente, definir como essas coisas vão existir dentro do sistema maior, aí é que vem a complexidade do negócio.

E você entender que... vai ter coisa que vai quebrar sua arquitetura, vai ter coisa que vai mudar, vai ter coisa que você vai ter que parar e "pô, aqui eu vou ter que rever, eu tô entrando num outro país onde as coisas são diferentes, os meios de pagamento são diferentes".

E aí você vai fazendo a coisa funcionar. É só você não entrar nesse negócio, ah, eu vou isolar tudo, vai ser perfeito, eu não vou conseguir não vou ter mais que mudar nada, não, você vai ter que mudar coisa pra caralho, né?

Ninguém consegue acertar na primeira vez e a sua arquitetura você vai ter que ir lentamente evoluindo, por isso que eu gosto muito dessa ideia de arquiteturas que são evolutivas, que elas vão evoluindo junto com a aplicação, porque é mais fácil você ir evoluindo com os problemas do que você tentar entender todos os problemas.

Não sei se você já tem experiência, né? Você foi uma pessoa... Ah, eu trabalho com pagamentos faz 10 anos, eu botei, fiz, trabalhei com adquirência em 50 países diferentes. Foda!


Então você já provavelmente já viu muita coisa, você vai conseguir arquiteturar tudo, mas... é difícil você ser essa pessoa.

Na maior parte das vezes, a gente não tem tanto conhecimento assim para tomar essas decisões e definir essas coisas.

Então é entender que quanto mais conhecimento você precisa para colocar dentro do sistema, porque eu...

Pronto, e vou dizer agora o que eu gostei da porra do livro do Bob Martin, que escrever software é como se fosse um experimento científico.

Isso, isso, isso tá pronto. Aí foi uma coisa que me marcou.

Gostei dessa definição. Dele ter essa visão, porque é exatamente isso mesmo.

Dá para você discutir isso de uma forma mais longa dentro do livro.

Eu acho que isso é uma parada muito válida e eu acho que é assim que a gente escreve software.

A gente vai com pequenos experimentos, construindo o conhecimento, construindo o entendimento do que está acontecendo ali.

E você vai sempre nesse caminho de pequenos experimentos.

Você faz um pequeno experimento aqui, agora isso aqui está afetando outra coisa,

Vai lá, melhora essa outra coisa, melhora sua arquitetura, coloca mais uma opção lá, e você vai lentamente fazendo o negócio crescer.

Com essa ideia de que escrever software é trabalhar com experimentos científicos.

**[Alexandre Aquiles]**

E, assim, alguém já leu o "Building Evolutionary Architectures"?

Eu acho que o "Software Architecture: the Hard Parts" tem uma pegada também dessa pelo que vocês postaram ali, parece que tem essa ideia de você ir descobrindo e mudando.

> [Livro "Software Architecture: The Hard Parts", por Neal Ford, Mark Richards, Pramod Sadalage e Zhamak Dehghani, publicado em 2021](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/)

Tem isso, Linhares? Só para você comentar, acho que você já leu, né?

**[Mauricio Linhares]**

Tem, tem isso.

Acho que hoje não vale mais a pena ler ele não, ele já está meio velhinho, na época valia mais a pena.

Acho que hoje o "Fundamentals of Software Architecture" e o "Software Architecture: The Hard Parts", eles cobrem mais, mas eles seguem muito essa ideia.

> [Livro "Fundamentals of Software Architecture", por Mark Richards e Neal Ford, publicado em 2020](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/)

Quem está com tempo livre, lê o livro, vale a pena ter essa ideia, mas esses dois livros, eles abordam também essa ideia.

**[Alexandre Aquiles]**

Legal. Ô Branas, vai lá.

**[Rodrigo Branas]**

Não, só para fechar aqui.

Para mim, o princípio mais importante é o tal do KISS, que é o Keep It Simple.

Então, eu acho que estou muito aí com a opinião do Maurício [Linhares].

Software é um grande experimento, sabe? Envolve em alguns casos até sorte, sabe? De você pegar o caminho certo pra você não ter um grande retrabalho depois.

Então, pra mim, a melhor alternativa sempre foi manter o software o mais simples possível e ir dando passos pra gente conseguir manter uma boa curva de aprendizado pra equipe,
um bom clima e ir gerenciando a dor.

Pode doer por dois motivos.

E é mais comum, às vezes, até mesmo doer, porque você escolheu a "arquitetura" ou o "design" errado, e aquilo está te forçando numa burocracia sem fim, do que doer pela manutenibilidade que está prejudicada. Às vezes também dói.

Então, talvez, se você conseguir perceber essa dor no momento certo, tomar as decisões certas com coragem, e aí pode ter um teste de integração, ali, como o Ponte citou, pode ter um teste  end-to-end, o teste só está aí pode te dar coragem.

Se você tem a coragem necessária e o teste te garante isso. Para você tomar a ação na hora certa e na hora que precisa, você mitiga muito achismo e muita coisa que você talvez não vá precisar e assim você consegue estabelecer a melhor experiência possível para as pessoas que estão trabalhando e o melhor fluxo de valor de negócio para o cliente final.

Então, para mim, o melhor caminho segue sendo esse.

Às vezes a gente está discutindo uma coisa muito específica, falando de DDD, falando de Clean Arch, mas dando uns passos atrás, eu acho que o que vale muito é essa postura de humildade frente ao problema que você não conhece, e aí você ter a capacidade de, ao longo do trajeto, ter coragem para tomar as ações.

Para mim, esse é o ponto.

**[Alexandre Aquiles]**

Boa. Perfeito, muito bem colocado, Branas. É isso.

Pessoal, vamos encerrando assim, vamos fazer uma rodada de tipo...

Estava pensando assim, fazer uma... "Clean Arch morreu", e aí? Sim ou não?

Mas não é uma pergunta que faça sentido, né?

Então, pode ter considerações finais. Tá bem?

Eu queria abrir a palavra para muita gente que está aqui que eu admiro e tal, muito obrigado por ter comparecido.

Está bem pessoal? Muita, mas muita gente mesmo. Mas não dá, né?

Então vamos fazer essa rodada?

Roberta, você tem alguma coisa a colocar assim, considerações finais? Você aprendeu algo aqui?

**[Roberta Arcoverde]**

Ah, sempre, sempre.

Essas discussões são muito ricas. Eu acho que uma coisa que eu estava pensando à medida que a discussão estava se desenrolando, que fica sempre muito na minha cabeça, é a questão de desperdício.

Eu sou um pouco cria da época que se discutia muito Lean, desenvolvimento, tentar evitar desperdício e tal.

E eu lembrei, quando o Linhares falou de experimento e de experimentação, eu lembrei de um artigo de pesquisa da área de Engenharia de Software.

Eu trabalhei com pesquisa durante um curto espaço de tempo, trabalhei durante o mestrado, e era um artigo que se debruçava sobre a quantidade de código morto nos projetos, quanto código a gente escreve que, no fim, ou nunca é executado, ou muito pouco é executado, acaba não servindo para nada.

E um dos exemplos que mais me marcou nesse artigo era justamente uma investigação em vários repositórios de código de CLIs, de aplicações que eram CLIs, mostrando que mais de 80% dos parâmetros de configuração de comandos em CLIs nunca eram utilizados pelos usuários dessas CLIs.

E isso é código, né, gente? Toda linha de código que você adiciona num sistema, numa aplicação, ela vem com um custo, não é de graça.

Ela adiciona custo porque alguém vai precisar parar para ler, para entender.

Aquela velha máxima de que o melhor código é aquele que a gente não escreve.

E eu acho que isso casa muito bem com a discussão, porque é sempre, a gente tem que sempre avaliar esse trade-off, do quanto a gente está complexificando o nosso código, o nosso software, por opções e flexibilidades que a gente acabará não de fato utilizando.

Enquanto isso... Existem concorrentes, existem outras pessoas, outros times, outras aplicações sendo construídas que estão mais focadas em deliverables, em entregar software funcionando.

Pelo menos a minha filosofia como desenvolvedora sempre foi fazer a coisa mais simples que pudesse funcionar e adaptá-la quando e se fosse preciso adaptá-la.

Então era isso.

**[Alexandre Aquiles]**

Uau! Muito bom. Vamos lá, Linhares. Tem alguma consideração final?

**[Mauricio Linhares]**

Leiam Domain Driven Design, por favor.

Para vocês verem essa discussão de uma forma mais profunda.

Leiam "Fundamentals of Software Architecture" para entender o que é a arquitetura do software, para ver os fundamentos, questões de... os tipos de arquitetura, quais são os tipos de comunicação, como a gente está produzindo aplicações hoje.

Então, a gente tem muito material. É incrível olhar a bibliografia que a gente tem de material disponível hoje para você entender um pouco mais sobre esse tipo de coisa.

Me perguntaram no Twitter, mas eu posso dizer que o Clean Architecture é uma merda sem ter lido?

Não, você não pode. Se você não leu a porra do livro, você não fala do livro.

Se você não entende o que é que está lá, você não sabe por que é que é problemático, as ideias que estão lá dentro, então é melhor você não dizer.

É a mesma coisa que o menino estava falando, todo mundo viu no blog que o Clean Arch e fica falando as coisas, você pega o livro e vai ler, bicho, vai ver o que está escrito lá,
vai ver quais são as ideias que estão sendo definidas lá para você poder entender o que vai usar e o que não vai usar.

Então a gente tem muito material, a gente tem muita coisa que ajuda, inclusive a gente tem que agradecer, porque na época que eu e o Ponte...

o Ponte querendo pagar de jovem aí. Ele não é jovem, o Ponte tem a mesma idade. É velho igual a mim. A gente começou a trabalhar junto praticamente.

E nessa época a gente não tinha toda essa bibliografia, toda essa oportunidade de discutir essas coisas.

Você pega um livro como o "Designing Data Intensive Applications", se a gente tivesse esse livro 15 anos atrás, a gente tinha evitado fazer muita merda que a gente escreveu.

> [Livro "Designing Data-Intensive Applications", por Martin Kleppmann, publicado em 2017](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)

A gente fez muita merda nesses 16, 18 anos que a gente está escrevendo software porque a gente tava aprendendo.

As pessoas estavam aprendendo essas merdas e estão escrevendo os livros e mostrando: "olha todas as merdas que a gente fez, aprenda a não fazer essas merdas".

Então peguem esse material, leiam também o livro do Aquiles.

Vamos estudar um pouquinho mais, vamos entender um pouquinho mais pra gente escrever software melhor pra hoje e pro futuro.

Porque, no fim das contas, é você que vai se rasgar dando manutenção a essa merda que você produziu hoje.

Então... De um jeito ou de outro, a gente que vai ter que pagar essa conta.

Então, vamos fazer um pouquinho melhor para a gente não ter tanta dor de cabeça aí no longo prazo.

**[Alexandre Aquiles]**

Duas lições então.

A Roberta falou que o nosso código 80% é inútil e o Mauricio falou que...

**[Roberta Arcoverde]**

Que isso? Eu falei isso não.

**[Alexandre Aquiles]**

Tô brincando. Tô fazendo factoide aqui. hahaha

E o Mauricio [Linhares] falou que a gente vai sofrer com o código que a gente mesmo produz.

Essa segunda aí realmente é isso mesmo, né pessoal?

Ô, Branas, considerações finais...

**[Rodrigo Branas]**

Considerações finais... basicamente agradecer a todos aí, obrigado.

Acho que a discussão é sempre muito válida.

Por mim, sigam o conselho do Keep It Simple.

No fim das contas, o legado vai ser teu, a dor vai ser tua. Então aprenda a lidar com ela, da melhor forma possível.

E tenta sempre... estar um passo a frente, nem que seja pra não usar.

Vale muito o conselho que o Mauricio [Linhares] colocou.

Cara, você pode estudar Domain Driven Design, nem que seja pra dizer, aqui não se aplica.

Mas pelo menos você tira esse peso do teu coração e tira essa síndrome, às vezes, de estar pegando o caminho errado.

Na maior parte das vezes o caminho simples é o melhor.

Um pouco do que o Ponte falou ali, eu concordo.

Boa parte das vezes o simples e o direto... vai atender, vai resolver e vai ser a melhor saída e o teste de integração vai ser o mais assertivo.

Então, Keep It Simple, esteja sempre um passo à frente, nem que seja para saber que você não precisou daquilo.

**[Alexandre Aquiles]**

E o seu curso, como é que eu pego, Branas? Fala aí.

**[Rodrigo Branas]**

A gente está na turma número 8, o meu curso basicamente ele reúne desde Refactoring, Test Driven Development... entrando em Ports & Adapters, discutindo Clean Architecture, entrando em DDD, SOLID, Design Patterns, CQRS, e muito nesse viés, tá?

Assim, é aonde você talvez precise usar isso e como você faria.

Mas muito para trazer essa clareza para as pessoas, né?

Então a gente vai desde a escrita de código até a estruturação disso, seja em microserviços, né?

Então é só entrar aí no meu canal no YouTube, você vai encontrar bastante informação.

> [Canal do YouTube do Rodrigo Branas](https://www.youtube.com/rodrigobranas)

**[Alexandre Aquiles]**

Boa. Valeu! Aniche, vamos lá?

Considerações finais e fala do seu livro também. Eu comprei. Muito bom.

**[Mauricio Aniche]**

Eu não vou fazer jabá aqui não, Alexandre.

> [Livro "Effective Software Testing", por Mauricio Aniche, publicado em 2022](https://www.manning.com/books/effective-software-testing)


Mas o que eu ia falar, eu acho que esse livro é muito mais sobre design do que arquitetura, né?

É muito mais sobre como organizar classes e criar código flexível, etc. e tal. E bem menos de arquitetura, né?

E o DDD é um livro muito legal quando se fala de design, mas acho que o que me influenciou de verdade foi o "Growing Object-Oriented Software, Guided By Tests".

> [Livro "Growing Object-Oriented Software, Guided by Tests", por Steve Freeman e Nat Pryce, pioneiros do uso de mocks, publicado em 2009](https://www.amazon.com/Growing-Object-Oriented-Software-Guided-Tests/dp/0321503627)

E quando eu vi a pegada dos dois autores ali, em como eles programam, em como eles deixam... as abstrações emergirem, acho que me influenciou bastante.

É um livro que a gente fala bem pouco, né?

Porque o Steve Freeman e Nat Pryce não são tão populares aí na comunidade, mas é um livro bem bom. 

Dói um pouco ler porque um monte de código em Swing ali que ninguém gosta mais, né?

Três páginas pra colocar um botão na tela, mas a ideia ali de como eles programam é bem legal, me influenciou bastante.

Então fica aí essa recomendação.

E boa noite aí, gente.

**[Alexandre Aquiles]**

Inclusive, Aniche, esse livro chega a uma arquitetura hexagonal.

A gente pode dizer que chega nesse ponto, não?

**[Mauricio Aniche]**

Eu acho que eles não usam o termo Ports & Adapters no livro, boa pergunta, mas eles têm bastante discussões sobre como modelar classes que são flexíveis, como fazer com que partes dos sistemas sejam fáceis de serem trocadas, etc.

Mas acho que eles são um pouco mais pragmáticos na discussão deles.

**[Alexandre Aquiles]**

Sim, sim.

Ô Ponte, vamos lá, considerações finais.

**[Rafael Ponte]**

Eita, não vou falar sobre o livro porque eu não li o livro do Clean Arch.

Então é mais para deixar aqui uma reflexão que eu tenho, do tipo, da minha carreira, que é o cuidado de ser dogmático ou pragmático.

Eu já fui, no início da minha carreira, ali, jovem, sem muito entendimento do mundo, do mercado, já fui dogmático, já segui Uncle Bob, já segui Domain Driven Design ao pé da letra e vi que só é dor e sofrimento.

Então eu tento balancear isso com um pouco mais de pragmatismo.

E um dos pilares do pragmatismo que eu uso é "Don't fight your frameworks". Não brigue com seus frameworks.

Já dizia Martin Fowler em seu livro de 2002, já dizia Eric Evans em seu livro de 2004. Não brigue com seus frameworks.

E hoje não há qualquer motivo de eu brigar com meu Rails, ou brigar com meu Laravel, ou eu brigar aqui com meu Spring Boot.

Porque eles tão fazendo mais de 80% do trabalho sujo.

Eu só tenho que me preocupar com a regra de negócio, e é isso que a gente tenta fazer há mais de 20 anos, deixar o desenvolvedor, a desenvolvedora, só se preocupar com a regra de negócio.

Mas quando está simples e tedioso, a gente gosta de complicar.

Então eu não sei se vale, talvez no início da sua carreira, investir tanto em estilos arquiteturais.

Não é que você não vai estudar fundamentos, orientação a objetos, ou um paradigma funcional, ou mesmo SOLID, ou alguns padrões de projeto.

Só acho que talvez não vale tanta pena você investir nessa briga dogmática
de estilos arquiteturais, Hexagonal, Clean ou qualquer outro, quando boa parte do seu trabalho vai ser usar um framework.

Então domine aquele framework, tá bom?

Então acho que deixo essa sessão com isso.

**[Alexandre Aquiles]**

Perfeito. Aprendam seu framework. Porque o framework não é um detalhe.

Ou o framework é um detalhe? Brincadeira.

Considerações finais, Otávio?

**[Otávio Lemos]**

Pô, pessoal, obrigado.

Nossa, achei bem legal a discussão.

É isso, né? Eu sou entusiasta do estudo, sou professor universitário.

Então eu fico muito feliz de ver o pessoal na linha de frente, que é dev mesmo, recomendando que se leia mais livros, que o pessoal estude mesmo, acho que vale a pena esse tipo de recomendação.

Porque é como o Branas falou, mesmo que seja pra você saber onde não usar certas coisas.

Então só esse recado final mesmo, acho que vale a pena a gente se aprofundar nas coisas, porque senão você acaba sendo um... vira uma espécie de robô fazendo as coisas sem pensar, sem saber exatamente o que está fazendo.

Então acho legal essa profundidade, de a gente pegar esses livros.

Eu gosto muito do livro que o Aniche recomendou também. E de fato, ele usa Ports & Adapters mesmo. Acho que foi um dos primeiros livros que fala...

Não sei se ele fala o termo, mas no próprio Clean Architecture ele fala desse livro como se fosse um dos primeiros a... utilizar esse tipo de estilo arquitetural.

**[Alexandre Aquiles]**

Eu lembro que chega em algo parecido mesmo.

Esse "Growing Objects Guided by Tests", eu segui o exemplo, sabe? Eu fiz lá, deu um trabalho do caramba. Mas foi bem legal.

E eles chegam em algo parecido, né, Otávio?

**[Otávio Lemos]**

Sim, é isso mesmo. E o livro é espetacular.

Apesar de eu gostar mais do estilo de TDD mais clássico, do estilo do Kent Beck mesmo, mas...

Então é isso, né? Acho que é legal a gente conhecer todos os tipos, estilos de programação, de desenvolvimento, TDD, etc. E saber isso também tem, vai ter esses temas.

Também assim, a cultura é muito diversa, dependendo da empresa que você tá a empresa tá fechada com o framework.

Então, por exemplo, eu tenho amigos, eu tenho... o Tony, que é meu amigão, que é Principal Engineer da Buser. A Buser, ela é feita em cima do Django.

Então assim, tem problema isso? Não tem problema.

Funciona muito bem o aplicativo. Claro, você fechou com o framework.

Pode ser que tenha algum risco nisso.

Quer dizer, o framework pode ser que seja menos estável do que a linguagem.

Então você está dependendo de uma coisa que talvez seja menos estável, mas é um trade-off, sempre tem esses trade-offs na vida.

Então acho que vale a pena, só queria deixar esse recado final, que o pessoal se aprofundar mesmo, estudar, através de livros que realmente aprofundam esses temas, para não fazer as coisas de qualquer jeito nas coxas e fazer cada vez melhor, como o Linhares falou, você que vai ter que cuidar do legado depois.

Valeu, galera.

**[Alexandre Aquiles]**

Pois é. E o Otávio tem um livro aí muito bom.

> [Site do livro "Arquitetura Limpa na Prática", por Otávio Lemos](https://www.otaviolemos.com.br/)

Eu estou lendo. E é sucinto, mas consegue ser mais ponderado do que o... livro do Uncle Bob que tem 400 páginas. É impressionante.

**[Mauricio Aniche]**

E o termo Ports & Adapters aparece mesmo no livro, Alexandre. Tô com ele aberto aqui.

**[Alexandre Aquiles]**

Ah, legal. Legal.

E então é isso, pessoal.

Aí... A gente não falou um monte de coisas que a gente abordou na thread lá, tipo o que é design, o que é arquitetura.

E o Otávio só chegou a mencionar a Functional Core / Imperative Shell.

Tem tanta coisa interessante assim, né?

Mas é isso. Senão a gente vai ficar aqui para sempre conversando, né?

Mas muito obrigado. Desculpa aí, o Hugo, o Juan Lopes, a Gleice, o Rinaldo e várias outras pessoas aí que eu não consegui dar a palavra que estão aparecendo aqui.

E várias outras que eu não vou mencionar porque senão eu vou ficar falando aqui pra sempre.

Mas muito obrigado por comparecer aí, pessoal.

Eu vou ter que ouvir isso 15 vezes pra absorver todo o conhecimento aqui.

Então muito obrigado e eu vou finalizar aqui então. Beleza?

Tchau, tchau pessoal! Valeu!