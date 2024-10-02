# Sistema de Avaliação de Redações usando LangGraph

## Visão Geral

Este notebook apresenta um sistema automatizado de avaliação de redações implementado usando LangGraph e um modelo LLM. O sistema avalia redações com base em quatro critérios principais: relevância, gramática, estrutura e profundidade de análise.

## Motivação

Sistemas automatizados de avaliação de redações podem agilizar significativamente o processo de avaliação em ambientes educacionais, fornecendo avaliações consistentes e objetivas. Esta implementação visa demonstrar como modelos de linguagem grandes e fluxos de trabalho baseados em grafos podem ser combinados para criar um sistema sofisticado de avaliação.

## Componentes Principais

Grafo de Estado: Define o fluxo de trabalho do processo de avaliação
Modelo LLM: Fornece a compreensão e análise de linguagem subjacente
Funções de Avaliação: Funções separadas para cada critério de avaliação
Lógica Condicional: Determina o fluxo do processo de avaliação com base em pontuações intermediárias
Método

## O sistema segue uma abordagem passo a passo para avaliar redações:

Relevância do Conteúdo: Avalia quão bem a redação aborda o tema proposto
Verificação Gramatical: Avalia o uso da linguagem e a correção gramatical da redação
Análise da Estrutura: Examina a organização e o fluxo de ideias na redação
Profundidade de Análise: Mede o nível de pensamento crítico e insight apresentado
Cada etapa é executada condicionalmente com base nas pontuações das etapas anteriores, permitindo o término antecipado de redações de baixa qualidade. A pontuação final é uma média ponderada de todas as pontuações dos componentes individuais.

## Conclusão

Este notebook demonstra uma abordagem flexível e extensível para a avaliação automatizada de redações. Ao aproveitar o poder dos grandes modelos de linguagem e um fluxo de trabalho baseado em grafos, oferece uma avaliação nuançada de redações que considera múltiplos aspectos da qualidade da escrita. Este sistema pode ser refinado e adaptado para vários contextos educacionais, potencialmente melhorando a eficiência e consistência das avaliações de redações.
