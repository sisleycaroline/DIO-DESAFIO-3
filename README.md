## Desafio - Criando um Dashboard de Vendas do Xbox com Excel
Olá!<br>
Me chamo Sisley e vou detalhar um pouco sobre o terceiro Desafio do Bootcamp da Dio. Foi solicitada a criação de um Dashboard de Vendas do Xbox com Excel, aplicando os conceitos de Excel no desenvolvimento dessa ferramenta. A seguir, detalho como foi feito o passo a passo dessa ferramenta.<br>

## 📌 Objetivo
Aplicar os conceitos de Excel no desenvolvimento de um Dashboard de Vendas do Xbox com Excel.<br>

## 🛠️ Como foi feito

1º Passo:

Definir as perguntas de negócio <br>
Por que isso está sendo feito? Resposta: Simular investimentos em fundos imobiliários. <br>
Quais informações eu preciso para fazer essas simulações? Resposta: Taxa de Rendimento Mensal, Por quantos Anos/Meses, Quanto investir por mês, Tipos de FII existentes.<br>
Quais informações terei como resultado dessas simulações? Resposta: Patrimônio acumulado no tempo estimado e Dividendos mensais.<br>
Quais perfis possíveis para esse investidor? Resposta: Moderado, Agressivo<br>
Além dessas informações, quais outras são necessárias para a ferramenta? Resposta: Salário, Sugestão de investimento (% com base no salário)<br>
É necessário uma demonstração gráfica? Resposta: Sim <br>
É necessário calcular Cenários? Resposta: Não é algo extremamente necessário, mas um detalhe a mais para que o usuário possa fazer projeções futuras de forma rápida e prática.<br>

2º Passo:<br>

Após definir perguntas de negócio, criar um fluxograma lógico para dar andamento no projeto.<br>

3º Passo:<br>

Segui o método utilizado por Felipão em aula, o método ABCDE.<br>

A - Assets (recursos: imagens, vídeos, gifs, paletas cores)<br>
B - Bases (dados para gerar a dashboard principal ou outras medidas)<br>
C - Cálculos (meio de campo que processa dados para transformar em informações)<br>
D - Dashboard (Painel visual)<br>
E - Extras<br>

Separei cada Planilha para a letra correspondente. <br>

1. Assets<br>

Imagens: Logos do Xbox <br>
Vídeos: N/A <br>
Gifs: N/A <br>
Cores: como se trata do Xbox, paleta de tons em verde. <br>
Tons: #107C10  (verde principal), #2E9B2E  (verde médio), #FFFFFF  (branco), #A6A6A6  (cinza) <br>

Estética: Oculta planilhas que servem como base de assets. <br>

2. Bases <br>

Nossos dados, nossa base pro dashboard ser realizado. <br>

Selecionar todo o conjunto de dados e criar uma tabela dinâmica. <br>

3. Cálculos  <br>

Onde processamos os dados. <br>
Perguntas de negócio respondidas através de análise de dados. <br>
Uso de tabelas dinâmicas, gráficos dinâmicos e filtros visuais para facilitar. <br>

Quais são minhas perguntas de negócio?<br>
  - Qual faturamento Total de vendas de planos anuais (contendo todas as assinaturas agregadas? <br>
  - Qual faturamento toal de vendas de planos anuais, separado por auto renovação e não é por auto renovação <br>
  - Total de vendas de assinaturas do EA Play <br>

4.  Dashboard <br>

Onde visualizamos o resultado do processamento dos dados <br>

5.  Extras <br>
Não foi necessário o uso dessa planilha. <br>

4º Passo: <br>

Definir quais informações aparecerão no dashboard <br>
- Icon do Perfil <br>
- Logo xbox <br>
- Logo EA play <br>
- Logo Minecraft <br>
- Gráficos e big numbers que respondam as perguntas de negócio <br>
- Segmentação de Dados (filtro visual e interativo que se conecta a Tabela Dinâmica e permite filtrar os dados com cliques)


5º Passo:<br>
Montar Layout da Tabela no Excel<br>
- Tentei fazer com que meu layout lembrasse a página de um site e que as cores fossem semelhantes a cor da logo do xbox. Inclui as logos do Xbox, EA Play e Minecraft. Utilizei de formas retangulares para ilustrar os big numbers. <br>
- Na planilha de Cálculos, gerei três tabelas dinâmicas para obter as seguintes informações: ,
- Conexões de Relatório na aba "Segmentação": deixei selecionada as 3 tabelas geradas
- Gerei um gráfico dinâmico e copiei para a Planilha Dashboard. Eliminei o excesso de informações, fazendo uma “limpeza” visual e deixando apenas o necessário. <br>




Aplicar fórmulas e ferramentas. Testar seus resultados<br>
Unanimidade visual, ou seja, deixar sua ferramenta visualmente coerente e agradável (transmite confiança no trabalho).<br>
Foi utilizada a Tabela dinâmica para geração de gráficos e filtros. <br>

6º Finalização <br>
Aplicar ajustes finos para que a ferramenta fique 100%.

## 🤖 Ferramentas utilizadas
- Github<br>
- Excel<br>
- Chat GPT<br>

## 📚 Aprendizados
Primeiramente: não conhecia muito sobre fundos de investimentos e através desse desse desafio pude conhecer e entender como funciona. Além disso, não tinha conhecimento sobre fundos imobiliários e seus tipos, já foi um incremento em meu conhecimento. Foi bem interessante explorar um pouco mais do Excel, ir além do básico e usar diferentes fórmulas e designs.<br>

## Arquivos complementares


