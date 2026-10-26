# Impacto Ambiental do Comércio Internacional de Roupas Usadas

## 1. Apresentação do projeto

O comércio internacional de roupas usadas faz parte de uma cadeia global que envolve consumo, reutilização, revenda e destinação de produtos têxteis. Embora a reutilização de roupas possa contribuir para prolongar a vida útil das peças e reduzir a demanda por novos produtos, a circulação internacional também levanta questões sobre a qualidade das roupas comercializadas, a capacidade de reutilização nos países importadores e a destinação das peças que não podem ser aproveitadas.

Este projeto utiliza dados públicos para analisar os fluxos internacionais de importação e exportação de roupas usadas, identificar os países com maiores volumes registrados e investigar como essas movimentações podem contribuir para a compreensão dos desafios relacionados à economia circular e à gestão de resíduos têxteis.

O objetivo é transformar dados comerciais em informações relevantes, apresentando não apenas números e gráficos, mas também perguntas de negócio, insights, conclusões e limitações que ajudem a compreender melhor o problema investigado.

## 2. Problema de negócio

A circulação internacional de roupas usadas gera uma questão importante: como identificar os principais fluxos comerciais e investigar se eles estão associados a desafios de reutilização, reciclagem e destinação de resíduos têxteis?

Os dados de comércio internacional permitem observar quais países declaram maiores volumes de importação e exportação. Entretanto, essas informações não mostram necessariamente o destino final das peças. Parte das roupas pode ser revendida ou reutilizada, enquanto outra parte pode não apresentar condições adequadas de uso e precisar de outra forma de destinação.

Essa falta de informação dificulta a avaliação dos possíveis impactos ambientais e a identificação dos locais que precisam de maior investigação.

Diante disso, o projeto busca organizar e analisar os dados disponíveis para identificar padrões comerciais, acompanhar mudanças ao longo dos anos e apontar quais informações adicionais seriam necessárias para avaliar os impactos ambientais com maior precisão.

## 3. Perguntas de negócio

A análise foi estruturada para responder às seguintes perguntas:

1. Quais países registram os maiores volumes de exportação de roupas usadas?
2. Quais países registram os maiores volumes de importação?
3. Como os volumes de importação e exportação mudaram ao longo dos anos analisados?
4. Quais países aparecem com destaque nos dois fluxos comerciais?
5. Existe uma relação entre o peso comercializado e o valor declarado das mercadorias?
6. Quais países e períodos merecem uma investigação ambiental mais aprofundada?
7. Até que ponto os dados comerciais permitem compreender os desafios relacionados à reutilização e à destinação de resíduos têxteis?
8. Quais dados complementares seriam necessários para avaliar se as roupas importadas estão sendo reutilizadas, recicladas ou descartadas?

Essas perguntas direcionam a análise para resultados que podem apoiar investigações futuras, facilitar a interpretação dos dados e demonstrar como a análise de dados pode contribuir para a compreensão de problemas reais.

## 4. Objetivos

O objetivo geral é analisar o comércio internacional de roupas usadas para identificar os principais países envolvidos, observar tendências ao longo do tempo e investigar possíveis relações com questões ambientais.

Como objetivos específicos, pretende-se:

- Identificar os principais países exportadores e importadores.
- Comparar os volumes registrados por país e ano.
- Observar aumentos, reduções e mudanças na distribuição dos fluxos comerciais.
- Investigar a relação entre peso e valor comercial declarado, quando os dados estiverem disponíveis.
- Contextualizar os resultados com indicadores de economia circular.
- Identificar limitações nas bases utilizadas.
- Propor caminhos para aprofundar a investigação sobre reutilização, reciclagem e destinação de resíduos têxteis.

## 5. Fontes de dados

O projeto utiliza bases públicas relacionadas ao comércio internacional e à economia circular.

UN Comtrade: fornece registros de comércio internacional associados ao código HS 6309, referente a artigos usados, incluindo vestuário e outros artigos usados. Essa fonte é utilizada para analisar os fluxos de importação e exportação por país e ano.

Eurostat: disponibiliza o indicador Circular Material Use Rate, que representa a taxa de uso circular de materiais. O indicador contribui para contextualizar a discussão sobre economia circular, embora não meça especificamente a reutilização de roupas.

Agência Europeia do Ambiente (EEA): fornece informações relacionadas às exportações de têxteis usados na União Europeia, contribuindo para a compreensão do comércio internacional desses materiais.

As fontes possuem escopos, unidades e períodos distintos. Por isso, as comparações entre elas precisam considerar suas definições e limitações.

## 6. Metodologia

O desenvolvimento do projeto foi organizado em cinco etapas principais.

Coleta dos dados: obtenção de bases públicas relacionadas ao comércio internacional de roupas usadas e a indicadores de economia circular.

Preparação dos dados: inspeção das colunas, padronização dos nomes dos campos, identificação de valores ausentes e organização das informações por país, ano e fluxo comercial.

Análise exploratória de dados (EDA): investigação dos volumes de importação e exportação, comparação entre países, observação de mudanças ao longo dos anos e análise dos valores comerciais disponíveis.

Visualização: elaboração de gráficos e construção de um painel no Looker Studio para facilitar a exploração dos resultados.

Interpretação dos resultados: identificação de padrões relevantes, formulação de conclusões, reconhecimento das limitações e proposição de novas perguntas para aprofundar a análise ambiental.

## 7. Insights preliminares

A base tratada do UN Comtrade contém registros de importação e exportação referentes ao período de 2022 a 2025. Entretanto, a disponibilidade das informações varia entre países, anos e variáveis.

Entre os resultados preliminares observados, a China aparece como principal exportadora por peso em 2025 nos dados tratados, com aproximadamente 1,37 milhão de toneladas registradas. O volume informado para o país aumentou de cerca de 603,7 mil toneladas em 2022 para aproximadamente 1,37 milhão de toneladas em 2025.

O Paquistão também aparece entre os principais importadores nos anos em que há dados de peso disponíveis, com aproximadamente 1,08 milhão de toneladas registradas em 2024.

Outro ponto importante é a existência de valores ausentes. O peso das importações do Paquistão em 2025, por exemplo, não está disponível na base utilizada. Essa ausência não deve ser interpretada como importação igual a zero e limita a comparação entre os anos.

Esses resultados mostram como a análise exploratória pode identificar países e períodos que merecem atenção. No entanto, os números devem ser validados na fonte original antes de serem apresentados como resultados definitivos.

Além disso, grandes volumes comerciais não comprovam, por si só, que as roupas foram descartadas ou que causaram determinado impacto ambiental. Para chegar a esse tipo de conclusão, seria necessário combinar os registros comerciais com dados sobre a destinação efetiva das peças.

## 8. Aplicação prática da análise

Os resultados podem ser utilizados para identificar quais países concentram os maiores volumes registrados no comércio internacional de roupas usadas e acompanhar como esses fluxos mudam ao longo do tempo.

Um ranking de exportadores pode ajudar a identificar os principais países declarantes nas vendas internacionais. Da mesma forma, um ranking de importadores pode indicar quais países registram maiores volumes de entrada dessas mercadorias.

A comparação entre peso e valor comercial pode revelar diferenças entre os mercados, desde que as unidades e os valores sejam consistentes. Já a análise temporal pode mostrar se os volumes registrados aumentaram ou diminuíram, ajudando a selecionar períodos que merecem uma investigação mais detalhada.

Do ponto de vista ambiental, esses resultados funcionam como um ponto de partida para direcionar pesquisas complementares. Se determinados países registram grandes volumes de importação, por exemplo, uma etapa posterior pode investigar a infraestrutura disponível para reutilização, triagem e reciclagem, além da quantidade de resíduos têxteis gerados.

Assim, o projeto demonstra como os dados podem ajudar a formular perguntas mais específicas e orientar investigações, sem atribuir aos registros comerciais informações que eles não contêm.

## 9. Conclusões

A análise dos registros comerciais permite identificar os países com maiores volumes declarados de importação e exportação de roupas usadas, observar mudanças ao longo dos anos e reconhecer lacunas que precisam ser consideradas na interpretação dos resultados.

Os dados preliminares destacam a importância de investigar os fluxos comerciais por país e período, evitando conclusões baseadas apenas em totais gerais. A ausência de informações para determinados países ou anos também demonstra a necessidade de verificar a cobertura das bases antes de realizar comparações.

A principal conclusão é que os dados de comércio internacional permitem mapear a circulação de roupas usadas, mas não são suficientes, isoladamente, para medir seu impacto ambiental efetivo.

Para avaliar a proporção de roupas que é reutilizada, reciclada ou descartada, seria necessário obter informações adicionais sobre a condição das peças, a destinação após a importação, a geração de resíduos têxteis e a capacidade local de triagem e reciclagem.

Portanto, a contribuição do projeto está em transformar registros comerciais em informações organizadas, identificar padrões relevantes e estabelecer uma base para investigações mais aprofundadas sobre economia circular e gestão de resíduos têxteis.

## 10. Limitações da análise

Algumas limitações precisam ser consideradas na interpretação dos resultados.

Primeiramente, o país declarante em um registro comercial não deve ser automaticamente interpretado como destino final das roupas. Além disso, valores ausentes não significam necessariamente que não houve comércio.

O código HS 6309 possui um escopo específico e não representa todo o comércio de resíduos têxteis nem todas as categorias de roupas usadas. Também podem existir diferenças de cobertura, qualidade e reporte entre países e anos.

O indicador de circularidade do Eurostat representa uma medida geral de uso circular de materiais e não deve ser interpretado como um indicador específico de reutilização de roupas.

Por fim, uma associação entre volumes comerciais e indicadores ambientais não comprova uma relação de causa e efeito. As conclusões devem permanecer proporcionais às informações efetivamente disponíveis.

## 11. Próximas etapas

Para aprofundar o projeto, as próximas etapas incluem validar os principais valores na base original, concluir o painel do Looker Studio e registrar os critérios utilizados no tratamento dos dados.

Também será importante investigar fontes adicionais sobre geração e destinação de resíduos têxteis, reutilização e reciclagem por país. A inclusão dessas informações poderá permitir análises mais específicas sobre a relação entre o comércio de roupas usadas e os desafios ambientais.

## 12. Painel interativo

O painel desenvolvido no Looker Studio tem como objetivo facilitar a exploração dos dados por meio de gráficos e filtros. As visualizações previstas incluem rankings de exportadores e importadores, evolução anual dos volumes comerciais e comparação entre os fluxos de importação e exportação.

O painel também pode permitir a seleção de países e anos, tornando mais fácil identificar padrões e consultar os registros que sustentam as conclusões do projeto.

Link do painel: https://datastudio.google.com/reporting/96288a34-8dc4-47db-87c0-48d90dadc375

## 13. Autor

Yago Bartensky de Lima
