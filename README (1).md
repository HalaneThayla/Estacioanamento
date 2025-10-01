# DIO - Trilha .NET - Fundamentos
## Desafio de projeto

Utilizei os conhecimentos adquiridos no módulo de fundamentos da **trilha .NET da DIO**.

---

## Contexto

Fui contratada como desenvolvedora para construir um sistema de estacionamento que gerencia os veículos estacionados e realiza operações como adicionar, remover (com cálculo do valor cobrado) e listar os veículos.

## Proposta

Desenvolvi uma classe chamada **Estacionamento**, conforme o diagrama abaixo:

**![Diagrama de classe Estacionamento](img/diagrama_classe_estacionamento.png)**

<br>

A classe contém três **propriedades** (variáveis) principais:

* `precoInicial` (decimal): valor cobrado para deixar o veículo estacionado.
* `precoPorHora` (decimal): valor por hora que o veículo permanece estacionado.
* `veiculos` (List<string>): coleção de veículos estacionados, contendo apenas a placa.

<br>

A classe também possui três **métodos** principais:

* **AdicionarVeiculo**: responsável por receber uma placa digitada pelo usuário e armazená-la na lista de veículos.
* **RemoverVeiculo**: verifica se o veículo está estacionado e, caso esteja, solicita a quantidade de horas que permaneceu. Em seguida, realiza o cálculo (`precoInicial + precoPorHora * horas`) e exibe o valor ao usuário.
* **ListarVeiculos**: lista todos os veículos presentes no estacionamento. Caso não haja nenhum, exibe a mensagem "Não há veículos estacionados".

<br>

Por fim, implementei um **menu interativo** no console com as seguintes opções:

* Cadastrar veículo
* Remover veículo
* Listar veículos
* Encerrar

---

## Solução

A solução desenvolvida atendeu ao desafio, aplicando conceitos fundamentais de **Programação Orientada a Objetos**, manipulação de **listas** e **interação com o usuário** no console.