# Validação da central

- 5 disciplinas e 50 rotas únicas, todos os arquivos existem; 49 páginas reservadas e 1 laboratório real.
- Molecular Builder v0.2.2 copiado byte a byte; SHA-256: 21d20325a321f90e06cd3a11432f5a5c509b74b116c2d427c7e6d11014c13817. Sem alteração dos originais.
- 22 verificações Chromium aprovadas: catálogo, filtros, busca, tela vazia, página reservada, carregamento de água no editor, controle Linhas, Nexus Learn, foco, navegação de retorno, link separado, responsividade em 390 px e substituição simulada de módulo. Zero erros JS e requisições HTTP(S) no teste.
- A política do navegador bloqueou navegação por file:// e HTTP loopback; teste de interface via set_content com catálogo injetado e adaptador de teste que fornece o HTML correspondente via srcdoc. A resolução de caminhos foi conferida em disco; abertura real por file://, nova aba e fullscreen não foram validados. Testes nos dispositivos do estudante pendentes.
- O motor molecular não foi alterado; Three.js e WebGL continuam com as ressalvas anteriores.
