# Análise Semântica de Detratores - E-commerce Olist

Um projeto de analise de dados focado em analisar o sentimento dos clientes que comentaram\fizerem review com apenas uma estrela em produtos comprados digitalmente, levando em conta dados reais retirados de https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

# 📊 Análise Semântica de Detratores - E-commerce Olist

Este projeto analisa as reclamações de score 1 em compras online para identificar falhas operacionais e quantificar o impacto financeiro da insatisfação.

## 🚀 Destaques do Projeto
- **Limpeza de Dados:** Tratamento de +3000 comentários reais de e-commerce.
- **NLP de Baixo Custo:** Classificação semântica via dicionários de palavras-chave.
- **Visão de Negócio:** Mapeamento geográfico de falhas e cálculo de prejuízo estimado.

## 📖 Storytelling: A Jornada dos Dados

1. O Problema: O Silêncio dos Números Baixos
Iniciamos o projeto com uma base bruta de reviews da Olist. O desafio era claro: notas "1" indicam uma falha crítica, mas a nota sozinha não nos diz o porquê. Precisávamos ouvir o que o cliente tinha a dizer nos comentários para transformar frustração em dado acionável.

2. O Filtro: Focando no que é Relevante
Decidimos filtrar apenas comentários com mais de 30 caracteres, o que chamamos de Comentários Ricos, dado a maior quantidade de informação presente na review.

3. Pensamento: Comentários curtos como "Ruim" ou "Não gostei" podem ser ruído. Queríamos a densidade da reclamação; queríamos o cliente que parou para explicar sua dor. Isso nos garantiu uma base rica para análise semântica.

4. A Descoberta Geográfica: Onde a dor se concentra?
Ao cruzar os dados com a localização, confirmamos que o volume segue a densidade populacional (SP na liderança). Porém, o insight real veio ao observar que em estados mais distantes, a Logística devora as outras categorias. Isso prova que o desafio logistico dos E-commerces não é apenas vender, mas vencer a infraestrutura brasileira.

5. O Xeque-Mate: Do Comentário ao Bolso
Finalizamos conectando as reclamações ao valor dos produtos. Transformamos sentimentos expressos nos comentários em Impacto Financeiro.

Insight Final: Descobrimos que a insatisfação tem preço. Saber que a categoria "Pedido Errado" coloca em risco R$ 1,129,861.81, dá ao gestor o argumento necessário para investir em novos processos para incentivo a melhor infroestrutura no quesito Logistico.

## 📂 Estrutura do Repositório
- `notebooks/`: Script completo com os 13 passos da análise.
- `data/`: Datasets utilizados (originais e processados).
- `images/`: Gráficos gerados durante o diagnóstico.

## 📈 Insights Principais
1. **Logística:** É o maior motivo de nota 1, concentrada fortemente no Sudeste (SP/RJ).
2. **Múltiplos Problemas:** Identificamos clientes que sofreram com atraso e falta de qualidade simultaneamente.
3. **Impacto Financeiro:** O valor total de produtos sob risco foi de **R$1,129,861.81**.

## 🛠️ Como rodar o projeto
1. Clone o repositório.
2. Certifique-se de ter as bibliotecas `pandas`, `seaborn` e `matplotlib` instaladas.
3. atualize os diretórios conforme necessário em sua maquina (no arquivo .ipynb faça uma busca por "read_csv" e "xlsx" e encontrará todos as chamadas de arquivos necessários para a execução)
4. Execute o arquivo `/notebooks/Análise Semântica de Detratores - E-commerce Olist.ipynb`.
