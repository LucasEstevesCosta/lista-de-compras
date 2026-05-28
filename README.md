# lista-de-compras
lista de prioridade de coisas para comprar

## Atualizações
### ver 1.2
O que foi corrigido e adicionado:
#### 🔧 Tamanho da fonte — Substituído pelos botões quebrados por um slider de 11px a 26px. O valor atual aparece ao lado em tempo real, e a mudança aplica no font-size do elemento <html>, fazendo com que todos os elementos com unidade rem escalem corretamente.
#### 📱 Responsividade — Modais sobem como bottom sheet no mobile, painel de configurações ocupa 100% da largura em telas pequenas, botões de ação sempre visíveis em touch (sem depender de hover), áreas de toque mínimas de 34–40px, padding adaptado por clamp().
#### ↕ Drag & drop — Usa SortableJS (biblioteca leve, sem dependências). O ícone ⠿ aparece nos itens e nos cabeçalhos dos grupos. Itens podem ser arrastados entre categorias diferentes — ao soltar, o categoria_id é atualizado automaticamente. A ordem é salva no Supabase com debounce de 600ms para não sobrecarregar a API.
#### 🎨 Cor de fundo — Nova opção "Aparência" no painel de configurações com um color picker para o fundo da página, salvo no Supabase junto com as outras preferências.
