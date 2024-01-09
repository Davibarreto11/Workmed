# SigIn

## Funcionalidades em si
**RF**

- O usuário deve consegui de cadastrar na aplicação passando nome, email, senha;
- O usuário deve ser direcionado para pagina de SigIn;
- - Mostrar oque está faltando/errado para criação da conta

## Qual lib, qual banco de dados e etc...
**RNF**

- Utilizar Yup para validação de parametros

# Atualização do perfil

## Funcionalidades em si
**RF**

- O usuário deve poder atualizar o seu nome, perfil e senha;

## Qual lib, qual banco de dados e etc...
**RNF**

## Regras de negócio
**RN**

- O usuário não pode alterar seu e-mail para um email já utilizado;
- Para atualizar sua senha, o usuário deve informar a senha antiga;
- Para atualizar a sua senha, o usuário precisa confirmar a nova senha;


# CRUD

**RF**

- O usuário deve poder listar todos os médicos, pacientes, salas e cirurgias;
- O usuário deve poder apagar qualquer médico, paciente, salas e cirurgia;
- O usuário deve poder atualizar qualquer médico, paciente, salas e cirurgia;
- O usuário deve poder registrar qualquer médico, paciente, salas e cirurgia;

**RNF**

- Redux, Saga;

# Dashboard

**RF**

- O usuário deve poder listar o médico com mais cirugias feitas no hospital;
- O usuário deve poder listar o histórico medico mais comum entre os pacientes;
- O usuário deve poder listar as cirurgias feitas no dia;
- O usuário deve poder listar as cirurgias nos ultimos 3 meses;
- O usuário deve poder listar os gastos totais de cirurgias nos ultimos 3 meses;

**RNF**

- Os agendamentos do prestador no dia devem ser armazenados em cache
- As notificações do prestador devem ser armazenadas no MongoDB
- As notificações do prestador devem ser enviadas em tempo-real para que o prestador possa controlar

**TDD**

![image](https://github.com/Davibarreto11/reactypescript/assets/102602408/61a2f4d9-5bd8-4a05-a2d5-ba49fc2545e6)
![image](https://github.com/Davibarreto11/reactypescript/assets/102602408/2c5678cf-0d74-42f4-ba4f-898f7d8b23bf)
