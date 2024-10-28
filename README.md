#  Projeto Final Machine Learning - Discípulos de Hemera ☀️

<img src="https://github.com/user-attachments/assets/1607eb2b-f452-4ea1-af3b-0c96546e17fd">

*"Faça-se Luz!"*

Neste repositório, iremos adicionar os códigos produzidos pelo grupo *Discípulos de Hemera* na disciplina de Aprendizado de Máquina da faculade Ilum - Escola de Ciência (CNPEM), ministrada pelo professor doutor Daniel Roberto Cassar. Os códigos desse repositório foram desenvolvidos utilizando a linguagem de programação Python no Jupyter Notebook. A linguagem HTML também foi utilizada na elaboração deste READ-ME

# !["Badge Ilum"](https://img.shields.io/badge/Ilum%20-%20purple) !["Badge License"](https://img.shields.io/badge/License%20-%20MIT%20-%20green) !["Badge Status"](https://img.shields.io/badge/Status-Em_constru%C3%A7%C3%A3o-yellow) !["Badge Reino"](https://img.shields.io/badge/Reino-Lumi-red) !["Badge Continente"](https://img.shields.io/badge/Continente-Senepem-blue) !["Badge Guilda"](https://img.shields.io/badge/Guilda-Discípulos_de_Hemera-white)

<p align="center">
  ✨ Introdução -
  🧭 Quests -
  :dragon: A batalha contra o dragão
</p>

# ✨ Introdução:
Nesta disciplina aprendemos teoria, conceitos e os principais modelos de Aprendizado de Máquina de forma gamificada, incluindo histórias personalizadas e personagens em estilo RPG. Cada grupo faz parte de uma guilda, a qual é composta por cavaleiros, magos e escudeiros, e o nosso objetivo é cumprir atividades semanais (quests) a fim de ajudar o Reino de Lumi, um mundo fictício, além de realizar um projeto final (A Batalha contra o Dragão).

Nossa guilda é formada pela guerreira Mantis Pennata, pelo mago Zeriel Héosforo e pelo escudeiro Rhaegar Kamoris. A história e representação destes personagens pode ser encontrada <a href="https://discipulosdehemera.vercel.app/"> nesse site</a>

⚔️: **Guerreira - Mantis Pennata**: [Joana Medeiros](https://github.com/JojoMolinetes)

:mage_man: **Mago - Zeriel Héosforo**: [Rômulo Emanuel](https://github.com/Romulo177)

:shield: **Escudeiro - Rhaegar Kamoris**: [Enzo Januzzi](https://github.com/EnzoJanuzzi)

# 🧭 Quests:
Semanalmente, fazemos atividades de aprendizado de máquina sobre temas específicos, impulsionando nossa aprendizagem. Aqui colocaremos todas as quests realizadas, as quais estão anexadas neste repositório, na pasta <a href="Quests"> "Quests"</a>, com seus respectivos enunciados e resoluções. Segue um resumo de cada atividade:

[Quests 1 - Dados 1](Quests/Quests%201%20-%20Dados%201.ipynb) Exploramos os datasets didáticos "Penguins", "Taxis" e "Health EXP", fazendo gráficos e computando estatísticas descritivas

[Quests 1 - Dados 3](Quests/Quests%201%20-%20Dados%203.ipynb) Usamos o dataset 'Flights' para fazer uma conversão simbólico-numérica neste conjunto de dados utilizando o codificador ordinal

[Quests 2 - Modelos 1](Quests/Quests%202%20-%20Modelos%201.ipynb) Alteramos um modelo de regressor linear para classificador linear, com base no material de sala. Além disso, mudamos a métrica da distância para Manhattan e por fim testamos a eficácia do nosso modelo.

[Quests 2 - Modelos 3](Quests/Quests%202%20-%20Modelos%203.ipynb) Mostramos didaticamente como o modelo linear Lasso funciona a e como ele se difere do modelo linear estudado em sala de aula 

[Quests 3 - Modelos 4](Quests/Quests%203%20-%20Modelos%204.ipynb) Ajudamos a Vossa Iluminação a responder 3 das múltiplas hipóteses levantadas pelo Reino de Lumi, usando o dataset deste projeto como base

[Quest 3 - Modelos 6](Quests/Quests%203%20-%20Modelos%206.ipynb) Estudamos o algoritmo Support Vector Machine, induzindo um modelo preditivo nos dados deste projeto

Todos os datasets utilizados estão disponíveis junto à pasta de Quests ou podem ser acessados conforme explicado nos respectivos notebooks.

# 🐉 A Batalha contra o Dragão:
O enunciado do projeto é: "Obtenha um conjunto de dados tabulados de interesse científico com pelo menos 4 atributos, pelo menos 1 target numérico e que tenha pelo menos 50
exemplos. Estes dados não podem ser dados sequenciais (como, por exemplo, séries temporais). O objetivo é utilizar os dados coletados a fim de induzir modelos preditivos através de algoritmos de aprendizado de máquina. Espera-se o uso de boas práticas em ciências de dados. Não é necessário utilizar todas as estratégias e ferramentas apresentados durante a disciplina, mas por se tratar de um projeto de semestre, espera-se que a entrega seja suficientemente completa e detalhada, demonstrando o entendimento e a aplicação prática dos conceitos discutidos ao longo da disciplina. Pode utilizar estratégias e ferramentas não apresentados durante a disciplina caso tenha interesse e faça sentido dentro do escopo do projeto."

Nosso dataset apresenta informações sobre supercondutores, com 81 atributos e 21263 dados. Treinaremos 3 modelos de Machine Learning - Árvore de Decisão, k-NN e Support Vector Machine -, a fim de prever a temperatura crítica ideal desses supercondutores. A comparação entre os modelos utilizados será realizada por meio da métrica da Raiz do Erro Quadrático Médio (RMSE) e tem como intuito entender acerca de como cada modelo se aplica e realiza suas previsões de forma diferente em um mesmo conjunto de dados.

Todos os arquivos podem ser encontrados no repositório <a href="A Batalha contra o Dragão"> "A Batalha contra o Dragão"</a>
O notebook é dividido em 4 partes principais que resultam em uma 5ª parte que revisa e conclui eles a partir do objetivo do trabalho que é a comparação entre modelos, sendo elas:

Introdução: Apresenta e dita o rumo que será seguido, além de uma manipulação e explicação dos dados que serão utilizados para a previsão realizada por cada modelo;

Implementação do modelo da Árvore de Decisão: Utilização de um modelo mais visual para realizar a previsão da temperatura crítica a partir de atributos válidos;  

Implementação do modelo dos k-NN vizinhos: Utilização de um modelo mais simples como o dos k-NN vizinhos para realizar a previsão e entendimento acerca da influência do número de vizinhos e modo de calcular a distância;

Implementação do modelo do Support Vector Regression: Implementação de um modelo mais robusto e que demanda mais tempo derivado do Support Vector Machine para previsão da temperatura crítica buscando valores dentro de uma margem e não um valor exato.

#### REFERÊNCIAS:

[1] CASSAR, Daniel. *ATP-203 1.1 - Tratamento de dados*

[2] CASSAR, Daniel. *ATP-203 2.0 - Tipos de aprendizado de máquina e algoritmo k-NN*

[3] CASSAR, Daniel. *ATP-203 2.1 - Aprendizado de máquina, k-NN e métricas*

[4] CASSAR, Daniel. *ATP-203 3.0 - Modelo linear e baseline*

[5] CASSAR, Daniel. *ATP-203 4.0 - Split de dados de treino e teste*

[6] CASSAR, Daniel. *ATP-203 4.1 - Árvore de decisão*

[7] CASSAR, Daniel. *ATP-203 5.0 - Validação cruzada, busca aleatória e busca em grade*

[8] CASSAR, Daniel. *ATP-203 5.1 - Floresta aleatória*

[9] CASSAR, Daniel. *ATP-203 6.0 - Desempacotando listas e dicionários com operadores estrela*

[10] CASSAR, Daniel. *ATP-203 6.1 - Otimização de hiperparâmetros com optuna*

[11] CASSAR, Daniel. *ATP-203 7.0 - Dados sintéticos e pipeline*

[12] CASSAR, Daniel. *ATP-203 7.1 - Seleção de atributos*

[13] CASSAR, Daniel. *ATP-203 7.0 - Dados sintéticos e pipeline*

[14] CASSAR, Daniel. *ATP-203 8.0 - A matriz de covariância e a matriz de correlação*

[15] CASSAR, Daniel. *ATP-203 8.1 - Redução de dimensionalidade com PCA*

[16] CASSAR, Daniel. *ATP-203 9.0 - Tratamento de exceções*

[17] CASSAR, Daniel. *ATP-203 9.1 - Classificação binária*

[18] CASSAR, Daniel. *ATP-203 10.0 - Outras métricas de classificação*

[19] CASSAR, Daniel. *ATP-203 10.1 - Classificação multiclasse*

[20] Scikit-Learn. *KNeighborsRegressor* Disponível em:
https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html

[21] Scikit-Learn. *DecisionTreeRegressor*. Disponível em: https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html

[22] Scikit-Learn. *Support Vector Regressor*. Disponível em: https://scikit-learn.org/1.5/modules/generated/sklearn.svm.SVR.html

[23] Optuna. *Documentação suporte para o uso do Optuna*. Disponível em: https://optuna.readthedocs.io/en/stable/reference/index.html

[24] Dataset Supercondutores. *Superconductivty Data*. Disponível em: https://archive.ics.uci.edu/dataset/464/superconductivty+data

