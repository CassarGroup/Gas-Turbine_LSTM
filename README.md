# Estágio de Férias - Modelos de Machine Learning em séries temporais
## Uso de 3 bibliotecas de Machine Learning (Darts, Skorch, Pytorch) para previsão de emissão de gases em um dataset sobre turbinas à gás
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)
![Liçenca MIT](http://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=for-the-badge)

### Brainstorm:
- Lembrar de falar instalações necessárias para usar os códigos
- Ver sites: construir um bom readme
- Se inspirar em outros projetos, mas não copiar
- Entender linguagem html
- Fazer um resumo do trabalho, com introdução, resultados prévios e conclusão simples
- Guiar o leitor por onde começar, como proceder etc
- Colocar contatos, fotos e redes sociais da equipe

### Descrição do Projeto
O dataset [Gas Turbine CO and NOx Emission Data Set](https://doi.org/10.24432/C5WC95) foi utilizado a fim de compreender mais sobre Séries Temporais, além de comparar bibliotecas de Machine Learning na previsão da emissão dos gases CO e NOX. O modelo base empregado foi o Multi Layer Perceptron (MLP) e as métricas de erro Mean Absolute Error (MAE) e Root Mean Squared Error (RMSE) foram calculadas para testar a eficiência das bibliotecas. O trabalho está dividido em 3 notebooks, nos quais há uma introdução geral dos conceitos estudados, a análise do dataset, o treinamento dos modelos e uma conclusão dos resultados obtidos. Começe por aqui - [Introdução](https://github.com/CassarGroup/Enzo-Januzzi---Redes-Neurais/Projeto/Introdução.ipynb)

### Pré-requisitos:
É necessário instalar as bibliotecas referentes aos modelos [Darts](https://unit8co.github.io/darts/index.html) e [Skorch](https://github.com/skorch-dev/skorch?tab=readme-ov-file), bem como ter ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/). Conhecimentos em ciência de dados, algoritmos de aprendizado de máquina como o MLP e em séries temporais são bem vindos.

#### Instalação com o pip:
Após baixar os arquivos do projeto, rode os códigos abaixo:
```bash
pip install darts

pip install -U skorch
```

### Pessoas Contribuidoras:
| [<img width=75 src="https://github.com/user-attachments/assets/6beafce6-ebe3-4696-8973-b439df68e3b8" ><br><sub>Daniel Cassar</sub>](https://github.com/drcassar) | 
| :---: |

### Autor:
| [<img width="75" alt="Enzo" src="https://github.com/user-attachments/assets/b0725864-0940-4d00-81cd-7eb514f78290" ><br><sub>Enzo Januzzi</sub>](https://github.com/EnzoJanuzzi) |
| :---: |

### Referências Base:
[1] Gas Turbine CO and NOx Emission Data Set. 2019. UCI Machine Learning Repository. https://doi.org/10.24432/C5WC95.

[2] RUSSO, Cibele. **Uma Introdução a Séries Temporais usando o Python.** 2022. Tutorial - Machine Learning School for Materials @Ilum, CNPEM.

[3] KARPATHY, Andrej. **The spelled-out intro to neural networks and backpropagation: building micrograd.** 2022. Vídeo do YouTube. https://youtu.be/VMj-3S1tku0.




