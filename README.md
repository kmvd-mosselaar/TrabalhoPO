O crescimento acelerado do comércio eletrônico nas últimas décadas tem imposto desafios significativos às operações logísticas, especialmente no contexto urbano. O aumento exponencial do volume de pedidos, aliado às elevadas expectativas dos consumidores quanto a prazos de entrega, confiabilidade e custo, intensifica a complexidade do planejamento de transporte e distribuição de mercadorias. Nesse cenário, a logística da chamada última milha torna-se um dos principais gargalos operacionais e financeiros das empresas de e-commerce.

Um dos problemas centrais enfrentados nesse contexto é a necessidade de distribuir pedidos a partir de múltiplos centros de distribuição (CDs), frequentemente caracterizados por estoques fragmentados, para centenas de clientes geograficamente dispersos. Essa fragmentação de estoque faz com que, em muitos casos, um único centro não disponha de todos os produtos necessários para atender integralmente um pedido, exigindo decisões adicionais como a entrega fracionada (split delivery) ou a troca de produtos entre centros de distribuição (transbordo).

Além disso, as operações logísticas são fortemente impactadas por restrições práticas, como a capacidade limitada dos veículos, a existência de diferentes tipos de frota (veículos pequenos, médios e grandes, com custos e capacidades distintas) e a necessidade de garantir o atendimento completo de todos os clientes. Essas restrições ampliam significativamente o espaço de decisões e tornam o problema computacionalmente complexo, especialmente quando se busca minimizar os custos totais de transporte.

Do ponto de vista da Pesquisa Operacional, esse problema pode ser modelado como uma variação do clássico Problema de Roteamento de Veículos (Vehicle Routing Problem – VRP), com características adicionais relevantes para o contexto do e-commerce. Diferentemente do VRP tradicional, o foco deste trabalho não está na definição explícita das rotas, mas na tomada de decisões estratégicas e táticas relacionadas a:

- qual centro de distribuição deve atender cada pedido ou parte dele;

- quando a entrega fracionada é vantajosa ou necessária;

- quando o transbordo entre centros deve ser utilizado;

- qual tipo de veículo deve ser alocado para cada entrega, respeitando as restrições de capacidade;

- como essas decisões impactam o custo total da operação.

O artigo de referência utilizado neste trabalho aborda esse problema por meio de um modelo matemático exato resolvido com o auxílio de um solver comercial, garantindo a obtenção de soluções ótimas. Contudo, embora os métodos exatos apresentem elevada qualidade de solução, sua escalabilidade é limitada, tornando-se inviáveis para instâncias de grande porte, como aquelas encontradas em operações reais de e-commerce com centenas de clientes e múltiplos cenários de estoque.

Diante dessa limitação, surge a necessidade de investigar abordagens alternativas capazes de fornecer soluções de boa qualidade em tempo computacional viável. Nesse contexto, este trabalho propõe o uso de uma meta-heurística do tipo Adaptive Large Neighborhood Search (ALNS) para resolver o problema de planejamento de entregas diretas em e-commerce. A abordagem busca reproduzir, de forma heurística, as decisões contempladas no modelo matemático exato, avaliando diferentes cenários operacionais e comparando os resultados obtidos com aqueles gerados pelo solver.

Assim, a problemática central deste trabalho consiste em investigar até que ponto uma meta-heurística baseada em ALNS é capaz de produzir soluções eficientes e operacionais para o problema de entrega direta em um contexto de comércio eletrônico, considerando múltiplos centros de distribuição, diferentes políticas de entrega (com ou sem fracionamento e transbordo), restrições de capacidade veicular e dados realistas de localização e demanda, mantendo o custo total de transporte o mais baixo possível.
