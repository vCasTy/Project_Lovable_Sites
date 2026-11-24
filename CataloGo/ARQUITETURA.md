# Arquitetura modular proposta

Stack em aberto, adaptável à ferramenta e ao curso. Preferir módulos por responsabilidade, contratos claros e baixo acoplamento, sem abstrações prematuras.

```text
src/
  app/              # rotas, composição, layout
  core/             # configuração e contratos
  shared/           # componentes e utilitários comuns
  infrastructure/   # persistência e integrações
  modules/
    catalog/        # consulta, categorias, filtros
    cart/           # itens, quantidades e cálculos
    checkout/       # resumo e integração WhatsApp
    admin/          # gestão e autenticação
 tests/             # testes
```

## Contratos conceituais
- Estabelecimento: identidade, contatos, endereço, horários, tema e moeda.
- Categoria: ID, nome, estado ativo.
- Produto: ID, categoria, nome, descrição, preço, imagem, estado ativo/disponibilidade.
- Carrinho: IDs de produtos e quantidades, persistidos localmente; consultar dados vigentes antes do checkout. Valores monetários em centavos ou tipo decimal apropriado.
- Checkout: gera mensagem e abre WhatsApp; não representa pedido confirmado nem pagamento.
- Admin: operações de escrita exigem autenticação e autorização no backend. Leitura pública limitada aos dados publicados.

Módulos opcionais posteriores: estoque, pagamentos, agendamento, delivery, promoções e relatórios. Não implementar antecipadamente.

## Reutilização
Configurações e conteúdo por estabelecimento, lógica compartilhada. Começar com instalações independentes; arquitetura SaaS multi-tenant seria uma evolução distinta, exigindo isolamento de dados e controles adicionais.
