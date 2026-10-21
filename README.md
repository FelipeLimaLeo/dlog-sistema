# DLOG → Template de Carga de Itens de Fatura

Ferramenta web (roda 100% no navegador, sem backend) que lê o PDF de uma fatura
("dlog"), extrai os itens automaticamente e exporta no layout exato do
Template de Carga de Dados de Itens de Fatura.

## Uso

Abra `index.html` (local ou via GitHub Pages), arraste o PDF da fatura,
confira/complete os campos em amarelo (Peso Líquido e Regime Aduaneiro) e
clique em **Exportar XLSX**.

A ferramenta lembra, por Part Number, o peso e o regime já preenchidos antes
(guardado no navegador), reduzindo o preenchimento manual a cada nova fatura.
