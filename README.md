# Projeto Machine Learning

## Primeira etapa

- Criar um recurso na plataforma Azure

![Criando um recurso no Azure](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/1.png)

- Escolher o recurso Azure Machine Learning

![Escolhendo recurso do Azure Machine Learning](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/2.png)

- Ao criar o recurso, definiremos a subscrição, o grupo de recursos utilizados e o tipo de conta.

![Configurando recurso](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/3.png)

## Segunda Etapa

- Acessar portal do Azure Machine Learning
- Criar um espaço de trabalho
- Acessar opção de ML automatizado

![Criando um recurso no Azure](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/4.png)
![Criando um recurso no Azure](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/5.png)

- Em definições básicas, vamos atribuir um nome a aplicação, descrição e nome da tarefa.

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/6.png)

- Em tipo de tarefa, escolhemos a tarefa do tipo regressão, escolhemos a fonte dos datos (nesse caso foi de maneira online) e definimos os valores dos limites.

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/7.png)

- Em ver definições de configurações adicionais, realizaremos os seguintes passos:
    - Desmarcar todos os itens da checklist
    - Em métrica principal, escolhemos NormalizedRootMeanSquaredError
    - Em modelos permitidos, escolhemos RandomForest, LigthGBM
  
![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/8.png)
![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/9.png)

- Nos recursos de Computação, manteremos:

    - tipo de computação como sem servidor
    - tipo de máquina virtual com CPU
    - camada de máquina virtual como dedicada

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/10.png)

- Em revisão, analisar todas as variáveis e submeter modelo ao treinamento

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/11.png)

## Terceira Etapa

- Para analisar o modelo treinado, selecionamos o modelo e clicamos em métricas

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/12.png)

- Observamos os gráficos de predição vs valor real
- Outras análises, como os dados residuais, também podem ser feitas

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/13.png)

## Quarta Etapa

- Acessar a guia implementar

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/14.png)

- Adicionar nome e descrição a aplicação
- Definir tipo de computação como instancia de contentor do Azure

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/15.png)

## Quinta Etapa

- Após implementar, obtemos uma nova tela, nela, vamos acessar a guia Testar.

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/16.png)

- No campo a esquerda inserimos nosso dados de teste em formato json, ao submeter os dados ao modelo, obtemos o resultado a direita.

![](https://github.com/Victor-Ribeiro-Acosta/Bootcamp-Azure-AI-Fundamentals-Projeto-Machine-Learning/blob/main/Passos/17.png)

