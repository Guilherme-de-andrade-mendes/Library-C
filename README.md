//--------------------------------------------------------------------------------------------------------------------------------//

#Funções do projeto:

##Funções Relacionadas a Usuários:

###Incluir Usuário (incluirUsuario):
    Essa função permite adicionar um novo usuário ao sistema.O usuário será solicitado a fornecer todas as informações necessárias, como CPF,nome, data de nascimento, endereço, telefone, e email.
    Após a inclusão bem-sucedida, o número total de usuários é atualizado.

###Imprimir Dados do Usuário (imprimirDadosDoUsuario):
    Esta função imprime os detalhes de todos os usuários registrados no sistema.
    Apresenta informações como CPF, nome, data de nascimento, endereço, telefone,email e profissão.

###Imprimir Usuário Específico (imprimirUsuarioEspecifico):
    Solicita ao usuário que insira o CPF do usuário que deseja visualizar.
    Após fornecer o CPF válido, a função exibe os detalhes específicos desse usuário.

###Alterar Informações do Usuário (alterarInformacoesUsuario):
    Permite ao usuário alterar informações específicas de um usuário existente, comonome, endereço, telefone, email ou profissão.
    O usuário é identificado pelo CPF.

###Excluir Usuário (excluirUsuario):
    Permite excluir um usuário do sistema.
    Solicita o CPF do usuário que se deseja excluir.
    Verifica se o usuário tem empréstimos associados antes de excluir

//--------------------------------------------------------------------------------------------------------------------------------//

##Funções Relacionadas a Livros:

###Incluir Livro (incluirLivro):
    Adiciona um novo livro ao sistema, solicitando informações como ISBN, título,gênero, autores, número de páginas, etc.

###Imprimir Dados do Livro (imprimirDadosDoLivro):
    Exibe detalhes de todos os livros cadastrados, incluindo ISBN, título, gênero,autores, e número de páginas.

###Imprimir Livro Específico (imprimirLivroEspecifico):
    Solicita o ISBN do livro que se deseja visualizar.
    Apresenta os detalhes específicos desse livro.

###Alterar Informações do Livro (alterarInformacoesLivro):
    Permite ao usuário modificar informações específicas de um livro, como título,gênero, autores ou número de páginas.


###Excluir Livro (excluirLivro):
    Remove um livro do sistema, solicitando o ISBN do livro a ser excluído.
    Verifica se o livro possui empréstimos associados antes de excluir.

//--------------------------------------------------------------------------------------------------------------------------------//

##Funções Relacionadas a Empréstimos:

###Incluir Empréstimo (incluirEmprestimo):
    Registra um novo empréstimo, solicitando informações como CPF do usuário, ISBNdo livro, datas de retirada e devolução, e valor diário da multa.

###Imprimir Dados do Empréstimo (imprimirDadosDoEmprestimo):
    Exibe detalhes de todos os empréstimos realizados, incluindo CPF do usuário, ISBNdo livro, datas de retirada e devolução, e multa diária.

###Imprimir Empréstimo Específico (imprimirEmprestimoEspecifico):
    Solicita informações específicas, como CPF do usuário, ISBN do livro e data deretirada, para exibir detalhes de um empréstimo específico.

###Alterar Informações do Empréstimo (alterarInformacoesEmprestimo):
    Permite a alteração de informações de um empréstimo, como a data de devoluçãoou o valor da multa diária.

###Excluir Empréstimo (excluirEmprestimo):
    Remove um empréstimo do sistema, solicitando informações como CPF do usuário,ISBN do livro e data de retirada.

//--------------------------------------------------------------------------------------------------------------------------------//

##Funções Relacionadas a Relatórios:

###Listar por Idade (listarPorIdade):
    Solicita a idade mínima e exibe detalhes dos usuários que atendem ou excedemessa idade.
    
###Listar por Quantidade de Autores (listarPorQuantidadeDeAutores):
    Solicita o número mínimo de autores e exibe detalhes dos livros que têm pelomenos esse número de autores.

###Listar por Intervalo de Empréstimo (listarPorIntervaloDeEmprestimo):
    Solicita um intervalo de datas e exibe os empréstimos que ocorreram nesseintervalo, incluindo detalhes dos usuários, livros e empréstimos.

//--------------------------------------------------------------------------------------------------------------------------------//
