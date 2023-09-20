# Implantação de Sistemas de Gestão Empresarial - Artefatos UX

&emsp;&emsp; As vantagens da implementação de um sistema SAP em uma empresa é muito relevante, para melhorar a comunicação e transferência de dados entre áreas, aumentar a agilidade dos processos e facilitar a tomada de decisão. Mas para realizar uma integração eficaz, é preciso realizar análises com diferentes metodologias e ferramentas voltadas ao desenvolvimento do projeto e ao negócio do cliente que irá receber a implementação (Chang, 2013). Neste arquivo serão apresentadas as ferramentas e matrizes desenvolvidas para este projeto, ressaltando a importância de sua utilização. <br>

# 1. Imersão preliminar

## 1.1 Pesquisa Exploratória

### 1.1.1 Introdução

&emsp;&emsp; Um ERP (Planejamento de Recursos Empresariais) é um sistema que auxilia na gestão eficiente de todos os processos de uma empresa (como finanças, recursos humanos, produção, entre outros) em um ambiente integrado [1]. Este projeto visa implantar o ERP SAP Business One em um comércio varejista (Premium), visando melhorar os processos operacionais e de tomada de decisões na organização.
A Premium é uma das maiores lojas Motorsport do Brasil, voltada ao público feminino e masculino. Seus produtos são oficiais e licenciados de marcas mundialmente conhecidas, como: JEEP, RAM, Dodge, Mopar, Camaro, S-10, Hot Whells [2].
<br>
&emsp;&emsp; A pesquisa descrita neste tópico teve como objetivo mapear os processos de negócios da Premium. A metodologia utilizada foi de entrevista, utilizando a técnica de coleta de dados em pesquisa qualitativa. Os resultados obtidos foram satisfatórios para o entendimento inicial do projeto. <br>

### 1.1.2 Objetivos

**Objetivo Geral** <br>
&emsp;&emsp; Esta pesquisa tem como objetivo geral mapear os processos de negócios da Premium, com o intuito de compreender seus objetivos, desafios e a estrutura organizacional. <br>

**Objetivo Específicos** <br>
&emsp;&emsp; Os objetivos específicos são:

- Identificar as dificuldades relacionadas à gestão;
- Compreender a estrutura organizacional da empresa;
- Mapear os macroprocessos da empresa, abrangendo vendas, compras, contabilidade, financeiro e estoque;
- Identificar possíveis obstáculos que possam surgir durante a implantação do sistema;
- Identificar os indicadores e métricas de desempenho do projeto;
- Explorar casos reais de implementações de sistemas de gestão empresarial.

### 1.1.3 Justificativas

&emsp;&emsp; As empresas são formadas por um conjunto de atividades estruturadas e medidas, destinadas a resultar num produto especificado para um determinado cliente ou mercado. Nesse sentido, entender como todos os processos são estruturados e se relacionam é um grande desafio, mas necessário durante a implantação de um ERP [3]. <br>
&emsp;&emsp; Para realizar uma transição de sistemas eficaz, é crucial detalhar as configurações, funções, responsabilidades e regras de negócios. Ter essas informações devidamente definidas facilita a criação do sistema e a integração dos diferentes módulos. Portanto, a pesquisa exploratória e a coleta de dados secundários (desk research) têm como objetivo reunir informações tanto internas (objetivos e processos da Premium) quanto externas (casos de implementação de sistemas ERP), visando compreender principalmente as dificuldades, necessidades e expectativas de todas as partes interessadas. <br>


### 1.1.3 A pesquisa 

&emsp;&emsp; No dia 05 de agosto de 2023 foi realizado um kick-off, para marcar o início do projeto, estabelecendo os objetivos, responsabilidades e alinhando as expectativas. Em um segundo momento, a turma fez uma entrevista com a G2 (parceira de projeto) e a premium (cliente) para compreender o projeto. Os grupos elaboraram um conjunto de perguntas, que foram posteriormente analisadas e selecionadas (Figura 1) pelos Products Owners de cada equipe. <br>



 <img src="https://github.com/2023M7T4-Inteli/grupo3/blob/main/assets/imagens/Kickoff_Perguntas%20selecionadas.png" width="900"/>

Imagem 3. Perguntas selecionadas. <br>
Fonte: Dado dos autores (2023).

&emsp;&emsp; No total foram selecionadas 20 perguntas, relacionadas aos aspectos de negócios, à experiência do usuário (UX) e aos processos envolvidos (Tabela 1). Essas perguntas foram distribuídas entre os 5 grupos, que as abordaram ao longo de 4 rodadas. A primeira rodada teve início no grupo 1 e foi concluída no grupo 5, seguida por rodadas subsequentes da mesma maneira. Como resultado final, foi compilado um conjunto abrangente de informações sobre o projeto e a empresa, contribuindo para uma compreensão aprofundada das expectativas e necessidades dos parceiros envolvidos. <br>


| QUANTIDADE      | TEMA     |
|---------------|--------------|
| 1             | Personas     |
| 1             | Análise Financeira|
| 2             | Restrições do Projeto |
| 3             | Objetivos do projeto |
| 13            | Processos de negócio|


Tabela 1. Temas gerais das perguntas. <br>
Fonte: Dado dos autores (2023).

&emsp;&emsp; Através desta pesquisa exploratória, constatou-se que a empresa é composta pelos seguintes setores: logística, compras, financeiro, comercial (B2B e B2C), criativo e eventos. No momento, esses departamentos operam de forma não integrada, o que dificulta a obtenção de demonstrativos de resultados e avaliações de desempenho. Portanto, a implementação do SAP Business One visa simplificar e automatizar a geração de projeções financeiras, cálculos de impostos e métricas de vendas (expectativa dos gestores da Premium). <br>

## 1.2 Pesquisa Desk

&emsp;&emsp; A fim de entender a complexidade e abrangência do SAP, é essencial estabelecer uma base sólida de conhecimento através de fontes bibliográficas relevantes, envolvendo os processos de pesquisa, seleção e análise crítica. Esse fator permite aos pesquisadores e estudantes compreenderem os fundamentos do SAP, suas funcionalidades, arquitetura e aplicações. Portanto, esta pesquisa foi estabelecida através da metodologia por pesquisa bibliográfica.
Evidencia-se que, conforme a ampliação dos meios de utilização das tecnologias de informação para os mais diversos âmbitos e a mudança de interações e relações sociais, maior integração entre clientes, sistemas e empresas (GRIECO, 2012).


&emsp;&emsp;Exposto isso, vemos uma grande mudança na agenda de prioridades de gestão de empresas, anteriormente, focada em monitoramento de caixa e produção.
As empresas reconheceram a necessidade de coordenar melhor as suas atividades dentro de sua cadeia de valor para eliminar desperdícios de recursos, reduzindo o custo e melhorando o tempo de resposta às mudanças das necessidades do mercado, principalmente, com enfoque na satisfação dos clientes.
Um ERP pode ser definido como um sistema de gestão integrado, adquirido sob a forma de pacote de software, que visa atender às necessidades de informação das empresas (ALBRECHT ET AL. 2005).


&emsp;&emsp;A SAP (Sistemas, Aplicativos e Produtos para Processamento de Dados) teve sua origem em 1972, na cidade de Walldorf, na Alemanha. O sistema foi desenvolvido a partir de uma aplicação criada a fim de suportar a escrituração contábil das empresas a partir da integração dos processos da empresa. 
Já o SAP Business One é,  especificamente, o ERP que auxilia no  gerenciamento e suporte de pequenas e médias empresas.
A fim de que a implementação seja realizada da forma mais consistente e satisfatória possível, existem metodologias que se adaptam conforme o tipo e dinâmicas da empresa, o tempo esperado de implementação e outros. São eles:

- Summit;
- ASAP;
- Method Blue.
  
Processo de implementação ERP 



 <img src="https://github.com/2023M7T4-Inteli/grupo3/blob/main/assets/imagens/Processo%20de%20implementa%C3%A7%C3%A3o%20ERP.png" width="900"/>

Figura 2.Processo de implementação ERP.
Fonte: Dado dos autores (2023).

&emsp;&emsp; A implementação de um sistema ERP pode ser conceituada como o processo no qual os módulos são utilizados em uma corporação.
Os fatores de compatibilidade entre a organização e as características dos sistemas ERP mantém toda a relação com a etapa de implementação (LUCAS,1985). Durante o processo de implementação, é fundamental resolver essas discrepâncias, podendo ser efetivada de duas maneiras: ou muda-se o pacote, por meio da parametrização ou customização, ou mudam-se os procedimentos da organização. <br>

**Dificuldades**
&emsp;&emsp; A obra de Carvalho et al. (2019) realiza o estudo de caso da empresa “Rosa Choque”, companhia de roupas femininas, de médio porte e está no mercado há 30 anos. Com base na implementação do sistema na empresa, o autor ressaltou elementos que são fundamentais e podem apresentar impedimento durante a utilização completa e satisfatória do ERP. <br>
- Criação de um time de trabalho que englobe os melhores profissionais da
empresa;
- Criação de forte parceria com os três principais atores do processo: os
consultores da implantação, o fornecedor do software e o fornecedor de hardware;
- Buscar sem parar os menores níveis de personalização do sistema;
- Escolha do ERP com base na adaptação aos negócios da empresa;
- E as pessoas.

&emsp;&emsp;Em suma, à medida que exploramos a integração cada vez maior das tecnologias de informação em diversos setores, é evidente a necessidade de uma maior conectividade entre clientes, sistemas e empresas. Esse panorama em constante evolução trouxe à tona a importância da implementação do Sistema de Processamento de Dados (SAP), em empresas de médio porte, uma vez que a gestão eficaz da cadeia de valor se tornou uma prioridade primordial

## 1.3 Reflexão com Base nos Dados
&emsp;&emsp; Com uma pesquisa imersiva é possível compreender detalhes, desafios, oportunidades e nuances que compôem toda a cadeia de colaboradores e setores da empresa, bem como onde e a forma que a empresa atua no mercado, ressaltando as operações internas e vivências sobre o ambiente de trabalho, indo além de uma coleta de dados superficiais, ajudando os desenvolvedores a entenderem o todo, e não apenas uma parte, com uma imersão direta e a interação dos elementos avaliados na pesquisa.

&emsp;&emsp; Após uma análise detalhada sobre os dados, fica evidente como a partir de uma pesquisa imersiva é possível entender melhor os fluxos de trabalhos a partir dos desafios cotidianos, oportunidades de melhorias e gargalos nos processos, estes que passariam desapercebidos com uma pesquisa de abordagem mais superficial.

&emsp;&emsp; Com isso, torna-se viável também a elaboração de regras de negócio que refletem de maneira precisa e eficaz a realidade operacional e estratégica da empresa, como por exemplo, na relação entre a equipe de vendas em uma loja física, com o seu estoque de produtos locais, e o transporte de produtos do estoque geral, e todas as restrições que modulam os processos e afetam diretamente no fluxo de trabalho da empresa, que necessitam refletir no sistema a ser implementado utilizando o SAP Business One, evitando retrabalho e possíveis atritos entre as partes, como a equipe de consultores e desenvolvedores com a empresa que deseja implementar o sistema em seus processos e seus colaboradores.


## 2. Personas

&emsp;&emsp; A fim de ajudar a equipe de desenvolvimento, foram desenvolvidos dois modelos de persona, que representam um cliente ou usuário ideal do sistema. Essa análise facilita  o entendimento da dor do usuário do sistema, com atenção ao elaborar a melhor estratégia e solução.
A seguir, seguem as personas desenvolvidas:



 <img src="https://github.com/2023M7T4-Inteli/grupo3/blob/main/assets/imagens/Persona_Gabriel.png" width="900"/>

Imagem 1. Persona Gabriel Almeida <br>
Fonte: Dados dos autores (2023) <br>

&emsp;&emsp; A persona do Gabriel Almeida é desenvolvida a fim de compreender o key user que gerencia o fluxo operacional da empresa, a fim de condicionar o treinamento e disseminação do SAP Business One.



 <img src="https://github.com/2023M7T4-Inteli/grupo3/blob/main/assets/imagens/Persona_Fernanda.png" width="900"/>

Imagem 2. Persona Fernanda Macedo <br>
Fonte: Dados dos autores (2023) <br>

&emsp;&emsp; Já a persona Fernanda Macedo corresponde a key user responsável pelo módulo de vendas, disposta a melhorar o processo e aumentar a integração dos outros módulos essenciais para o funcionamento da corporação.


## 3. User Story

&emsp;&emsp; Ao colocar as personas no centro das ações da solução, é útil para mapear o esforço e potenciais dificuldades enfrentadas pelo usuário do sistema, além de validar se as requisições do cliente estejam presentes e funcionais no sistema desenvolvido. O grupo viu a necessidade de criar mais uma user stories para o Gustavo, que é sócio da empresa, por ele ter uma quantidade de tarefas no dia a dia maior do que a Fernanda, como gerente de vendas. 

&emsp;&emsp; A seguir seguem as user stories desenvolvidas para este projeto:

| **${\color{gold}Número}$** 	| ${\color{Gold}01}$  | 
|---	|---	|
| **Título** 	| Validação de dados | 
| **Personas** 	| Gustavo Almeida	| 
| **História** 	| Eu, como sócio fundador da empresa, desejo ter meus dados validados, para que o SAP B1 seja implementado, por meio da consultoria. | 
| **Critérios de aceitação** 	| 1. BBP validados  <br /> 2. Dados mestres validados	| 
| **Testes de aceitação** 	|  Critério 1: <br /> -> O BBP foi preenchido 100% <br /> <ul><li> Aceitou: Correto, começar o próximo critério </li><li> Recusou: Errado, reformular o processo </li></ul> <br /> -> O BBP foi preenchido 80% <br /> <ul><li>  Aceitou: Errado, reformular o processo <br />  </li><li> Recusou: Correto, retornar para o cliente para o preenchimento </li></ul> <br /> Critério 2: <br /> -> O dados mestres foram preenchidos 100% <br /> <ul><li> Aceitou: Correto, começar o próximo critério </li> <li> Recusou: Errado, reformular o processo </li></ul> <br /> -> Os dados mestres foram preenchidos 70% <br /> <ul><li>Aceitou: Errado, reformular o processo </li> <li> Recusou: Correto, retornar para o cliente para o preenchimento 	| 

| **${\color{gold}Número}$** 	| ${\color{Gold}02}$  | 
|---	|---	|
| **Título** 	| Configurações SAP B1 | 
| **Personas** 	| Gustavo Almeida	| 
| **História** 	| Eu, como sócio fundador da empresa, desejo ter as configurações do sistema parametrizadas, para que o sistema seja implementado, por meio da consultoria. | 
| **Critérios de aceitação** 	| 1. Configurações do sistema 	| 
| **Testes de aceitação** 	|  Critério 1: <br /> -> O sistema foi configurado corretamente e está acessível <br /> <ul><li> Aceitou: Correto, começar próxima user story </li><li> Recusou: Errado, reformular o processo </li></ul> <br /> -> O sistema foi configurado corretamente e não está acessível <br /> <ul><li>  Aceitou: Errado, entrar em contato com o suporte <br />  </li><li> Recusou: Correto, entrar em contato com o suporte para entender o erro </li></ul> 

| **${\color{gold}Número}$** 	| ${\color{Gold}03}$  | 
|---	|---	|
| **Título** 	| Testes unitários | 
| **Personas** 	| Gustavo Almeida	| 
| **História** 	| Eu, como sócio fundador da empresa, desejo entender os processos do SAP B1, para que eu possa aplicar no meu dia a dia, por meio das rodadas de testes feitas pela consultoria. | 
| **Critérios de aceitação** 	| 1. Realização de testes unitários  | 
| **Testes de aceitação** 	|  Critério 1: <br /> -> O teste foi realizado com o Key Users <br /> <ul><li> Aceitou: Correto, começar a próxima user story </li><li> Recusou: Errado, reformular o processo </li></ul> <br /> -> O teste não foi realizado com o key users <br /> <ul><li>  Aceitou: Errado, reformular o processo <br />  </li><li> Recusou: Correto, realizar testes com os Key Users </li></ul>| 

| **${\color{gold}Número}$** 	| ${\color{Gold}04}$  | 
|---	|---	|
| **Título** 	| Relatórios da empresa | 
| **Personas** 	| Gustavo Almeida	| 
| **História** 	| Eu, como sócio fundador da empresa, desejo receber relatórios, para me ajudar a tomar decisões. | 
| **Critérios de aceitação** 	| 1. Relatórios consolidados  | 
| **Testes de aceitação** 	|  Critério 1: <br /> -> O sistema gerou relatórios consolidados <br /> <ul><li> Aceitou: Correto, começar o próximo critério </li><li> Recusou: Errado, reformular o processo </li></ul> <br /> -> O sistema gerou relatórios com dados inconsistentes <br /> <ul><li>  Aceitou: Errado, entrar em contato com o suporte <br />  </li><li> Recusou: Correto, entrar em contato com o suporte para entender o erro </li></ul>| 

| **${\color{gold}Número}$** 	| ${\color{Gold}05}$  | 
|---	|---	|
| **Título** 	| Configurações do módulo de vendas | 
| **Personas** 	| Fernanda Macedo	| 
| **História** 	| Eu, como gerente de vendas, desejo ter as configurações do módulo de vendas parametrizadas, para que o sistema seja implementado, por meio da consultoria. | 
| **Critérios de aceitação** 	| 1. Configuração do sistema  | 
| **Testes de aceitação** 	|  Critério 1: <br /> -> O sistema foi configurado corretamente e está acessível <br /> <ul><li> Aceitou: Correto, começar a próxima user story </li><li> Recusou: Errado, reformular o processo </li></ul> <br /> -> O sistema foi configurado corretamente e não está acessível <br /> <ul><li>  Aceitou: Errado, entrar em contato com o suporte <br />  </li><li> Recusou: Correto, entrar em contato com o suporte para entender o erro </li></ul>| 

| **${\color{gold}Número}$** 	| ${\color{Gold}06}$  | 
|---	|---	|
| **Título** 	| Testes Unitários - Vendas | 
| **Personas** 	| Fernanda Macedo	| 
| **História** 	| Eu, como gerente de vendas, desejo que o sistema seja capaz de aceitar e processar os inputs presentes nos plano de testes, para que eu consiga realizar o treinamento a fim de que a utilização do sistema SAP B1 seja da forma correta. | 
| **Critérios de aceitação** 	| 1. Realização de testes unitários  | 
| **Testes de aceitação** 	|  Critério 1: <br /> -> O teste foi realizado com o Key User de Vendas <br /> <ul><li> Aceitou: Correto, começar a próxima user story </li><li> Recusou: Errado, reformular o processo </li></ul> <br /> -> O teste não foi realizado com o Key User de Vendas <br /> <ul><li>  Aceitou: Errado, reformular o processo <br />  </li><li> Recusou: Correto, realizar testes com o Key Users de Vendas </li></ul>| 

| **${\color{gold}Número}$** 	| ${\color{Gold}07}$  | 
|---	|---	|
| **Título** 	| Relatórios do módulo de vendas | 
| **Personas** 	| Fernanda Macedo	| 
| **História** 	| Eu, como gerente de vendas, desejo receber relatórios da área de vendas, para me ajudar a tomar decisões. | 
| **Critérios de aceitação** 	| 1. Relatórios de vendas validados  | 
| **Testes de aceitação** 	|  Critério 1: <br /> -> O sistema gerou relatórios de vendas validados <br /> <ul><li> Aceitou: Correto, começar o próximo critério </li><li> Recusou: Errado, reformular o processo </li></ul> <br /> -> O sistema gerou formulários de vendas com dados inconsistentes <br /> <ul><li>  Aceitou: Errado, entrar em contato com o suporte <br />  </li><li> Recusou: Correto, entrar em contato com o suporte para entender o erro </li></ul>| 




## 4. Referências

VALENTIM, Onivaldo; POLITANO, Paulo; PEREIRA, Néocles; FILHO, Targino. Análise comparativa entre a implementação e atualização do sistema ERP R/3 da SAP considerando os fatores críticos de sucesso descritos na literatura: um estudo de caso em uma empresa do segmento de bebidas. SciELO, [S. l.], 21 fev. 2014. Disponível em: https://www.scielo.br/j/gp/a/KYVmhdHxR6wGPnxbPYwxQ8R/?lang=pt. Acesso em: 2 ago. 2023.


CAPELLI, Andressa; STORK, Emanuela; SCHUNSK, Fernanda; TOAZZA, Mieli; LEONI, Thais. IMPLEMENTAÇÃO E AVALIAÇÃO DO SISTEMA ERP-SAP NA EMPRESA JOHN DEERE BRASIL -FÁBRICA DE TRATORES. Caderno de Administração. Revista do Departamento de Administração da FEA, [S. l.], v. 8, p. 38-49, 1 jan. 2014. Disponível em: https://revistas.pucsp.br/index.php/caadm/article/view/21135/19679. Acesso em: 2 ago. 2023.

GRIECO, F. A. O Brasil e a globalização econômica. São Paulo: Aduaneiras, 2012.


LUCAS, Henry C. Jr. The analysis, design and implementation of information systems. 3ª ed. New York: McGraw Hill, 1985.


SANTOS, Bruno; TRANCOSO, Ederlaine; CARVALHO, Évelyn; ZAPPAROLLI, Luciana. O ERP NAGESTÃO DE PEQUENAS E MÉDIAS EMPRESAS: UM ESTUDO DE CASO. 2019. Revista (Tecnólogo em Logística) - Revista, [S. l.], 2014. Disponível em: https://www.revistarefas.com.br/RevFATECZS/article/view/344/232. Acesso em: 13 ago. 2023.

SAP. SAP Business One. In: SAP. SAP Business One. [S. l.], 2 fev. 2016. Disponível em: https://www.sap.com/products/erp/business-one.html. Acesso em: 13 ago. 2023.


[1] O que é ERP?. SAP, [s.d.]. Disponível em: <https://www.sap.com/brazil/products/erp/ what-is-erp.html>. Acesso em: 07 de ago. de 2023.

[2] Sobre a Premium Collection. Premium Collection, [s.d.]. Disponível em: <https:// www.usepremium.com.br/sobre-a-premium-collection>. Acesso em: 07 de ago. de 2023.

[3] ALLEN, ROGER K. The Design Process. The Center For Organizational Design, [s.d.]. Disponível em: <https://centerod.com/2012/02/organizational-design-process/>. Acesso em: 07 de ago. de 2023.
