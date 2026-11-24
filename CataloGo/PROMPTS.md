# Prompts por etapa — Lovable

Copie apenas a etapa atual. O contexto comum deve acompanhar cada prompt se a ferramenta não o retiver. Não execute todos de uma vez.

## Contexto comum

```text
Projeto CataloGo: catálogo comercial modular, responsivo e replicável para pequenos negócios. Uma instalação por estabelecimento, sem pagamento online, cadastro de consumidor ou multi-tenant no MVP. Trabalhe incrementalmente, preserve funcionalidades existentes, separe responsabilidades, centralize configurações e use apenas dados fictícios. Não exponha segredos. Antes de mudanças arquiteturais importantes, apresente proposta. Ao terminar, descreva alterações, testes realmente executados e pendências.
```

## 00 — Concepção

```text
Trabalhe somente na etapa 00 — Concepção. Planeje e apresente decisões para revisão, sem implementar código.
Requisitos:
- Definir objetivo comercial
- Definir público-alvo
- Identificar problema resolvido
- Definir funcionalidades essenciais
- Delimitar fora do escopo
- Mapear jornada do consumidor
- Mapear jornada do administrador
- Estabelecer critérios de conclusão
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 01 — Fundação

```text
Trabalhe somente na etapa 01 — Fundação. Inspecione o projeto existente e proponha a estrutura antes de alterar arquivos.
Requisitos:
- Definir stack
- Inicializar Git
- Organizar diretórios modulares
- Definir responsabilidades e contratos
- Configurar dependências e ambiente
- Definir componentes reutilizáveis
- Documentar convenções
- Garantir execução local
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 02 — Core e configurações

```text
Trabalhe somente na etapa 02 — Core e configurações. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Nome comercial
- Logotipo
- Descrição
- Paleta de cores
- Tipografia
- WhatsApp comercial
- Endereço e horários
- Redes sociais
- Moeda e idioma
- Centralizar configurações sem valores fixos espalhados
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 03 — Dados

```text
Trabalhe somente na etapa 03 — Dados. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Modelo de estabelecimento
- Modelo de categorias
- Modelo de produtos
- Relacionamentos
- Identificadores únicos
- Validação de dados
- Persistência
- Camada de acesso aos dados
- Dados fictícios para testes
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 04 — Interface

```text
Trabalhe somente na etapa 04 — Interface. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Layout responsivo
- Cabeçalho
- Rodapé
- Menu
- Página inicial
- Componentes reutilizáveis
- Aplicar identidade visual configurável
- Estados de carregamento, erro e vazio
- Acessibilidade básica
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 05 — Catálogo

```text
Trabalhe somente na etapa 05 — Catálogo. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Listagem
- Cards
- Imagens
- Nome, descrição e preço
- Categorias
- Pesquisa por nome
- Filtros
- Detalhes em página ou modal
- Disponibilidade
- Ocultar produtos desativados
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 06 — Carrinho

```text
Trabalhe somente na etapa 06 — Carrinho. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Adicionar produtos
- Remover produtos
- Alterar quantidades
- Calcular subtotais
- Calcular total
- Exibir quantidade de itens
- Persistir localmente
- Validar preços e disponibilidade antes de finalizar
- Limpar carrinho
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 07 — Checkout

```text
Trabalhe somente na etapa 07 — Checkout. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Resumo do pedido
- Observações opcionais
- Mensagem formatada com produtos e quantidades
- Incluir preços e total estimado
- Abrir WhatsApp com mensagem preenchida
- Validar número comercial
- Bloquear carrinho vazio
- Informar necessidade de confirmação pelo comerciante
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 08 — Administração

```text
Trabalhe somente na etapa 08 — Administração. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Autenticar administrador
- Proteger rotas e operações
- Painel
- CRUD de categorias
- CRUD de produtos
- Gerenciar imagens
- Alterar preços
- Ativar/desativar produtos
- Editar informações comerciais
- Editar identidade visual
- Persistir alterações
- Validar permissões no backend
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 09 — Validação

```text
Trabalhe somente na etapa 09 — Validação. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Testar jornada do consumidor
- Testar jornada do administrador
- Testar persistência após recarregar
- Testar responsividade
- Testar cálculos
- Testar WhatsApp
- Testar erros e entradas inválidas
- Testar acesso não autorizado
- Verificar exposição de credenciais
- Revisar desempenho e acessibilidade
- Corrigir bugs
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```

## 10 — Publicação

```text
Trabalhe somente na etapa 10 — Publicação. Implemente incrementalmente os requisitos aplicáveis, respeitando a arquitetura já validada.
Requisitos:
- Definir hospedagem
- Configurar produção
- Configurar variáveis de ambiente
- Configurar domínio ou subdomínio
- HTTPS
- Metadados e SEO básico
- Avaliar privacidade e LGPD
- Backup e recuperação
- Documentar instalação
- Documentar uso administrativo
- Testar replicação para segundo cliente fictício
- Levantar custos operacionais
Não avance para a próxima etapa. Informe como validar esta entrega e o que ficou pendente.
```
