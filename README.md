
📊 Banco de Dados – Modelagem e Implementação
Este repositório contém o desenvolvimento das duas etapas do trabalho acadêmico de Banco de Dados, englobando modelagem conceitual (MER) e implementação prática com MySQL.

📌 Etapa 1 – Modelagem (MER)
O estudo de caso consiste no projeto de um banco de dados para uma Rede de Hotéis, contemplando:

Entidades

Atributos

Relacionamentos

Cardinalidades

Chaves primárias

Chaves estrangeiras

📍 Regras de Negócio (Resumo)
Funcionário: CPF, nome, telefone, e-mail, login, senha.

Hotel: identificação, nome, categoria, telefone, e-mail, endereço (rua, número, complemento, bairro, CEP, cidade, estado).

Quarto: identificação, número de leitos, tipo (standard, luxo ou suíte), preço da diária, status (disponível, ocupado, manutenção).

Hóspede: CPF, nome, telefone, e-mail, endereço completo.

Reserva: identificação, data de entrada, data de saída, status (ativa, cancelada, concluída).

Pagamento: identificação, forma (cartão, pix ou dinheiro), data, valor total, status (pago ou pendente).

Relacionamentos importantes:

Um hotel possui um ou vários quartos.

Funcionários trabalham em hotéis e realizam reservas.

Hóspedes podem fazer várias reservas.

Reservas geram pagamentos.

📌 Etapa 2 – Implementação (MySQL)
O cenário implementado é de uma Locadora de Veículos, com as seguintes tabelas:

Cliente

Pagamento

Veiculo

Locacao

LocacaoVeiculo

Manutencao

🛠 Tecnologias Utilizadas
MySQL Workbench

SQL (DDL e DML)

Modelo Relacional conforme especificações

📂 Scripts Implementados
Criação do banco de dados e tabelas (CREATE DATABASE, CREATE TABLE)

Definição de chaves primárias e estrangeiras

Restrições NOT NULL

Consultas SQL para:

Listar manutenções realizadas.

Calcular valor total arrecadado.

Contar número de locações por veículo.

Listar clientes com pagamentos pendentes.



👤 Autor
Matheus Jesus Santos da Guarda
RU: 5216319
Curso: Análise e Desenvolvimento de Sistemas – UNINTER

