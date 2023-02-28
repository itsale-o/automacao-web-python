## Automação de processos - Pesquisa de Preços

#### :notebook: :pencil2: Objetivo:

Construir um projeto de automação web em python, fazeno uso principalmente do selenium para fazer as buscas das informações que precisamos. Faremos a pesquisa e o filtro de alguns produtos pré estabelecidos vindos de uma base de dados (neste caso em excel.xlsx)

#### :computer: Funcionamento:

Aqui estabelecemos uma situação imaginária onde trabalhamos na área de compras de uma empresa e precisamos fazer uma comparação de fornecedores para os nossos produtos. Com essas informações naturalmente buscamos nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes.

Nossos objetivos então são o seguinte: 

- O preço dos produtos que procuramos deve ser abaixo de um preço limite definido previamente. Vamos descobrir os produtos mais baratos e atualizar isso em uma planilha.
- Em seguida, vamos enviar um e-mail com a lista dos produtos abaixo do seu preço máximo de compra.
- No nosso caso, vamos fazer com produtos comuns em sites como Google Shopping.

#### :pencil: Em resumo:

O programa construído deve fazer a leitura da bese de dados, fazer a pesquisa dos produtos contidos nela e filtrá-los de acordo com algumas especificações e a faixa de preço. No fim da sua execução, o programa deve criar uma nova base de dados listando todos os produtos que atendem a todas especificações estabelecidas e enviar um e-mail com as informações obtidas


:exclamation: Observações: 
- Neste projeto, o programa foi desenvolvido considerando a ferramenta de busca google shopping mas pode ser adaptado para qualquer outro site de compras
- A base de dados que foi utilizada na costrução do programa está disponível para a visualização neste repositório
- O e-mail utilizado neste projeto é um e-mail criado exclusivamente para testes de códigos
- O e-mail foi enviado usando o serviço do Google, onde é preciso gerar uma senha de app na área de configuração do gmail. Esta senha foi utilizada como senha do e-mail ao invés da senha do email de fato 
