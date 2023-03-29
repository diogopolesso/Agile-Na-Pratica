Usaremos o exemplo do GPS. O GPS nos diz em quantos metros temos que virar à esquerda ou a direita quando estamos dirigindo. Pode ser mais difícil para muitos conseguir deduzir quanto é essa distância em metros, em vez de entender se ele dissesse algo como "Vire a terceira rua à direita".

Os pontos fazem um trabalho parecido no sentido de que são unidades de medida relativas. Uma quadra é sempre uma quadra, independentemente das variações de tamanho.É possível haver uma quadra de 200 e uma de 300 m. Portanto, essa é uma medida relativa.

Se tratando de desenvolvimento de software, no começo não saberemos muitos detalhes quanto às histórias dele, e por isso tentaremos estimar o esforço que despenderemos para desenvolver essas histórias. Então, teremos uma sequência de números a ser usados na estimativa.

Essa sequência de números encontrada nos baralhos de Planning Pôquer ("1, 2, 3, 5, 8, 13, 20, 40, 100") é baseada na sequência de Fibonacci. Funciona da seguinte forma: começa-se com 1. 1+1=2. 2+1= 3. 3+2=5. 5+3=8, 8+5=13, e assim por diante. Porém, do 20 em diante arredonda-se o resultado dessa soma para mais. A sequência é valorosa porque se uma história vale 1, ela é simples. Uma história que vale 2, portanto, deve valer o dobro da primeira.

Esse será um valor relativo, não absoluto. Ele não se baseia em horas, por exemplo.

Os pontos são All-Inclusive, pois quando estimamos uma história em pontos. precisamos lembrar que não há apenas o esforço em desenvolvê-la, como também o risco envolvido tanto na arquitetura quanto na tecnologia dela, a refatoração da história, o teste. Então, todas essas questões deverão contar na estimativa.

Jogamos Planning Pôquer porque é rápido e divertido. Jogar permite que o grupo interaja e estime um grande número de histórias de maneira rápida. Essa velocidade também depende de termos antes escrito boas histórias.

Todos terão um baralho com o valor 1, ou A, 2, 3, 5 e 8. Esse baralho pode ser comprado ou produzido pelas próprias pessoas da equipe. Cada um tendo um baralho, haverá confidencialidade.

O Planning Pôquer funcionará de forma que todos terão suas cartas. Uma pessoa lê uma história. Antes de começarmos, haverá uma base para comparar os pontos. Para isso, há duas maneiras. A primeira é pegar uma história considerada simples para todo o grupo e definir que ela valerá 1. A partir de então, todas as outras serão estimadas em comparação a essa.

Uma outra maneira é colocar uma história mediana como valendo 5. Então, as histórias mais simples valerão menos (3, 2 ou 1) e as mais complexas, mais (20, 40 ou 100).

É mais recomendável começar pegando uma história valendo 1, simplificando depois o trabalho de estimar. Mas a melhor maneira de começar dependerá de como a equipe se sentir confortável.

É claro que não devemos olhar o que o outro pretende colocar, "colar" de que forma pretende estimar. Uma pessoa lerá uma história em voz alta, então:

_**"Como vendedor, eu gostaria que o aplicativo salvasse as oportunidades que insiro a cada dois minutos, então eu não perderia os dados caso esquecesse de salvá-las."**_

Depois da leitura, todos jogam, Vamos supôr que três pessoas jogaram a carta indicando que consideram essa uma história de complexidade 3 e uma, considerou de complexidade 5.

A história, então, é estimada como 5 por regra, pois o número 5 vem logo depois do 3. Quando dois números estimados são próximos, deverá prevalecer o maior.

A próxima história, será a seguinte:

_**"Como um vendedor, eu gostaria de adicionar apenas os detalhes básicos das minhas oportunidades de vendas como valor, nome do cliente, produto e mês. Então, eu teria o *total das oportunidades de vendas do mês corrente para fácil consulta.**_

Jogando novamente, duas pessoas estimaram como 3, uma como 5 e uma como 8. Há um gap entre 3 e 8, então, será necessária uma conversa, pois como já foi dito, o mais importante sobre o Story card é proporcionar a conversa, mais do que o que está escrito ser adotado como uma regra. Deverá ocorrer um entendimento comum entre a equipe sobre o que o desenvolvimento dessa história envolverá.

E é importante que o tempo dessa conversa seja monitorado, para não demorar muito nessa etapa. É recomendável ter uma ampulheta ou timer, que pode ser do próprio celular de alguém do time para o monitoramento. Geralmente, estipula-se 2 minutos. Ao final desse tempo, os membros apontam os dedões para cima para indicar se precisarão continuar a conversa, e pra baixo se já conversaram o bastante. Se a conversa não se esgotar naquele momento, é preferível deixá-la para um outro momento e continuar estimando.

Supondo que essa conversa tenha sido suficiente, joga-se de novo. Então, três pessoas consideram como 3 e uma, como 5. O valor da história, portanto, passará a ser 5.

A próxima história, será:

_**"Como um vendedor eu gostaria de adicionar todos os detalhes das minhas oportunidades de vendas como o meu diretor gostaria de ver. Então, eu teria todos os detalhes das vendas da minha região para fácil consulta."**_

Jogando, todos lançarão o 100. Isso porque é uma história muito grande e precisa ser melhor fatiada, conforme o valor alto indica. Então 100 será o número para a história e seguiremos estimando.

A quarta história, será:

_**"Como um vendedor, eu gostaria de exportar meu relatório de oportunidades em CSV. Então eu poderia ter a visão de quantas oportunidades tenho no sistema para esse mês."**_

Jogando, três pessoas estimaram como 3. Mas para um desenvolvedor, pode não estar claro o que o cliente deseja de acordo com a história, então lança uma carta com um ponto de interrogação. Talvez, quem esteja desenvolvendo o projeto não tenha entendido a tenologia envolvida, ou qual é a área do negócio. Essa falta de compreensão ocorre em especial quando uma história está mal escrita, apesar de não ser esse o caso.

Então, deve ser discutido durante um tempo para que tudo seja entendido. Alguns baralhos do Planning Pôquer também podem ter uma carta com uma xícara de café, indicando que uma pessoa está cansada e pedindo um break.

Depois da conversa, então, esperamos que chegue-se num entendimento. Digamos que a partir de agora não só a pessoa entendeu, como o time todo passa a acreditar que a história era mais simples do que haviam imaginado, com as quatro pessoas da equipe estimando como 2.

Quando temos um problema de defeito no código, como pode acontecer, poderemos inclui-lo num cartão para ser priorizados, pedindo por ajustes (bug fix). Os defeitos muitas vezes são pequenos. Caso a equipe tenha um Story card para ajustar defeitos, todas as tarefas relacionadas a esse tema devem ser grampeadas juntamente com esse Story card e estimadas para que os defeitos não se acumulem. O melhor é estimar com pontos baixos, e colocar isso no Backlog. Todos os bug fixes, então, vão incluídos num Story card, o que também é um esforço feito pelo time.

Com o passar do tempo, pode haver uma inflação dos pontos, principalmente se o time estiver com problemas para entregar histórias ao fim das iterações. É recomendável ter um baralho e as histórias pregadas embaixo, para ficar claro se as histórias estimadas de modo semelhante realmente se assemelham no conteúdo. É possível comparar, inclusive, de iteração para iteração, se uma história estimada como 5 numa iteração passada, na atual permanece com esse valor. Caso contrário, pode ficar difícil comparar as métricas.

As métricas também serão tema do curso a seguir, pois no Agile todos devem avaliar e demonstrar o que realmente está gerando bons resultados para o projeto de trabalho.
