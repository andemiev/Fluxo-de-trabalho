# Software e engenharia de software

> IEEE - Engenharia de software
>
> Engenharia de software: A aplicação de uma abordagem sistemática, disciplinada e quantificável no desenvolvimento, na operação e na manutenção de software; isto é, a aplicação de engenharia ao software.

---

## Natureza do software

Software consiste em:

1. **instruções** que *fornecem características, funções e desempenho desejados*;
2. **estruturas de dados** que possibilitam aos programas manipular informações adequadamente; e
3. **informação descritiva** (documentação), descrevendo a operação e o uso dos programas.

---

## Domínios de aplicação de software

### **Software de sistema**

Conjunto de programas feito para **atender a outros programas**. Certos softwares de sistema processam estruturas de informação complexas, mas determinadas. Outras aplicações de sistema processam dados amplamente indeterminados.

### **Software de aplicação**

Programas independentes que solucionam uma necessidade específica de negócio.
Processam dados comerciais ou técnicos de uma forma que facilite operações comerciais ou tomadas de decisão administrativas/ técnicas.

### Software de engenharia/científico

**Programas de “cálculo em massa”** que abrangem astronomia, vulcanologia, análise de estresse automotivo, dinâmica orbital, projeto auxiliado por computador, hábitos de consumo, análise genética e meteorologia, entre outros.

### **Software embarcado**

Residente num produto ou sistema e utilizado para implementar e controlar características e funções para o usuário e para o próprio sistema.
Executa funções limitadas e específicas (p. ex., controle do painel de um forno micro-ondas) ou fornece função significativa e capacidade de controle (p. ex., funções digitais de automóveis, como controle do nível de combustível, painéis de controle e sistemas de freio).

### Software para linha de produtos

Composto por componentes reutilizáveis e projetado para prover capacidades específicas de utilização por muitos clientes diferentes.
Pode se concentrar em um mercado hermético e limitado (p. ex., produtos de controle de inventário) ou lidar com consumidor de massa.

### Aplicações Web/aplicativos móveis

Abrange uma ampla variedade de aplicações, contemplando aplicativos voltados para navegadores, computação em nuvem, computação baseada em serviços e software residente em dispositivos móveis.

### Software de inteligência artificial

Faz uso de heurísticas para solucionar problemas complexos que não são passíveis de computação ou de análise direta.
Aplicações nessa área incluem: robótica, sistemas de tomada de decisão, reconhecimento de padrões (de imagem e de voz), aprendizado de máquina, prova de teoremas e jogos.

---

## Definição da disciplina

Pedra fundamental → **foco na qualidade**.

![0edcca01aa3bb51ba6c5bb79090a757a.png](../_resources/0edcca01aa3bb51ba6c5bb79090a757a.png)

:> [!WARNING] Importante
Base da EE → camada de processos

### Processo de engenharia de software

Mantém as camadas de tecnologia coesas e possibilita o desenvolvimento de software de forma racional e dentro do prazo.
O processo define uma metodologia que deve ser estabelecida para a entrega efetiva de tecnologia de engenharia de software.

### Métodos da engenharia de software

Fornecem as informações técnicas para desenvolver o software.

### Ferramentas da engenharia de software

Fornecem suporte automatizado ou semiautomatizado para o processo e para os métodos.

---

## O processo de software

### Processo

Conjunto de atividades, ações e tarefas realizadas na criação de algum artefato.

### Atividade

É voltada para atingir um objetivo amplo (p. ex., comunicar-se com os envolvidos) e é utilizada independentemente do domínio de aplicação, do tamanho do projeto, da complexidade dos esforços ou do grau de rigor com que a engenharia de software será aplicada.

### Ação

Envolve um conjunto de tarefas que resultam em um artefato de software fundamental (p. ex., um modelo arquitetural).

### Tarefa

Se concentra em um objetivo pequeno, porém bem-definido (p. ex., realizar um teste de unidades), e produz um resultado tangível.

---

### Metodologia do processo

Uma metodologia de processo genérica para engenharia de software compreende cinco atividades:

#### Comunicação

Ajustes com o cliente e outros envolvidos.

- entender os objetivos dos envolvidos para o projeto e
- reunir requisitos que ajudem a definir os recursos e as funções do software.

#### Planejamento

A atividade de planejamento cria um “mapa” que ajuda a guiar a equipe na sua jornada.

O mapa – denominado plano de projeto de software – define o trabalho de engenharia de software, descrevendo

- as tarefas técnicas a serem conduzidas,
- os riscos prováveis,
- os recursos que serão necessários,
- os artefatos a serem produzidos e
- um cronograma de trabalho.

#### Modelagem

Criação de modelos para entender melhor as necessidades do software e o projeto que vai atender a essas necessidades.

#### Construção

Essa atividade combina geração de código (manual ou automatizada) e testes necessários para revelar erros na codificação.

#### Entrega

O software (como uma entidade completa ou como um incremento parcialmente concluído) é entregue ao cliente, que avalia o produto e fornece feedback, baseado na avaliação.

---

### Atividades de apoio

#### Controle e acompanhamento do projeto

Possibilita que a equipe avalie o progresso em relação ao plano do projeto e tome as medidas necessárias para cumprir o cronograma.

#### Administração de riscos

Avalia riscos que possam afetar o resultado ou a qualidade do produto/projeto.

#### Garantia da qualidade de software

Define e conduz as atividades que garantem a qualidade do software.

#### Revisões técnicas

Avaliam artefatos da engenharia de software, tentando identificar e eliminar erros antes que eles se propaguem para a atividade seguinte.

#### Medição

Define e coleta medidas (do processo, do projeto e do produto). Auxilia na entrega do software de acordo com os requisitos dos envolvidos; pode ser usada com as demais atividades (metodológicas e de apoio).

---

## A prática de engenharia de software

### A essência da prática

No livro clássico **How to Solve It (A Arte de Resolver Problemas)**, escrito antes de os computadores modernos existirem, George Polya descreveu em linhas gerais a essência da solução de problemas e, consequentemente, a essência da prática da engenharia de software:

- Compreender o problema (comunicação e análise);
- Planejar uma solução (modelagem e projeto de software);
- Executar o plano (geração de código);
- Examinar o resultado para ter precisão (testes e garantia da qualidade).

#### Primeiro princípio: a razão de existir

Um sistema de software existe por um motivo: agregar valor para seus usuários.

Antes de especificar um requisito de um sistema, antes de indicar alguma parte da funcionalidade de um sistema, antes de determinar as plataformas de hardware ou os processos de desenvolvimento, pergunte a si mesmo: “Isso realmente agrega valor real ao sistema?”.

#### Segundo princípio: KISS (Keep It Simple, Stupid!, ou seja: não complique!)

Todo projeto deve ser o mais simples possível, mas não simplista. Este princípio contribui para um sistema mais fácil de compreender e manter.

Isso não significa que características, até mesmo as internas, devam ser descartadas em nome da simplicidade. De fato, os projetos mais elegantes normalmente são os mais simples. A contrapartida é um software mais fácil de manter e menos propenso a erros.

#### Terceiro princípio: mantenha a visão

Sem uma integridade conceitual, corre-se o risco de transformar o projeto em uma colcha de retalhos de projetos incompatíveis, unidos por parafusos inadequados.

Comprometer a visão arquitetural de um sistema de software debilita e até poderá destruir sistemas bem projetados. Ter um arquiteto responsável e capaz de manter a visão clara e de reforçar a adequação ajuda a assegurar o êxito de um projeto.

#### Quarto princípio: o que um produz, outros consomem

Sempre especifique, projete, documente e implemente ciente de que mais alguém terá de entender o que você está fazendo. Especifique tendo como objetivo os usuários.

Projete tendo em mente os implementadores. Codifique se preocupando com aqueles que deverão manter e ampliar o sistema. Alguém terá de depurar o código que você escreveu, e isso o torna um usuário de seu código.

#### Quinto princípio: esteja aberto para o futuro

Jamais fazer projetos limitados a determinada tecnologia, plataforma ou hardware específico.

Sempre pergunte “e se” e prepare-se para todas as respostas possíveis, criando sistemas que resolvam o problema geral, não apenas o específico.

#### Sexto princípio: planeje com antecedência, visando a reutilização

A reutilização economiza tempo e esforço. Alcançar um alto grau de reutilização é indiscutivelmente a meta mais difícil de ser atingida ao se desenvolver um sistema de software.

Planejar com antecedência para a reutilização reduz o custo e aumenta o valor tanto dos componentes reutilizáveis quanto dos sistemas aos quais eles serão incorporados.

#### Sétimo princípio: "pense!"

Pensar bem e de forma clara antes de agir quase sempre produz melhores resultados. Quando se analisa alguma coisa, provavelmente ela sairá correta. Ganha-se também conhecimento de como fazer correto novamente.

Se você realmente analisar algo e mesmo assim o fizer da forma errada, isso se tornará uma valiosa experiência. Um efeito colateral da análise é aprender a reconhecer quando não se sabe algo, e até que ponto poderá buscar o conhecimento. Quando a análise clara faz parte de um sistema, seu valor aflora.
