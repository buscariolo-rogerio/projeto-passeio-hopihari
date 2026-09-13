# Hopi Hari — Roteiro do passeio

Site estático com Three.js, mapa de referência em perspectiva 3D e roteiro de 11 paradas para 4 de outubro de 2026.

## Abrir o site

1. Instale o Node.js, caso ainda não tenha.
2. Extraia o ZIP e abra um terminal na pasta extraída.
3. Execute `node servir.cjs`.
4. Acesse http://127.0.0.1:4173 no navegador.

Não é necessário instalar dependências. Para encerrar o servidor, pressione Ctrl+C no terminal.

## Arquivos

- `dist/index.html`: estrutura e textos iniciais.
- `dist/style.css`: aparência e adaptação para celular.
- `dist/app.js`: roteiro, marcadores e interação com o mapa.
- `dist/mapa.png`: imagem de referência enviada pelo usuário.
- `dist/three.module.js`: biblioteca Three.js incluída, com licença no próprio arquivo.
- `servir.cjs`: servidor local para visualizar o projeto.

Edite a lista `stops` em `dist/app.js` para alterar o roteiro. As posições dos marcadores são aproximadas. O mapa usa a ilustração em uma superfície 3D; não contém modelos individuais das atrações. As fontes do Google são opcionais e usam fontes locais alternativas sem conexão.

## Hospedagem

Publique o conteúdo da pasta `dist` em uma hospedagem de sites estáticos. A publicação online anterior não foi concluída.
