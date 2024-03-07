# Projeto Machine Learning

## Primeira etapa

- Criar um recurso na plataforma Azure

- Escolher o recurso Azure Machine Learning

- Ao criar o recurso, definiremos a subscrição, o grupo de recursos utilizados e o tipo de conta.

## Segunda Etapa

- Acessar portal do Azure Machine Learning
- Criar um espaço de trabalho
- Acessar opção de ML automatizado
- Em definições básicas, vamos atribuir um nome a aplicação, descrição e nome da tarefa.
- Em tipo de tarefa, escolhemos a tarefa do tipo regressão, escolhemos a fonte dos datos (nesse caso foi de maneira online) e definimos os valores dos limites.

- Em ver definições de configurações adicionais, realizaremos os seguintes passos:
    - Desmarcar todos os itens da checklist
    - Em métrica principal, escolhemos NormalizedRootMeanSquaredError
    - Em modelos permitidos, escolhemos RandomForest, LigthGBM

- Nos recursos de Computação, manteremos:

    - tipo de computação como sem servidor
    - tipo de máquina virtual com CPU
    - camada de máquina virtual como dedicada

- Em revisão, analisar todas as variáveis e submeter modelo ao treinamento

## Terceira Etapa

- Para analisar o modelo treinado, selecionamos o modelo e clicamos em métricas
- Observamos os gráficos de predição vs valor real
- Outras análises, como os dados residuais, também podem ser feitas

## Quarta Etapa

- Acessar a guia implementar
- Adicionar nome e descrição a aplicação
- Definir tipo de computação como instancia de contentor do Azure

## Quinta Etapa

- Após implementar, obtemos uma nova tela, nela, vamos acessar a guia Testar.
- No campo a esquerda inserimos nosso dados de teste em formato json, ao submeter os dados ao modelo, obtemos o resultado a direita.