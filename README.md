# dp100challenge1
Entrega do Desafio - Prevendo Vendas de Sorvete com Machine Learning (Curso DP-100 DIO)

Considerando que eu já havia criado um grupo de recursos e um Workspace Azure ML, 
parti para a criação do Dataset utilizando um .csv com as colunas de Temperatura e Vendas,
para posterior utilização nos modelos.

![1 Dataset criado](https://github.com/user-attachments/assets/bb8e2863-472f-4b7d-8034-bc5a9b3d610a)

Tendo o dataset criado, dei início à criação e execução do AutoML de Regressão:

![2 Finalizando a criação do automl](https://github.com/user-attachments/assets/08793c31-3f07-449e-9fa4-e6d5dd681efc)
![3 Automl rodando](https://github.com/user-attachments/assets/588e4bd5-0fd1-4df0-a3f0-27fb55747e3a)

AutoML executado com sucesso, verifiquei o resultado do modelo:

![Resultado AutoML](https://github.com/user-attachments/assets/370719b3-1902-4a32-bda7-6e23c276147d)

Daí então iniciei a implementação do modelo utilizando os Notebooks, com código Phyton, importando a biblioteca
MLFlow para geração de logs:

![5 Rodando o arquivo jupyter e gerando o script](https://github.com/user-attachments/assets/d472ef1f-77c4-4491-beb7-84e85d50a345)
![4 Instalação do mlflow e azureml-mlflow no notebook](https://github.com/user-attachments/assets/2337e818-d721-4ceb-9d04-3af3be8b6ccb)

O script sorvetes-training.py foi gerado, então criei o Job via comando:

![comando job](https://github.com/user-attachments/assets/45e3985d-f955-4499-a507-236513bb9682)
