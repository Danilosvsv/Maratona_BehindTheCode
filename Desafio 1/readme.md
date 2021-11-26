# Desafio de Negócio

"Cada vez que um cliente solicita um empréstimo a uma instituição financeira, diversos processos e controles internos são acionados, necessários para a avaliação da solicitação recebida. Desta forma, são analisadas manualmente muitas informações relacionadas com o perfil do cliente, destinos de crédito, atividade de trabalho, rendimentos, condições de habitação, entre outros dados demográficos. Além disso, a instituição utiliza os chamados bureaus de crédito para conhecer o histórico de crédito do cliente, a fim de definir o perfil de crédito do cliente. Em conjunto com outros registros próprios, informações de outros créditos, grau de conformidade e comportamento dos produtos contratados, a instituição aprova um valor a ser emprestado e um prazo para sua devolução ou rejeita a solicitação.

# Visão Geral do Modelo

A concessão de crédito envolve diversas esferas de dados dos clientes, entender cada variável foi essencial para moldar qual estratégia de tratamento de dados escolher. Nesse sentido foram realizadas atividades como:

- Análise de Correlação de cada variável com a concessão de crédito
- Análise Gráfica de Outliers
- Aplicação da técnica de IQR para identificar e remover outliers
- Aplicação do Algoritmo de Aprendizado de Máquina Random Forest (ou Floresta Aleatória).
- Verificar precisão do modelo com a Média de erro absoluto (MAE) e Coeficiente de Determinação($R^2$).
- Deploy do modelo
- Armazenamento das respostas do modelo a novos dados em 'ANSWER.csv'

# Melhorias Futuras

Devido a precisão obtida inicialmente, um trabalho adicional envolveria testar outros métodos de Aprendizado de Máquina e outras técnicas de pré-processamento de dados.

Referência: https://github.com/maratonadev/desafio-1-2021/blob/main/doc/instructions/pt.md


