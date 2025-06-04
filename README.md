# Bootcamp-Excel - Santander

>Repositório dedicado aos estudos do Bootcamp de Excel com IA do Santander.

# Desafios de Projeto

Nesta seção estão todos os desafios de projeto propostos no bootcamp, juntamente com suas respectivas resoluções.

# Desafio 1

A partir de uma compreensão aprofundada sobre como os fundos imobiliários funcionam e as perguntas típicas dos investidores (quanto investir, por quanto tempo, taxa de rendimento, etc.), o desafio consiste em construir uma planilha que ajude o usuário a realizar essas simulações, auxiliando-o a tomar decisões mais informadas sobre seus investimentos. 

## Objetivos de aprendizagem

* Criar ferramentas de simulação de investimentos em Excel;
* Aplicar cálculos financeiros como rendimento mensal e cálculo de dividendos;
* Documentar processos técnicos de forma clara e estruturada; 
* Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica. 

## Resolução do desafio

![Logo da planilha de investimentos](Imagens/Desafio1/planilha_logo.png)

Com esta planilha, é possível configurar uma simulação para um perfil de usuário. Automaticamente, ela realiza os cálculos necessários para que possamos analisar qual perfil de investidor seria mais adequado, além de estimar o tempo ideal para investir com base no perfil e vontade de cada usuário.

### Tabela de Configuração

![Tabela para configuração](Imagens/Desafio1/tabela_de_configuracao.png)

Aqui nessa tabela temos os campos editáveis: Salário, Rendimento Carteira, Sugestão de Investimento

### Investimento Mensal

![Tabela para investimento mensal](Imagens/Desafio1/investimento_mensal.png)

Aqui nessa tabela temos as perguntas de negócio, com elas, automaticamente a planilha calcula o patrimônio acumulado bem como os dividendos mensais.


### Cenários

![Tabela para Cenário](Imagens/Desafio1/cenario.png)

Nessa seção, com base no que foi preenchido na tabela anterior (Respondendo as perguntas de negócio), temos uma projeção pré-elaborada e calculada automaticamente em possíveis cenários para estudo do usuário.

### Perfil de investidor

![Tabela para Perfil](Imagens/Desafio1/perfil_de_investidor.png)

Esta tabela permite alteração no campo de perfil, podemos definir como : Conservador, Moderado ou Agressivo. Além de também definir um valor para ser investido mensalmente. Após essas definições, será calculado automaticamente qual o valor mensal será investido em cada FII, o percentual a ser investido é coletado de uma tabela externa, a qual o usuário pode definir de acordo com os seus próprios critérios.

![Tabela externa](Imagens/Desafio1/tabela_externa.png)

### Gráfico do Perfil de Investidor

![Gráfico do Perfil de investidor ](Imagens/Desafio1/grafico_perfil.png)

Com base nos dados calculados, a planilha plotará um gráfico para análise de dados.

