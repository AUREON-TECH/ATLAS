# ATLAS — Inteligência de Resultados

Aplicação PWA para consolidar e analisar resultados comerciais por período, profissional e equipe.

## Primeira versão
- Importação local de arquivos Excel (.xlsx/.xls) e CSV.
- Filtros por ano, mês, profissional e equipe.
- Indicadores de VGV, vendas, casais e conversão.
- Evolução mensal de VGV e ranking de profissionais.
- Tabela de registros importados.
- Interface responsiva para desktop e celular.

## Publicação
O projeto é estático e pode ser publicado pelo GitHub Pages na branch `main`, pasta `/ (root)`.

## Importante
Nesta versão, os dados importados ficam apenas na memória da sessão do navegador. Não há envio para servidor nem alteração de dados do RAIO X. A estrutura de colunas da planilha será refinada com base no arquivo oficial utilizado na operação.

## Próximas etapas
1. Validar a importação com a planilha real.
2. Ajustar o mapeamento de colunas e regras de consolidação.
3. Adicionar metas, comparativos, visão trimestral/anual e exportação de relatórios.
4. Definir persistência e controle de acesso antes de uso operacional compartilhado.
