# Atlas de Mortalidade do Ceará — painel (versão preliminar)

Painel interativo com os óbitos de residentes no Ceará registrados no Sistema de Informação sobre Mortalidade (SIM), de 1979 a
2025 (2025 preliminar): causas, idade e sexo, municípios e regiões de saúde, mortalidade infantil, meses do ano, local de
ocorrência e qualidade dos registros. É uma página única (`index.html`): as contagens estão embutidas nela, e os filtros
funcionam no navegador, sem servidor e sem internet depois de aberta.

## Aviso

Este painel é um projeto pessoal, em **versão preliminar e de teste**. Não é um produto oficial, não foi revisado nem
aprovado por nenhuma instituição e não representa a posição da Secretaria da Saúde do Ceará, do Ministério da Saúde, da
Universidade de Fortaleza (Unifor) ou de qualquer outra instituição a que o autor esteja vinculado.

**Pode conter erros, e é provável que contenha.** Feito com inteligência artificial, sobre métodos e projetos anteriores
de cgarciafilho: o pedido, as convenções de trabalho, as regras de rigor e o método (o Atlas de Mortalidade do Ceará
1979–2024, de junho–julho de 2026, e os painéis de anomalias congênitas e de leishmaniose visceral) são dele; a execução
desta versão (o plano, a obtenção dos dados, as definições, o código, os gráficos e os textos) foi da IA, em modo
autônomo. As decisões de método foram validadas pelo autor em 04/10/2026; **a conferência dos números por pessoa
está pendente**: ninguém leu ou recalculou sistematicamente os números, gráficos e textos até a data da página. A aba
“Sobre esta versão” diz quem fez o quê e lista as decisões de método. Use com cautela e confira os números nas fontes oficiais
(TabNet do DATASUS, IntegraSUS) antes de citar ou de decidir algo com base neles. As limitações estão na aba “Métodos”.

## Fontes

- SIM e SINASC: microdados públicos do DATASUS, arquivos do Ceará, sem identificação de pessoas.
- População: séries POP e POPSVS do IBGE/DATASUS.
- Malha municipal: IBGE.
- Regionalização: lista de Superintendências Regionais e Áreas Descentralizadas de Saúde da SESA-CE de 02/03/2022.
- Razão entre óbitos informados e estimados (indicador A.18) e taxa de mortalidade infantil estimada (indicador C.1): RIPSA, Indicadores e Dados Básicos 2012.

As datas de cada arquivo estão na aba “Métodos” da página.

## Contato

Erros, dúvidas e sugestões: cgarciafilho@gmail.com

## Sobre este repositório

Aqui fica só a página publicada. Os scripts que baixam os dados, calculam as contagens e conferem o painel (com o TabNet,
com cálculo direto em Python e por combinações sorteadas de filtros) ficam no projeto de origem, que não está publicado.

## Licença

MIT (arquivo `LICENSE`), para a página e o código. Os dados de origem (SIM, SINASC e população do DATASUS/IBGE, malha do
IBGE, regionalização da SESA-CE) são públicos e seguem os termos de cada fonte.
