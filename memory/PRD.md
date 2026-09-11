# PRD — Gi Inovações

## Problema original
Implementar fielmente o repositório público https://github.com/treedbkp-art/gi2-09 no workspace `/app`.

## Decisões de arquitetura
- React 19 com React Router, GSAP/ScrollTrigger, Lenis e Three.js no frontend.
- FastAPI com MongoDB via `MONGO_URL` e `DB_NAME` existentes no ambiente.
- Artigos e uploads persistidos no MongoDB; mídia institucional permanece em `frontend/public`.
- Rotas administrativas protegidas pelo token compatível com o repositório original.

## Personas
- Profissional de P&D e desenvolvimento de produtos para calçados.
- Cliente industrial buscando matrizes, EVA, E-TPU ou compostos.
- Administrador responsável por artigos técnicos.

## Requisitos principais
- Home cinematográfica com vídeo, soluções, sustentabilidade, artigos e contato.
- Páginas Empresa, Gi Reboot, EVA, Matrizes, Contato, Artigos e detalhe de artigo.
- Navegação desktop/mobile, menu de soluções, cursor customizado, mouse trail e viewers 3D.
- Login administrativo, CRUD de artigos e upload de imagens.

## Implementado
- 2026-09-08 — Código, componentes, páginas, estilos e assets sincronizados do repositório público.
- 2026-09-08 — Dependências frontend instaladas e build de produção validado.
- 2026-09-08 — Credenciais administrativas registradas para validação dos fluxos.

## Backlog priorizado
- P0: validar APIs e fluxos administrativos no ambiente em execução.
- P1: corrigir avisos de minificação CSS caso afetem animações no navegador.
- P2: ampliar cobertura de testes automatizados para navegação e viewers 3D.

## Próximas tarefas
1. Executar testes backend de autenticação, artigos e uploads.
2. Capturar screenshots da Home e validar navegação responsiva.
3. Corrigir somente divergências encontradas na execução.