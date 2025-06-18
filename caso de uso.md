#UC1 – Visualizar Pagina Inicial

Objetivo: Permitir que o cliente veja as ofertas e acesse agendamentos.
Atores: Cliente, Visitante

Pré-condições: Acesso ao site

##Fluxo Principal

Sistema mostra opções de compra.
Destaque das promoções.
Exibição dos botões para agendamento (banho e tosa, consulta).

#UC2 – Ver Serviços

Objetivo: Mostrar serviços com descrição e botões de agendamento.
Atores: Cliente, Visitante

##Fluxo Principal:

Sistema lista os serviços (banho e tosa, vacina, brinquedos etc).
Exibe catálogo de produtos relacionados.
Mostra botão para agendar atendimento.

#UC3 – Agendar Atendimento

Objetivo: Permitir que o cliente agende banho, tosa ou consultas.
Atores: Cliente
Pré-condições: Cliente informado no formulário.

##Fluxo Principal:

Cliente preenche nome, telefone, tipo de pet, serviço, data e hora.
Sistema confirma agendamento por e-mail ou WhatsApp.

##Fluxo Alternativo:

Dados inválidos:
Mostrar mensagem de erro.

#UC4 – Fazer Compras Online

Objetivo: Permitir que o cliente compre produtos e realize pagamento.
Atores: Cliente

##Fluxo Principal:

Cliente adiciona produtos ao carrinho.
Informa dados de entrega (CEP, bairro e número).
Escolhe forma de pagamento (Pix, cartão ou boleto).
Finaliza a compra.


#UC5 – Login e Cadastro

Objetivo: Permitir que o cliente se cadastre ou faça login.
Atores: Cliente

##Fluxo Principal:

Sistema exibe formulario de login e cadastro contendo:

Cadastro:
1. Nome
2. Cpf
3. E-mail
4. Senha
5. Endereço
6. Telefone/Celular
7. Tipo de Pet
8. Raça do Pet
9. Idade do Pet
10. Peso do Pet

Login:
1. E-mail
2. Senha
Cliente adiciona dados e confirma.
Sistema redireciona a area do cliente.

#UC6 – Acessar Area do Cliente

Objetivo: Ver pedidos e agendamentos.
Atores: Cliente
Pré-condição: Estar logado.

##Fluxo Principal:

Sistema exibe favoritos, histórico de compras e agendamentos.

#UC7 – Acessar Blog

Objetivo: Permitir leitura de conteudos sobre cuidados.
Atores: Cliente, Visitante

##Fluxo Principal:

Sistema lista postagens com dicas e curiosidades
Cliente seleciona e visualiza conteudo.

#UC8 – Área Administrativa

Objetivo: Gerenciar conteudo e agendamentos.
Atores: Administrador
Pré-condição: Login administrativo

##Fluxo Principal:

Cadastrar, editar ou excluir
Produtos
Serviços
Notícias do blog
Gerenciar agendamentos dos clientes.