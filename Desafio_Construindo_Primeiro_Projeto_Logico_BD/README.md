## Desafio de  Projeto - Construindo seu Primeiro Projeto Lógico de Banco de Dados.
<br>
### Descrição do Desafio
Replique a modelagem do projeto lógico de banco de dados para o cenário de e-commerce. Fique atento as definições de chave primária e estrangeira, assim como as constraints presentes no cenário modelado. Perceba que dentro desta modelagem haverá relacionamentos presentes no modelo EER. Sendo assim, consulte como proceder para estes casos. Além disso, aplique o mapeamento de modelos aos refinamentos propostos no módulo de modelagem conceitual.
<br>
Assim como demonstrado durante o desafio, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas dos que apresentadas durante a explicação do desafio. Sendo assim, crie queries SQL com as cláusulas abaixo:
<br>
* Recuperações simples com SELECT Statement; <br>
* Filtros com WHERE Statement;<br>
* Crie expressões para gerar atributos derivados;<br>
* Defina ordenações dos dados com ORDER BY;<br>
* Condições de filtros aos grupos – HAVING Statement;<br>
* Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados;<br><br>
### Diretrizes
* Não há um mínimo de queries a serem realizadas;<br>
* Os tópicos supracitados devem estar presentes nas queries;<br>
* Elabore perguntas que podem ser respondidas pelas consultas;<br>
* As cláusulas podem estar presentes em mais de uma query;<br>

#### Objetivo:
Aplique o mapeamento para o  cenário:<br>

“Refine o modelo apresentado acrescentando os seguintes pontos”<br><br>

* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;<br>
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento;<br>
* Entrega – Possui status e código de rastreio;<br>
<b> Algumas das perguntas que podes fazer para embasar as queries SQL:</b><br>
<br>
* Quantos pedidos foram feitos por cada cliente?
* Algum vendedor também é fornecedor?
* Relação de produtos fornecedores e estoques;
* Relação de nomes dos fornecedores e nomes dos produtos;