# Avaliador de redações - Desafio Alura - Google

Este projeto pretende usar IA para corrigir redações utilizando o critério de avaliação do ENEM.

# Objetivos
O avaliador de redações poderia ser utilizado em vários cenários como, por exemplo, catalogar redações a serem avaliadas por um professor, priorizando os possíveis desvios. Também poderia ser utilizada por estudantes para praticar.

# Método
O Gemini recebe como parâmetros os critérios públicos de avaliação do ENEM e algumas redações com as respectivas notas atribuidas, para gerar seu próprio critério de avaliação.

# Notas
Alterando o modelo de IA é possível obter resultados diferentes. Alguns modelos avaliaram redações fora dos critérios atribuindo notas, ainda que baixas. Outros entenderam que, por estarem fora de padrão, a nota é zero ou simplesmente disseram não ser possível avaliar.

Por questões de prazo foi enviado o projeto funcional mais simples. Porém foi testado com relativo sucesso a avaliação de redações **digitalizadas**, o que tornaria ainda mais útil.

# Redações de teste

- Receita de bolo
  > Um bolo simples fofinho e quentinho com uma xícara de café pode ser tudo o que você precisa numa tarde chuvosa. E essa aqui é a receita que pode dar isso para você. Essa receita é bem simples e não leva muitos ingredientes. A massa branca pode ser usada com recheios de diferentes sabores e irá combinar com todos, já que não tem nenhum sabor dominante mais forte. Há quem diga que a massa branca é "sem graça", mas se você quiser, pode incrementar o bolo com alguma cobertura de brigadeiro, beijinho, leite condensado para dar mais sabor e deixar o bolo ainda mais molhadinho. Com bastante cuidado e pré-aquecendo o forno antes de colocar ele para assar, você consegue evitar que o bolo sole. Confira como fazer essa receita de bolo simples, também conhecido como bolo de farinha de trigo. Ele cai muito bem com um café quentinho!
- Redação real nota 840
  > Na obra "Utopia", do escritor inglês Thomas More, é retratada uma sociedade perfeita, na qual o corpo social padroniza-se pela a ausência de conflitos e problemas. No entanto, observa-se que na realidade contemporânea é o oposto do que o autor prega, uma vez que os desafios para a valorização de comunidades e povos tradicionais no Brasil apresenta barreiras, as quais dificultam a concretização dos planos de More. Esse cenário antagônico é fruto tanto da negligência governamental, quanto da omissão educacional.
Nesse contexto, depreende-se que a negligência governamental é fator primordial para a manutenção do contratempo. Sob essa ótica, Thomas Hobbes, filósofo inglês, defendia que é dever do Estado proporcionar meios que auxiliem o progresso de toda a coletividade. Tal concepção, todavia, não está ligada à conjuntura hodierna, visto que as autoridades governamentais não medem esforços para criar ações que resolveriam a valorização de sociedade e indivíduos tradicionais brasileiros, como, campanhas de conscientização visiabilizando a importância dos povos tradicionais, tanto para a inclusão social, quanto para a atividade econômica.
Dessa forma, faz-se mister a reformulação dessa postura estatal de forma urgente. Ademais, a omissão educacional é outra peça chave para o revés. Acerca disso, Paulo Freire em sua obra "Pedagogia do oprimido", afirma que a educação brasileira é bancária, isto é, conteudista. Tal pressuposto, denuncia-se um ensino falho, haja vista que as instituições educacionais não debatem com os estudantes sobre os desafios da valorização dos povos tradicionais, como, por exemplo o direito à educação eficiente. Tudo isso retarda a resolução do empecilho, já que a precariedade da educação persiste nesse quadro deletério.
Portanto, medidas são necessárias para combater o problema na sociedade brasileira. Cabe o Governo Federal - órgão responsável pelos direitos básicos dos cidadãos - promover campanhas publicitárias na mídia e nas escolas, com o intuito de valorizar esses povos e promover a garantia de acesso à cidadania. Dessarte, com bases nessas medidas, a realidade da obra Utopia será concretizada na sociedade brasileira.
