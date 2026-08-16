<!-- BEGIN:nextjs-agent-rules -->

# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

# Objetivo

O projeto tem como objetivo contruir uma cópia o mais parecida possível de um caixa eletronico preferencialmente com a interface dos caixas eletrônicos da Caixa Econômica Federal que é o banco brasileiro mais usado por idosos e aposentados.

# Stack

Deve ser utilizado Tailwind para estilização da aplicação e padronização de componentes.

# InstruçÕes de arquitetura

Todo componente que tiver o mesmo propósito deve ser separado e parametrizado para ser utilizado em N lugares, mantendo consistência no projeto e facilitando manutenção.

As telas devem ser projetadas para serem usadas em resoluções de tablet, notebook e desktop. Dado que será um projeto para ensino de idosos e o professor ira instruílos usando esses dispositivos.

Será hospedado em um Google Cloud Run, então é impressindível a construção do ambiente Docker para executar o projeto.

Será publicado usando o GitHub Actions para autenticar e publicar no ambiente Google.
