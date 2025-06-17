# Bootcamp-Excel - Santander

>Repositório dedicado aos estudos do Bootcamp de Excel com IA do Santander.

# Desafios de Projeto

Nesta seção estão todos os desafios de projeto propostos no bootcamp, juntamente com suas respectivas resoluções.

* [Desafio 1 : Planilha de Investimentos](#desafio-1)
* [Desafio 2 : Planilha moderna para Informe de Rendimentos](#desafio-2) 
* [Desafio 3 : Planilha com Dashboard Interativo](#desafio-3) 

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

# Desafio 2

A proposta é construir um agregador de dados no qual o usuário possa controlar suas entradas de maneira eficiente e validada, com menus de navegação, validações automáticas e funcionalidades extras, como links rápidos. A solução será completamente construída no Excel, com recursos que tornam a ferramenta robusta, mas com uma interface amigável e prática.

## Objetivos de aprendizagem

* Aplicar os conceitos aprendidos em um ambiente prático;
* Documentar processos técnicos de forma clara e estruturada; 
* Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica. 

## Resolução do desafio

![Logo da planilha de investimentos](Imagens/Desafio2/logo.png)

Com esta planilha moderna, a qual podemos navegar através dela com itens clicáveis muito parecida com um app, podemos organizar de forma adequada os informes de rendimento para que facilite a declaração dos mesmos. Tudo organizado em um único lugar, com cálculo de totais e um gráfico gerado para que o usuário consiga observar os valores referente a cada categoria declarada de forma visual.

## Planilha para o Titular

![Planilha do titular](Imagens/Desafio2/titular.png)

Nesta aba, devemos preencher os dados do titular o qual fará a declaração do imposto de renda. Aqui, o usuário somente conseguirá alterar os campos onde ele deve preencher, pois o restante está protegido, como em todo o restante do projeto. O botão de navegação "Próximo", leva o usuário para a próxima página, porém, também é possível navegar através dos botões laterais.


## Planilha para os Informes

![Planilha informes](Imagens/Desafio2/informes.png)

Aqui, o usuário deve preencher os dados atuais de cada banco, após realizar o preenchimento de todos os campos, poderemos vizualizar o campo total com o cálculo exato de todos os valores atuais, ou seja, tudo que o usuário possui em conta naquele momento. Nessa aba, além dos botões de navegação lateral, temos os botões "Próximo" e "Anterior", pelos quais é possível ir para a próxima aba ou voltar para a anterior.

## Planilha para as Notas

![Planilha notas](Imagens/Desafio2/notas.png)

Nessa planilha, o usuário deve preencher todos os valores de entrada mês a mês, em categoria, foi definido que ele somente poderá escolher entre as 3 disponíveis definidas pela validação de dados do excel ( HOLERITE, CNPJ, FREELANCE), após preencher todos os dados, o usuário poderá clicar no botão "Gerar Gráfico" para que seja gerado um gráfico conforme os dados de entrada dele.

## Gráfico de notas

![Grafico de notas](Imagens/Desafio2/grafico.png)

O gráfico contém as informações separadas por categorias, esse gráfico só pode ser acessado ao clicar no botão de gerar gráfico.

# Desafio 3

Neste desafio, o foco foi criar uma planilha analítica e interativa voltada para o controle de vendas e assinaturas de serviços do tipo *Game Pass*, simulando um cenário empresarial com diferentes tipos de planos e recursos extras, como cupons e passes de temporada. A proposta se baseia em responder a perguntas de negócio fundamentais e construir um dashboard com visual moderno e responsivo no Excel.

## Objetivos de aprendizagem

* Trabalhar com dashboards dinâmicos no Excel;
* Utilizar fórmulas e automações para análise de dados;
* Desenvolver visualizações interativas com filtros aplicáveis;
* Responder perguntas de negócio com base em dados reais ou simulados;
* Documentar processos técnicos e boas práticas em Excel.

## Resolução do desafio

![Logo da planilha de assinaturas](Imagens/Desafio3/logo.png)

A planilha conta com estrutura modular, organizada em quatro abas principais:

- `Assets`: onde estão armazenadas paletas de cores e elementos visuais;
- `Bases`: contém a base de dados com todas as assinaturas;
- `Cálculos`: onde são realizadas análises e respostas às perguntas de negócio;
- `Dashboard`: interface final para interação e visualização dos resultados.

### Aba "Bases"

![Base de dados](Imagens/Desafio3/bases.png)

Essa aba contém a base de dados com as seguintes colunas principais:

- ID do Assinante  
- Nome  
- Data de Início do Plano  
- Tipo de Renovação (Automática ou Não)  
- Preço da Assinatura  
- Tipo de Assinatura (Mensal, Anual, Trimestral)  
- Inclusão de EA Play e Minecraft  
- Valores extras por passes  
- Cupons aplicados  
- Valor total calculado  

Todos esses dados são utilizados como base para os cálculos e visualizações.

### Perguntas de Negócio

![Perguntas de negócio](Imagens/Desafio3/perguntas.png)

A aba de **Cálculos** é onde ficam centralizadas as perguntas de negócio, todas respondidas com fórmulas e funções avançadas:

1. **Qual o faturamento total por tipo de assinatura?**  
2. **Quantas assinaturas têm renovação automática?**  
3. **Qual o impacto dos cupons de desconto no valor final?**  
4. **Quantas pessoas adquiriram os passes EA Play e Minecraft?**  
5. **Qual o ticket médio por tipo de plano?**

Essas análises fornecem base para o dashboard visual.

### Dashboard

![Dashboard principal](Imagens/Desafio3/dashboard.png)

A aba `Dashboard` consolida os dados em visualizações interativas, permitindo análises rápidas por meio de gráficos e segmentações. Entre os recursos visuais estão:

- **Gráfico de Barras** comparando o faturamento por tipo de assinatura;
- **Cartões Resumo** mostrando dados como total de assinantes, receita gerada e número de planos com recursos adicionais;
- **Slicers (Segmentadores de Dados)** que permitem filtrar por:
  - Tipo de plano (Mensal, Trimestral, Anual)  
  - Presença de EA Play  
  - Presença de Minecraft  
  - Uso de Cupons  
  - Renovação automática

Esses filtros tornam a experiência do usuário mais dinâmica, permitindo análises específicas de subgrupos dentro do universo de assinaturas.
