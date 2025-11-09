# Avaliacao-Formadora3

Fala: "Olá — vou explicar os models que implementei."
Ação: Mostrar estrutura de pastas Models no VS Code.
LivroModel (20s)
Fala: "LivroModel representa a tabela livro. Contém id, isbn, título, ano, estoque, valor e editora."
Ação: Abrir LivroModel.php, apontar atributos, depois mostrar getters/setters rápidos.
Fala: "toArray() transforma o objeto num array usado pelas views e DAOs."
VendaModel e Item (25s)
Fala: "VendaModel contém id, data, forma de pagamento, referência ao cliente e lista de itens."
Ação: Abrir VendaModel.php, mostrar propriedade itens e método toArray() que inclui itens.
Fala: "ItemLivroVenda liga um livro a uma venda e guarda a quantidade vendida."
Ação: Abrir ItemVendaLivroModel.php e mostrar toArray().
Cliente e subtipos (25s)
Fala: "ClienteModel tem id, endereço e tipo. ClienteFisico e ClienteJuridico estendem Cliente e adicionam nome/cpf ou razãoSocial/cnpj."
Ação: Abrir ClienteModel.php, ClienteFisicoModel.php, ClienteJuridicoModel.php e mostrar getters/setters e toArray().
