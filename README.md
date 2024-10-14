<h1 align='center'> Clareyamar X Hidra - Projeto Machine Learning </h1>
<h3 align='center'> Desenvolvemos um projeto para prever a dureza da água, através de um dataset com diversas informações sobre águas.</h3>

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

![_Beige Medieval City Desktop Wallpaper](https://github.com/user-attachments/assets/aac17c75-806e-4130-b3eb-0e0960b2c9e2)

## Resumo do Projeto

<b>*Após escapar das profundezas do oceano, a Divisão Clareyamar foi perseguida pela Hydra de Lumi, enviada por Netuno, desde a fuga dos heróis da Sociedade Aurora. Assim, este monstro passou a contaminar as águas do Reino de Lumi e sua população, sendo responsabilidade de Clareyamar combater o dragão do mar.*</b>

Este é um projeto de aprendizado de máquina para a matéria de Aprendizado de Máquina, do curso de Bacharelado em Ciência e Tecnologia da Ilum Escola de Ciência. O trabalho consiste em desenvolver e treinar modelos de machine learning desenvolvidos em Python para, a partir de dados coletados no dataset <b>*Water Quality*</b> obtido na plataforma Kaggle, prever os valores de dureza da água a partir de alguns atributos.

## ÍNDICE
* [Resumo do Projeto](#resumo-do-projeto)
* [Introdução](#introdução)
* [Lore](#lore)
* [Recursos Utilizados](#recursos-utilizados)
* [Data Set](#data-set)
* [Modelos Preditivos](#modelos-preditivos)
* [Resultados](#resultados)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Agradecimentos](#agradecimentos)
* [Desenvolvedores](#desenvolvedores)
<br>

## Introdução

Como trabalho final da matéria de Aprendizado de Máquina do Bacharelado em Ciência e Tecnologia da Ilum, os presentes discentes desenvolveram algoritimos de aprendizado de máquina para construir modelos preditivos que prevessem a dureza da água considerando parâmetros como pH, turbidez, total de sólidos dissolvidos, condutividade, entre outros. Para isso, aplicamos 4 modelos diferentes: **um Regressor K-NN, um Regressor Linear por Mínimos Quadrados, um Regressor Linear Lasso e uma Árvore de Decisão**.

Antes dos treinos dos modelos, foi aplicada uma busca em grade para encontrar os melhores hiperparâmetros para os treinos. Os modelos foram treinados no mesmo split de treino e testados no split de teste. Ao longo da aplicação, realizamos medidas de erro dos modelos utilizando como métrica a raiz do erro quadrático médio e plotamos gráficos comparando as previsões com os dados de teste conhecidos para análise da performance dos modelos.

## Lore
<b>*Há muitos éons, Netuno - deus dos mares - relacionou-se com Aura, uma herdeira de Pheabus - deus do Sol. Dessa relação, foram gerados seres marinhos que, próximos de sua mãe, desenvolveram habilidades luminosas quando sob raios e ventos solares, as quais desagradaram o deus Netuno. Assim, nasceu a Sociedade Subaquática de Aurora, herdeiros de Aura e deserdados de Netuno, exilados no profundo e escuro oceano com sua luz reprimida. Desde então, os seres de Aurora almejam retornar ao alcance do Sol e à proteção de sua mãe para despertar seus adormecidos poderes de luz e vingar a tirania de seu pai.*</b>

<b>*Ebony Vitrum, Escudeiro de Cristal :shield: - Ebony cresceu entre os vidraceiros reais de Aurora, um importante ofício no reino, já que vidro é um recurso muito abundante e valorizado para essa sociedade. A produção e uso de armas e escudos de vitrais cativou Ebony e o fez desenvolver grandes habilidades com escudos, tornando-o um dos maiores escudeiros de Aurora. Ao longo de sua vida, Ebony se incomodava com o conformismo da população em permanecerem reclusos no fundo do oceano, e desejava alcançar o sol novamente para reencontrar seus ancestrais e libertar seu povo.*</b>

<b>*Olive Solace, Arcano do Sol :sunny: - Olive foi abandonado recém nascido na porta de um templo secreto para Pheabus, os sacerdotes guardavam um pedaço do sol que caiu do céu e ensinaram a Olive as artes da luz, mas o mantinham escondido de Netuno, até que em uma de suas fugas do templo, Ebony Vitrum, uma guerreira real, descobriu sobre os poderes de Olive, mas prometeu não contar para o resto das pessoas, esse segredo às aproximou e uniu seus impetos de voltarem para a luz do sol*</b>

<b>*Haryell Marino, Mago do Mar :ocean: - Haryell nasceu como príncipe de Aurora, filho do Rei Arthur. Desde pequeno ele foi treinado para ser o sucessor do trono, porém, nunca foi sua aspiração de fato, Haryell sonhava em sair das profundezas e conhecer o mundo da superfície. Em vez de se preparar para ser rei, Haryell fugia para se encontrar com os magos guerreiros de Aurora, que lhe ensinavam sobre as artes das águas. Os magos sabiam dos sonhos dele e conheciam outra pessoa com o desejo similar, assim eles apresentaram Haryell a Ebony e logo se tornaram amigos.*</b>

<b>*Ebony reuniu o grupo e, juntos, formaram a Divisão Clareyamar, os seres marinhos que finalmente conquistaram a magia do sol e alcançaram a superfície, juntando-se ao Reino de Lumi como defensores das águas e das regiões portuárias locais para recuperar suas habilidades solares na luz do dia sem abandonar suas tradições aquáticas. Sua principal missão em Lumi? Alcançar a Legião da Alvorada, onde esperam encontrar o deus Sol, Pheabus, para finalmente recuperar a honra, a liberdade e a luz do povo de Aurora de Netuno.*</b>

<b>*Netuno, porém, não ficou nada feliz em saber que seus filhos estavam tentando voltar para a luz, e mandou a Hidra, o dragão marinho mais temido e poderoso para atacar o Reino de Lumi e encontrar a divisão Clareyamar. Ao chegar a Lumi, a fera começou a atacar os habitantes e poluir as águas do reino. Clareyamar ao perceber que isso era obra de Netuno, se encarregou de encontrar a Hidra, através dos rastros de poluição deixados na água por ela, e derrotá-la, para impedir a destruição de Lumi e se provarem dignos de entrar na Legião da Alvorada.*</b>

## Recursos Utilizados

<img src="https://github.com/user-attachments/assets/78c00970-b717-4c28-b086-a4b73a294a27" alt="Texto Alternativo" width="100">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/dd5953d4-0b62-467b-85ed-9a992d6c1511" alt="Texto Alternativo" width="101">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/025152bd-de97-420c-8a96-bf4d675bea31" alt="Texto Alternativo" width="101">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/314dcd00-784b-4f40-b361-a46329aad30e" alt="Texto Alternativo" width="145">

<img src="https://github.com/user-attachments/assets/379bd928-e479-427d-8d49-651a65dc1315" alt="Texto Alternativo" width="195">

<img src="https://github.com/user-attachments/assets/ac550461-c75f-40aa-ba05-6c9189de6825" alt="Texto Alternativo" width="103">

## Data Set

Todos os dados foram obtidos no data set *Water Quality* da plataforma *Kaggle*, O arquivo contém métricas de qualidade da água para 3276 corpos d'água diferentes. O dataset tem dados de propriedades da água como pH, dureza, condutividade, turbidez e potabilidade, além de dados acerca dos poluentes presentes na água como os sólidos, as cloroaminas, os sulfatos, os carbonos orgânicos e os trialometanos dissolvidos. O dataset possui 3276 linhas e 10 colunas, porém para a aplicação do trabalho, retiramos as linhas que tinham dados faltantes, restando 2011 linhas para trabalhar.

O link para a página do dataset no Kaggle se encontra [aqui](https://www.kaggle.com/datasets/adityakadiwal/water-potability/data)

## Modelos Preditivos

Neste trabalho,foram utilzados quatro modelos preditivos: regressor k-NN, regressor linear por mínimos quadrados, regressor linear lasso e árvore de decisão. Para a aplicação, foi feita uma divisão do *dataset* em treino e teste com o `split_train_test()` e a busca pelos melhores hiperparâmetros com o `GridSearchCV()`, ambas implementadas do `scikit-learn`.

* Regressor k-NN:

O regressor k-NN ou k-Vizinhos mais próximos é um algoritmo de aprendizado de máquina que se baseia na premissa de que dados semelhantes representam pontos próximos no espaço dos atributos. O funcionamento deste regressor é relativamente simples, o modelo é descrito pelas coordenadas dos dados de treino e pelo target associado a cada uma. Para realizar uma previsão o algoritmo recebe um conjunto de atributos X e calcula a distância entre o exemplo dado e os valores conhecidos, selecionando os k vizinhos mais próximos e calculando a média dos seus respectivos targets, o valor obtido é o resultado da previsão.  
 

* Regressor Linear por mínimos quadrados:

Modelos lineares de previsão consistem em métodos de regressão nos quais há uma combinação linear dos atributos para ajustar os dados. Em geral, modelos lineares são expressos por:

$$ \hat{y} = \beta_0 + \sum_{i=1}^{p}\beta_ix_i$$

em que $\hat{y}$ é previsão do modelo, $x_i$ são os atributos analisados, $\beta_i$ são os coeficientes que acompanham $x_i$ da combinação linear, e $\beta_0$ é o *intercepto* - ou seja, o valor inicial do modelo. Note que $p$ representa o número de atributos.


A previsão de modelos lineares mais tradicional é o **método de mínimos quadrados**, que define os coeficientes $\beta_i$ buscando minimizar a soma dos resíduos quadrados. 

Neste trabalho, implementamos o modelo `LinearRegression()` do `scikit-learn`

* Regressor linear Lasso:

Partindo da regresão linear por mínimos quadrados, é possível aplicar uma penalização nos termos $\beta_ix_{ji}$, a fim de minimizar ainda mais o erro quadrado. Tal modelo com penalização é chamado de **Lasso**, que visa eliminar alguns termos do modelo linear zerando coeficientes $\beta_i$ para apresentar um modelo que se adeque melhor aos dados evitando o *overfiting*. Essa eliminação de coeficientes é dada ao somar o produto entre um *índice de penalização* $\alpha$ e cada coeficiente $\beta$. 

É importante observar que, se $\alpha=0$, o ajuste obtido pelo Lasso é o mesmo obtido pelo método de mínimos quadrados, visto que não há penalização sobre os coeficientes. Já se $\alpha \rightarrow \infty$, a penalização é infinita e todos os coeficientes são zerados, de modo que o modelo linear obtido seja inconclusivo e igual a zero. Desse modo, é preciso encontrar um valor $0<\alpha<\infty$ que torne o modelo mais eficiente, utilizando uma métrica como, por exemplo, o RMSE, para testar os modelos treinados. Para isso, é possível utilizar a estratégia de *validação cuzada* para dividir os dados analisados, testando diferentes valores de $\alpha$ em cada *fold* e analisando o melhor desempenho dos modelos treinados através de uma métrica.
    
Neste trablalho, implementamos o `LassoCV()` do `scikit-learn`, que utiliza validação cruzada para otimizar o parâmetro $\alpha$.

* Árvore de decisão:

O modelo de Àrvore de Decisão apresenta um grafo direcional acíclico na qual seus vértices apresentam condições que representam alguma característica dos dados analisados. Inicialmente, o grafo começa pelo vértice raiz, a qual duas setas saem e nenhuma chega, caso o critério seja cumprido, segue-se no grafo pela esquerda, se não, segue-se pela direita. Após o vértice raiz, temos vértices de decisão, na qual uma seta chega e duas saem. Ao longo desse trajeto, a porcentagem de dados que seguem aqueles parâmetros tende a diminuir até o suficiente para a previsão probabilística. Esse vértice final é chamado de vértice folha, na qual uma seta chega e nenhuma sai, e apresenta um valor de previsão final.

## Resultados

Ao final do projeto, obtivemos com sucesso os 4 modelos almejados inicialmente, realizamos as métricas para avaliar o desempenho destes, e conseguimos valores não muito satisfatórios, próximos a 34 mg/L, considerando a magnitude dos dados, que estão em um intervalo entre cerca de 73 e 317. Além disso, pelos resultados dos gráficos, há bastante divergência entre os valores previstos e os valores de teste conhecidos.

## Acesso ao projeto

O caderno com os códigos em Python estão presentes nesta documentação, e contém toda a descrição dos processos desenvolvidos e de como funcionam os modelos e as métricas. O link para o download do dataset está disponível [aqui](https://www.kaggle.com/datasets/adityakadiwal/water-potability/data)

## Agradecimentos

Nossos agradecimentos se estendem ao nosso professor e orientador Doutor Daniel Roberto Cassar, responsável por nos ensinar de maneira clara os métodos e modelos aqui utilizados, além de disponibilizar material de aula para nos basearmos ao longo do desenvolvimento do trabalho.

## Desenvolvedores
[<img src="https://avatars.githubusercontent.com/u/172425313?v=4" width=115>](https://github.com/GabrielMartinsSousa) <img src="https://github.com/user-attachments/assets/28fd049c-d60b-4c86-b7b6-2d794dea3fdf" alt="Texto Alternativo" width="115">

*Gabriel Martins Sousa* como *Haryell Marino*

[<img src="https://avatars.githubusercontent.com/u/172424981?v=4" width=115>](https://github.com/ClaraLelis) <img src="https://github.com/user-attachments/assets/6cc61d25-b6fb-4cd1-a724-26d55bab1fac" alt="Texto Alternativo" width="115">

*Maria Clara Macedo Lelis* como *Olive Solace*

[<img src="https://avatars.githubusercontent.com/u/171518829?v=4" width=115>](https://github.com/yasminbshimizu) <img src="https://github.com/user-attachments/assets/f79e5706-9497-4185-b489-2972365729d0" alt="Texto Alternativo" width="115">

*Yasmin Barbosa Shimizu* como *Ebony Vitrum*
