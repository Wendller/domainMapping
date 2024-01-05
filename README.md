# Domain Mapping

## Sistema de gerenciamento de estoque

### Entidades

- Produto
  - Identificação única
  - Informações individuais extras
    - Tamanho
    - Cor
  - Limite mínimo no estoque
  - Quantidade no estoque
- Vendas
- Fornecedores
- Ordem de compra

### Casos de uso

- Rastrear produtos
- Visualização de histórico de vendas
  - Produtos vendidos por período
  - Lucro gerado por produto em determinado período
  - Produto mais vendido por período
  - Tendências de estoque

### Eventos de domínio

- Alerta de limite mínimo de produto atingido
  - Email
  - Notificação
- Emitir ordem de compra para produtos com limite mínimo atingido
