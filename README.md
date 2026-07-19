# Guardian Tech: Sistema de Manutenção preditiva 

## Descrição do Problema
Este projeto tem como objetivo realizar uma análise preditiva para identificar falhas potenciais em ativos industriais, visando reduzir o tempo de inatividade não planejado.

## Tecnologias Utilizadas
* Python
* VS Code
* Git e GitHub
* Bibliotecas: Pandas, Matplotlib, Seaborn, Sklearn

## Estrutura do Projeto (Fases de Desenvolvimento)
O projeto foi desenvolvido em 7 fases estruturadas para garantir a qualidade da análise:
* **Fase 1:** Análise Exploratória (EDA)
* **Fase 2:** Limpeza e Tratamento de Dados
* **Fase 3:** Feature Engineering
* **Fase 4:** Divisão e balanceamento dos dados
* **Fase 5:** Escalonamento de variáveis
* **Fase 6:** Ajuste de parâmetros e combate ao overfitting
* **Fase 7:** Avaliação da acurácia e veredito final

## Como Executar
1. Clone este repositório.
2. Certifique-se de ter o Python instalado.
3. Abra o arquivo `.ipynb` no VS Code e execute as células.

## Melhorias Futuras
* Implementação de modelos de Machine Learning.
* Criação de dashboards de visualização.

## Análise de Importância das Variáveis
O modelo de Árvore de Decisão permitiu identificar quais fatores são determinantes para a falha dos equipamentos. Observou-se que as variáveis **RPM** e **Potência** possuem a maior importância preditiva, sendo os principais indicadores para uma estratégia de manutenção preventiva eficiente.