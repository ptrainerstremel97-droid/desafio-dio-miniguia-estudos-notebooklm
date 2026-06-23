# Engenharia de Prompts e Cicatrizes

Nesta etapa, foram testadas perguntas no NotebookLM para transformar os PDFs em conhecimento organizado. As "cicatrizes" representam os ajustes feitos nos prompts quando as respostas ficaram vagas, incompletas ou genericas.

## Prompt 1: entendimento geral da bolsa

```text
Com base somente nas fontes enviadas, explique de forma introdutoria como funciona a bolsa de valores, destacando os principais participantes, os tipos de ativos negociados e os riscos para investidores iniciantes.
```

Resposta obtida, em resumo: a bolsa funciona como um ambiente organizado e regulado para negociacao de ativos financeiros. O investidor acessa esse mercado por meio de corretoras, enquanto instituicoes como CVM e B3 ajudam na regulacao, fiscalizacao e infraestrutura das negociacoes.

Referencias principais: Guia CVM Como Funciona a Bolsa.

Cicatriz: quando o prompt nao limitava a resposta as fontes, a IA trazia explicacoes muito genericas. A solucao foi incluir "com base somente nas fontes enviadas".

## Prompt 2: analise fundamentalista

```text
Explique como o metodo de analise de Graham e Buffett pode ser aplicado na avaliacao de acoes brasileiras. Destaque margem de seguranca, valor intrinseco e limitacoes do metodo.
```

Resposta obtida, em resumo: a abordagem de Graham e Buffett busca analisar fundamentos da empresa, qualidade do negocio, preco em relacao ao valor estimado e margem de seguranca. A decisao de investimento nao deve depender de um unico indicador.

Referencias principais: artigo sobre aplicabilidade do metodo de Graham e Buffett.

Cicatriz: a primeira resposta parecia apresentar o metodo como uma formula garantida. O prompt foi ajustado para pedir tambem as limitacoes.

## Prompt 3: dividendos

```text
Compare a estrategia baseada em dividendos com a estrategia baseada em valorizacao da acao. Aponte vantagens, riscos e cuidados para investidores iniciantes.
```

Resposta obtida, em resumo: dividendos podem ser usados como parte de uma estrategia de renda, mas nao devem ser analisados isoladamente. E necessario observar lucro, consistencia, capacidade de pagamento e sustentabilidade da empresa.

Referencias principais: artigo sobre dividendos como estrategia de investimento.

Cicatriz: a IA inicialmente tratou dividendos como sinal automatico de boa empresa. O prompt foi refinado para exigir riscos e cuidados.

## Prompt 4: estrategia long-short

```text
Explique o que e uma estrategia long-short e como a neutralidade em relacao ao Ibovespa pode reduzir ou modificar a exposicao ao risco de mercado.
```

Resposta obtida, em resumo: a estrategia long-short combina posicoes compradas e vendidas para tentar capturar diferencas de desempenho entre ativos. A neutralidade pode reduzir exposicao ao movimento geral do mercado, mas nao elimina todos os riscos.

Referencias principais: artigo sobre estrategia long-short e neutralidade dos fundos brasileiros.

Cicatriz: a palavra "neutralidade" poderia ser interpretada como ausencia total de risco. Foi necessario pedir que a IA diferenciasse reducao de risco e eliminacao de risco.

## Prompt 5: simulacao da dinamica de precos

```text
Use a fonte sobre abordagem multiagente para explicar como simulacoes podem ajudar a entender a formacao de precos na bolsa.
```

Resposta obtida, em resumo: modelos multiagentes permitem representar o mercado como um conjunto de participantes que interagem por meio de decisoes de compra e venda. A formacao de precos surge dessa interacao entre agentes.

Referencias principais: trabalho sobre abordagem multiagente para simulacao da dinamica de precos.

Cicatriz: quando o prompt era amplo demais, a IA falava de inteligencia artificial de forma generica. A melhoria foi citar explicitamente a fonte que deveria orientar a resposta.

## Prompt 6: criacao do miniguia

```text
Crie um miniguia de estudos para iniciantes sobre investimentos em bolsa, usando somente as fontes enviadas. Organize em: resumo, conceitos-chave, riscos, boas praticas, glossario e perguntas de revisao.
```

Resposta obtida, em resumo: o NotebookLM consolidou os temas em uma estrutura de estudo com explicacoes sobre bolsa, analise de acoes, dividendos, long-short, riscos e conceitos principais.

Referencias principais: todas as fontes do caderno.

Cicatriz: pedir o formato da resposta foi essencial para transformar a resposta em material aproveitavel na documentacao final.

