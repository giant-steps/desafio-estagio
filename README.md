# Desafio Estágio
Este repo contém o enunciado do desafio proposto para os candidatos a vaga de estágio em tecnologia da Giant Steps Capital

## Instruções de Entrega
Segue nosso desafio técnico que deve ser entregue em um repositório **privado** no GitHub, autorizar o acesso usuário [@rafalee](https://github.com/rafalee) e enviar um e-mail para a pessoa que entrou em contato para a vaga quando finalizar o desafio com o link para o repositório.
A solução deverá ser implementada utilizando Python e o repositório deverá conter um README contemplando instruções suficientes para execução da solução e execução dos testes automatizados.

## Enunciado
O sistema dos correios de Gotham City tiveram um problema e perderam seu validador de CEPs.
Hoje, sua missão é criar um validador de CEPs baseados em algumas pequenas regras listadas abaixo:
- O CEP é um número maior que 100.000 e menor que 999.999
- O CEP não pode conter nenhum nenhum dígito repetitivo alternado em pares

### Exemplos

#### CEP Inválido
- "012345" # Valor menor que 100.000
- "9999999" # Valor maior que 999.999
- "121426" # 1 é um dígito repetitivo alternado em par.
- "352523" # Os dígitos 2 e 5 são alternados repetitivos em par.

#### CEP Válido
- "523563"
- "123456"
- "997531"

Você deve desenvolver isto utilizando TDD. Damos preferência a soluções utilizando REGEX e string slicing.
