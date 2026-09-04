# Corridas de Táxi em Chicago

Análise de corridas de táxi em Chicago a partir de dados extraídos com SQL, com foco em entender o mercado de empresas, os bairros de destino e o efeito do clima na duração das viagens.

**Principais etapas do projeto**

- **Extração e carga.** Importação dos resultados das consultas SQL e verificação de tipos e valores ausentes.
- **Análise exploratória.** Ranking das 10 empresas com mais corridas e dos bairros que mais recebem viagens, com gráficos e conclusões escritas.
- **Teste de hipótese.** Comparação da duração média das corridas do Loop para o aeroporto O'Hare em sábados com e sem chuva, usando teste t de Welch.
- **Resultado.** Com valor-p de 6,74e-12, a hipótese nula foi rejeitada. Em dias chuvosos a viagem passa de cerca de 33,3 para 40,4 minutos, um aumento médio de 21%.

**Tecnologias**

Python, pandas, NumPy, SciPy e Matplotlib, além de SQL na extração.
