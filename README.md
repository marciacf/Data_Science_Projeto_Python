# Data_Science_Projeto_Python
Portifólio de projeto de Data Science em Python

# Projeto Simulador de Pesagens

![Imagem1](https://github.com/marciacf/Data_Science_Projeto_Python/assets/102993177/a5f1ecd0-d592-4ef9-ab87-ec13187fd48b)


#### Trabalho de Análise de Dados aplicado na Mineração usando linguagem Python
## Simulação de pesagem de caminhões na mineração ⚒
 
A simulação em Python mostrou uma maneira de melhorar a eficiência 📈 no processo produtivo da empresa contratante.

Neste trabalho recebi a solicitação para o desenvolvimento de um código para simular diferentes amostragens de pesagens em uma frota de caminhões que operam na área de mineração.
Utilizei dados da balança rodoviária, localizada na mineradora. Na operação é feita a pesagem de cada caminhão (100%) após ser carregado com o minério de ferro, gerando uma coluna de dados com a informação da massa, em toneladas, transportada por cada caminhão.
O alvo foi simular os valores médios da carga transportada buscando valores aleatórios em amostragens reduzidas.

O objetivo foi provar ao cliente que a variabilidade da carga média transportada não tem uma alteração significativa, quando se pesa um número menor de caminhões.
Nesse caso específico, o direcionamento dos caminhões para pesagem aumenta em quase 1km sua distância de transporte, portanto quanto mais caminhões forem pesados menor a produtividade da operação.
 
Criei um código em Python, para simular a carga média em pesagens aleatórias. O código utiliza bibliotecas como numpy, pandas e statistics, e contém inputs para inserir o percentual de pesagens que se deseja realizar e para inserir o número de réplicas que se deseja simular. Para cada réplica o programa calcula o valor médio de uma amostra aleatória de pesagens dentro do percentual escolhido.
 
A ferramenta foi validada pelo engenheiro responsável e provou que o menor percentual de pesagens não alterou, de forma significativa, a carga média transportada pelos caminhões.
De posse desses resultados, foi sugerido a empresa contratante reduzir o número de caminhões pesados. Essa ação vai aumentar a produtividade da operação e reduzir consumo de combustível dos caminhões.
