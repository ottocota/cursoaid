# Projeto de Lei para Abertura de Crédito Suplementar

Os projetos de lei para abertura de crédito suplementar são utilizados quando a edição de decreto do Poder Executivo não é suficiente para autorizar a suplementação, exigindo-se, portanto, a aprovação de uma proposta legislativa específica. O primeiro passo consiste na criação de um processo no SEI, que deve ser vinculado ao processo de solicitação do órgão, caso este já exista.

No processo SEI recém criado, serão instruídos seis documentos: Nota Técnica de Projeto de Lei, Exposição de Motivos do Ato Normativo, Memorando, Ofício, Proposição de Lei e Mensagem do Governador.

Este site elenca uma serie de prompts de IA para a criação desses documentos. A inteligência artificial a ser utilizada é o [Copilot](https://m365.cloud.microsoft/chat/?auth=2&home=1) com a funcionalidade GPT-5 ativada.

## Criação do Processo SEI

Criar um processo do tipo "Execuções Física e Orçamentária: Processo de Alteração Orçamentária".

Colocar como restrito com a hipótese legal de documento preparatório.

## Estabelecimento de Parâmetros

Essa etapa serve para introduzir parâmetros que serão utilizados na documentação. Todo trecho da documentação que estiver assinalado entre xx deve ser substituído pelo parâmetro correspondente. Na ausência do parâmetro correspondente, deve ser interpretado e substituído conforme orientação caso a caso.

É necessário preencher o seguinte [formulário](https://cecad365.sharepoint.com/:w:/s/Splor/EdZiXcr0I45JnksfdWVNw-kBAx3d5oH4UYmiX98RmW6FFg?e=aafEv6) e inseri-lo na IA com o seguinte prompt:

> Armazene os seguintes parâmetros. Eles serão utilizados em todos os documentos seguintes:

## Nota Técnica de Projeto de Lei

Para elaborar a nota técnica, é necessário ter as informações das suplementações e, se houver, das anulações organizadas em uma tabela neste [formato](https://cecad365.sharepoint.com/:x:/s/Splor/EUryIbXcfhFJnHe3Osyafo8BccE5pNKeXWR7nSd6wWgb5Q?e=zhcpdl). Normalmente, essas informações são enviadas pelo órgão que fez a solicitação.

A nota técnica é feita em duas partes: o texto e os comentários da tabela.

### Texto

Para elaborar o texto da nota técnica, insira este [arquivo](https://cecad365.sharepoint.com/:w:/s/Splor/EfFr3Srd6JZJoCpvpAQJmaQBEc44fzQCvu5HptjaIt0mTA?e=ToWNWQ) com o seguinte prompt:

>Substitua os xx pelos textos armazenados correspondentes e não altere o restante do texto. Não altere o campo xxCOMENTÁRIOS DAS TABELASxx. Não entregue o resultado como um arquivo.

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

>Substitua os xx pelos textos armazenados nos parâmetros, não altere o restante do texto e não entregue o resultado como um arquivo externo.

>Para o item 6.2, siga esse padrão e faça um parágrafo por unidade orçamentária:

>O crédito suplementar ao orçamento do xxSigla do órgãoxx no valor total de xxValor total da Suplementaçãoxx atenderá despesas de xxGrupos Suplementadosxx, tendo como origem: xxPara as anulações, some todo o valor anulado e escreva da seguinte forma: a anulação de dotações orçamentárias próprias de xxGrupos anuladosxx, no valor de (valor - somar todas anulações) Para as outras origens de crédito, a estrutura é (origem de crédito) de receita de (fonte), no valor de (valor)xx

> Revise para que nenhum grupo seja esquecido na formação dos parágrafos do item 6.2

##Memorando

O memorando deve ser destinado ao Assessor-Chefe da Assessoria Jurídico-Administrativa (AJA/SEPLAG). Essa informação pode ser obtida no site da Seplag. 

Para elaborar o texto do memorando, insira este [arquivo](https://cecad365.sharepoint.com/:w:/s/Splor/EXKTJei8YJtCqKT3KDuXywQBJZz4a5Xp2333JYHd9nGvzA?e=ef9uR4) com o seguinte prompt na IA:

>Substitua os xx pelos textos armazenados correspondentes, não altere o restante do texto e não entregue o resultado como um arquivo externo.

##Ofício

Para elaborar o texto do ofício, insira este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B5EE5B907-5BC7-40CA-82F2-EF628ECD215D%7D&file=Modelo%20-%20Of%C3%ADcio.docx&action=default&mobileredirect=true) com o seguinte prompt na IA:

>Substitua os xx pelos textos armazenados correspondentes, não altere o restante do texto e não entregue o resultado como um arquivo externo.

##Preposição de Lei

Para elaborar o projeto de lei, insira este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B5DD92CA2-5D7F-4BB8-AAFD-9135C459135E%7D&file=Modelo%20de%20Projeto%20de%20lei.docx&action=default&mobileredirect=true) com o seguinte prompt na IA:

>Preciso que você estruture os dados da(s) tabela(s) em um projeto de lei similar a este:
Desconsidere qualquer conhecimento prévio sobre o orçamento brasileiro e siga apenas as orientações fornecidas. Considere valores em branco como zero (0).
O projeto de lei deve conter dois artigos para cada unidade orçamentária:
O primeiro artigo de cada unidade orçamentária apresenta os valores das suplementações, e seus incisos demonstram a divisão por grupo. O caput apresenta o valor global e, depois, a divisão por grupos nos incisos conforme exemplo anexo. Nesse caso, as realocações devem utilizar o valor da suplementação. Para outras origens de crédito, também deve ser usado o valor da suplementação.
O segundo artigo de cada unidade orçamentária descreve a origem dos recursos. No caso das realocações, é o valor da anulação seguido do texto: da anulação de dotação orçamentária de (grupo), de (fonte), no valor de (valor em numeral, em reais) [(valor por extenso, em reais)]. Para outras origens, use o padrão (origem de crédito) de (fonte), no valor de (valor em numeral, em reais) (valor por extenso, em reais).
Os últimos dois artigos são:
Art. x A aplicação desta Lei observará o disposto no art. 169 da Constituição da República e as normas pertinentes da Lei Complementar federal nº 101, de 4 de maio de 2000.
Art. x Esta Lei entra em vigor na data de sua publicação.
Entregue em formato word com a mesma formatação do exemplo.

##Mensagem do Governador

Para elaborar o projeto de lei, insira este [arquivo](https://cecad365.sharepoint.com/:w:/r/sites/Splor/_layouts/15/Doc.aspx?sourcedoc=%7B2F148E45-347E-4452-B9C3-A6DE74BA6CB5%7D&file=Modelo%20de%20Mensagem%20do%20Governador.docx&action=default&mobileredirect=true) com o seguinte prompt na IA:

>Altere este documento modelo com base nas informações anteriores. Não mude nada que não estiver entre xx e trate cada órgão como independente.

##Processos Concluídos

Para uso como referência de formatação, segue uma lista de processos anteriores:

1500.01.0499446/2024-32

1500.01.0309716/2024-75

1500.01.0258741/2025-64

1500.01.0294921/2025-91	