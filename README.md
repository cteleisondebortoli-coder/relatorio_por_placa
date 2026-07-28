# Consolidador CTe

App estático (HTML/JS) que lê XMLs de CT-e + eventos de cancelamento e gera planilhas Excel consolidadas por CNPJ emissor + série, agrupadas por placa do veículo tracionador.

## Uso

Abra `index.html` (local ou via GitHub Pages). Selecione arquivos `.xml` ou `.zip`, clique em Processar, depois Baixar Todos.

## GitHub Pages

Settings → Pages → Deploy from branch → `master` / `(root)`.

## Stack

- Sem build. HTML + JS puro.
- Bibliotecas via CDN: JSZip, ExcelJS.
