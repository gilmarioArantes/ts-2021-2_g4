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
<p style="text-align: center;">Aluno 1:201703739:André Maikel Soares Lopes</p>
<p style="text-align: center;">Aluno 2:201703755:Gustavo Marques Reis</p>
<p style="text-align: center;">Aluno 3:201709004:Fabiano Gomes Pires</p>
<p style="text-align: center;">Aluno 4:201700281:Virgínia de Fernandes Souza</p>
</b>
## Histórico

|Versão|Data|Alteração|Autor|
|------|----|---------|-----|
|0.1|29/01/2022|Criação do Documento|gustavo.marques|

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

<span style="color:blue">Descrever a fase de planejamento, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.</span>

## Atividade 1 (definir)

<span style="color:blue">Descrever a atividade 1</span>

### Responsável(eis)

 <span style="color:blue">quais são os papéis envolvidos nesta atividade?</span>

### Quando

<span style="color:blue">quando a atividade deve ser executada?</span>

### Como

<span style="color:blue">como é a execução da atividade?</span>

### Prazo

<span style="color:blue">qual o prazo para execução?</span>

### Entradas

<span style="color:blue">quais são as entradas que subsidiam a execução?</span>

### Saídas

<span style="color:blue">quais são as saídas geradas pela execução?</span>

### Fluxo

<span style="color:blue">qual a próxima atividade a ser executada na sequencia?</span>

## Atividade 2

### Responsável

### Quando

### como

### Prazo

### Entradas

### Saídas

### Fluxo

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Projetar os Casos de Teste

<span style="color:blue">Descrever a fase de Projetas os Casos de Teste, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.</span>

## Atividade 1

### Responsável

### Quando

### como

### Prazo

### Entradas

### Saídas

### Fluxo

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Executar

<div align="justify"><h3>Execução de teste de software - </h3>

<p>Nesta etapa apresenta-se um modelo abrangente de processo de teste, o qual leva em consideração vários níveis de teste e atividades. É um modelo genérico, uma vez que não está ligado a teste de um tipo de software em particular, nem a um processo específico de desenvolvimento de software.
Seguindo o que é geralmente apresentado nessa etapa de teste de software, segue o Modelo V. Esse modelo considera as principais fases do processo de software, associando cada nível de teste de software relacionado. Neste modelo, o ramo esquerdo corresponde à preparação do teste de software, tendo como referencial os estágios do processo de desenvolvimento de software. Enquanto o ramo direito se relaciona à execução e registro do teste, se referenciando nos níveis de teste de software (figura XX).</p>
<figure>
  <img src="imagens/modelo_v1.png" alt="modelov">
  <figcaption></figcaption>
</figure>

<p>
Nas etapas iniciais do processo de software é feita a preparação do teste que engloba o planejamento e o projeto de teste.
 A fase de especificação de requisitos é responsável pela elaboração dos requisitos do usuário que são usados para a determinação dos requisitos dos Teste de Aceitação, este por sua vez, verifica se o sistema satisfaz os requisitos do usuário.</p>
<p>
Na fase de Especificação do Sistema, ocorre a produção das especificações Funcionais e Não Funcionais, usadas para a determinação dos requisitos do Teste de Sistema. Já o teste de sistema é responsável pela verificação das funções, se estão ou não implementadas e se as suas características estão satisfazendo os requisitos.</p>
<p>
A fase de Projeto do Sistema abarca a produção da arquitetura do sistema e estabelece as relações entre os componentes do sistemas usados para a determinação do Teste de integração. É no teste de Integração que ocorre a verificação desses relacionamentos, sua própria  existência e se estes estão implementados corretamente.</p>
<p>
 Na fase de projeto de unidade ocorre a produção do projeto dos módulos do sistema utilizado para determinação dos requisitos do Teste de Unidade. Este testes é responsável por verificar se esses módulos estão codificados corretamente.
</p>
<h4>Preparação para o teste de software</h4>
<p>
O Plano de Teste é,inicialmente, elaborado  a partir dos requisitos do usuário. As
especificações funcionais e não funcionais são utilizadas para refinamento do plano de teste, que pode ser mais detalhado a partir da definição da arquitetura do sistema. Ou seja, o plano de teste é produzido a partir dos artefatos que foram gerados nas fases de especificação de
requisitos, especificação do sistema e projeto do sistema e é complementado com informações
geradas nas especificações de projeto de teste</p>
<p>
O Projeto de Teste de Aceitação é elaborado, em sua versão inicial, a partir dos
requisitos do usuário. Durante essa fase, os requisitos do usuário definidos não contêm informações suficientes para a especificação dos casos de teste nem para a especificação dos
procedimentos de teste, que devem ser completamente especificadas posteriorermente. Apesar disso, já podem ser estabelecidos os critérios de Teste de Aceitação do Sistema.</p>
<p>
O Projeto de Teste de Sistema é elaborado partindo das especificações funcional e não
funcional do sistema, o que também inclui as informações da especificação de casos de teste e da especificação de Procedimentos de Teste</p>
<p>
O Projeto de Teste de Integração é elaborado a partir da arquitetura do sistema, e
inclui as informações da especificação de casos de teste e da especificação de
procedimentos de teste.</p>
<p>
Por fim, o Projeto de Teste de Unidade é desenvolvido partindo do projeto de Unidade, e inclui as informações da especificação de casos de teste e da especificação de procedimentos de teste.</p>

<h4>Execução do teste de software</h4>
<h4>Fluxograma de execução do teste de software</h4>
<p>
A figura(XX) ilustra o fluxo de execução do teste de spftware de um processo genérico de teste, nesa constam os níveis de teste.</p>
<p>
O teste de uma unidade começa após o término de sua codificação e processa-se
através de ciclos de detecção de falhas e de alterações para corrigi-las.

</p>
<p>Para testar uma unidade são aplicadas as seguintes técnicas de teste:</p>
<ul>
<li><p>Técnica Estrutural - técnica na qual os seguintes critérios para a geração dos casos de teste podem ser adotados: Teste de Comandos, Teste de Ramos, Teste de caminhos, Teste de Caminhos Básicos, Teste de Condições, Teste de Condições Múltiplas, Teste de Laços, Teste de Fluxo de Dados.
</p></li>
<li><p>Técnica Funcional- técnica na qual os seguintes critérios para a geração dos casos de teste podem ser adotados: Particionamento de Equivalência, Análise de Valores Limites, Teste Baseado em Casos de Uso, Grafo de Causas e Efeito, Teste Baseado em Tabelas de Decisão, Teste Baseado em Máquinas de Estados. </p></li>
</ul>
<p>Os testes de funcionalidade, desempenho, confiabilidade, usabilidade, e outros, podem  ser utilizados a depender das características da unidade que está sendo testada e também dos objetivos do teste.  </p>
<p>
</p>
<p>O teste de aceitação inicia-se depois da conclusão do teste de sistema. O teste de aceitação se processa através de detecção de problemas e de alterações. Para esse teste, todas as técnicas de todos os tipos de teste sao aplicados no teste de sistema. Embora um processo de teste não precise necessariamente incluir todos os níveis de teste.

</p>

<figure>
  <img src="imagens/fig-exec2.png" alt="bpmn">
  <figcaption></figcaption>
</figure>

</div>

<span style="color:blue">Descrever a Executar, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.></span>

## Atividade 1

### Responsável

### Quando

### como

### Prazo

### Entradas

### Saídas

### Fluxo

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Entregar

<span style="color:blue">Descrever a Entregas, junto com suas respectivas tarefas e papéis responsáveis. Criar um diagrama bpm para apresentar visualmente as atividades componentes desta fase.></span>

## Atividade 1

### Responsável

### Quando

### como

### Prazo

### Entradas

### Saídas

### Fluxo

<span style="color:blue">Identificar e descrever outras atividades componentes desta fase do processo.</span>

# Considerações Finais

<span style="color:blue">Descrever as considerações finais a respeito deste processo de teste de software.</span>
