# AC_modelagem_logica_de_dados
trabalho de avaliação continuada - engenharia da computação

**2.	Com base no modelo relacional criado na questão anterior, responda o que se pede:**

a.	A tabela Aluguel contém uma chave primária composta de quantos atributos? Analisando isso sob uma perspectiva do negócio, que restrição está sendo aplicada ao aluguel de carros por clientes?
R: 3 atributos na tabela aluguel. O cliente pode alugar 1 ou vários carros, desde de que tenha cpf ou cnpj.

b.	Uma vez o modelo populado com tuplas, é possível identificar carros que nunca foram alugados por nenhum cliente? Explique o raciocínio que você usaria para obter essa informação.
R: Sim.Na tabela, deve-se ocultar as tuplas de carros que foram alugados, ou seja, que já estiveram vinculados a um cpf ou cnpj. 
