# Knowledge Graph em Python (EDA - 4º Semestre)

Implementação didática de grafo de conhecimento com nós/arestas em dicionários para O(1) em buscas por ID. Aplicado a rivalidades NBA.

## Funcionalidades
- Adicionar/remover nós e relacionamentos
- Buscar por ID (O(1)) e tipo (O(N))
- Impressão de grafo e análise de complexidade

## Como usar
grafo = KnowledgeGraph()
grafo.adicionar_no("LeBron", "Jogador")
grafo.adicionar_relacionamento("LeBron", "rival", "Curry")
print(grafo.buscar_nos_por_tipo("Jogador"))


## Análise de Complexidade
- Inserções/buscas por ID: **O(1)**
- Travessias: **O(N)/O(E)**
- Otimização proposta: índice `nos_por_tipo`

## Relatório Técnico
[PDF completo com análise detalhada]

## Tech
Python | Dicionários | Big O | Triplas semânticas
