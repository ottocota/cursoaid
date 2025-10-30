# Elaboração de Projeto de Lei para Abertura de Crédito Suplementar

Os projetos de lei para abertura de crédito suplementar são utilizados quando a edição de decreto do Poder Executivo não é suficiente para autorizar a suplementação, exigindo-se, portanto, a aprovação de uma proposta legislativa específica. O primeiro passo consiste na criação de um processo no SEI, que deve ser vinculado ao processo de solicitação do órgão, caso este já exista.

No processo SEI recém criado, serão instruídos seis documentos: Nota Técnica de Projeto de Lei, Exposição de Motivos do Ato Normativo, Memorando, Ofício, Proposição de Lei e Mensagem do Governador.

Este site elenca uma serie de prompts de IA para a criação desses documentos. A inteligência artificial a ser utilizada é o [Deepseek](https://chat.deepseek.com/) com a funcionalidade DeepThink ativada

## Criação do processo SEI

Criar um processo do tipo "Execuções Física e Orçamentária: Processo de Alteração Orçamentária".

Colocar como restrito com a hipótese legal de documento preparatório.

## Estabelecimento de Parâmetros

Essa etapa serve para introduzir parâmetros que serão utilizados na documentação. 

É necessário preencher o seguinte [formulário](https://cecad365.sharepoint.com/:w:/s/Splor/EdZiXcr0I45JnksfdWVNw-kBAx3d5oH4UYmiX98RmW6FFg?e=aafEv6) e inseri-lo na IA com o seguinte prompt:

> Armazene os seguintes parâmetros.

## Nota Técnica de Projeto de Lei

Para elaborar a nota técnica, é necessário ter as informações das suplementações e, se houver, das anulações organizadas em uma tabela neste [formato](https://cecad365.sharepoint.com/:x:/s/Splor/EUryIbXcfhFJnHe3Osyafo8BccE5pNKeXWR7nSd6wWgb5Q?e=zhcpdl). Normalmente, essas informações são enviadas pelo órgão que fez a solicitação.

A nota técnica é feita em duas partes: o texto e os comentários da tabela.

### Texto

Para elaborar o texto da nota técnica, insira este [arquivo](https://cecad365.sharepoint.com/:w:/s/Splor/EfFr3Srd6JZJoCpvpAQJmaQBEc44fzQCvu5HptjaIt0mTA?e=ToWNWQ) com o seguinte prompt:

>Substitua os xx pelos textos armazenados correspondentes e não altere o restante do texto.

### Descrições das Tabelas
As descrições das tabelas devem ser inseridas na parte assinalada como xxCOMENTÁRIOS DAS TABELASxx. Deve ser feita uma tabela por unidade orçamentária. As informações para o preenchimento são enviadas pelos órgãos. A tabela deve ter o seguinte formato: [Tabela Exemplo](https://cecad365.sharepoint.com/:x:/s/Splor/EUryIbXcfhFJnHe3Osyafo8BccE5pNKeXWR7nSd6wWgb5Q?e=zhcpdl).

Após preencher a tabela, insira-a na IA e utilize o seguinte prompt:

>Preciso que você escreva uma frase com esta estrutura, substitua xx pelas informações da tabela: "O crédito suplementar ao orçamento da unidade orçamentária xxUnidade Orçamentáriaxx no valor total de R$xxTotal da Suplementaçãoxx (número em extenso) é composto por:"

>Desconsidere todo seu conhecimento em orçamento brasileiro. Utilize apenas as orientações enviadas. Interprete vazio como 0.

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
|24|Convênios com a União e suas Entidades - Exceto Emendas Individuais e de Bancada|
|42|Contribuição Patronal para o RPPS|
|43|Contribuição do Servidor para o RPPS|
|59|Outros Recursos Vinculados|
|60|Recursos Diretamente Arrecadados|

>O valor, se a origem de crédito for realocação, deve corresponder ao valor da anulação. Se a origem de crédito for outra, deve corresponder ao valor da suplementação. 

>As linhas de realocação que apresentarem grupo e fonte iguais devem, obrigatoriamente, ser somadas. Para as outras origens de crédito, some todas as linhas com fontes iguais.

>Oculte as linhas com valor R$0,00

>Segue um exemplo de como deve ser feito: “Anulação de dotação orçamentária de Outras Despesas Correntes, da fonte Recursos Ordinários - Recursos não Vinculados de Impostos no valor de R$20.000.000,00 (vinte milhões de reais)”. Agora, faça conforme o exemplo e os parâmetros informados.

##Exposição de Motivos
Para elaborar o texto da exposição de motivos, basta inserir este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B06B96B58-3471-48F1-A916-8B10D5F0CA9B%7D&file=Modelo%20-%20Exposi%C3%A7%C3%A3o%20de%20Motivos.docx&action=default&mobileredirect=true) e o seguinte prompt na IA:

>Substitua os xx pelos textos armazenados correspondentes e não altere o restante do texto.

>Para o item 6.2, preencha com os dados das tabelas anteriores, descreva o grupo quando for tratar da realocação. 

>Utilize este formato como referência: O crédito suplementar ao orçamento do TCEMG no valor total de R$182.757.788,00 (cento e oitenta e dois milhões, setecentos e cinquenta e sete mil, setecentos e oitenta e oito reais) atenderá despesas de (preencher com os grupos que serão suplementados. Ex: Pessoal e encargos sociais, inversões financeiras e etc.), tendo como origem a anulação de dotações orçamentárias próprias de custeio e investimento, no valor de R$44.779.514,00; o saldo financeiro da receita de Recursos Diretamente Arrecadados no valor de R$95.000.000,00; o excesso de arrecadação da receita de Contribuição Patronal para o RPPS, no valor de R$18.817.178,00; e o excesso de arrecadação da receita de Contribuição do Servidor para o RPPS, no valor de R$24.161.096,00.


##Memorando

O memorando deve ser destinado para o Assessor-Chefe da Assessoria Jurídico-Administrativa (AJA/SEPLAG). Essa informação pode ser obtida no site da Seplag. 

Para elaborar o texto do memorando, insira este [arquivo](https://cecad365.sharepoint.com/:w:/s/Splor/EXKTJei8YJtCqKT3KDuXywQBJZz4a5Xp2333JYHd9nGvzA?e=ef9uR4) com o seguinte prompt na IA:

>Substitua os xx pelos textos armazenados correspondentes e não altere o restante do texto.

##Ofício

Para elaborar o texto do ofício, insira este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B5EE5B907-5BC7-40CA-82F2-EF628ECD215D%7D&file=Modelo%20-%20Of%C3%ADcio.docx&action=default&mobileredirect=true) com o seguinte prompt na IA:

>Substitua os xx pelos textos armazenados correspondentes e não altere o restante do texto.

##Projeto de Lei

Para elaborar o projeto de lei, insira este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B5DD92CA2-5D7F-4BB8-AAFD-9135C459135E%7D&file=Modelo%20de%20Projeto%20de%20lei.docx&action=default&mobileredirect=true) com o seguinte prompt na IA:

>Preciso que você estruture os dados da(s) tabela(s) em um projeto de lei similar a este:

##Mensagem do Governador

Para elaborar o projeto de lei, insira este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B2F148E45-347E-4452-B9C3-A6DE74BA6CB5%7D&file=Modelo%20de%20Mensagem%20do%20Governador.docx&action=default&mobileredirect=true) com o seguinte prompt na IA:

>Altere este documento modelo com base nas informações anteriores. Não mude nada que não estiver entre xx e trate cada órgão como independente

#A FAZERES

Colocar mais fontes?

Fazer testes