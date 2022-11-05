# algoritmos-aula-03-11

## Exercícios
1. Crie um Programa em HTML o qual:

a) Tenha uma lista de frutas a qual o usuário não vê

b) Tenha na tela um campo na qual o usuário digita o nome de uma fruta e um botão "Pesquisar"

c) Ao clicar nesse botão, o programa busca essa fruta na lista. Se achar, exibe um texto abaixo com uma frase como esta:

A fruta X existe na lista

d) Caso a fruta pesquisada não exista, exiba:

Não existe a fruta X na lista

#ficaadica – para criar um vetor com conteúdo, separe cada elemento com virgula, p.e.    

var vt_alunos = [“Paulo”, “Ana”, “João”];

 


2. Crie um Programa o qual:

a) Tenha um campo "Destino de viagem" e um botão "Adicionar"

b) Ao clicar no botão, esse destino deve ser adicionado em algum lugar o qual o usuário não vê. Não existe problema em serem registrados valores repetidos

c) Deve haver os botões:

  "Primeira viagem" - Ao clicar nele, aparece abaixo o primeiro local cadastrado ou "ainda não viajou", caso nenhuma viagem tenha sido registrada

  "Terceira viagem" - Ao clicar nele, aparece abaixo o 3º local cadastrado ou "ainda fez a 3ª viagem", caso não tenha feito 3 viagens ainda

  "Última viagem" - Ao clicar nele, aparece abaixo o último local cadastrado ou "ainda não viajou", caso nenhuma viagem tenha sido registrada

OBS: Obtenha esses três valores SOMENTE do vetor que criar

 

3. Crie um programa onde o usuário vá cadastrando os bairros para onde já morou. Ele digita o nome do lugar e vai clicar em "Cadastrar bairro".

Deve haver um outro campo, onde ele digita apenas um número, indicando o local para onde morou, a partir do número 1 (porque os usuários comuns contam as coisas a partir do 1) e clica em "Relembrar moradia". Se ele informar 1, exiba o primeiro bairro cadastrado e assim por diante.

Porém, se ele informar um número maior do que a quantidade de bairros, exiba: "Você ainda não morou num Xº bairro!"

 

4. Crie um programa no qual o usuário informa os nomes dos filmes que mais gosta, começando pelo seu favorito e depois o 2º que mais gosta e assim por diante.

Para ir cadastrando cada filme, ele clica em "Cadastrar filme".

Crie um botão "Ver Favoritos". Ao clicar ele, exiba os filmes favoritos, abaixo, uma frase "Total: X".

Abaixo, mostra essas frases:

 O que mais gosta é A

 E desses, o que menos gosta é B

 

Onde A é o primeiro cadastrado e B, o último

 

5. Crie um programa o qual:

a) Usuário vai cadastrando os nomes de seus filmes favoritos. Digita num campo e clica em "Cadastrar"

b) Ele pode cadastrar quantos filmes quiser

c) Na medida que vai cadastrando, deve ser exibido ou atualizado um "painel" como neste exemplo:

  Seu filme favorito: 50 tons de cinza

  Seu 3º filme favorito: A era do gelo 1

  Total de filmes cadastrados: 5

OBS: no "3º filme", caso não tenham sido cadastrados ainda 3 filmes, exibir "Ainda não existe".

OBS: o "filme favorito" é o primeiro cadastrado

 
 
6. Crie um programa no qual o usuário informa os nomes dos filmes que mais gosta. Ele digita e clica em "Cadastrar".
Na medida em que vai cadastrando, os filmes vão aparecendo um abaixo do outro abaixo do botão.

OBS. Tem que usar um vetor para guardar e mostrar os filmes. #ficaadica – Use uma estrutura de repetição (for/while) para mostrar os filmes na página.

 

7. Crie um programa no qual o usuário informa os nomes dos filmes que mais gosta. Ele digita e clica em "Cadastrar".
Na medida em que vai cadastrando, os filmes vão aparecendo um abaixo do outro abaixo do botão. SÓ QUE, aparecem na cor azul, depois vermelho, depois azul, depois vermelho, e assim por diante.

 

8. Crie um programa no qual o usuário vai cadastrando nomes de alunos.

Porém, na medida que vai cadastrando, ele vai aparecendo um abaixo do outro na ordem inversa em que foram cadastrados (ou seja, o último sempre fica no topo, o penúltimo em abaixo dele e assim por diante).

 

9. a) Pergunte para o usuário o nome de cada projeto que já criou na vida. Ele digita e clica em "Registrar projeto". Na medida que ele vai cadastrando, verifique quantos projetos já foram cadastrados e exiba o seguinte texto abaixo:

Você já fez X projetos. Por isso você é um profissional Z

X é a quantidade de projetos e Z é seu nível de experiência, segundo estas regras:

  0 a 4: Júnior

  5 a 12: Pleno desde o projeto "nome do 5º projeto"

    u mais: Sênior desde o projeto "nome do 13º projeto"

b)  Tenha um botão “Mostrar Projetos” que quando clicado mostra os projetos cadastrados, um abaixo do outro, em ordem inversa ao que foi cadastrado.

 

10 (desafio). Crie um programa no qual o usuário vá registrando os nomes das linhas de ônibus que ele pegou durante a semana. Ele digita o nome da linha e clica em "Gravar buzão", Cada vez que o botão é clicado o programa deve mostrar a lista de linhas de ônibus abaixo do botão e em ordem inversa (do último para o primeiro).

Deve haver outro campo onde ele pesquisa por uma linha que já tenha pego. Ao clicar em "Pesquisar", ele deve ver uma dessas frases, abaixo da lista de linhas de ônibus que já pegou:

   Você nunca pegou essa linha (caso não tenha cadastrado ela mesmo)

   OU

   Você já pegou essa linha 4 vezes, nessa ordem: 2, 4, 8, 9

   (supondo que ele cadastrou a mesma linha na 2ª vez, na 4ª vez, na 8ª vez e na 9ª vez)
