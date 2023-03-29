Precisamos saber Análise Avançada em Métrica porque às vezes uma métrica só não responde todas as nossas perguntas. Poderá ser interessante comparar uma métrica com a outra para entender o que aconteceu.

Pensemos num gráfico Burnup de release, com uma entrega grande. No eixo y, vertical, teremos os números de Pontos (10, 100, 150, 200, 250, 300, 400). No eixo x, horizontal, teremos 8 iterações.

A release começará com 300 pontos nas duas primeiras iterações. Depois o Product Owner aumentará para 350 pontos na 3ª. tendo permanecido em 350 na 4ª e na 5ª . Na 6ª iteração, chegaremos a 400 pontos, ficando assim até a 8ª . Essa será a linha que diz respeito ao planejamento.

Quando de fato os resultados começarão a ser entregues, na 3ª iteração, quando o Product Owner acrescentará pontos, a inclinação do gráfico do time se alterará.

Na 6ª iteração, se traçarmos uma linha imaginária, veremos que conseguiríamos queimar o combinado inicial, 300 pontos, mas não os 400. Então já na 5ª iteração será possível chamar o Product Owner e avisá-lo de que ou a equipe precisará de mais uma iteração, ou da retirada de 100 pontos.

Então, será muito importante usar a métrica a nosso favor e evitar que não tenhamos tempo para a realização da entrega do produto.

Um novo gráfico que veremos será o de Velocidade versus defeitos por iteração. Ele mostrará se com o aumento da velocidade, haverá impacto no número de defeitos inseridos no código. Os dados desse gráfico serão referentes ao mesmo projeto que o anterior.

Esse gráfico terá colunas cuja altura atingirá a velocidade que atingimos por iteração. Abaixo da coluna, na linha horizontal, estará a informação de quantos defeitos foram adicionados naquela iteração também.

Na 1ª coluna, teremos alcançado a velocidade 45 e inserido 1 defeito no código. Na 2ª iteração, inseriremos 3 defeitos no código à velocidade 55. Na 3ª , inseriremos 6 defeitos com uma velocidade menor. Na 4ª , a velocidade será 75, mas inseriremos 10 defeitos.

Então, a 3ª e a 4ª iteração serão objeto de reflexão. Após o susto de ter inserido 10 defeitos, o que comparativamente é uma quantidade grande, voltaremos a fazer uma velocidade de 40 na 5ª iteração, com 2 defeitos, e na 6ª , 40 de velocidad e 1 defeito.

Isso indicará que a velocidade tende a se estabilizar conforme o passar do tempo, ainda que no começo ela possa ser instável. Ela melhorará no decorrer do projeto, dependendo de aprendermos a estimar melhor no Planning Pôquer, e depois se estabilizará.

Analisando nossos gráficos comparativamente, tanto o Burnup de release quanto o gráfico de colunas, poderemos traçar algumas hipóteses sobre o que terá ocorrido. Uma delas é que conforme os propósitos do time aumentarão, as pessoas poderão se sentir emocionalmente abaladas, achando que não conseguirão entregar tudo para o cliente conforme o planejado, o que tem um impacto moral. Isso poderá causar um aumento no número de defeitos, como ocorrerá na 3ª iteração.

Outra questão a ser levada em conta é que na 3ª iteração também haverá uma redução na velocidade, que poderá se dever ao problema de foco, da mesma forma. Ainda conforme nossa hipótese, na 4ª iteração há possibilidade do time, após essa queda na produtividade, ter querido mostrar mais serviço. Por isso, terá entregues muitos pontos, que não saberemos se foram inflacionados sem conferir no Affinity Mapping, e as histórias terão 10 novos erros dentro do código, o que será mais trabalhoso para solucionar até do que escrever uma nova história.

Um gráfico apontando esse tipo de anomalia torna importante utilizar outras métricas para entender a situação. Uma boa sugestão é que com o tempo, conforme dominemos métricas mais simples como o Burndown, comecemos a monitorar, por exemplo, os defeitos versus a velocidade. Assim, entenderemos se há relação entre a velocidade e os defeitos inseridos no código, o que costuma ser algo bem frequente.
