
#Funções Principais
menu:

Exibe o menu principal e retorna a opção escolhida pelo usuário.
depositar:

Recebe como parâmetros o saldo atual, o valor a ser depositado e o extrato.
Verifica se o valor é positivo e, se for, adiciona o valor ao saldo e registra o depósito no extrato.
Retorna o saldo atualizado e o extrato.
sacar:

Recebe os parâmetros saldo, valor, extrato, limite, número de saques e limite de saques.
Verifica várias condições, como se o saldo é suficiente, se o valor do saque excede o limite, e se o número de saques excede o limite permitido.
Atualiza o saldo e o extrato se o saque for bem-sucedido.
Retorna o saldo atualizado e o extrato.
exibir_extrato:

Recebe o saldo e o extrato.
Exibe o extrato de transações e o saldo atual.
criar_usuario:

Recebe a lista de usuários.
Solicita as informações do novo usuário e verifica se o CPF já está cadastrado.
Adiciona o novo usuário à lista de usuários.
filtrar_usuario:

Recebe o CPF e a lista de usuários.
Filtra e retorna o usuário correspondente ao CPF, se existir.
criar_conta:

Recebe a agência, o número da conta e a lista de usuários.
Solicita o CPF do usuário e verifica se o usuário existe.
Cria uma nova conta para o usuário, se ele for encontrado.
listar_contas:

Recebe a lista de contas.
Exibe os detalhes de cada conta cadastrada.
Função Principal (main)
A função main coordena todas as operações:

Define constantes como o limite de saques por dia e a agência padrão.
Inicializa variáveis como saldo, limite, extrato, número de saques, lista de usuários e lista de contas.
Entra em um loop que exibe o menu e executa a operação escolhida pelo usuário.
Permite ao usuário fazer depósitos, saques, consultar o extrato, criar novos usuários, criar novas contas, listar contas e sair do programa.
Fluxo do Programa
O usuário é apresentado com um menu de opções.
Dependendo da opção escolhida, uma das funções é chamada para realizar a operação correspondente.
O programa continua em loop até que o usuário escolha a opção de sair.
Resumo das Operações
Depósito: Adiciona um valor ao saldo e registra no extrato.
Saque: Deduz um valor do saldo (se permitido) e registra no extrato.
Extrato: Exibe todas as transações e o saldo atual.
Nova Conta: Cria uma nova conta vinculada a um usuário existente.
Listar Contas: Exibe todas as contas cadastradas.
Novo Usuário: Cadastra um novo usuário com informações básicas.
Sair: Encerra o programa.
