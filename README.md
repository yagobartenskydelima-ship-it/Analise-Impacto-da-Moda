#Comércio Internacional de Roupas Usadas: Dados, Economia Circular e Desafios Ambientais
Resumo do projeto

Este projeto utiliza dados públicos de comércio internacional para investigar como as roupas usadas circulam entre países e quais perguntas essa movimentação levanta para a economia circular e a gestão de resíduos têxteis.

Pergunta central: quais países concentram os maiores volumes registrados no comércio internacional de roupas usadas e o que esses fluxos permitem — e não permitem — concluir sobre os desafios ambientais associados a esse comércio?
1. Problema que a análise busca resolver
Organizações, pesquisadores e formuladores de políticas precisam entender a dimensão e a distribuição geográfica do comércio de roupas usadas para identificar onde vale a pena investigar a reutilização, a reciclagem e a destinação final das peças.

O problema é que os registros comerciais mostram o que foi declarado como importado ou exportado, mas não informam necessariamente o destino final de cada peça. Uma roupa exportada pode ser revendida e reutilizada; outra pode não ter condições de uso e acabar como resíduo. Sem dados adicionais, esses resultados não podem ser tratados como equivalentes.

A contribuição deste projeto é transformar registros dispersos em uma visão comparável por país, ano e fluxo comercial, identificar padrões que merecem atenção e explicitar as lacunas de informação para avaliar impactos ambientais.
2. Perguntas de negócio
1. Quem são os principais exportadores? Quais países registram os maiores pesos exportados em cada ano?
2. Quem são os principais importadores? Quais países registram os maiores pesos importados e como o ranking muda ao longo do tempo?
3. O comércio está crescendo ou diminuindo? Como os volumes declarados evoluem entre os anos disponíveis?
4. Os mesmos países aparecem nos dois fluxos? Quais países têm registros relevantes tanto de importação quanto de exportação?
5. Peso e valor comercial contam a mesma história? O valor declarado por tonelada varia entre países e anos?
6. O que podemos concluir sobre o impacto ambiental? Quais hipóteses podem ser levantadas pelos fluxos comerciais e quais exigem dados de resíduos, reutilização ou reciclagem?
7. Onde é necessário investigar mais? Quais países e períodos merecem prioridade para pesquisa complementar por apresentarem grandes volumes ou lacunas de dados?
3. Fontes de dados
- UN Comtrade: registros de comércio internacional associados ao código HS 6309, referente a artigos usados, incluindo vestuário e outros artigos usados.
- Eurostat: indicador Circular material use rate (taxa de uso circular de materiais), usado como contexto geral de economia circular.
- Agência Europeia do Ambiente (EEA): informações relacionadas às exportações de têxteis usados na União Europeia.
Consulte 02_fontes_dados/ para conferir os arquivos de origem e os períodos cobertos. As fontes têm escopos e métodos diferentes; só devem ser comparadas diretamente quando definições, unidades e períodos forem compatíveis.
4. Principais achados preliminares
A base tratada do UN Comtrade contém registros para 2022 a 2025, mas a cobertura varia conforme o país, o ano e a variável.
- China: nos dados tratados, aparece como principal exportador por peso em 2025, com aproximadamente 1,37 milhão de toneladas registradas. O volume registrado passa de cerca de 603,7 mil toneladas em 2022 para 1,37 milhão em 2025.
- Paquistão: aparece entre os principais importadores nos anos com peso disponível, com aproximadamente 1,08 milhão de toneladas em 2024.
- Lacunas de dados: o peso de importação do Paquistão em 2025 está ausente na base usada. Isso não significa importação zero e impede uma comparação completa desse país nesse ano.
Esses são achados descritivos preliminares e devem ser conferidos nos arquivos originais antes de serem publicados como resultados definitivos. Eles não demonstram, por si só, que as roupas foram descartadas ou que houve determinado nível de poluição.
5. Como os resultados apoiam decisões
Necessidade	Como a análise ajuda	O que ainda falta
Identificar países prioritários para pesquisa	Ranking de importadores e exportadores por peso e ano	Validar cobertura e qualidade dos registros
Monitorar mudanças no comércio	Série anual dos volumes declarados	Mais anos comparáveis e atenção a dados ausentes
Investigar diferenças entre mercados	Comparação entre peso e valor comercial declarado	Verificar moeda, unidade e consistência dos valores
Avaliar possíveis riscos ambientais	Identifica fluxos que podem orientar investigação complementar	Dados sobre reutilização, descarte, reciclagem e resíduos têxteis
Contextualizar a economia circular	Permite discutir os resultados junto a indicadores gerais de circularidade	Indicadores específicos de têxteis e períodos compatíveis


6. Painel no Looker Studio
O painel deve permitir que qualquer pessoa explore os dados sem precisar programar. Visualizações recomendadas:
- Ranking de exportadores: país como dimensão e peso em toneladas como métrica.
- Ranking de importadores: mesma estrutura, filtrando o fluxo de importação.
- Evolução anual: peso registrado por ano, separando importações e exportações.
- Comparação entre fluxos: gráficos separados para evitar interpretações equivocadas ao combinar importação e exportação.
- Peso versus valor: exploração da relação entre volume e valor comercial declarado, quando ambos estiverem disponíveis.
- Filtros: ano, país e fluxo comercial.
Link do painel: adicione aqui o link compartilhável do Looker Studio.
7. Conclusões
A análise dos registros comerciais permite identificar os países que concentram os maiores volumes declarados, acompanhar variações ao longo dos anos e localizar lacunas de informação. Isso ajuda a organizar o problema e a definir onde estudos adicionais podem ser mais úteis.

No entanto, volume comercial não é o mesmo que volume de resíduo. Os registros não mostram, sozinhos, quantas peças foram revendidas, reutilizadas, recicladas ou descartadas depois de chegar ao país de destino. Por isso, não é correto classificar um país como destino de resíduos têxteis apenas porque ele apresenta importações elevadas.

A principal conclusão metodológica é que os dados de comércio são um ponto de partida para investigar o tema, não uma medida direta do impacto ambiental. A combinação com dados de geração e destinação de resíduos, infraestrutura de triagem e reciclagem e condições das peças permitiria avançar de uma descrição dos fluxos para uma avaliação ambiental mais robusta.
8. Limitações
- O país declarante não deve ser automaticamente interpretado como destino final das roupas.
- Valores ausentes não equivalem a zero.
- O código HS 6309 tem um escopo específico e não representa todo o comércio de resíduos têxteis.
- Diferenças de cobertura e qualidade podem afetar comparações entre países e anos.
- A taxa de uso circular de materiais do Eurostat é um indicador geral de materiais, não uma medida exclusiva da reutilização de roupas.
- Correlação entre comércio e indicadores ambientais não comprova causalidade.
- Os resultados preliminares devem ser validados na fonte antes da publicação.
9. Próximas etapas
1. Conferir os principais valores na base original e registrar os filtros usados.
2. Finalizar os gráficos de importação e exportação no Looker Studio.
3. Calcular e comparar o valor por tonelada apenas nos registros com peso e valor válidos.
4. Investigar fontes adicionais sobre resíduos têxteis, reutilização e reciclagem por país.
5. Atualizar as conclusões quando as análises forem validadas.
Estrutura do repositório
- 02_fontes_dados/ — fontes e arquivos originais.
- 03 EDA/ — materiais da análise exploratória.
- 03_dados/ — bases tratadas e preparadas para análise.
- Projeto_Impacto_Roupas.docx — documento de apresentação do projeto.
- RELATÓRIO DE INSIGHTS.docx — relatório de resultados.
- link look studio — arquivo destinado a registrar o link do painel.
- README.md — documentação principal.
Referências
- UN Comtrade — conceitos e definições de estatísticas de comércio internacional
- Eurostat — Circular material use rate
- Agência Europeia do Ambiente — Circular material use rate in Europe
Autor
Yago Bartensky de Lima
