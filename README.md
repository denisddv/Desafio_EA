#Projeto de Engenharia de Analytics - BanVic

##Introdução

Este projeto tem como objetivo implementar um sistema de análise de dados para o banco fictício Banco Vitória (BanVic). O foco principal é melhorar a compreensão dos dados financeiros da instituição, permitindo a tomada de decisões mais informadas e aumentando a eficiência operacional.
Descrição do Desafio

O desafio envolve várias etapas essenciais para a criação de um ambiente de análise de dados robusto, desde a preparação dos dados até a criação de visualizações interativas no Power BI. Os principais objetivos são:

    Criação do Banco de Dados: Configurar um banco de dados PostgreSQL e criar as tabelas necessárias para armazenar os dados fornecidos.
    Limpeza e Preparação dos Dados: Carregar e limpar os dados fornecidos, garantindo que estejam prontos para análise.
    Inserção dos Dados: Inserir os dados limpos no banco de dados PostgreSQL.
    Criação da Dimensão de Datas: Criar uma tabela de dimensão de datas para facilitar a análise temporal.
    Análises e Visualizações: Realizar análises detalhadas e criar visualizações interativas no Power BI para apresentar os insights extraídos dos dados.

## Etapas do Projeto
1. Criação do Banco de Dados e Tabelas em PostgreSQL

O primeiro passo foi criar o banco de dados banvic em PostgreSQL. As tabelas foram estruturadas para armazenar informações sobre agências, clientes, colaboradores, contas, propostas de crédito, transações e relacionamentos entre colaboradores e agências. Este banco de dados serve como a base central para armazenar e gerenciar todos os dados necessários para o projeto.

2. Limpeza e Preparação dos Dados

Os dados foram carregados a partir de arquivos CSV e submetidos a um processo de limpeza para remover caracteres problemáticos e garantir a integridade dos tipos de dados. Foram tratadas inconsistências como duplicatas e valores nulos, e garantido que todos os dados estivessem formatados corretamente para a análise.

3. Inserção dos Dados no Banco de Dados

Com os dados limpos, a próxima etapa foi inseri-los no banco de dados PostgreSQL. Esta etapa garante que todos os dados estejam centralizados e acessíveis para análises futuras. O processo de inserção envolveu o uso de scripts para carregar os dados nas tabelas criadas.

4. Criação da Dimensão de Datas

Uma tabela de dimensão de datas (dCalendar) foi criada para facilitar as análises temporais. Esta tabela inclui colunas como ano, mês, dia da semana (numérico e escrito), e dia do mês. A dimensão de datas é essencial para realizar análises detalhadas e comparações ao longo do tempo, fornecendo uma base para segmentação e agregação de dados temporais.

5. Análises e Visualizações

Após a preparação dos dados, foram realizadas várias análises para extrair insights valiosos. As principais análises incluem:

    Volume de Transações por Dia da Semana: Identificar quais dias da semana têm o maior volume de transações. Esta análise ajuda a entender padrões de comportamento dos clientes e a planejar recursos de atendimento.
    Valor Movimentado por Dia da Semana: Analisar quais dias da semana têm o maior valor movimentado. Este insight é crucial para gerenciar o fluxo de caixa e entender os picos de movimentação financeira.
    Valores Movimentados no Início e Fim do Mês: Comparar os valores movimentados no início (primeiros 15 dias) e no final (últimos 15 dias) do mês. Esta análise pode ajudar a identificar tendências de gastos e recebimentos ao longo do mês.
    Distribuição de Transações por Agência: Visualizar a distribuição de transações por diferentes agências. Este dado é útil para avaliar a performance de cada agência e identificar oportunidades de melhoria.
    Evolução Temporal das Transações: Observar a tendência de transações ao longo do tempo. Esta visualização permite analisar o crescimento ou declínio das transações e identificar fatores que influenciam estas mudanças.

## Configuração de Dashboards Interativos

No Power BI, foram criados dashboards interativos que permitem uma análise visual e dinâmica dos dados. Algumas das visualizações incluídas nos dashboards são:
Além das visualizações gráficas, foram incluídos vários cards informativos para destacar métricas importantes:

## Conclusão

Este projeto demonstrou a importância da análise de dados para melhorar a compreensão das operações e comportamentos dos clientes do BanVic. Através das análises e visualizações criadas, a instituição pode tomar decisões mais informadas e melhorar sua eficiência operacional. O próximo passo envolve a implementação desses insights para otimizar as operações do BanVic e proporcionar uma melhor experiência aos seus clientes.
