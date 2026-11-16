# Diagnóstico CONDES de Saúde Financeira

Landing page do **Método CONDES** (Coronel Mário Lopes Condes): o Google Form do diagnóstico virou um quiz em etapas, que termina no Índice CONDES, no mapa dos 6 pilares e na oferta do e-book *Servidor Público Rumo à Liberdade Financeira* (R$ 49,90, checkout Hotmart).

## Conteúdo
- `index.html` — página completa (HTML, CSS e JS em um único arquivo, com as imagens embutidas).

## Como visualizar
Abra o `index.html` no navegador. As fontes vêm do Google Fonts, então é preciso estar conectado à internet.

## Observações
- **Respostas:** ainda não são enviadas a lugar nenhum. A função `enviarRespostas()` é o ponto para ligar uma planilha (Google Apps Script), CRM ou webhook.
- **Rastreamento:** os eventos do Meta Pixel e do GA4 já estão no código; faltam os IDs reais (ver comentário no topo do arquivo).
- **Pontuação:** as faixas do índice (alerta, atenção, em construção, sólida) são uma proposta e devem ser validadas com o cliente.
- **Exemplo:** o link "Ver um resultado de exemplo" mostra o resultado com respostas fictícias.
