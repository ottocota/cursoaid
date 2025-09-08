# Elaboração de Projeto de Lei de Abertura de Crédito Suplementar
Os projetos de lei de abertura de crédito suplementar são utilizados quando o decreto do Poder Executivo não é suficiente para autorizar a suplementação, sendo necessária a aprovação de uma proposta legislativa específica.
O primeiro passo é criar um processo e vinculá-lo ao processo de solicitação do órgão, caso este exista.
O processo será composto por 6 documentos: Nota Técnica de Projeto de Lei, Exposição de Motivos de Ato Normativo, Memorando, Ofício, Proposição de Lei e Mensagem do Governador

## Estabelecimento de Parâmetros
Essa etapa serve para introduzir parâmetros que serão utilizados na documentação. Você deve utilizar o seguinte prompt substituindo os textos em negrito conforme descrito em cada item:


>Preciso que você armazene algumas informações que serão substituídas em outros textos posteriormente:

>INICIATIVA: **Preencha como executivo, legislativo ou outro**

>AUTORIA: **Geralmente, é Subsecretaria de Planejamento e Orçamento / SEPLAG**

>ÓRGÃO DE ORIGEM QUE SOLICITOU MANIFESTAÇÃO DA SEPLAG: **Preencher com o órgão solicitante**

>IMPACTO FINANCEIRO PARA O ESTADO: **Preencher com Sim ou Não**

>MANIFESTAÇÃO SEPLAG: **Preencha com favorável, favorável com ressaltas, contrária ou competência não afeta a Seplag, encaminhara para:**

>ÓRGÃOS E SIGLAS: **Preencha com a relação de órgãos, entidades e fundos que são afetados pelo projeto de lei**

>DATA: **Preencha com base no modelo exemplo 13 de janeiro de 2025**

>RESPONSAVEL PELA NOTA TECNICA: **Preencher com nome e cargo deve estar entre (). Geralmente, é o superintendente**

## Nota Técnica de Projeto de Lei

### Texto

Para elaborar o texto da nota técnica, insira este prompt na IA:

>Substitua os xx pelos textos armazenados correspodentes:

>NATUREZA DO PROJETO: Projeto de Lei de abertura de crédito suplementar ao orçamento fiscal do estado.

>EMENTA: Projeto de Lei de abertura de crédito suplementar ao orçamento fiscal do Estado, em favor da(s) unidade(s) orçamentária(s) do xxÓRGÃOS E SIGLASxx.

>INICIATIVA: xxINICIATIVAxx

>AUTORIA: xxAUTORIAxx

>ÓRGÃO DE ORIGEM QUE SOLICITOU MANIFESTAÇÃO DA SEPLAG: xxÓRGÃO DE ORIGEM QUE SOLICITOU MANIFESTAÇÃO DA SEPLAGxx

>IMPACTO FINANCEIRO PARA O ESTADO: xxIMPACTO FINANCEIRO PARA O ESTADOxx

>MANIFESTAÇÃO SEPLAG: xxMANIFESTAÇÃO SEPLAGxx

>PARECER/FUNDAMENTAÇÃO:

>Lei Federal nº 4.320, de 17 de março de 1964, dispõe, em seu art. 42, que “os créditos suplementares e especiais serão autorizados por lei e abertos por decreto do Poder Executivo”. Nesse contexto, a Lei nº 25.124, de 30 de dezembro de 2024 – Lei Orçamentária Anual para o exercício vigente – autoriza a abertura de créditos suplementares aos orçamentos dos Poderes Executivo e Legislativo, mas não abrange a(s) seguinte(s) unidade(s) orçamentária(s): xxÓRGÃOS E SIGLAS:xx. Nesses casos, a abertura de crédito suplementar somente poderá ocorrer mediante proposta legislativa específica. O detalhamento da proposta segue a seguir.

>xxLEGENDAS DOS GRÁFICOSxx

>Uma vez aprovado este Projeto de Lei, serão abertos decretos de crédito suplementar para efetivar as realocações e as suplementações propostas.

>xxDATAxx

>RESPONSÁVEL PELA NOTA TÉCNICA: xxRESPONSÁVEL PELA NOTA TECNICAxx

### Quadro
O Quadro será inserido na parte assinalada como xxLEGENDAS DOS GRÁFICOSxx. Deve ser feito um quadro por unidade orçamentária. As informações para o preenchimento do quadro são enviadas pelos órgãos. O quadro deve ter o seguinte formato: [Quadro Exemplo](https://cecad365.sharepoint.com/:x:/s/Splor/EUryIbXcfhFJnHe3Osyafo8BccE5pNKeXWR7nSd6wWgb5Q?e=zhcpdl).

Após preencher a tabela, insira-a na IA e utilize o seguinte prompt:

>Preciso que você escreva uma frase com esta estrutura, substitua xx pelas informações da tabela: "O crédito suplementar ao orçamento da UO xxUnidade Orçamentáriaxx no valor total de R$xxTotal da Suplementaçãoxx (número em extenso) é composto por:"

>Depois, descrever a composição das suplementações. Vou citar os textos a serem preenchidos, mas, por enquanto, quero apenas que você compreenda o padrão. A descrição das origens de crédito de realocação deve ser feita da seguinte forma: (origem do crédito) de (grupo), da fonte (informação da fonte), no valor de (valor em numeral, em reais) [(valor por extenso, em reais)]. Para outras origens, não é necessário informar o grupo. Não execute ainda; aguarde os inputs.
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

>O valor, se a origem de crédito for realocação, deve corresponder ao valor da anulação. Se a origem de crédito for outra, deve corresponder ao valor da suplementação. Linhas que apresentarem origem de crédito, grupo e fonte iguais devem ser somadas. Aguarde outras informações antes de executar.

>Segue um exemplo sobre como deve ser feito: “Anulação de dotação orçamentária de Outras Despesas Correntes, da fonte Recursos Ordinários - Recursos não Vinculados de Impostos no valor de R$20.000.000,00 (vinte milhões de reais)”. Agora, faça conforme o exemplo e os parâmetros informados:

##Exposição de Motivos
Para elaborar o texto da exposição de motivos, insira este prompt na IA:
>1. IDENTIFICAÇÃO DO ATO NORMATIVO
>1.1 Tipo normativo: Projeto de Lei
>1.2 Ementa: Projeto de Lei de abertura de crédito suplementar ao orçamento fiscal do Estado, em favor da(s) unidade(s) orçamentária(s) do xxÓRGÃOS E SIGLASxx
