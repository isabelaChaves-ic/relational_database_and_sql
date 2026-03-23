# Sprint 2

Modelagem de Dados Relacional e Dimencional com Linguagem SQL.

# Exercícios

Linguagem SQL - Exercícios - Casos de Estudo

1. 
[Resposta Ex1.](exercicios/ex1.txt)

2.
[Resposta Ex2.](exercicios/ex2.txt)

3.
[Resposta Ex3.](exercicios/ex3.txt)

4.
[Resposta Ex4.](exercicios/ex4.txt)

5.
[Resposta Ex5.](exercicios/ex5.txt)

6.
[Resposta Ex6.](exercicios/ex6.txt)

7.
[Resposta Ex7.](exercicios/ex7.txt)

8.
[Resposta Ex8.](exercicios/ex8.txt)

9.
[Resposta Ex9.](exercicios/ex9.txt)

10.
[Resposta Ex10.](exercicios/ex10.txt)

11.
[Resposta Ex11.](exercicios/ex11.txt)

12.
[Resposta Ex12.](exercicios/ex12.txt)

13.
[Resposta Ex13.](exercicios/ex13.txt)

14.
[Resposta Ex14.](exercicios/ex14.txt)

15.
[Resposta Ex15.](exercicios/ex15.txt)

16.
[Resposta Ex16.](exercicios/ex16.txt)

#### Exercício de esxportação de dados

1. Arquivo CSV
[Etapa I](exercicios/exercicio2_expotacao_de_dados/Etapa1.csv)

    1. Query 
[Etapa I](exercicios/exercicio2_expotacao_de_dados/query_etapa1.txt)

2. Arquivo CSV
[Etapa II](exercicios/exercicio2_expotacao_de_dados/Etapa2.csv)

    2. Query 
[Etapa II](exercicios/exercicio2_expotacao_de_dados/query_etapa2.txt)





# Evidências

Ao descompactar o arquivo `concessionaria.zip` e abrir o arquivo `.sqlite` na ferramenta *DBeaver* pude ter acesso ao banco de dados que necessitava ser normalizado.

![Evidencia 1](evidencias/sample1.png)


Executando a query **SELECT * FROM tb_locacao LIMIT 15;** verifiquei que a formatação dos atibutos que possuem tipo: *DATE* e *TIME* não estava de acordo com sua formatação. 

![Evidencia 2](evidencias/sample2.png)

Visto isso, na query abaixo é possível ver que utilizei a função **SUBSTR** para poder deixar as datas na formatação correta. Enquanto que para a hora apenas acrescentei os segundos com concatenação.

![Evidencia 3](evidencias/sample3.png)

Para a inserção dos dados nas tabelas, eu simplesmente fazia o uso do **SELECT DISTINCT** com os campos específicos para não vir dados duplicados, então exportava esses dados para SQL, então copiava e colava no *DBeaver*.

![Evidencia 4](evidencias/sample4.png)

Abaixo, os dados inseridos na tabela com a formatação adequada.

![Evidencia 5](evidencias/sample5.png)

Na query **VIEW** dim_vendedor, fiz uma estrutura condicional simples, apenas para que em sexoVendedor no lugar de 0 e 1, apareça M ou F para deixar mais intuivivo a visualização.

![Evidencia 6](evidencias/sample6.png)

O banco de dados `tb_locacao` normalizado ficou da seguinte maneira no modelo relacional. 

![Evidencia 7](evidencias/sample7.png)

Por fim o modelo dimencional na modelagem *star schema*, com a tabela fato ao centro com os atributos numéricos, e as dimesões ao redor contendo os atributos descritivos.

![Evidencia 8](evidencias/sample8.png)



# Certificados

- AWS Partner Sales Accreditation (Business) (Portuguese)
![Curso AWS Partner Sales Accreditation (Business) (Portuguese)](certificados/AWS-Partner-Sales-Accreditation_Business-Portuguese.jpg)




# Aprendizados



