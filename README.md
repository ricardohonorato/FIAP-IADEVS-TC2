# FIAP-IADEVS-TC2

Equipe: <br> 
João Helton RM364239 <br>
João Almeida Furtado Neto RM364164 <br>
Murilo Polli RM364642 <br>
Rafael Pinheiro RM363960 <br> 
Ricardo Honorato RM364026 <br>


VIDEO Youtube Explicativo: https://youtu.be/4z36mZQ6GOs <br>
  
Arquivos:<br>
  Base de dados Mil registros do MCMV: AMOSTRA_1K_dados_abertos_FGTS_ANALITICO_202505.csv <br>
  Base de dados 100 mil registros do MCMV: AMOSTRA_100K_dados_abertos_FGTS_ANALITICO_202505 (1).csv <br>
  Notebook com mutação de 5%: Equipe_Fiap_Fase_2_AGs_ORIGINAL_MUT5.ipynb <br>
  Notebook com mutação de 10%: Equipe_Fiap_Fase_2_AGs_ORIGINAL_MUT10.ipynb <br>

Problemática:<br>
  Utilizando os dados dos financiamentos do Programa Minha Casa Minha Vida do Governo Federal e associando ao problema da mochila, iremos desenvolver um algoritmo genético para maximizar o uso do subsidio do governo federal, dado que os recursos são finitos e devemos atingir o maior número de famílias possíveis.<br>

  Dado essa problemática, fizemos um estudo que utiliza apenas mil linhas de dados para acharmos uma solução ótima.<br>
  Iniciamos o trabalho com a análise exploratória dos dados, retirando dados duplicados e zerados.
  Além disso, trabalhamos conhecendo mais o dados fazendo diversos agrupamentos e estudos estatisticos, conforme notebooks.
  Dividimos conforme figura abaixo para mutação com 5% e 10%, observamos que há uma diferença nos resultados, no primeiro temos uma convergência mais abrupta, enquanto na segunda imagem temos uma convergência mais atenuada. 

Destacamos que incluímos o mesmo SEED para a função random.

Para Mutações de 5%
<br>
--- Melhor Solução Encontrada --- <br>
Número de Unidades Habitacionais (Benefício) Financiadas: 312 <br>
Número de Contratos Selecionados: 312 <br>
Custo Total do Subsídio: R$ 999,962.75 <br>
Orçamento Total Disponível: R$ 1,000,000.00 <br>
Percentual do Orçamento Utilizado: 100.00% <br>

  <img width="1135" height="544" alt="image" src="https://github.com/user-attachments/assets/c82ef08a-0520-44ec-9481-f35182d0db81" /> <br><br>


Para Mutações de 10%
<br>
--- Melhor Solução Encontrada --- <br>
Número de Unidades Habitacionais (Benefício) Financiadas: 314 <br>
Número de Contratos Selecionados: 314 <br>
Custo Total do Subsídio: R$ 998,762.61 <br>
Orçamento Total Disponível: R$ 1,000,000.00 <br>
Percentual do Orçamento Utilizado: 99.88% <br>


  <img width="1138" height="547" alt="image" src="https://github.com/user-attachments/assets/24c2b96a-e57e-462a-abf6-8f7b7c5ce924" />


Destacamos os trabalhos futuros a serem desenvolvidos:
1) Adicionar uma outra variável para limitação de orçamento global, ficando 2, uma para subsídio e outra para orçamento global. <br>
2) Limitar orçamento por faixa de renda*, faixa de renda 1, 2,3 ou 4. Por exemplo, 60% para a faixa 1, 30% para a faixa 2 e 5% para faixa 3 e  5% para a faixa 4.
3) Em vez de selecionar contratos individuais, o objetivo aqui é encontrar um conjunto de regras ou um perfil de contrato que seja "ideal" segundo múltiplos critérios. Por exemplo: qual perfil de cliente/imóvel oferece o melhor "custo-benefício social"?

*<br>
Faixa 1: famílias com renda de até R$ 2.850 mensais;<br>
Faixa 2: famílias com renda de até R$ 4,7 mil mensais;<br>
Faixa 3: famílias com renda de até R$ 8,6 mil mensais; <br>
Faixa 4: famílias com renda de até R$ 12.000;






