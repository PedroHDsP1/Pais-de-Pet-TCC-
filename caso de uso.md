# UC1 – Visualizar Pagina Inicial

Objetivo: Permitir que o cliente veja as ofertas e acesse agendamentos.

Atores: Cliente, Visitante

Pré-condições: Acesso ao site

## Fluxo Principal

o sistema carrega a index com uma menu para navegar pelo site

o sistema exibe botões para fazer agendamentos(banho, tosa e consulta)

o sistema mostra ícone do carrinho de compras

# UC2 – Ver Serviços

Objetivo: Mostrar serviços com descrição e botões de agendamento.

Atores: Cliente, Visitante

## Fluxo Principal:

O sistema mostra menu de serviços de banho, tosa, vacina e brinquedos

O sistema mostra o serviço escolhido e sua descrição 

O sistema exibe catálogo do serviço escolhido 

O sistema mostra botão de adicionar ao carrinho e botão  de compra/agendamento

# UC3 – Agendar Atendimento

Objetivo: Permitir que o cliente agende banho, tosa ou consultas.
Atores: Cliente

Pré-condições: Cliente ter um login 

## Fluxo Principal:

O sistema mostra um formulário contendo:

1.Nome
2.Telefone
3.Tipo de pet
4.Serviço(Banho, tosa e Consulta podendo fazer multi seleções)
5.Data e hora
com um botão escrito "Confirmar" e retorna para o index

Sistema confirma agendamento por e-mail ou WhatsApp.

# UC4 – Fazer Compras Online

Objetivo: Permitir que o cliente compre produtos e realize pagamento.
Atores: Cliente
Pré-condição: estar logado

## Fluxo Principal:

Sistema mostra o carrinho de compras com itens que foram selecionados 

Sistema mostra as opções de pagamento: pix, cartão de crédito, cartão de débito, boleto

Sistema mostra um campo para por CEP, bairro, número de casa e referência 

# UC5 – Area do Cliente

Objetivo: Permitir que o cliente cadastre/faça login/veja perfil, veja seu histórico de compra e agendamentos e itens desejados

Atores: Cliente

## Fluxo Principal:

Sistema exibe botão para se cadastrar ou logar, abrindo um formulário.

Sistema exibe seus últimos 3 itens desejados e botão para exibir o restante.

Sistema exibe sua última compra e um botão de redirecionamento para o restante das compras.

Sistema mostra calendário do mês atual com seus agendamentos destacados.

# UC6 – Acessar Blog

Objetivo: Permitir leitura de conteudos sobre cuidados.
Atores: Cliente, Visitante

##F luxo Principal:

Sistema mostra postagens com dicas e curiosidades de fontes confiáveis.


# UC7 – Área Administrativa

Objetivo: Gerenciar conteudo e agendamentos.
Atores: Administrador
Pré-condição: Login administrativo

## Fluxo Principal:

Sistema deve permitir Administrador Cadastrar, editar ou excluir:
Produtos
Serviços
Notícias do blog
Gerenciar agendamentos dos clientes.
