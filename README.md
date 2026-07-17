# Instituto Kronos · Painel — Layout Bento Grid

Hub agregador do Instituto Kronos num único arquivo HTML.

- **Versão**: v0.13-teste · Layout Bento Grid
- **Inspiração**: Apple / Linear — cards com hover suave, gradiente sutil, contadores em rosa
- **Conteúdo**: 6 camadas (Gestão/Operação/Produtos/SOPs/Biblioteca/Conhecimento) + 7 sub-áreas de Operação + 5 produtos + Playbook Mentoria Kairós com 10 notas
- **Persistência**: localStorage (`kronos_state_v1`)

## Como rodar

```bash
# 1. Servir local
python -m http.server 8000

# 2. Abrir no browser
open http://localhost:8000
```

Single-file, sem build, sem dependências. Funciona offline.

## Funcionalidades

- Busca com stemmer + 200+ sinônimos
- Botão Resumo (todos os links/docs/notas em uma página)
- Modal Adicionar/Editar
- Visualizador de notas (Playbook Kairós)
- Drag handle `⋮⋮` aparece no hover
- 4 abas: Gestão / Operação / Produtos / SOPs / Biblioteca / Conhecimento
- Vazios visíveis por padrão
