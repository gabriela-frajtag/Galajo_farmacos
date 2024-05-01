# Galajo Fármacos


## Introdução
Neste projeto, propomos a utilização de redes neurais (NN) para prever a solubilidade de compostos químicos, um fator crucial na absorção de fármacos (ADME: Absorção, Distribuição, Metabolismo e Excreção). A solubilidade de um composto é um indicador importante de sua capacidade de ser absorvido pelo corpo humano, portanto, sua predição é essencial no desenvolvimento de novos medicamentos.

![ADME (imagem retirada da wikipédia](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Pharmacokinetics.svg/1200px-Pharmacokinetics.svg.png)

## Teoria 

### o que é LogP
O coeficiente de partição octanol-água (LogP) é uma medida experimental amplamente utilizada na química e na farmacologia para avaliar a lipofilicidade de compostos químicos. Ele representa o logaritmo da razão das concentrações de um soluto em duas fases imiscíveis: octanol e água. O experimento para fazer essa medida, simplificadamente, envolve agitar uma quantidade medida de um composto com volumes definidos de água e n-octanol, um solvente bastante lipofílico. Após a agitação, mede-se a quantidade do composto que acaba em cada camada (água e octanol), e então calcula-se o logaritmo da razão entre as concentrações do composto nas duas fases. A fórmula para calcular o LogP é:

```math
LogP = \log \left( \frac{[\text{Soluto}]_{\text{oct}}}{[\text{Soluto}]_{\text{água}}} \right)
```
Se um laboratório está realizando um projeto de triagem, é provável que precise avaliar um grande número de compostos. No entanto, realizar a medida experimental do LogP para cada um desses compostos é inviável, já que o processo experimental para muitos compostos é demorado e caro, se tornando impraticável. Dessa forma, abordagens computacionais, como o uso de redes neurais, surgem como alternativas viáveis para prever o LogP de grandes conjuntos de compostos, a fim de selecionar os mais interessantes para prosseguir na parte experimental.
