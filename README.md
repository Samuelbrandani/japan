# JAPÃO 2026 🇯🇵

Site da viagem de 4 amigos — Samuel, Paulo, Emanuel e Jonathan — ao Japão em junho de 2026.

Página única (`index.html`), sem build, pronta para o GitHub Pages.

## Rota

| Data        | Horário      | Aeroporto            |
|-------------|--------------|----------------------|
| 18 jun 2026 | 16:35 (BRT)  | São Paulo — GRU      |
| 19 jun 2026 | 11:15 (TRT)  | Istambul — IST (escala) |
| 20 jun 2026 | 02:05 (TRT)  | Istambul — IST       |
| 20 jun 2026 | 19:20 (JST)  | Tóquio — HND         |

## Publicar (GitHub Pages)

1. Repositório → **Settings** → **Pages**
2. **Source**: `Deploy from a branch`
3. **Branch**: `master` · pasta `/ (root)` → **Save**
4. Site sai em `https://samuelbrandani.github.io/japan/`

## Roteiro (kanban + CRUD)

Seção **ROTEIRO** = quadro estilo Trello com CRUD completo:

- **Criar / editar / excluir** cartões e cidades direto na página
- Cada cartão: dia, flag "comprar entradas" e link do Google Maps
- Dados gravados no `localStorage` do navegador (persistem entre visitas)
- **Exportar JSON** baixa o roteiro · **Restaurar** volta ao padrão
- **Rota no Google Maps** abre direções Tóquio → Kyoto → Osaka → Tóquio

Roteiro inicial fica no `<script>`, constante `DEFAULT_ITIN`.

## Editar

Tudo num arquivo só: `index.html` (HTML + CSS + JS inline).
Data do voo no `<script>`: variável `DEPARTURE`.
