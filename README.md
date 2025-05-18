1 - Explicação das funções def do código

1.1 – Dicionários bases do Código: para armazenamento de dados ‘email_senha’ e ‘cardapio’ serão usados como base para criar, respectivamente, cadastro.json e cardapio.json. Esses dicionários podem ser alterados a necessidade do cliente – os logins e cardápio apresentados, são meramente exemplos;
 
1.2 – Criação dos arquivos cadastro.json e cardapio.json;
 
1.3 - Função login() e cadastro(): funções para gerenciamento de pessoas;

1.4 – Função pedido(): Menu para ‘Clientes’ fazerem pedidos;

1.5 – Função gerenciar_pedidos(): Menu para alterar status do pedido ‘visto’ ou ‘não visto’ e ‘entregue’;
 
1.6 – Função adicionar_pratos(): Menu para adicionar novos pratos;
 
1.7 – Funções reindexar_cardapio() e remover_pratos(): estão interligadas, quando um ‘Empregado’ remover um prato qualquer, a função de reindexar irá reorganizar as chaves restantes do cardápio;

1.8 – Função alterar_preços(): Menu para alterar preços com a opção de aplicar um desconto ou mudar o preço.
 
1.9 – Função menu_clientes(): Menu para clientes com a opção de fazer pedidos, a partir da função pedido(), e checar o status do pedido ‘visto’ ou ‘não visto’.
 
1.10 – Função menu_funcionario(): Menu para funcionários com as funções gerenciar_pedidos(), adicionar_pratos(), remover_pratos() e alterar_preços().

1.11 – Checkout: verifica se o cadastro() retornou o user, em caso positivo direciona o user dependendo de sua ‘função’: ‘Cliente’ ou ‘Empregado’ para, respectivamente, o menu_cliente() ou o menu_funcionario().
