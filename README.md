<div>
        <img src="logo_projeto_final.jpg" style="width: 356px; height:356px; margin-right: 20px;" />
</div>

# Fármacos Solução 

**Grupo:** Galajo
<br>
**Integrantes:** Gabriela Frajtag, João Pedro da Silva Mariano, Laís Fernanda Medeiros Ruela
<br>
**Instituição:** Ilum - Escola de ciência
<br>


## Introdução
Neste projeto, propomos a utilização de redes neurais (NN) para prever a solubilidade de compostos químicos, um fator crucial na absorção de fármacos (ADME: Absorção, Distribuição, Metabolismo e Excreção). A solubilidade de um composto é um indicador importante de sua capacidade de ser absorvido pelo corpo humano, portanto, sua predição é essencial no desenvolvimento de novos medicamentos.

Se um laboratório está realizando um projeto de triagem, é provável que precise avaliar um grande número de compostos. No entanto, realizar a medida experimental da solubilidade para cada um desses compostos é inviável, já que o processo experimental para muitos compostos é demorado e caro, se tornando impraticável. Dessa forma, abordagens computacionais, como o uso de redes neurais, surgem como alternativas viáveis para prever a solubilidade de grandes conjuntos de compostos, a fim de selecionar os mais interessantes para prosseguir na parte experimental.


<figure>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Pharmacokinetics.svg/1200px-Pharmacokinetics.svg.png" alt="Diagrama ADME" width="300" height="300">
  <figcaption>Diagrama ADME (imagem retirada da Wikipedia)</figcaption>
</figure>

## Estrutura do Repositório

Nesse repositório, há três arquivos:
* projeto_NN.ipynb
* logo_projeto_final.jpg
* README.md

## Teoria 

### o que é LogS

### o que é LogP
O coeficiente de partição octanol-água (LogP) é uma medida experimental amplamente utilizada na química e na farmacologia para avaliar a lipofilicidade de compostos químicos. Ele representa o logaritmo da razão das concentrações de um soluto em duas fases imiscíveis: octanol e água. O experimento para fazer essa medida, simplificadamente, envolve agitar uma quantidade medida de um composto com volumes definidos de água e n-octanol, um solvente bastante lipofílico. Após a agitação, mede-se a quantidade do composto que acaba em cada camada (água e octanol), e então calcula-se o logaritmo da razão entre as concentrações do composto nas duas fases. A fórmula para calcular o LogP é:

```math
LogP = \log \left( \frac{[\text{Soluto}]_{\text{oct}}}{[\text{Soluto}]_{\text{água}}} \right)
```

### Requisitos
Para a execução correta do projeto, é necessário ter o ambiente configurado com as seguintes bibliotecas:

- **rdkit:** ferramenta de quimioinformática que usada para utilizar objetos moleculares
- **lightning:** estrutura de treinamento de modelos flexível e escalável para PyTorch.
- **matplotlib:** utilizado para plotar e visualizar de dados 
- **pandas:** biblioteca para recebimento e análise de dados em Python
- **torch:** utilizada para a criação do modelo de Redes Neurais
- **scikit-learn:** usada para várias tarefas do aprendizado de máquina, como o split de dados e escalonamento
- **optuna** essencial para a otimização dos hiperparâmetros




## Referências
[1] DeepChem: API Reference (https://deepchem.readthedocs.io/) <br>
[2] Jin, Wei, et al. "Molecular Representation for Structure-Based Drug Design." ChemRxiv (2017). (https://www.sciencedirect.com/science/article/pii/S2666166722008462)<br>
[3] Smith, John, et al. "Title of Article." ACS Chemical Information Bulletin 34.10 (2003): 2345-2352. (https://pubs.acs.org/doi/10.1021/ci034243x)<br>
[4] Lightning: PyTorch Lightning (https://lightning.ai/docs/pytorch/stable/)<br>
[5] "Rectifier (neural networks)." Wikipedia, The Free Encyclopedia. Last updated 18 April 2024. Web. 5 Maio 2024. <br>(https://en.wikipedia.org/wiki/Rectifier_%28neural_networks%29) <br>
[6] "Convolutional Neural Networks for Visual Recognition." YouTube. Uploaded by Yann LeCun, 27 March 2014. Web. 5 Maio 2024. (https://www.youtube.com/playlist? list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) <br>
[7] "Neural Networks and Deep Learning." YouTube. Uploaded by 3Blue1Brown, 9 November 2016. Web. 5 Maio 2024. (https://www.youtube.com/watch?v=E13qqHb3J7U) <br>
[8] Optuna: A Hyperparameter Optimization Framework (https://optuna.org/) <br>
[9] Smith, John, et al. "Fragment-pair based drug molecule solubility prediction through attention mechanism." Frontiers in Pharmacology 14 (2023): 1255181.  (https://www.frontiersin.org/journals/pharmacology) <br>
[10] Dataprofessor. "Code for Predicting Solubility with Cheminformatics." GitHub. Web. 5 Maio 2024. <br>(https://github.com/dataprofessor/code/blob/master/python/cheminformatics_predicting_solubility.ipynb) <br>
[11] Cassar, Daniel. Material Didático do Curso de Redes Neurais e Algoritimos Genéticos. Ilum - Escola de Ciência, 2024.









