# WYD FieldScene Studio Pro

Editor standalone para arquivos de interface do WYD, desenvolvido em HTML e JavaScript, com foco em leitura, visualizacao, edicao, importacao e exportacao de paineis e recursos graficos.

Esta versao faz parte de uma linha extensa de evolucao do projeto, consolidando melhorias acumuladas ao longo de dezenas de iteracoes sobre uma base anterior. Com créditos  totais ao HC  _ Hamilton

O editor conta com um sistema de resolucao com adaptacao proporcional, conversao entre presets e visualizacao em escala 1:1, permitindo trabalhar o layout com mais fidelidade em diferentes tamanhos de tela.

## Principais recursos

- Abertura e leitura de arquivos `.bin` de interface.
- Visualizacao hierarquica dos elementos do painel.
- Workspace interativo com renderizacao, selecao, zoom e pan.
- Edicao de propriedades dos elementos em tempo real.
- Suporte a textos via `UIString.txt`.
- Suporte a coordenadas de textura via `UITextureSetList.txt`.
- Resolucao de imagens por `UITextureListN.bin` e `TextureListN.txt`.
- Compatibilidade com variantes diferentes de layout da `UITextureListN.bin`.
- Carregamento de recursos graficos a partir de pastas do cliente.
- Suporte a imagens `WYT`, `VGI`, `TGA`, `PNG`, `JPG`, `JPEG` e `BMP`.
- Remocao automatica de fundo escuro em imagens e texturas compativeis.
- Importacao de paineis e elementos a partir de outros arquivos.
- Exportacao de elementos, paineis, textos e imagens.
- Undo/redo para alteracoes de edicao.
- Ferramentas de busca, filtros e ordenacao de elementos.
- Sistema de resolucao com adaptacao proporcional e visualizacao em escala 1:1.
- Processamento de transparencia para remocao de fundo em imagens compativeis.
- Ferramentas de conversao entre resolucoes.
- Ferramentas de ajuste por ancora para reposicionamento de paineis.
- Visualizador interno de imagens e texturas.

## Destaques tecnicos

- Aplicacao standalone executada diretamente no navegador.
- Persistencia de diretorios usando `IndexedDB`.
- Integracao com `File System Access API` quando disponivel.
- Estrategias de fallback para navegadores com suporte parcial.
- Estrutura preparada para fluxos locais com backend auxiliar em rotas `/api/scene/...`.

## Arquivo principal

- `WYD FieldScene Studio Pro - Versão Teste 90.html`

## Como usar

1. Abra o arquivo HTML no navegador.
2. Carregue um arquivo `.bin`.
3. Carregue a pasta de recursos do cliente quando necessario. Recomendado carregar a pasta do cliente onde seja possivel ao programa ler as pastas UI, NUI E MESH
4. Edite, visualize, importe ou exporte conforme o fluxo desejado.

## Requisitos

- Navegador moderno.
- Suporte a `File System Access API` para a melhor experiencia de abertura e salvamento.
- Suporte a `IndexedDB` para persistencia local de diretorios.
- Conexao com internet para carregar o Font Awesome via CDN.

## Observacoes

- Parte dos recursos avancados pode depender de backend local, conforme a configuracao usada no ambiente.
- O projeto foi construido com abordagem iterativa, preservando compatibilidade com varios fluxos de trabalho do editor.
- O foco principal desta versao e reunir correcoes, compatibilidade e ferramentas praticas de uso real.

## Status

Projeto funcional em evolucao continua, derivado de uma serie extensa de versoes incrementalmente melhoradas.
