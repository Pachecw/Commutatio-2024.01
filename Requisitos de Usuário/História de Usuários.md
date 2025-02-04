# 3. Histórias de Usuários

<p align="justify">A <i>Tabela 3</i> a seguir contém as Histórias de Usuários elicitados utizando a técnica de Brainstorm.</p>

| ID   |                                História de Usuário                        | Critério de Aceitação | Prioridade | RF/RNF Relacionado |
| :--: | :-----------------------------------------------------------------------: | :--------: | :---------: | :---------: |
| US01 |Eu, como um usuário, quero poder escolher a moeda de referência e a moeda a ser convertida.| 1. O sistema deve exibir uma lista de moedas disponíveis para seleção.<br/>2. O usuário pode escolher tanto a moeda de referência quanto a moeda convertida.|     Alta     |  US04  |
| US02 |Eu, como um usuário, quero converter um valor em uma moeda para outra.|1. O sistema deve utilizar a taxa de câmbio atualizada para realizar a conversão.<br/>2. A conversão deve ser automática após o usuário inserir o valor e selecionar as moedas.| Alta | |
| US03 |Eu, como um usuário, quero ver o valor convertido.|1. A moeda de destino deve ser informada junto com o valor convertido.<br/> 2. O sistema deve garantir precisão no cálculo com até duas casas decimais.<br/> O sistema deve apresentar o valor convertido de maneira clara e destacada.| Alta | US02 | 
| US04 |Eu, como um usuário, quero poder inserir um valor como moeda de referência.|1. O sistema deve permitir que o usuário insira valores numéricos positivos.<br/>2. O sistema deve validar se o valor está em um formato correto (ex: números decimais).<br/>3. O valor deve ser processado para conversão após a inserção.| Alta | US01|
| US05 |Eu, como um usuário, quero poder ver as cotações atualizadas das moedas de minha escolha|1. O sistema deve buscar as taxas de câmbio das principais moedas em tempo real.|Alta||
| US06 |Eu, como um usuário, quero informações sobre as moedas que escolhi.|1. O sistema deve apresentar ao menos um fato curioso.<br/>2. O conteúdo apresentado deve ser relevante e preciso.|Baixa||


<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>
