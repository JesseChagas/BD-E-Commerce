### Desafio Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE
<p>Digital Innovation One </p>
<p>Instrutora:Juliana Mascarenhas </p>

<h2> Tecnologias </h2>
<br> - [BD_Designer](https://app.dbdesigner.net/) 

<h2>Narrativa - Produto </h2>
Os produtos são vendidos por uma única plataforma online. 
Contudo, estes podem ter vendedores distintos (terceiros).
Cada produto possui um fornecedor.
Um ou mais produtos podem comper um pedido.

<h2>Narrativa - Cliente </h2>
O cliente pode se cadastrar no site com seu CPF ou CNPJ.
O endereço do cliente irá determinar o valor do frete.
Um cliente pode comprar mais de um pedido. 
Este tem um período de carência para devolução do produto.

<h2>Narrativa - Pedido </h2>
Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
Um produto ou mais compoem o pedido.
O pedido pode ser cancelado.

<h2>Narrativa - Fornecedor & Estoque</h2> 
Base: Juliana Mascarenhas
[DBdesigner] (https://app.dbdesigner.net/designer/schema/0-bd_e_commerce1)
[DBdesigner] (https://dbdesigner.page.link/inDzBhmQ9vjWWjpw8)

No BD_E_Commerce1 - Variáveis criadas durante o curso pela professora
![Projeto_Conceitual_By_Juliana_Mascarenhas]()

Fornecedor
ID_Fornecedor
Razao_Social
Terceiro Vendedor
ID_Terceiro_Vendedor
Razao_Social
Local

Estoque
ID_Estoque
Local
Produto
ID_Produto
Categoria
Descricao
Valor

Pedido
ID_Pedido
Descricao_Pedido
Status_Pedido

Cliente
Nome
Identificacao
ID_Cliente
Endereco

Relacao de Produto / Pedido
Quantidade
ID_Produto
ID_Pedido

Disponibilizando um Produto
ID_Fornecedor
ID_Produto
ID_Produto

Produto has Estoque
ID_Produto

=================================================
Realizada a redefinição
![Redefinindo_BD_E_Commerce_By_Jesse Chagas]()

Não foi possível gerar nova URL, pois a gratuidade são válidas até dez tabelas relacionadas.

Variáveis criadas
===========
BD_E_Commerce_Refinado
Fornecedor
ID_Fornecedor
Razao_Social

Terceiro Vendedor
ID_Terceiro_Vendedor
Razao_Social
Local

Estoque
ID_Estoque
Local

Produto
ID_Produto
Categoria
Descricao
Valor
Sub_Categoria
Quantidade_Estoque

Pedido
ID_Pedido
Descricao_Pedido
Status_Pedido
Data_Solicitacao
Data_Cancelamento
Data_Entrega
Valor_Total
Codigo_Envio
Data_Envio

Cliente
Nome_Cliente
CPF_CNPJ_Cliente
ID_Cliente
Endereco
Email
Telefone
Login_Usuario
Senha_Usuario
Status_Login
Forma_Pagamento
Valor_Total_Compra

Relacao de Produto / Pedido
Quantidade
ID_Produto
ID_Pedido

Disponibilizando um Produto
ID_Fornecedor
ID_Produto
ID_Produto

Produto has Estoque
ID_Produto
ID_Estoque

Produtos por Vendedor (Terceiro)
ID_Terceiro_Vendedor
ID_Produto
Quantidade

Forma_Pagamento
ID_Forma_Pagmento
Boleto_Bancario
Cartao_Credito
Cartao_Debito
Pix
Transferencia_Bancaria
Descricao

Endereco
ID_Endereco
UF
Cidade
Bairro
Rua
Complemento
Numero
CEP



Pessoa Juridica
CNPJ
Razao_Social
Nome_Fantasia
Data_Cadastro_PJ

Pessoa Fisica
CPF
Nome
Sobrenome
Data_Nascimento

Forma Envio
ID_Envio
Forma_Envio
Custo_Envio
Endereco
Codigo_Envio

Atenciosamente,

[Linkedin](https://www.linkedin.com/in/mirian-ajiki-molicawa-a770902b/)
