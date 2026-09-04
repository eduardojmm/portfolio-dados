# Otimização e Comparação de Modelos de Classificação Supervisionada

Projeto focado em prever a adesão dos clientes ao plano de telefonia *Ultra* a partir do comportamento de uso (`calls`, `minutes`, `messages` e `mb_used`).

**Principais etapas do projeto**

- **Tratamento de dados.** Validação de ausentes, duplicados e ajuste de tipos numéricos.
- **Divisão do dataset.** Separação em 60% treino, 20% validação e 20% teste, para que a avaliação final acontecesse em dados nunca usados no ajuste dos modelos.
- **Comparação de modelos.** Teste de três algoritmos de classificação (*Regressão Logística*, *Árvore de Decisão* e *Floresta Aleatória*), com variação de profundidade e da quantidade de estimadores.
- **Resultado na validação.** A Floresta Aleatória (`max_depth=9`, `n_estimators=5`) teve a melhor acurácia, 84,60%, contra 81,80% da Árvore de Decisão e 73,25% da Regressão Logística.
- **Avaliação final.** O modelo escolhido foi retreinado com os conjuntos de treino e validação juntos e alcançou 77,92% de acurácia nos dados de teste, separados no início do processo.

**Tecnologias**

Python, pandas e scikit-learn.
