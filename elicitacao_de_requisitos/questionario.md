# Questionário

## Introdução

O questionário é uma das tecnicas mais utilizadas para a elicitação de requisitos. Esta tecnica se sai muito bem perante publicos de diversos tamanhos, pois, ela consegue abordar todos os perfis de usuário de uma forma metódica e rápida. Este artefato tem como objetivo relatar como foi a experiência do questionário e elicitar os requisitos provindos desta tecnica.

## Metodologia

O questionário contou com 18 perguntas que contaram com a escala de likert, sendo destas 5 pessoais e as outras 13 relativas ao aplicativo [MOJ-Naquadah](https://moj.naquadah.com.br/cgi-bin/index.sh). As perguntas foram elaboradas com base nas [Heurísticas de nielsen](https://brasil.uxdesign.cc/10-heur%C3%ADsticas-de-nielsen-para-o-design-de-interface-58d782821840) afim de melhorar a interface gráfica do aplicativo e por consequencia a interação do mesmo com o usuário.

O questionário foi elaborado buscando somente respostas de pessoas que já tenham utilizado o aplicativo. Por isso, a primeira questão delimitava se iria para a página de envio (não utilizou) ou para as páginas com as outras perguntas (sim utilizou).

O mesmo ficou aberto do dia 17/09/23 a 21/09/23 e foi distríbuido em grupos de whatsapp e telegram da FGA.

Por fim, foi feita uma analise de dados para saber se o questionário era de fato válido.

## Analise de dados

Antes da analise, foi feito um tratamento dos dados, por fim o processo de analise de dados foi feito do Jupiter Notebook que você pode acessar clicando neste [link](https://github.com/ananorberto/Interacao-Humano-Computador/blob/main/analise_de_dados/analise.ipynb). Em suma, foi utilizado o [Alfa de cronbach](https://pt.wikipedia.org/wiki/Alfa_de_Cronbach) para validar o questionário e após a [Correlação de Pearson](https://pt.wikipedia.org/wiki/Coeficiente_de_correla%C3%A7%C3%A3o_de_Pearson) para entender as conexões entre as perguntas.

## Requisitos elicitados

### Requisitos funcionais

A tabela 1 aponta todos os requisitos funcionais elicitados:

| ID   | Description                                                        | Implementado |
| ---- | ------------------------------------------------------------------ | ------------ |
| RF1  | O usuário deve submeter seus códigos                               | Sim          |
| RF2  | O usuário deve poder encontrar suas listas                         | Sim          |
| RF3  | O usuário deve poder logar em suas listas                          | Sim          |
| RF4  | O usuário deve poder ocultar submissões já feitas                  | Não          |
| RF5  | O usuário deve poder escolher a linguagem para submeter seu código | Sim          |
| RF6  | O usuário deve poder encontrar suas listas através de tags         | Não          |
| RF7  | O usuário deve poder recuperar arquivos de submissões anteriores   | Não          |
| RF8  | O usuário deve poder interagir com o MOJITO através do proprio MOJ | Não          |
| RF9  | O usuário deve poder escrever o código dentro do MOJ               | Não          |
| RF10 | O usuário deve poder encontrar questões fora dos contests          | Não          |
| RF11 | O usuário deve poder ter acesso a um FAQ                           | Não          |
| RF12 | O usuário deve poder sugerir problemas através de uma area especifica | Não       |

<p align="center"> Tabela 1: Requisitos elicitados. Fonte: autores, 2023</p>

### Requisitos não-funcionais

A tabela 2 aponta todos os requisitos não-funcionais elicitados:

| ID    | Description                                                       | Implementado |
| ----- | ----------------------------------------------------------------- | ------------ |
| RNF1  | O usuário deve encontrar suas listas com facilidade               | Não          |
| RNF2  | O sistema deve julgar o código rapidamente                        | Não          |
| RNF3  | O sistema deve informar qual o status do código durante submissão | Não          |
| RNF4  | O sistema deve ser acessível e inclusivo                          | Não          |
| RNF5  | O sistema deve prover auxilio para caso ocorra um erro inesperado | Não          |
| RNF6  | O sistema deve ser minimalista                                    | Não          |
| RNF7  | O sistema deve ser intuitivo e organizado                         | Não          |
| RNF8  | O sistema deve fornecer explicação sobre sua linguagem ao usuário | Talvez       |
| RNF9  | O sistema deve ter fontes grandes, assim como seus botões         | Não          |
| RNF10 | O sistema deve fornecer informações sobre seu funcionamento       | Não          |
| RNF11 | O sistema deve prover sempre o compilador mais atualizado         | Não          |

<p align="center"> Tabela 2: Requisitos elicitados. Fonte: autores, 2023</p>

## Referências Bibliográficas

> [1] Barbosa, S. D. J.; Silva, B. S. da; Interação Humano-Computador.
>
> [2] Questionário - Simplenote. Github.io. Disponível em: <https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/questionario/>. Acesso em: 22 set. 2023.
>
> [3] MOMA, Gabriel. 10 heurísticas de Nielsen para o design de interface. Medium. Disponível em: <https://brasil.uxdesign.cc/10-heur%C3%ADsticas-de-nielsen-para-o-design-de-interface-58d782821840>. Acesso em: 22 set. 2023.
>
> [4] DOS, Contribuidores. Alfa de Cronbach. Wikipedia.org. Disponível em: <https://pt.wikipedia.org/wiki/Alfa_de_Cronbach>. Acesso em: 22 set. 2023.
>
> [5] DOS, Contribuidores. Coeficiente de correlação de Pearson. Wikipedia.org. Disponível em: <https://pt.wikipedia.org/wiki/Coeficiente_de_correla%C3%A7%C3%A3o_de_Pearson>. Acesso em: 22 set. 2023.

‌

‌

## Histórico de Versões

| Versão | Data       | Descrição               | Autor(es) | Revisor(es) |
| ------ | ---------- | ----------------------- | --------- | ----------- |
| `1.0`  | 21/09/2023 | Criação da documentação | Kauã      | Ana Beatriz |
