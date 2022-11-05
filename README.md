> ### **_ATIVIDADE_LP2_**
> [Exercício: Pesquisar bibliotecas python. Escolher uma e: Elaborar um texto explicando qual é a biblioteca, para que serve, como deve ser instalada ou se é built-in. Elaborar um exemplo prático funcional usando uma biblioteca selecionada. Criar um repositório com o nome Atividade_LP2 e adicionar o arquivo readme.md. Adicionar o seu módulo, arquivos .py com o exemplo da biblioteca. Atualizar o arquivo readme.md com a descrição da biblioteca, com as funcionalidades criadas e explicar o que foi feito no exemplo prático. ](url)
> 
> _**Apresentação da Biblioteca Atividade_LP2**_
> 
> _**Nesta atividade usaremos como exemplo a biblioteca "Pandas".**_
> 
> **_O que é a biblioteca Pandas afinal?_** Em programação de computadores, pandas é uma biblioteca de software criada para a linguagem Python para manipulação e análise de dados. Em particular, oferece estruturas e operações para tabelas numéricas e séries temporais. É software livre sob licença licença BSD.
> 
> **_Como usar a biblioteca Pandas em phyton?_** A maneira mais fácil de instalar a biblioteca Pandas é usando o pip, o sistema de gerenciamento de pacotes padrão de instalação do Python. Primeiro de tudo, você precisa estar com o Python já instalado na máquina. Depois, você deve ir para o prompt de comando.
> 
> _**Para que serve uma biblioteca pandas?**_ A biblioteca pandas pode ser considerada a mais importante dentro do mundo da análise de dados para o Python. É a ferramenta principal de construção de estrutura, manipulação e limpeza de dados, sendo utilizada com bibliotecas de processamento numérico também e construção de gráficos.

> **_Neste script irei usar como exemplo a biblioteca pandas:_**


### **_

```
[> #Importar o módulo pandas
> 
> import pandas as pd
> 
> #Criar objeto series
> 
> #pd.Series([list_valores], index=[lista_indices], nome='Nome para objeto')
> 
> lista = ['Morango', 'Maça', 'Uva', 'Pêssego', 'Carambola','Lichia']
> 
> #s1 = pd.Series(lista, name = 'Frutas' )
> 
> indices = ['Mo','Ma','U','Pe','C','Li']
> 
> s1 = pd.Series(lista, index = indices, name = 'Frutas' )
> 
> #print(lista)
> 
> print(s1.str.upper( ))
> 
> #print(type(s1))
> 
> #s1[2]
> 
> print('Número de Frutas:', s1.count( ))](url)
```

_** 

