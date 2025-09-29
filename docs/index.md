# Elaboração de Projeto de Lei de Abertura de Crédito Suplementar

Os projetos de lei de abertura de crédito suplementar são utilizados quando a edição de decreto do Poder Executivo não é suficiente para autorizar a suplementação, exigindo-se, portanto, a aprovação de uma proposta legislativa específica. O primeiro passo consiste na criação de um processo no SEI, que deve ser vinculado ao processo de solicitação do órgão, caso este já exista. Esse processo será instruído com seis documentos: Nota Técnica de Projeto de Lei, Exposição de Motivos do Ato Normativo, Memorando, Ofício, Proposição de Lei e Mensagem do Governador.

A inteligência artificial a ser utilizada é o Deepseek com a funcionalidade Deepthink ativada

## Criar um processo 

Criar um processo do tipo "Execuções Física e Orçamentária: Processo de Alteração Orçamentária"

Colocar como restrito com a hipótese legal de documento preparatório


## Estabelecimento de Parâmetros

Essa etapa serve para introduzir parâmetros que serão utilizados na documentação. 

Você preencher o seguinte [formulário](https://cecad365.sharepoint.com/:w:/s/Splor/EdZiXcr0I45JnksfdWVNw-kBAx3d5oH4UYmiX98RmW6FFg?e=aafEv6)

## Nota Técnica de Projeto de Lei

Para montar a nota técnica, você precisa ter os dados das suplementações e, se houver, das anulações organizados em uma tabela nesse [formato](https://cecad365.sharepoint.com/:x:/s/Splor/EasrCiDLgcJCrfFLfBL-UUcBOZYDMV6W9tmgGHiCUtEDbQ?e=lPlRxh). Normalmente, essas informações são enviadas pelo órgão que fez a solicitação.

A nota técnica é feita em duas partes: o texto e os comentários da tabela.

### Texto

Para elaborar o texto da nota técnica, insira este [arquivo](https://cecad365.sharepoint.com/:w:/s/Splor/EfFr3Srd6JZJoCpvpAQJmaQBEc44fzQCvu5HptjaIt0mTA?e=ToWNWQ) com o seguinte prompt:

Substitua os xx pelos textos armazenados correspondentes:

### Comentários das Tabelas
Os comentários das tabelas serão inseridos na parte assinalada como xxCOMENTÁRIOS DAS TABELASxx. Deve ser feito um quadro por unidade orçamentária. As informações para o preenchimento do quadro são enviadas pelos órgãos. O quadro deve ter o seguinte formato: [Quadro Exemplo](https://cecad365.sharepoint.com/:x:/s/Splor/EUryIbXcfhFJnHe3Osyafo8BccE5pNKeXWR7nSd6wWgb5Q?e=zhcpdl).

Após preencher a tabela, insira-a na IA e utilize o seguinte prompt:

>Preciso que você escreva uma frase com esta estrutura, substitua xx pelas informações da tabela: "O crédito suplementar ao orçamento da UO xxUnidade Orçamentáriaxx no valor total de R$xxTotal da Suplementaçãoxx (número em extenso) é composto por:"

>Depois, descrever a composição das suplementações. Vou citar os textos a serem preenchidos, mas, por enquanto, quero apenas que você compreenda o padrão. A descrição das origens de crédito de realocação deve ser feita da seguinte forma: (origem do crédito) de (grupo), da fonte (informação da fonte), no valor de (valor em numeral, em reais) [(valor por extenso, em reais)]. Para outras origens, use o padrão (origem de crédito) de (fonte), no valor de (valor em numeral, em reais)[(valor por extenso, em reais)]. Não execute ainda; aguarde os inputs.
Vou citar os textos da origem de crédito. Espere outras informações:

| Origem de Crédito    | Texto |
|--------------|------------|
|Realocação|Anulação de dotação orçamentária|
|Saldo financeiro de exercícios anteriores|Saldo financeiro da receita|
|Excesso de arrecadação|Excesso de arrecadação da receita|

>O grupo é o segundo número da coluna natureza. Espere outras informações:

| Grupo    | Texto |
|--------------|------------|
|1|Pessoal e Encargos Sociais|
|2|Juros e Encargos da Dívida|
|3|Outras Despesas Correntes|
|4|Investimentos|
|5|Inversões Financeiras|
|6|Amortização da Dívida|

>A fonte corresponde aos dois primeiros dígitos da coluna Fonte/IPU. Espere outras informações:

| Fonte    | Texto |
|--------------|------------|
|10|Recursos Ordinários - Recursos não Vinculados de Impostos|
|42|Contribuição Patronal para o RPPS|
|43|Contribuição do Servidor para o RPPS|
|60|Recursos Diretamente Arrecadados|

>O valor, se a origem de crédito for realocação, deve corresponder ao valor da anulação. Se a origem de crédito for outra, deve corresponder ao valor da suplementação. Linhas que apresentarem origem de crédito, grupo e fonte iguais devem, obrigatoriamente, ser somadas. Aguarde outras informações antes de executar.

>Segue um exemplo sobre como deve ser feito: “Anulação de dotação orçamentária de Outras Despesas Correntes, da fonte Recursos Ordinários - Recursos não Vinculados de Impostos no valor de R$20.000.000,00 (vinte milhões de reais)”. Agora, faça conforme o exemplo e os parâmetros informados:

##Exposição de Motivos
Para elaborar o texto da exposição de motivos, basta inserir este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B06B96B58-3471-48F1-A916-8B10D5F0CA9B%7D&file=Modelo%20-%20Exposi%C3%A7%C3%A3o%20de%20Motivos.docx&action=default&mobileredirect=true) e o seguinte prompt na IA:

Substitua os xx pelos textos armazenados correspondentes:

##Memorando

O memorando deve ser destinado para o Assessor-Chefe da Assessoria Jurídico-Administrativa (AJA/SEPLAG). Essa informação pode ser obtida no site da Seplag. Para elaborar o texto do memorando, insira este [arquivo](https://cecad365.sharepoint.com/:w:/s/Splor/EXKTJei8YJtCqKT3KDuXywQBJZz4a5Xp2333JYHd9nGvzA?e=ef9uR4) com o seguinte prompt na IA:

##Ofício

Para elaborar o texto do ofício, insira este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B5EE5B907-5BC7-40CA-82F2-EF628ECD215D%7D&file=Modelo%20-%20Of%C3%ADcio.docx&action=default&mobileredirect=true) com o seguinte prompt na IA:

##Projeto de Lei

Agora preciso que você estruture os dados da tabela em um projeto de lei similar a este:

##Mensagem do Governador

Altere este documento modelo com base nas informações anteriores

##Escreva o projeto de lei a partir deste modelo com as informações enviadas.
 (INSERIR LINK DO PL)

#A FAZERES
Mudar o máximo para modelos
Conferir a classificação de capital e custeio
Estruturar o site
Fazer testes
