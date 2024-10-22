# Projeto Aluguel de Carros

Este projeto foi desenvolvido para simular a estruturação de um sistema de back-end para o controle de aluguel de veículos. O sistema organiza diferentes tipos de veículos e pessoas, além de gerenciar aluguéis entre eles.

## Estrutura do Projeto

O projeto está dividido em classes organizadas dentro do diretório `Model`:

### Veículos

- **Vehicle.cs**: Classe abstrata base que define as propriedades e comportamentos comuns a todos os veículos.
- **Car.cs**: Classe derivada de `Vehicle` que representa um carro.
- **Truck.cs**: Classe derivada de `Vehicle` que representa um caminhão.
- **Motorcycle.cs**: Classe derivada de `Vehicle` que representa uma moto.

### Pessoas

- **Person.cs**: Classe abstrata base para representar os clientes do sistema.
- **PhysicalPerson.cs**: Classe derivada de `Person` que representa uma pessoa física (CPF).
- **LegalPerson.cs**: Classe derivada de `Person` que representa uma pessoa jurídica (CNPJ).

### Aluguel

- **Rent.cs**: Classe que gerencia o aluguel de um veículo por uma pessoa.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado o seguinte:

- [.NET SDK 6.0 ou superior](https://dotnet.microsoft.com/download)

## Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/arturpeixoto/projeto-aluguel-de-carros.git
```

### 2. Acesse o diretório do projeto

```bash
cd projeto-aluguel-de-carros
```

### 3. Restaure as dependências

Dentro do diretório do projeto, execute o seguinte comando:

```bash
dotnet restore /src
```

## Como usar

Este projeto representa a estruturação de um sistema de aluguel de carros. Não há um arquivo `Program.cs`, pois o foco está em mostrar como o back-end é organizado, com classes que definem veículos, clientes e o processo de aluguel.

## Tecnologias Utilizadas

- C#
- .NET 6

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
