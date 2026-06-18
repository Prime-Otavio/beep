# Regras do projeto Beep Elite

## Estilo de escrita (OBRIGATÓRIO em TODOS os projetos do Otavio)
- **NUNCA usar travessão "—" (em dash).** O usuário considera feio. Proibido em qualquer texto visível: conteúdo, títulos, menus, rótulos, frases.
- No lugar do travessão, usar: vírgula, dois-pontos, ou reescrever a frase.
- Vale para hífen longo de qualquer tipo. Hífen comum "-" em palavras compostas (ex: "pós-venda") é permitido.

## Design
- Tema claro estilo Apple: fundo papel amarelado (#F4EFE3), superfícies quase brancas (#FDFBF5), destaque âmbar/dourado discreto (#B6822A). Nada de laranja forte, nada de dark mode.
- Aulas longas devem usar o padrão índice + leitura focada (uma seção por vez), não scroll infinito.

## Técnico
- Projeto é um single-file (index.html) hospedado em Vercel + Supabase, versionado em git (github.com/Prime-Otavio/beep).
- A pasta é sincronizada via OneDrive: NÃO reescrever o arquivo inteiro via bash/python no sandbox (causa corrupção por sync parcial). Usar só as ferramentas Edit/Write, que passam pela camada autoritativa.
- Sempre fazer backup/commit antes de mudanças grandes.
