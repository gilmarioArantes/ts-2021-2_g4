<!--![Estado de Goiás](./images/sedi.png)-->
<div align=center>
  <img src="./imagens/teste-software.png">
</div>

# <p style="text-align: center;">Processo de Teste de Software</p>
<b>
<p style="text-align: center;">Universidade Federal de Goiás</p>
<p style="text-align: center;">Instituto de Informática</p>
<p style="text-align: center;">Bacharelado em Enenharia de Software</p>
<p style="text-align: center;">INF303 Teste de Software - 2021/2</p>
<p style="text-align: center;">Professor: Gilmar Ferreira Arantes</p>
<p style="text-align: center;">Aluno 1: 201703739: André Maikel Soares Lopes</p>
<p style="text-align: center;">Aluno 2: 201703755: Gustavo Marques Reis</p>
<p style="text-align: center;">Aluno 3: 201709004: Fabiano Gomes Pires</p>
<p style="text-align: center;">Aluno 4: 201700281: Virgínia de Fernandes Souza</p>
</b>
## Histórico

|Versão|Data|Alteração|Autor|
|------|----|---------|-----|
|0.1|29/01/2022|Criação do Documento|gustavo.marques|
|0.2|28/02/2022|Definição do Plano de Teste|fabianogomess|

# Introdução

<span style="color:blue">
Fazer uma introdução ao processo de teste elaborado pelo grupo. Nesta introdução deverá informar se o processo de teste do grupo é para um projeto de desenvolvimento ou para um projeto de manutenção de software
</span>

<!--![Figura 1 - Etapas do Processo de Teste](./images/ptts.png)-->
<div align="center">
  <img src="./imagens/ptts.png">
  <figcaption><br>Figura 1 - Etapas do Processo de Teste</figcaption>
  </div>
<br>

<span style="color:blue">Descrever em alto nível as etapas constituintes do processo, conforme Figura 1.</span>


## Papéis
<span style="color:blue">Descrever quais os papéis (roles) envolvidos no processo de teste.</span>

## Ambiente de teste
<span style="color:blue">Descrever o ambiente de testes, que envolve tanto software, quanto infraestrutura.</span>

# Planejar
  Esta é a primeira etapa do processo de teste, que envolve definir as atividades que determinam quais serão as abordagens dos testes, visando atingir os propósitos do cliente, tendo em vista todas as restrições impostas pelo contexto do projeto. 
  
  Os principais objetivos da etapa de planejamento são verificar a missão, definir os objetivos e as atividades de teste a serem realizadas.
  
  É durante essa etapa que definimos o **Plano de Teste**, um documento que descreve o escopo, abordagem, recursos e cronograma das atividades de teste. Aqui, estão documentadas as exceções quanto à abordagem do teste, recursos a serem utilizados, equipe envolvida e as técnicas a serem aplicadas. 
  Cada atividade aqui estabelecida irá gerar um tópico no Plano de Teste, desse modo ao final desta etapa, teremos o Plano de Teste, completo.
  
  Abaixo temos um diagrama BPM para apresentar visualmente as atividades componentes desta fase do processo de teste.

  
  <div align="center">
    <img src="./imagens/planoTeste.png">
    <figcaption><br>Figura 2 - Fluxo de atividades do Plano de Teste</figcaption>
    </div>
  <br>

## Atividade 1: Análise de Viabilidade.
  Nessa atividade deve-se analisar a viabilidade de se aplicar os testes no produto de software que está sendo desenvolvido. Identificar possíveis limitações que a equipe pode encontrar durante a execução dos testes e como tratá-las.
### Responsável(eis):
 Todos os envolvidos na equipe de desenvolvimento, principalmente a equipe de teste, podem incluir um ou mais stakeholders nesta atividade do processo.
### Quando:
  Deve ser executada antes da implementação do software, e depois de se ter levantado e aprovado os requisitos do sistema. Pode ser executada em paralelo com o design e arquitetura do software. 
### Como:
  Em uma reunião ou reuniões, após definir e aprovar todos os requisitos, deve-se estudar a viabilidade do teste, junto com as limitações que podem ser encontradas no caminho. Se encontrar limitações é indispensável traçar planos para superá-las. 
### Prazo:
  Em média cinco dias.
### Entradas:
  * O documento de requisitos funcionais e não funcionais do software.

### Saídas:
  O tópico “Análise de Viabilidade”, no documento Plano de Teste, deve estar completo.
### Fluxo:
  A atividade 2, Condições do teste.
## Atividade 2: Condições do Teste
  É na atividade de Condições do Teste que as condições do teste são produzidas. Ou seja, define “o quê” será testado. Pode ser definida, de acordo com o BSTQB, como um item ou evento de um componente ou sistema que pode ser verificado por meio de um ou mais casos de teste. Ou seja, pode ser uma função, transação, característica, atributo de qualidade ou elemento estrutural. Tem como propósito transformar os objetivos do teste em algo tangível.

  Essa etapa do processo de teste tem o propósito de exercitar eficientemente as condições de uso do software, procurando atingir o máximo de cobertura com o mínimo de casos de teste.

### Responsável:
  A equipe de teste, um ou mais stakeholders nesta atividade do processo.

### Quando:
  Após a atividade 1,  Análise de Viabilidade.
### Como
  Especificamos as condições de teste (cobertura de itens) para um item de teste (componente ou funcionalidade do software que deve ser testado), detalhando a abordagem do teste e identificando os casos de teste de alto nível associados.
### Prazo:
  Aproximadamente dez dias.
### Entradas:
  * O documento de requisitos funcionais e não funcionais do software.
  * O documento Plano de Teste - 1. Análise de Viabilidade.

### Saídas:
  O tópico “ Condições do Teste”, no documento Plano de Teste, deve estar com todos os casos de teste que serão executados no processo.
### Fluxo:
  A atividade 3, Definição de Critério Mínimos.
## Atividade 3: Definição de Critério Mínimos
Após ter feito a análise de viabilidade e definido as condições de teste, com base nesses dois itens, está na hora de definir os critérios mínimos de aceitação para cada condição de teste, ou caso de teste. Nessa etapa deve se estipular parâmetros de nível de qualidade esperados em cada caso de teste.
### Responsável
A equipe de teste, pode incluir um ou mais stakeholders nesta atividade do processo.
### Quando:
  Após a atividade 1, Análise de Viabilidade e a atividade 2,  Condições de Teste.

### Como
  Deve-se atribuir um nível de qualidade esperado para cada condição de teste descrita. Esse nível deve ser definido com base no escopo do e domínio do projeto e com base nos recursos disponíveis para a realização do processo de teste. Ao final dessa definição os stakeholders devem ser informados das decisões e acordarem sobre o nível de qualidade estabelecido.
### Prazo:
  Em média cinco dias.
### Entradas:
  * O documento de requisitos funcionais e não funcionais do software.
  * O documento Plano de Teste - 1. Análise de Viabilidade.
  * O documento Plano de Teste - 2. Condições do Teste (os casos de teste definidos na atividade 2).

### Saídas:
  O tópico “ Condições do Teste”, no documento Plano de Teste, deve estar com todos os casos de teste e seus respectivos níveis de aceitação.

### Fluxo:
  A atividade 4, Modelagem do Setup

## Atividade 4: Modelagem do Setup
A atividade de modelagem do setup tem como objetivo definir qual o ambiente que o teste será executado, identificação de requisitos de infraestrutura e a identificação de ferramentas que serão utilizadas no processo de teste.
### Responsável
A equipe de teste, pode incluir um ou mais stakeholders nesta atividade do processo.
### Quando:
A atividade 3, Definição de Critério Mínimos.
### Como
  Inicialmente deve-se levantar os recursos de infraestrutura e ferramentas já disponíveis, verificar com em relação aos casos de teste, se as ferramentas atendem os casos de teste que vão ser executados. Após o levantamento e avaliação definir quais as ferramentas serão utilizadas, as já disponíveis ou novas. 
  
  Além dos pontos de vista técnico tem que se levar em conta o ponto de vista do negócio e o valor disponível para adquirir novas ferramentas para a execução dos testes.
  
  As decisões tomadas devem ser registradas e justificadas do documento Plano de Teste e acordadas junto aos stakeholders.

### Prazo:
  Em média cinco dias.
### Entradas:
  * O documento de requisitos funcionais e não funcionais do software.
  * O documento Plano de Teste - 1. Análise de Viabilidade.
  * O documento Plano de Teste - 2. Condições do Teste (completo agora).

### Saídas:
  O tópico “ Modelagem do Setup”, no documento Plano de Teste, completo, com o ambiente e ferramentas, que serão utilizadas no processo de teste, definidas e justificadas. 

  Com esse tópico finalizado, finaliza-se também o documento de Palno de Teste.
### Fluxo:
Finaliza a fase de Planejar, podendo seguir para a fase de Projetar os Casos de Teste.


# Projetar os Casos de Teste
<span style="color:blue">Descrever a fase de Projetas os Casos de Teste, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.</span>

## Atividade 1

### Responsável

### Quando:

### como

### Prazo:

### Entradas:

### Saídas:

### Fluxo:

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Executar
<span style="color:blue">Descrever a Executar, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.></span>

## Atividade 1

### Responsável

### Quando:

### como

### Prazo:

### Entradas:

### Saídas:

### Fluxo:

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Entregar
<span style="color:blue">Descrever a Entregas, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.></span>

## Atividade 1

### Responsável

### Quando:

### como

### Prazo:

### Entradas:

### Saídas:

### Fluxo:

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Considerações Finais
<span style="color:blue">Descrever as considerações finais a respeito deste processo de teste de software.</span>
