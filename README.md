# Desafio Kaggle Titanic
O objetivo deste notebook é seguir um fluxo de trabalho passo a passo, explicando cada passo e justificativa para cada decisão que tomamos durante o desenvolvimento da solução.
## Estapas do desafio
Ao todo serão sete etapas
1. Definição do problema.
2. Aquisição dos dados de treino e teste.
3. Preparar, limpar dados.
4. Analisar, identificar padrões e explorar os dados.
5. Modelar, prevr e resolver o problema.
6. Visualizar, relatar e apresentar as estapas de solução de problemas e a solução final.
7. Fornecer e enviar os resultados.
O fluxo de trabalho indica a sequência geral de como cada estágio pode seguir o outro. No entanto, existem casos de uso com exceções.
* Podemos combinar vários estágios de fluxo de trabalho. Podemos analisar visualizando os dados.

* Realize uma etapa antes do indicado. Podemos analisar os dados antes de depois.

* Execute um estágio várias vezes em nosso fluxo de trabalho. O estágio de visualização pode ser usado várias vezes.

# Definição de Problema
Sites de competição como o Kaggle definem o problema a ser resolvido ou as perguntas a serem feitas enquanto fornecem os conjuntos de dados para treinar seu modelo de ciência de dados e testar os resultados do modelo em um conjunto de dados de teste. A questão ou definição do problema para a competição Titanic sobreviventes

Também podemos querer desenvolver algum entendimento inicial sobre o domínio do nosso problema. Isso é descrito na página de descrição da competição Kaggle aqui. Aqui estão os destaques a serem observados.

* Em 15 de abril de 1912, durante sua viagem inaugural, o Titanic afundou após colidir com um iceberg, matando 1.502 dos 2.224 passageiros e tripulantes. Taxa de sobrevivência traduzida de 32%.

* Uma das razões pelas quais o naufrágio levou a tantas perdas de vidas foi que não havia botes salva-vidas suficientes para os passageiros e tripulantes.

* Embora houvesse algum elemento de sorte envolvido em sobreviver ao naufrágio, alguns grupos de pessoas eram mais propensos a sobreviver do que outros, como mulheres, crianças e a classe alta.

# Objetivos
O fluxo de trabalho de soluções de ciência de dados resolve sete objetivos principais.

__Classificando.__ Podemos querer classificar ou categorizar nossas amostras. Também podemos entender as implicações ou a correlação de diferentes classes com nosso objetivo de solução.

__Correlacionando.__ Pode-se abordar o problema com base nos recursos disponíveis no conjunto de dados de treinamento. Quais recursos dentro do conjunto de dados contribuem significativamente para nossa meta de solução? Estatisticamente falando, existe uma correlação entre um recurso e o objetivo da solução? À medida que os valores dos recursos mudam, o estado da solução também muda e vice-versa? Isso pode ser testado para recursos numéricos e categóricos no conjunto de dados fornecido. Também podemos determinar a correlação entre recursos que não sejam de sobrevivência para objetivos subsequentes e estágios de fluxo de trabalho. A correlação de certos recursos pode ajudar na criação, conclusão ou correção de recursos.

__Convertendo.__ Para o estágio de modelagem, é preciso preparar os dados. Dependendo da escolha do algoritmo do modelo, pode-se exigir que todos os recursos sejam convertidos em valores numéricos equivalentes. Por exemplo, converter valores categóricos de texto em valores numéricos.

__Completando.__ A preparação de dados também pode exigir que estimemos quaisquer valores ausentes em um recurso. Algoritmos de modelo podem funcionar melhor quando não há valores omissos.

__Corrigindo.__ Também podemos analisar o conjunto de dados de treinamento fornecido em busca de erros ou valores possivelmente imprecisos nos recursos e tentar corrigir esses valores ou excluir as amostras que contêm os erros. Uma maneira de fazer isso é detectar quaisquer outliers entre nossas amostras ou recursos. Também podemos descartar completamente um recurso se ele não estiver contribuindo para a análise ou puder distorcer significativamente os resultados.

__Criando.__ Podemos criar novos recursos com base em um recurso existente ou em um conjunto de recursos, de modo que o novo recurso siga as metas de correlação, conversão e integridade.

__Gráficos.__ Como selecionar os gráficos e plotagens de visualização corretos, dependendo da natureza dos dados e dos objetivos da solução.

# Problemas de portabilidade
* Especifique as dimensões do gráfico, traga a legenda para o gráfico.
# Boas Práticas
* Realizar análise de correlação de recursos no início do projeto.
* Usando vários gráficos em vez de sobreposições para facilitar a leitura.