As histórias servem para facilitar a comunicação entre o time de desenvolvimento e o de negócios. Elas devem ser entendidas pelos dois grupos.

Utilizando as histórias, em vez de focar essa conversa nos detalhes técnicos do desenvolvimento do produto, como detalhes do código, focamos na funcionalidade, ou seja, no que ele será capaz de fazer.

Por isso, quem escreve uma história é o Product Owner, e não o time de desenvolvedores. Uma segunda razão para isso é que o cliente é quem sabe como nosso produto, que no nosso caso será um aplicativo, deverá se comportar. Fugiremos de detalhes como a arquitetura e a linguagem. Desenvolvedores podem auxiliar no processo, mas não serão os escritores.

Retomando o nosso aplicativo em desenvolvimento, o Sales Handy, a Starweb deverá ser responsável por ele. A Fast Sale será a empresa contratante. Teremos três tipos de usuários para o aplicativo, o vendedor, o analista e o CEO.

Geralmente, começa-se mapeando os potenciais usuários que vão interagir com o aplicativo. Depois desse mapeamento, é recomendável eleger um usuário principal para começar o Workshop de escrita de histórias.

No nosso caso, o principal usuário será o vendedor, pois ele sempre atualizará o aplicativo. É importante notar que há uma quebra de paradigmas nas histórias de usuários, pois antigamente o foco não era o usuário, mas sim o sistema. A forma de escrever o requerimento costumava se basear no que o sistema deve fazer. Agora, o que está no centro são as demandas do consumidor, o que modifica a forma de desenvolver um software.

Para ilustrar, poderemos pensar que um bom Product Owner deve saber fatiar o bolo. Fatiar o bolo será saber escrever uma história que permeie todas as camadas da arquitetura do software, porque assim ela será construída de forma que o cliente perceba qual o valor do uso do produto, além de poder mapear os riscos desde o começo.

Um bom Product Owner, portanto, deve saber fatiar, descartar e priorizar. Exemplificando, veremos o exemplo de uma história que representará uma fatia muito grande:

_**"Um vendedor pode adicionar todos os detalhes de uma oportunidade de venda em um aplicativo."**_

Outro exemplo, tratando de como o aplicativo funciona internamente:

_**"Os dados de venda são transmitidos do aplicativo a um banco de dados que os processa, gerando insights para oportunidades futuras.".**_

Com base nessas duas histórias, temos praticamente a história do nosso produto. Mas não é possível estimá-las por serem excessivamente amplas.

O papel do Product Owner, então, é saber pegar uma história como essas e conseguir fatiá-las em histórias menores, que sejam estimáveis e cabem dentro de uma Sprint.

Praticando como fatiar, pegaremos só um pedaço do bolo, ou seja, da história:

_**"Como um vendedor eu gostaria de adicionar apenas os detalhes básicos das minhas oportunidades de vendas como valor, nome do cliente, produto e mês. Então, eu teria o* total das oportunidades de vendas no mês corrente* para a consulta."**_

Pegando agora uma fatia maior, poderemos escrever a seguinte história:

_**"Como um vendedor, eu gostaria de adicionar todos os detalhes das minhas oportunidades de vendas, como o meu diretor gostaria de ver. Então, eu teria todos os detalhes das vendas da minha região para fácil consulta."**_

Assim, teremos pego uma grande fatia e escrito uma épica, que é como uma grande história com outras histórias menores envolvidas. Essa história não tem um tamanho adequado para ser estimada, porém, ela será fatiada mais adiante. Essa será a lógica. primeiro, pegar uma fatia pequena para ser estimada agora, e mais para frente conseguirmos dividir a maior parte, ainda que já tenhamos escrito, a fim de reservar um lugar para essas necessidades.

Uma dica importante para escrever boas histórias é que elas devem estar em primeira pessoa, assim como a última história que vimos foi escrita. O vendedor deverá relatar o que que funcionalidade ele quer que o produto tenha e o que essa funcionalidade trará de valor para ele como usuário.

A receita será semelhante à frase:

_**"Como um (papel de usuário) eu gostaria de (funcionalidade). Então, eu (valor)."**_

Analisaremos mais um exemplo:

_**"Como um vendedor, eu gostaria que o aplicativo salvasse as oportunidades que eu insiro a cada dois minutos. Então, eu não perderia os dados caso esquecesse de salvá-las.**_

Parece simples escrever uma história seguindo essa fórmula, mas ainda será necessário praticar para que não peguemos uma fatia muito grande, que não caiba na iteração.

É claro que o tamanho da história dependerá da iteração com que o time trabalha. Geralmente as interações são de no máximo até 30 dias. Isso dependerá da realidade do projeto.

Outra dica é que devemos escrever histórias fechadas, que permitem uma sensação de completude. As histórias possuem camadas, e quando uma história é completa, deverá ser capaz de ser completa em todas essas camadas.

_**"Como um vendedor eu gostaria de exportar meu relatório de oportunidades em CSV. Então, eu poderia ter a visão de quantas oportunidades eu tenho no sistema para este mês."**_

A história acima transmite uma sensação de que o objetivo do vendedor é completar uma etapa, o que é útil para todos que trabalham no time. As histórias fechadas, portanto, passam a impressão de que há começo, meio e fim para uma tarefa e a possibilidade dela ser completada.

Então, o tamanho da história é importante, assim como que ela seja fechada.

Devem ser escritas restrições em cartões. Ás vezes, o que será escrito nos cartões, em vez de histórias serão as restrições que o sistema apresentará. Se tratando de nosso projeto, um dos pedidos da Fast Sale para os próximos releases é que o sistema deve suportar um pouco de 1000 acessos simultâneos.

Isso poderá ser escrito num Story card para que seja priorizado, pois serve ao menos como um lembrete da necessidade de fazer testes de pico no aplicativo. Assim, apesar de não ser uma história, esse cartão guardará o registro de uma informação importante para não ser esquecida.

Também é importante já escrever lembretes para testes atrás dos próprios cartões de histórias, porque isso ajudará na elaboração progressiva desses testes. Como eles serão automatizados, o sistema ficará mais robusto.

Entendemos que existem bons caminhos para escrever histórias bem elaboradas, mas só será possível se tornar um bom escritor através da prática.
