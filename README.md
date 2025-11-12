# Trabalho-em-C-Lista-de-Chamada

Aluno: Matheus Lara  
 Professor: Marlon André  
 Curso: Ciência da Computação  
 Instituição: Universidade Positivo  

 O sisitema foi pensado para uma lista de chamada, tendo 5 opções, cadastro, listar e buscar alunos, alem de adicionar novos nomes a  turma.
 abaixo vou elaborar uma pequena apresentação para a aula.

 1. Estrutura
usei uma struct chamada “aluno” com três campos: matrícula, nome e presença.
ela representa cada aluno da turma e foi escolhida porque agrupa diferentes tipos de dados em uma única entidade.

2. Alocação dinâmica
usei malloc para criar a lista inicial de alunos e realloc para aumentar o tamanho da lista quando novos alunos entram.
isso mostra o uso de ponteiros e gerenciamento dinâmico de memória, que é um requisito do trabalho.

3. Funções
dividi o programa em funções: cadastrar, listar, buscar e adicionar.
a função de cadastro e a de adicionar usam passagem por referência, pois precisam alterar o conteúdo da variável original.

4. Busca
implementei a busca sequencial, que percorre toda a lista comparando nomes.
ela é simples e eficiente para listas pequenas como esta.

5. Menu
o programa tem um menu interativo para o usuário escolher as opções.
usei switch case e laço do-while para repetir até o usuário decidir sair.

6. Conclusão
com este trabalho consegui aplicar todos os conceitos pedidos:
struct, funções, ponteiros, passagem por referência, busca e realloc.
o sistema funciona corretamente e está pronto para ser apresentado.
