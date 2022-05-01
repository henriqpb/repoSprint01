## Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes

### 1. O que é um ataque DDoS e como posso me proteger?

Um ataque DDoS é um ataque realizado a um determinado servidor alvo que hospeda algum tipo de serviço no qual os atacantes querem deixar o serviço fora do ar, impedindo os usuários de utilizar ele. O método consiste em esgotar os recursos do servidor com milhares de acessos simultâneos, repetidamente, realizados por Botnets, máquinas de usuários infectados por vírus.
Podemos nos proteger colocando etapas de verificação de usuários para realizar o acesso, como cadastros, e verificações com captcha, além de investimentos na robustez da infraestrutura, como equipamentos de rede IDS, que consegue identificar anomalias no tráfego, e o IPS que consegue impedir que esse tráfego se espalhe para outros pontos da rede.

### 2. Por que o firewall é uma ferramenta muito importante de proteção?

O firewall é uma ferramenta de proteção importante porque ele isola uma rede interna do restante da internet, controlando o tráfego entre as duas, tornando-a mais segura contra ataques externos.

## Tema: Git e GitHub

### 3. Explique de forma sucinta, o fluxo e envio de um arquivo novo para o repositório do projeto.

Devemos estar no repositório e na branch que queremos “commitar”, executamos o comando git add seguido do nome do arquivo, em seguida executamos o comando git commit -m seguido de uma breve descrição e finalizamos com git push caso exista um repositório remoto.

### 4. Descreva sobre os ganhos de se utilizar a funcionalidade da branch do git.

A funcionalidade branch nos permite criar uma ramificação paralela da linha principal do projeto, o que deixa o desenvolvimento mais organizado e com a possibilidade de várias pessoas trabalharem em paralelo, normalmente em cada branch fica separada uma funcionalidade da aplicação.

### 5. Explique a diferença entre criar o repositório na nuvem e iniciar o repositório a partir de um código existente local.

Quando criamos um repositório na nuvem precisamos trazê-lo para nossa máquina para darmos continuidade ao desenvolvimento, já quando repositório é iniciado na máquina podemos criar um repositório remoto com a finalidade de podermos acessar o código em outras máquinas, compartilhar nosso trabalho, e ficarmos mais seguros com relação a perda de arquivos.

### 6. Qual a diferença entre Git e GitHub?

O git é um sistema de versionamento de arquivo e o github é uma plataforma de hospedagem dos arquivos versionados em git, guardando remotamente os repositórios da sua máquina. O github também possui outras funcionalidades como fork, pesquisar códigos e podemos utilizá-lo como portifólio.

## Tema: Fundamentos de Agilidade: seus primeiros passos para a transformação ágil

### 7. Quais as principais diferenças entre o modelo ágil e o waterfall (modelo em cascata)?

No modelo em cascata o trabalho é feito em fases, e cada fase depende da anterior para podermos avançar, existe uma grande demora para entregar valor e para recebermos feedbacks, é um modelo de trabalho que não performa bem em mercados voláteis.
O método ágil quebra o tamanho da entrega para resolvermos estas questões, são priorizadas as funcionalidades que entregam mais valor o mais rápido possível, possui um constante fluxo de tarefas sendo executadas e metas segmentadas, rápido feedback e ciclos mais rápidos.

### 8. Quais são as 3 perguntas que devem ser respondidas na Daily?

O que fizemos no dia anterior?

O que vamos fazer no dia de hoje?

E se tivemos impedimentos, quais?

### 9. Qual o intuito das seguintes cerimônias?

• Daily

A daily é utilizada para sabermos como está o progresso do trabalho do time, e resolvermos impedimentos e obstáculos do dia a dia. E para sabermos quais tarefas vão ser executadas no dia atual. A reunião tem duração de 15min, participa o time todo e precisam ser sempre no mesmo horário e no mesmo local.

• Planning

É a reunião de planejamento que é feita no início de cada ciclo, aqui o p.o. traz a product backlog já refinada e a apresenta para o time inteiro explicando as prioridades e o valor de negócio das histórias, gerando uma negociação com o time inteiro sobre as tarefas a serem executadas na sprint que está para começar. Seu timebox é de 5% da sprint, temos como resultado uma lista já refinada e priorizada com tarefas a sprint backlog.

• Refinamento

O refinamento é um processo que cabe ao p.o. do time fazer com o topo da lista da product backlog que está organizada por ordem de prioridade para o cliente, os itens que entregam maior valor de negócio. As histórias mais prioritárias têm sua clareza melhorada, e as funcionalidades maiores são quebradas em pedaços menores que já possuem valor para o cliente.

• Review

A review é o momento da apresentação do que foi feito durante a sprint para o cliente, ou seja, a entrega. Nesta reunião devemos levar somente os itens prontos, devem participar todos os participantes do time e se possível o usuário do produto, pois é uma boa oportunidade para um teste. Esta reunião tem um timebox de 2,5% da sprint e dela o p.o. deve gerar uma lista de itens organizados por prioridades do cliente a product backlog.

• Retrospectiva

A retrospectiva é o momento de avaliarmos o ciclo inteiro desde a última reunião de retrospectiva. Existem várias formas de fazermos esta reunião, mas o mais importante é não apontarmos culpados por determinados erros, não é esse intuito da reunião.
Devemos sair desta reunião com uma lista de ações, para promovermos o processo de melhoria contínua para sermos melhores na próxima sprint, o time inteiro deve participar da retrospectiva, seu timebox tem duração de 5% da sprint.

### 10. O que é a estimativa na metodologia ágil?

Entender a complexidade do item proposto na product backlog e estimar quanto de esforço empregar na tarefa de maneira confiável, o processo é repetido em todos os itens até completarmos a sprint backlog.

## Tema: Fundamentos HTTP

### 11. O que é o protocolo HTTP? Qual a diferença entre HTTP e HTTPS?

O protocolo HTTP é um conjunto de regras utilizadas nas comunicações entre as partes dentro da internet, sua sigla significa hypertext transfer procol, existem outros protocolos, mas o HTTP é de longe o mais utilizado dentro do método Cliente Servidor.
A diferença entre o HTTP e o HTTPS é a segurança, no HTTPS os dados das respostas e requisições trafegam criptografados por SSL ou TLS, no HTTP os dados trafegam em formato de textos abertos que se interceptados podem ser facilmente lidos.

### 12. Cite 4 métodos HTTP.

Temos os métodos mais comuns GET e POST, o método GET é quando passamos parâmetros de requisição na URL, geralmente usando para pesquisas. Já o método POST é usado quando incluímos parâmetros no corpo da mensagem como em um processo de login e senha.
Temos também o método DELETE que remove o recurso especificado e o método PUT que cria um novo recurso.
