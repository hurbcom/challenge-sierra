# <img src="https://avatars1.githubusercontent.com/u/7063040?v=4&s=200.jpg" alt="Hurb" width="24" /> Desafio Sierra

[[English](README.md) | [Português](README.pt.md)]

Construa um _smart contract_ para criar uma aplicação descentralizada (_dapp_) para podermos alugar a bicicleta compartilhada do Hurb!

<p align="center">
 <img src="hurb-bike.jpg" alt="Bicicleta do Hurb" />
</p>

O usuário da _dapp_ fictícia vai reservar a bicicleta do Hurb por tempo, a cada 1 hora ele pagará com 42 HRB tokens. Como garantia para alugar a bicicleta o usuário precisará depositar 4 vezes o valor dos tokens necessários para o aluguel em uma nova conta _escrow_.

Quando a bibicleta for entregue o valor do aluguel na conta _escrow_ será transferido para a carteira do Hurb e o valor extra será devolvido para a conta do usuário. Se a bicicleta não for entregue, o valor existente na conta _escrow_ será consumido integralmente.

> Exemplo: 3 horas de reserva necessitará 504 HRBs em depósito. Ao entregar a bicicleta terá 378 HRBs devolvidos em sua conta.

O usuário vai usar ETH para comprar HRB. A cotação atual é de 1 ETH para 6626070 HRB tokens.

A carteira do Hurb é `0x80210180b22ac1762df30Bd0dD6810D3aF8C798a`

## Requisitos

-   Forkar esse desafio e criar o seu projeto (ou workspace) usando a sua versão desse repositório, tão logo _acabe_ o desafio, submeta um _pull request_.
-   Caso você tenha algum motivo para não submeter um _pull request_, crie um repositório privado no Github, faça todo desafio na branch **main** e não se esqueça de preencher o arquivo `pull-request.txt`. Tão logo termine seu desenvolvimento, adicione como colaborador o usuário `automator-hurb` no seu repositório e o deixe disponível por pelo menos 30 dias. **Não adicione o `automator-hurb` antes do término do desenvolvimento.**
-   Caso você tenha algum problema para criar o repositório privado, ao término do desafio preencha o arquivo chamado `pull-request.txt`, comprima a pasta do projeto - incluindo a pasta `.git` - e nos envie por email.
-   Explicar no README como implementar e utilizar o _smart contract_.
-   O _smart contract_ deve funcionar em uma rede Ethereum privada ou na Ropsten.
-   Entregar o código com testes em Solidity ou Javascript

## Critério de avaliação

-   **Organização do código**: Separação de módulos, pastas, etc...
-   **Clareza**: O README explica de forma resumida qual é o problema e como pode rodar a aplicação?
-   **Assertividade**: A aplicação está fazendo o que é esperado? Se tem algo faltando, o README explica o porquê?
-   **Legibilidade do código** (incluindo comentários)
-   **Segurança**: Existe alguma vulnerabilidade clara?
-   **Cobertura de testes** (Não esperamos cobertura completa)
-   **Histórico de commits** (estrutura e qualidade)
-   **Escolhas técnicas**: A escolha dos componentes, padrões, arquitetura, etc, é a melhor escolha para o _smart contract_?

Bônus: Pontos extras para quem criar um processo de transferência da bicicleta alugada para outra pessoa, com o valor extra voltando para a pessoa original.

## Dúvidas

Quaisquer dúvidas que você venha a ter, consulte as [_issues_](https://github.com/HurbCom/challenge-sierra/issues) para ver se alguém já não a fez e caso você não ache sua resposta, abra você mesmo uma nova issue!

Boa sorte e boa viagem! ;)

<p align="center">
 <img src="ca.jpg" alt="Challange accepted" />
</p>
