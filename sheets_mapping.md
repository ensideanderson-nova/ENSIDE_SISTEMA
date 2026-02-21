# Mapeamento Completo das Abas da Planilha

ID da Planilha: `1FiP885Or0ncyRG_ZZaAvM2vP0sHhDzhLFYifYLjKyIE`

## GIDs Reais (verificados via clique na aba e leitura do grid-container ID)

| Aba | GID | Conteúdo |
|-----|-----|----------|
| CONTATOS | 1689968688 | 7.056 contatos (NOME, TELEFONE, CATEGORIA, SUBCATEGORIA, CIDADE, UF, EMAIL, EMPRESA, STATUS) |
| FRETES_DISPONIVEIS | 1716433489 | 49 fretes disponíveis |
| CAPTACAO_FRETES | 1335082895 | 7 captações de fretes |
| Leads_Motoristas | 961123584 | 7.054 leads de motoristas |
| LISTAS_TRANSMISSAO | 1114979046 | 10 listas de transmissão |
| MINHAS_LISTAS | 250132552 | 5 listas pessoais |
| RESUMO EXECUTIVO | 1707733664 | Resumo executivo |
| PARÂMETROS | 773407069 | 39 parâmetros de configuração |
| ANÁLISE CUSTOS | 1081938874 | Análise detalhada de custos por bitola/umidade |
| TRATAMENTO CCA | 2118458555 | Análise de custos - Serragem Eucalipto Citriodora |
| ATACADO | 773407069 | Tabela de preços atacado (NOTA: mesmo GID que PARÂMETROS - a aba ATACADO usa sheet=ATACADO no iframe) |
| SIMULADOR | 85954134 | Simulador de múltiplos produtos |
| RELATÓRIO | 2085464626 | Relatório consolidado |
| ESTADOS_CIDADES | 1784972020 | 5.573 cidades e estados |
| VAREJO | 2046460774 | Tabela de preços varejo |
| CUSTOS SERRAGEM | 2118458555 | Mesmo conteúdo que TRATAMENTO CCA |
| Tabela dinâmica 1 | 1142513380 | Tabela dinâmica de contatos |
| Detalhe1 | 1183996076 | Detalhe de análise de custos |
| GLOSSÁRIO | 1656119291 | Glossário completo de termos |
| PROPOSTAS | 2135374310 | Proposta comercial - Eucalipto Tratado |

## Observações
- ATACADO e PARÂMETROS retornam o mesmo GID (773407069) — usar `sheet=ATACADO` no iframe para ATACADO
- CUSTOS SERRAGEM e TRATAMENTO CCA têm o mesmo GID (2118458555) — usar `sheet=CUSTOS SERRAGEM` no iframe
- Para o iframe do Google Sheets, usar: `https://docs.google.com/spreadsheets/d/SHEET_ID/edit?gid=GID`
- Para leitura de dados via gviz/tq, usar: `sheet=NOME_ABA` (mais confiável que gid)
