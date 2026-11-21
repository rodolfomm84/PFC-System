# Sistema PFC

Sistema de gestão do clube: sócios e dependentes, mensalidades, inadimplentes, lista de bloqueio da catraca e importação e exportação em Excel.

## Arquivos

| Arquivo | O que é |
| --- | --- |
| `index.html` | O sistema inteiro (telas, regras e logo) |
| `config.js` | Escolhe onde os dados ficam: `"teste"` (no navegador) ou `"supabase"` (próxima etapa) |
| `.nojekyll` | Faz o GitHub Pages publicar os arquivos como estão |

## Publicar no GitHub Pages

1. Envie os três arquivos para a raiz do repositório, na branch `main`.
2. No repositório, abra **Settings > Pages**.
3. Em **Build and deployment**, escolha **Source: Deploy from a branch**, **Branch: main** e a pasta **/ (root)**. Clique em **Save**.
4. Depois de 1 a 2 minutos, o endereço aparece no topo da mesma página: `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Se o repositório for privado, o GitHub Pages só funciona em plano pago. Nesse caso, deixe o repositório público: no modo de teste, nenhum dado fica no repositório.

## Modo de teste

- Para entrar, use qualquer e-mail e a senha `teste`.
- Os dados ficam guardados só no navegador de quem está usando. Outro computador começa vazio.
- O botão **Apagar dados de teste**, na barra lateral, limpa tudo.
- Não importe a lista completa de sócios reais neste modo. Use uma cópia com poucas linhas.

## Próxima etapa: Supabase

Com os testes aprovados, o `config.js` passa a apontar para um projeto Supabase, com banco de dados real, login de verdade e permissão por usuário. As telas continuam as mesmas.
